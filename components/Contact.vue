<template>
  <section id="contact" class="section section-medium contact">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-md-7">
          <h2 class="display-3 mb-3">Contanos tu proyecto</h2>
          <p class="lead mb-5">
            Trabajamos junto a perfiles de empresas o personas que deseen
            cambiar su futuro, afianzando su presencia en internet
          </p>
          <form action="">
            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label for="">Nombre y Apellido</label>
                  <input type="text" class="form-control" />
                </div>
              </div>
              <div class="col-md-6">
                <div class="form-group">
                  <label for="">Email</label>
                  <input type="text" class="form-control" />
                </div>
              </div>
            </div>
            <div class="form-group">
              <label for="">Contamos en que podemos ayudarte</label>
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
