<template>
  <div class="dashboard_grid">
    <header class="dashboard__header">
      header
    </header>
    <nav class="dashboard__nav">
      <h1>Outside</h1>
      <ul>
        <li>Item 1</li>
        <li>Item 2</li>
      </ul>
    </nav>
    <main class="dashboard__main">
      <Nuxt />
    </main>
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'

@Component
export default class DashboardLayout extends Vue {
}
</script>

<style lang="scss" src="./dashboard.scss" />
