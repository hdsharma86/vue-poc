<template>
    <v-app>
        <Header />
        <v-content>
        <Drawer />
        <div class="page-content">
            <HelloWorld/>
        </div>
        </v-content>
    </v-app>
</template>

<style>
  .page-content{
    width:94%;
    float:right;
    position:relative;
    z-index: 1;
  }
</style>

<script>
import HelloWorld from './HelloWorld';
import Drawer from './Drawer';
import Header from './Header';

export default {
  name: 'App',
  components: {
    HelloWorld,
    Drawer,
    Header
  },
  data () {
    return {
        drawerIsOpen: true,
    }
  },
  methods: {
      toggleDrawer: function(){
          console.log('Hi');
      }
  }
};
</script>