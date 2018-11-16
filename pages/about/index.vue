<template>
  <section class="container">
    <div>
      <h1 class="title">
        about
      </h1>
      <h2 class="subtitle">
        My world-class Nuxt.js about
      </h2>
      <div class="links">
        {{ detail }}
      </div>
    </div>
  </section>
</template>
<script>
export default {
  data() {
    detail: 'hogehoge hoge'
  }
}
</script>
