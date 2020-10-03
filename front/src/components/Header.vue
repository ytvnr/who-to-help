<template>
    <gv-header
      :item='{"name":"Who to help ?",
      "_links":{"picture":"static/help.png"},
      "version":"v.0.1"}'>
    </gv-header>
    <gv-nav class="nav" :routes='[
      {"path":"","title":"My skills", active: true},
      {"path":"/help-me","title":"Help me!"}
      ]'>
    </gv-nav>
</template>

<script>
import '@gravitee/ui-components/wc/gv-header';
import '@gravitee/ui-components/wc/gv-nav';

export default {
  name: 'Header',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.nav {
  display: flex;
  flex-direction: row;
  justify-content: center;
}
</style>
