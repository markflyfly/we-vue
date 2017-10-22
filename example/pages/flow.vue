<template>
  <div>
    <wv-flow>
      <wv-flow-node :done="true" title="title">1</wv-flow-node>
      <wv-flow-line type="process"></wv-flow-line>
      <wv-flow-node title="title">2</wv-flow-node>
      <wv-flow-line></wv-flow-line>
      <wv-flow-node title="title">3</wv-flow-node>
      <wv-flow-line></wv-flow-line>
      <wv-flow-node title="title">4</wv-flow-node>
    </wv-flow>

    <wv-flow>
      <wv-flow-node :done="true" title="title">1</wv-flow-node>
      <wv-flow-line type="process"></wv-flow-line>
      <wv-flow-node title="title">2</wv-flow-node>
      <wv-flow-line></wv-flow-line>
      <wv-flow-node title="title">3</wv-flow-node>
      <wv-flow-line></wv-flow-line>
      <wv-flow-node title="title">4</wv-flow-node>
    </wv-flow>
  </div>
</template>

<script>
  export default {
    data () {
      return {
      }
    },

    methods: {
    },

    mounted () {
    }
  }
</script>

<style scoped lang="scss">
</style>
