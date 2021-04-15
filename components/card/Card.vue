<template>
  <NuxtLink :to="link" class="card-link">
    <div>{{ text }}</div>
  </NuxtLink>
</template>

<script lang="ts">
import { Vue, Component, Prop } from 'vue-property-decorator'

@Component
export default class Card extends Vue {
  @Prop({ type: String, default: '/' }) readonly link: string | undefined
  @Prop(String) readonly icon: string | undefined
  @Prop(String) readonly text: string | undefined

  name = 'Card'
};
</script>

<style lang="scss" src="./card.scss" />
