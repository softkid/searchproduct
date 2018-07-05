<template lang="pug">
  footer.footer
    .container
      .content.has-text-centered
<<<<<<< HEAD
        p Designed by #[a(:href="'https://github.com/' + app.github.username",target="_blank") {{ app.author }}]. Licensed under #[a(href="http://opensource.org/licenses/MIT") MIT].
        p.social-buttons
          span(v-for="link in app.links",v-html="link")
        p
          a.icon(:href="'https://github.com/' + app.github.repo",target="_blank")
            i.ion-social-github
=======
        p Designed by #[ {{ app.author }} ]  Licensed SEARCH TEXTILE 
>>>>>>> 87904cfcc6c599c6286699bba58afcaad7d7e8ed
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