<template>
  <v-card dark>
    <v-row justify="center">
      <v-col>
        <v-row justify="center">
          <v-col cols="5">
            <v-card light>
              <v-card-title class="text-capitalize">
                local animation
              </v-card-title>
              <v-card-text>
                In here, stage 2 (gear spins) runs with
                stage1 ... check
                <code>/src/components/svg/Process.vue</code>
                <v-divider />
                <Process />
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
      </v-col>
      <v-col>
        <v-card-title class="text-capitalize">
          reference animation on codepen
        </v-card-title>
        <v-card-text>
          The concept here is simple, having 2 stages of animations...
          using <pre>gsap utils</pre>
          <iframe src="https://codepen.io/nasr3090/pen/VweNvdg" width="100%" height="600"></iframe>
        </v-card-text>
      </v-col>
    </v-row>
  </v-card>
</template>

<script>
import Process from './svg/Process.vue'
export default {
  name: 'HelloWorld',
  components: { Process },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
