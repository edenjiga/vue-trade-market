<template>
<div><h1>Trade or View you portfolio
  <h6>You may save & Load your <datagrid><h6>Click on 'End Day' to begin a New Day!
    <hr><p>Your Funds: {{funds | currency}}</p></h6></datagrid></h6>
</h1>
</div></template>

<script>
export default {
  computed: {
    funds() {
      return this.$store.getters.funds;
    }
  }
};
</script>