<template>
  <section id="contact" class="section section-medium contact">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-md-8">
          <h2 class="display-3 mb-3">¿En que fase está tu negocio?</h2>
          <p class="lead mb-5 d-none">
            Trabajamos junto a perfiles de empresas o personas que deseen
            cambiar su futuro, afianzando su presencia en internet
          </p>
          <p class="lead mb-5">
            Nos encantan los desafíos y estamos muy motivados en ponernos a
            trabajar juntos para cambiar el futuro de tu negocio, queremos
            afianzar y hacer crecer tu presencia en internet.
          </p>
          <form action="">
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
                  <input type="text" class="form-control" placeholder="" />
                </div>
              </div>
            </div>
            <div class="form-group">
              <label for="">Contamos cómo podemos ayudarte</label>
              <textarea name="" rows="4" class="form-control"></textarea>
            </div>
            <button type="submit" class="btn btn-primary px-5 py-3 mt-3">
              ENVIAR
            </button>
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
