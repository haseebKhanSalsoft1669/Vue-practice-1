<template>
<div class="card">
    <h2>{{ twoboxes.title }}</h2>
    <img :src="twoboxes.image" >
    <p>{{ twoboxes.description }}</p>
</div>
</template>

<script>
export default {
    props:['twoboxes']
}
</script>