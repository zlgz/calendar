<template>
    <el-calendar v-model="value">
    </el-calendar>
</template>

<script>
    export default {
        name: 'calendar',
        data() {
            return {
                value: new Date()
            }
        }
    }
</script>

<style>
</style>
