<script>

import headerTop from './headerTop.vue';
import headerBottom from './headerBottom.vue';

    export default {
        components: {
            headerTop,
            headerBottom
        }
}

</script>

<template>
    <header>
        <headerTop></headerTop>
        <headerBottom></headerBottom>
    </header>
</template>

<style scoped lang="scss">

</style>
