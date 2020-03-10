<template>
  <section class="section section-medium contact">
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
                  <input
                    type="text"
                    placeholder="Nombre"
                    class="form-control"
                  />
                </div>
              </div>
              <div class="col-md-6">
                <div class="form-group">
                  <input type="text" placeholder="Email" class="form-control" />
                </div>
              </div>
            </div>
            <div class="form-group">
              <textarea
                name=""
                rows="4"
                placeholder="Contamos en que podemos ayudarte"
                class="form-control"
              ></textarea>
            </div>
            <button type="submit" class="btn btn-secondary btn-block py-2">
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
