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
          <form
            action=""
            data-aos="fade-up"
            data-aos-delay="0"
            data-aos-duration="1000"
            data-aos-mirror="false"
            data-aos-once="true"
          >
            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label for="">Dejanos tu nombre</label>
                  <input
                    type="text"
                    class="form-control"
                    placeholder="Elon Musk"
                  />
                </div>
              </div>
              <div class="col-md-6">
                <div class="form-group">
                  <label for="">Tu email</label>
                  <input
                    type="text"
                    class="form-control"
                    placeholder="elon@musk.com"
                  />
                </div>
              </div>
            </div>
            <div class="form-group">
              <label for="">Contanos cómo podemos ayudarte</label>
              <textarea name="" rows="4" class="form-control"></textarea>
            </div>
            <div class="d-md-flex justify-content-between text-center">
              <button
                type="submit"
                class="btn btn-primary px-5 py-3 mt-3 mb-3 mb-md-0"
              >
                ENVIAR
              </button>
              <a
                href=""
                class="btn btn-outline-secondary px-5 py-3 mt-3 d-md-flex align-items-center"
                ><ion-icon name="logo-whatsapp"></ion-icon>
                <span class="ml-2">ESCRIBINOS</span></a
              >
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

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
