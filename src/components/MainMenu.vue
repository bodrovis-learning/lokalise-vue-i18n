<template>
<div id="nav">
  <router-link :to="{ name: 'Home', params: { lang: this.$i18n.locale }}">
    Home
  </router-link>

  <br>
  
  <router-link :to="{ name: 'About', params: { lang: this.$i18n.locale }}">
    About
  </router-link>
</div>
</template>
