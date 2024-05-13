<script>

import OfferteLampo from './OfferteLampo.vue'
import MadeInItaly from './MadeInItaly.vue'
import CardSection from './CardSection.vue'

export default {
    components: {
        OfferteLampo,
        MadeInItaly,
        CardSection
    }
}

</script>

<template>
    <main>
        <OfferteLampo></OfferteLampo>
        <MadeInItaly></MadeInItaly>
        <CardSection></CardSection>
    </main>
</template>

<style scoped lang="scss"></style>