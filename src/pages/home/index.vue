<template>
    <div>
            hello 
    </div>
</template>

<script setup lang='ts'>
import { ref } from "vue" 
// .env.development
 let flag = import.meta.env.VITE_BASE_API
 console.log(flag);
 
</script>

<style lang="scss" scoped>

</style>