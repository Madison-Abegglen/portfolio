<template>
  <div class="home container-fluid">
    <navbar></navbar>
    <div class="row">
      <div class="col-12">
        <h1>This is the home screen</h1>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import navbar from "@/components/navbar.vue";

export default {
  name: "home",
  components: {
    navbar
  }
};
</script>
