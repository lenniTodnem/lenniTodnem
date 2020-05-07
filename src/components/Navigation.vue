<template>
  <div>
      <b-navbar toggleable="lg" type="dark" variant="dark" fixed="top">
    <b-navbar-brand href="/home">Unique</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item>
            <b-link to="/jobs">Jobs</b-link></b-nav-item>

          <b-button size="sm" class="mb-2">
            <b-link to="/login">
                <b-icon icon="gear-fill" aria-hidden="true"></b-icon>
            </b-link>
            Login
        </b-button>

      </b-navbar-nav>

    </b-collapse>
      </b-navbar>
  </div>
</template>

<script>

</script>

<style scoped>
#right{
    float: right;
}
</style>
