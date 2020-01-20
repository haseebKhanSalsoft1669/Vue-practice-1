<template>
<div class="card shadow">
    <h2>{{ box.title }}</h2>
    <img :src="box.image" >
    <p>{{ box.description }}</p>
</div>
</template>
<style>

.card{
    padding:20px;
    margin:0 0 20px;
}
</style>
<script>
export default {
    props:['box']
}
</script>
