<template>
  <div>
    <div>{{ text }}</div>
  </div>
</template>

<script lang="ts">
import { Vue, Component, Prop } from 'vue-property-decorator'

@Component
export default class Card extends Vue {
  @Prop(String) readonly icon: string | undefined
  @Prop(String) readonly text: string | undefined

  name = 'Card'
};
</script>
