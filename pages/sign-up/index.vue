<template>
  <app-sign-up/>
</template>

<script>
  export default {
    components: {
      appSignUp: () => import('~/components/registration/SignUp')
    }
  }

</script>

<style scoped>

</style>
