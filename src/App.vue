<template>
  <div id="app">
    <navbar-header />
    <main role="main">
      <router-view />
    </main>
  </div>
</template>

<script>
import NavbarHeader from '@/components/NavbarHeader'

export default {
  name: 'App',
  components: {
    NavbarHeader
  }
}
</script>


<style lang="scss">
body {
  padding-top: 3.5rem;
}

main {
  padding-top: 2rem;
}

.box {
  box-shadow: 0 0 1px rgba(0,0,0,.15);
  background-color: #fff;
  position: relative;
  margin-bottom: 1.5rem;
}

.box-body, .box-footer {
  padding: 1rem;
}
</style>

<style lang="scss" src="@/assets/scss/util.border.scss"></style>
<style lang="scss" src="@/assets/scss/util.spacing.scss"></style>

