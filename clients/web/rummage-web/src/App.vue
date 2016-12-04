<template>
  <div id="app">
    <site-header></site-header>
    <site-content></site-content>
  </div>
</template>

<script>
import SiteHeader from './components/SiteHeader'
import SiteContent from './components/SiteContent'

export default {
  name: 'app',
  components: {
    SiteHeader,
    SiteContent
  }
}
</script>
