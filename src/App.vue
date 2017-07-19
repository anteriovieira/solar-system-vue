<template>
  <div id="app" class="opening hide-UI view-3D zoom-large data-close controls-close">
    <navbar></navbar>
    <controls></controls>

    <universe>
      <galaxy>
        <solar-system>
          <earth></earth>
          <jupiter></jupiter>
        </solar-system>
      </galaxy>
    </universe>
    
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import Controls from './components/Controls'

import Universe from './components/Universe'
import Galaxy from './components/Galaxy'
import SolarSystem from './components/SolarSystem'

import Earth from './components/Earth'
import Jupiter from './components/Jupiter'

export default {
  name: 'app',
  components: {
    Navbar, Controls, Universe, Galaxy, SolarSystem, Earth, Jupiter
  },
  mounted () {
    // this.$el.removeClass('view-2D opening').addClass('view-3D').delay(2000).queue(() => {
    //   this.$el.removeClass('hide-UI').addClass('set-speed')
    //   this.$el.dequeue()
    // })
  }
}
</script>

<style>
@import './assets/app.css';
</style>
