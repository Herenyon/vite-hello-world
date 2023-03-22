<script setup>


defineProps({
    msg: String,
})


</script>

<template>
    <div class="container-jumbo">
        <h1 class="jumbotron">{{ msg }}</h1>
    </div>
</template>


