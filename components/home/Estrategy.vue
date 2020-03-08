<template>
  <section class="section section-medium estrategy">
    <div class="container">
      <h2 class="display-4">¿En que fase esta tu negocio?</h2>
      <div class="divider"></div>
      <img
        src="https://images.unsplash.com/photo-1543286386-2e659306cd6c?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=900&q=80"
        alt=""
        class="image"
      />
      <div class="row">
        <div class="col-md-3">
          <div class="card">
            <div class="card-body">
              <ion-icon name="bulb-outline"></ion-icon>
              <h3>Builders</h3>
              <p>
                Tenemos que construir nuestra marca y deseamos iniciar en el
                mundo digital
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="card">
            <div class="card-body">
              <ion-icon name="magnet-outline"></ion-icon>
              <h3>Finders</h3>
              <p>
                Queremos explorar nuevos mercados y saber donde estan nuestros
                clientes
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="card">
            <div class="card-body">
              <ion-icon name="heart-outline"></ion-icon>
              <h3>Loyalters</h3>
              <p>
                Necesitamos implementar estrategias para cuidar y fidelizar
                nuestros clientes
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="card">
            <div class="card-body">
              <ion-icon name="rocket-outline"></ion-icon>
              <h3>Xpanders</h3>
              <p>
                Vamos por todo, <br />
                estamos listos para llevar nuestra organización a tope
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Estrategy'
}
</script>

<style lang="scss">
.image {
  height: 300px;
  width: 100%;
  margin: 50px 0;
  object-fit: cover;
  object-position: center;
}

.card {
  text-align: center;
  background-color: transparent;
  border: 0px;

  .card-body {
    ion-icon {
      font-size: 2.6rem;
      margin-bottom: 0;
      color: #777;
    }
    h3 {
      font-weight: 400;
      margin: 4px 0 16px 0;
      text-transform: uppercase;
    }
  }
}
</style>
