<template>
  <div class="father">
      <h1>父组件</h1>
      <Son title="hello world" />
  </div>
</template>

<script>
import Son from './Son'
export default {
    components:{
        Son
    }
}
</script>

<style scoped>
.father{
    border:5px solid #ddd;
    padding: 50px;
    }
</style>