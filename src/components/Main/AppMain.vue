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
        <div class="container">
            <MadeInItaly></MadeInItaly>
            <OfferteLampo></OfferteLampo>
            <CardSection></CardSection>
        </div>
    </main>
</template>

<style scoped lang="scss"></style>