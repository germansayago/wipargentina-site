<template>
  <section id="contact" class="section section-medium contact">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-md-7">
          <h2 class="display-3 mb-3">¿En que fase está tu negocio?</h2>
          <p class="lead mb-5 d-none">
            Trabajamos junto a perfiles de empresas o personas que deseen
            cambiar su futuro, afianzando su presencia en internet
          </p>
          <p class="lead mb-5">
            Nos motiva el desafío de hacer crecer y afianzar tu presencia en
            internet, trabajemos juntos!
          </p>

          <form @submit.prevent="onSubmit">
            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label for="name">Nombre y Apellido</label>
                  <input
                    id="name"
                    v-model="name"
                    type="text"
                    class="form-control"
                    required
                  />
                </div>
              </div>
              <div class="col-md-6">
                <div class="form-group">
                  <label for="">Empresa</label>
                  <input
                    id="company"
                    v-model="company"
                    type="text"
                    class="form-control"
                    required
                  />
                </div>
              </div>
              <div class="col-md-6">
                <div class="form-group">
                  <label for="">Email</label>
                  <input
                    id="email"
                    v-model="email"
                    type="mail"
                    class="form-control"
                    required
                  />
                </div>
              </div>
              <div class="col-md-6">
                <div class="form-group">
                  <label for="">Teléfono</label>
                  <input
                    id="phone"
                    v-model="phone"
                    type="text"
                    class="form-control"
                    required
                  />
                </div>
              </div>
            </div>
            <div class="form-group">
              <label for="">Contanos cómo podemos ayudarte</label>
              <textarea
                id="message"
                v-model="message"
                name=""
                rows="4"
                class="form-control"
                required
              ></textarea>
            </div>
            <div class="d-md-flex justify-content-between text-center">
              <input
                type="submit"
                class="btn btn-primary px-5 py-3 mt-3 mb-3 mb-md-0"
                value="Enviar"
              />
              <a
                href="https://wa.me/5493584112731"
                class="btn btn-outline-secondary px-5 py-3 mt-3 d-md-flex align-items-center"
                target="_blank"
                ><ion-icon name="logo-whatsapp" />
                <span class="ml-2">ESCRIBINOS</span></a
              >
            </div>
          </form>
          <div class="mt-5">
            <div v-if="mailSending" class="alert alert-dark">
              Enviando...
            </div>
            <div
              v-if="mailError"
              class="alert alert-danger alert-dismissible fade show"
              role="alert"
            >
              No pudimos enviar u consulta, intente de nuevo!
              <button
                type="button"
                class="close"
                data-dismiss="alert"
                aria-label="Close"
              >
                <span aria-hidden="true">&times;</span>
              </button>
            </div>
            <div
              v-if="mailSend"
              class="alert alert-success alert-dismissible fade show"
              role="alert"
            >
              Consulta enviada! un miembro de nuestro equipo se comunicará
              contigo.
              <button
                type="button"
                class="close"
                data-dismiss="alert"
                aria-label="Close"
              >
                <span aria-hidden="true">&times;</span>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      mailSend: false,
      mailError: false,
      mailSending: false,
      name: '',
      company: '',
      email: '',
      phone: '',
      message: ''
    }
  },

  methods: {
    onSubmit() {
      const api = 'https://wipargentina.com/backend/mail/mail.php'

      this.mailSend = false
      this.mailError = false
      this.mailSending = true

      this.$axios
        .post(api, {
          name: this.name,
          company: this.company,
          email: this.email,
          phone: this.phone,
          message: this.message
        })
        .then((response) => {
          this.mailSending = false
          if (response.data.success === 1) {
            this.mailSend = true
            this.name = ''
            this.company = ''
            this.email = ''
            this.phone = ''
            this.message = ''
          } else {
            this.mailError = true
          }
        })
    }
  }
}
</script>
<style lang="scss" scoped>
.form-control {
  border-radius: 0px;
  padding: 20px 16px;
}
.btn {
  font-weight: 400;
  letter-spacing: 0.06rem;
}
</style>
