<template>
  <div id="app" class="h-100 d-flex flex-column align-items-center justify-content-center">

    <div class="w-100 text-center my-auto">
      <img id="logo" src="./assets/images/logo.png" :alt="title" class="img-fluid">

      <h1 id="title" class="sr-only display-1 my-3 text-warning">
        {{ title }}
      </h1>
    </div>

    <footer class="mb-0 py-2">
      <div class="container">
        <div class="text-center text-muted">
          &copy;
        </div>
      </div>
    </footer>

  </div>
</template>

<script>
export default {
  data () {
    return {
      title: 'MagicRL'
    }
  }
}
</script>

<style src="./assets/main.scss" lang="scss"></style>
