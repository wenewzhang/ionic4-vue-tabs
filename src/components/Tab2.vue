
<template>
  <ion-page
    class="ion-page">
    <ion-header>
      <ion-toolbar color="primary">
        <ion-title>Ionic4 VueJS: Tab 2</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content padding>
      <ion-item>
        THIS IS TAB 2
      </ion-item>
      <ion-item v-model="tabshow">
        Show
      </ion-item>
    </ion-content>
  </ion-page>
</template>

<script>
export default {
  name: 'tab2',
  data() {
    return {
      tabshow: false
    }
  }
}
</script>

<style>
</style>
