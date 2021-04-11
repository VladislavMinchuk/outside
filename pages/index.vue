<template>
  <section class="dashboard-cards">
    <Card
      icon="astronaut"
      text="astronauts"
    />
  </section>
</template>

<script>
import { Vue, Component, Prop } from 'vue-property-decorator'
import Card from '@/components/card'

export default class MainPage extends Vue {
  name = 'HomePage'
  layout = 'dashboard/index'
}
</script>
