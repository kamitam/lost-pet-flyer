<template>
  <div class="container">
    <div>
      <equallheader />
    </div>
    <div>
      <logo />
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Equallheader from '~/components/Equallheader.vue'

export default {
  components: {
    Logo,
    Equallheader
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;
}

</style>
