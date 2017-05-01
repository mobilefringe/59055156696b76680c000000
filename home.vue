<template>
  <div>
  <div class="row">
    <div class="large-6 columns">
      <h1 v-bind="title"></h1>
      <p v-bind="description"></p>
    </div>
  </div>
  </div>
</template>

<script>
  define(["Vue"], function(Vue) {
    return Vue.component("home-component", {
      template: template, // the variable template will be injected
      data: function() {
        return {
          title: "MM with Vue.js!",
          description: "An example of integration of Mall Maverick with Vue.js"
        }
      }
    })
  })
</script>
