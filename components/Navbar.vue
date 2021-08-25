<template>
  <nav id="navbar">
    <div class="container">
      <div class="navbar-block">

      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style lang="scss" scoped>
  #navbar {
    padding-top: 64px;
    padding-bottom: 20px;

    .navbar {
      &-block {
        display: flex;
        justify-content: space-between;
        align-items: center;
      }
    }
  }
</style>
