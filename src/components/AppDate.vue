<template>
    <section class="v-app-date" >
        <h3
            class="v-app-date__date"
        >{{date}}</h3>
        <div
            class="v-app-date__slot"
        >
            <div
                class="v-app-date__slot__content"
            >
                <div>
                    <slot/>
                </div>
                <img
                    v-if="src"
                    class="v-app-date__img"
                    alt="article cover"
                    :src="src"
                >
            </div>
        </div>
    </section>
</template>





<script lang="ts" setup>
defineProps<{
    date: string,
    src?: string,
}>()

</script>





<style lang="scss" scoped >
.v-app-date {
}

.v-app-date__slot__content {

}

.v-app-date__slot {
    box-sizing: border-box;
    padding-left: 5rem;

    @media (max-width: 900px) {
        padding-left: 0;
    }

    .v-app-date__slot__content {
        border-top: solid 1px white;
        border-bottom: solid 1px white;
        padding-top: 1rem;
        padding-bottom: 1rem;
    }
}

.v-app-date__img {
    display: block;
    width: 100%;
    max-width: 10rem;
}

</style>
