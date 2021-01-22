<template>
      <div :style="{'background-image':'url(https://giphy.com/gifs/3o6Zt481isNVuQI1l6/html5) '}"></div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {}
}

</script>
<style lang="css">
  .flex-center {
    display: flex;
    justify-content: center;
  }
  .home {
    &-content {
      max-width: 50vh;
      min-width: 400px;
    }
  }
</style>
