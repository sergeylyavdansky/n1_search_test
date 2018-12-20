<template>
  <section class="container">
    <div>
	  <Topbanner/>
      <Menu/>
    </div>
  </section>
</template>

<script>
import Topbanner from '~/components/Topbanner.vue'
import Menu from '~/components/Menu.vue'

export default {
  components: {
    Topbanner,
    Menu
  }
}
</script>

<style>

html {
    font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    font-size: 16px;
    word-spacing: 1px;
}

</style>