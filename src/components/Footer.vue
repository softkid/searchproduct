<template lang="pug">
  footer.footer
    .container
      .content.has-text-centered
        p Designed by #[ {{ app.author }} ]  Licensed SEARCH TEXTILE 
</template>

<script>
import config from '~config'

export default {
  computed: {
    app() {
      return config.app
    }
  }
}
</script>

<style lang="sass" scoped>
.social-buttons
  span
    margin: 0 3px  
</style>