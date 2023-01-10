<script>
export default {
    name: "AppHero",
    data() {
        return {
            AppHero: '/public/jumbo.jpg'
        }
    },
}
</script>
<template>
        <img :src="AppHero" alt="">
</template>
<style>
    
</style>