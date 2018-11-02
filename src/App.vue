<template>
  <v-app dark>

    <v-content style="background: url(art.jpg); background-size: cover; background-repeat: no-repeat; background-position: center center;">
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data () {
    return {
      //
    }
  }
}
</script>
