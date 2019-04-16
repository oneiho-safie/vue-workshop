<template>
  <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
    <a class="navbar-brand" href="#">Vue Workshop</a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarsExampleDefault"
      aria-controls="navbarsExampleDefault"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarsExampleDefault">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <router-link class="nav-link" to="/"
            >Home <span class="sr-only">(current)</span></router-link
          >
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/about"
            >About <span class="sr-only">(current)</span></router-link
          >
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/workshop"
            >Workshop <span class="sr-only">(current)</span></router-link
          >
        </li>
      </ul>
    </div>
  </nav>
</template>

<script lang="js">
export default {
  name: 'NavbarHeader',
  components: {},
  computed: {},
  watch: {},
  data () {
    return {

    }
  },
  created () {},
  methods: {}
}
</script>

<style lang="scss" scoped></style>
