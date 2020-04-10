<template>
<div id="nav">
  <router-link :to="$i18nRoute({ name: 'Home' })">
    Home
  </router-link>

  <br>

  <router-link :to="$i18nRoute({ name: 'About' })">
    About
  </router-link>
</div>
</template>
