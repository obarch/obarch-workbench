<template>
    <div>{{ message }}</div>
</template>
<script lang="ts">
export default {
    data() {
        let message: string = 'hello'
        return {
            message: message
        }
    }
}
</script>