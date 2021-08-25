<template>
 <div id="main-layout">
    <main class="main-wrap">
      <Navbar/>
      <section class="main-content">
        <nuxt />
      </section>
    </main>
    <aside class="right-sidebar">
    </aside>
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'

export default {
  components: { Navbar }
}
</script>

<style lang="scss" scoped>
  #main-layout {
    display: flex;
    width: 100%;
    height: 100%;
    min-height: 100vh;
    font-family: "Montserrat", sans-serif;

    .main-wrap {
      width: 62%;
      background: #e0ebf1;
    }

    .main-content {
      overflow: hidden;
    }

    .right-sidebar {
      position: relative;
      width: 38%;
      height: 100%;
      background-color: #fff;
      padding: 76px 95px;
      display: flex;
      justify-content: center;
      align-items: flex-start;
    }
  }
</style>
