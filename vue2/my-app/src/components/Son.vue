<template>
    <div class="son">
        <h1>{{title}}</h1>
    </div>
</template>

<script>
export default {
    props:['title']
}
</script>

<style scoped>
 .son{
    border:5px solid #999;
    padding: 50px;
    }
</style>