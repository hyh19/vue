<template>
    <div>{{ $route.params.id }}</div>
</template>
<script>
    export default {
        method () {
            console.log(this.$route.params.id);
        }
    }
</script>