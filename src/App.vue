<template>
    <div :class="$style.amazinq">Hello {{ vue }}!</div>
</template>
<script lang="ts">
export default {
    data() {
        return {
            vue: 'Vue'
        }
    }
}
</script>
<style module>
.amazinq {
    color: red;
}
</style>