<template>
  <footer class="footer_area">
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-3 col-xl-2 col-lg-3 col-md-3 col-sm-3">
          <div class="footer-widget">
            <div class="footer-title">Navegación</div>
            <ul class="list-unstyled">
              <router-link to="/"><li>Sobre nosotros</li></router-link>
              <router-link to="/"><li>Blog</li></router-link>
              <router-link to="/"><li>Contacto</li></router-link>
              <router-link to="/"><li>Mapa del sitio</li></router-link>
            </ul>
          </div>
        </div>

        <div class="col-3 col-xl-2 col-lg-3 col-md-3 col-sm-3">
          <div class="footer-widget">
            <div class="footer-title">Colección</div>
            <ul class="list-unstyled">
              <router-link to="/products"
                ><li>Nuevos productos</li></router-link
              >
              <router-link to="/products"><li>Destacados</li></router-link>
              <router-link to="/products"><li>Catálogo</li></router-link>
              <router-link to="/products"><li>Marcas</li></router-link>
            </ul>
          </div>
        </div>

        <div class="col-3 col-xl-2 col-lg-3 col-md-3 col-sm-3">
          <div class="footer-widget">
            <div class="footer-title">Categorías</div>
            <ul class="list-unstyled">
              <router-link to="/products"><li>Insumos</li></router-link>
              <router-link to="/products"><li>Desechables</li></router-link>
              <router-link to="/products"><li>Equipos</li></router-link>
              <router-link to="/products"><li>Servicios</li></router-link>
            </ul>
          </div>
        </div>

        <div
          class="col-12 col-xl-6 col-lg-3 col-md-3 col-sm-12 text-left text-md-right pb-5"
        >
          <div class="footer-widget">
            <h4>Bucaramanga,</h4>
            <h4>Santander 810002</h4>
            <a href="mailto:#">new@mail.com</a>
            <h6>+999-999-999</h6>
          </div>
        </div>
      </div>

      <div class="row justify-content-between">
        <div class="col-xl-7 col-lg-6 col-md-6 col-sm-6 col-6">
          <div class="tiny-footer">
            <p>Copyright © All Rights Reserved 2022</p>
          </div>
        </div>
        <div class="col-4 col-xl-4 col-lg-4 col-md-4 col-sm-4 text-right">
          <div class="social-info">
            <strong>Redes Sociales</strong>
            <img class="twitter" src="@/assets/twitter.png" />
            <img class="pinterest" src="@/assets/pinterest.png" />
            <img class="facebook" src="@/assets/facebook.png" />
            <img class="instagram" src="@/assets/insta.png" />
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.footer_area {
  position: relative;
  z-index: 1;
  color: #2c3539;
  background-color: #fefefe;
}

.footer-widget {
  padding-top: 60px;
}

.footer-title {
  padding-bottom: 20px;
  font-weight: bold;
}

.list-unstyled a {
  text-decoration: none;
}

.list-unstyled a li {
  color: #2c3e50;
  margin-bottom: 10px;
}

.social-info > img {
  padding-left: 10px;
}

.social-info > img:hover {
  opacity: 0.7;
}
</style>
