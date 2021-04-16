<template>
  <section class="dashboard-cards">
    <Card
      icon="icon-astronaut-user"
      text="astronauts"
      link="/astronauts"
    />
  </section>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'

@Component({ layout: 'dashboard/index' })
export default class MainPage extends Vue {
  name = 'HomePage'
}
</script>

<style lang="scss" src="./home.scss" />
