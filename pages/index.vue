<template>
  <section class="container">
    <div class="page-header">
	  <Topbanner/>
      <Menu/>
    </div>
    <div class="wrapper">
    	<div class="wrapper__content">
    		<Searchpanel/>
    	</div>
    </div>
  </section>
</template>

<script>
import Topbanner from '~/components/Topbanner.vue'
import Menu from '~/components/Menu.vue'
import Searchpanel from '~/components/Searchpanel'

export default {
  components: {
    Topbanner,
    Menu,
    Searchpanel
  }
}
</script>

<style>

html {
    font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    font-size: 16px;
    word-spacing: 1px;
}

.container {
	
}

.page-header {
	position: relative;
    z-index: 10;
}

.wrapper {
	display: block;
	min-height: 100%;
    padding-bottom: 412px;
    box-sizing: border-box;
    height: auto;
    position: relative;
    z-index: 2;
}

.wrapper__content {
	box-sizing: border-box;
    position: relative;
    height: 100%;
    z-index: 1;
}

</style>