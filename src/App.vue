<template>
  <div id="app">
    <b-navbar toggleable="md" type="dark" variant="dark">
      <b-container>
         <b-navbar-brand href="#">NavBar</b-navbar-brand>
          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
            <b-collapse id="nav-collapse" is-nav>
              <b-navbar-nav>
                <b-nav-item :to="{name:'Home'}">Home</b-nav-item>
                <b-nav-item :to="{name:'About'}">About</b-nav-item>
              </b-navbar-nav>
            </b-collapse>

      </b-container>
    
    </b-navbar>
    <router-view />
  </div>
</template>
<script>
export default {
  components: {},
};
</script>













