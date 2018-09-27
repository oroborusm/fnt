<template>
  <div class="container">
    <nav class="navbar navbar-light bg-light fadeIn animated">
      <img alt="Vue logo" class="navbar-brand" src="../assets/logo.png">

      <div class="nav">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <p class="nav-link">¿Cómo Funciona?</p>
          </li>
          <li class="nav-item">
            <p class="nav-link">19%</p>
          </li>
          <li class="nav-item">
            <p class="nav-link">Equipo</p>
          </li>
          <li class="nav-item">
            <p class="nav-link">Blog</p>
          </li>

          <li class="nav.item">
          </li>

          <li class="nav-item">
            <p class="nav-link">¿Cómo Funciona?</p>
          </li>
          <li class="nav-item">
            <p class="nav-link">
              <i class="material-icons">
                card_giftcard
              </i>
            </p>
          </li>
          <li class="nav-item">
            <p class="nav-link salir">Salir</p>
          </li>

        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
  export default {

  }
</script>

<style lang="sass" scoped>
nav
  border-radius: 8px
  box-shadow: 0 0 16px rgba(black, .1)
  padding: 16px
.nav
  .navbar-nav
    flex-direction: row
    .nav-item
      margin-right: 24px
      .nav-link
        margin-bottom: 0 !important
.salir
  color: #22A793 !important

@media (max-width: 1000px)
  .nav
    display: none
</style>

