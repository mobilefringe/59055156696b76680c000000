<template>
  <div>
    {{text}}
  </div>
</template>

<script>
  define(["Vue"], function(Vue) {
    return Vue.component("not-found-component", {
      template: template, // the variable template will be injected 
      data: function() {
        return {"text": "404 not found"};
      }
    });
  });
</script>