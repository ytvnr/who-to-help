<template>
  <div class="body">
    <gv-card :item='{"name":"Testing Gravitee component"}'></gv-card>
  </div>
</template>

<script>
import '@gravitee/ui-components/wc/gv-card';

export default {
  name: 'HelloWorld',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.body {
  display: flex;
  flex-direction: row;
  justify-content: center;
  padding-top: 25px;
  height: calc(100vh - #{$headerHeight});
  background-color: var(--gv-theme-font-color-light);
}
</style>
