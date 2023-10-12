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
                <slot/>
            </div>
        </div>
    </section>
</template>





<script lang="ts" setup>
defineProps<{
    date: string,
}>()

</script>





<style lang="scss" scoped >
.v-app-date {
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

        //@media (max-width: 1100px) {
        //    font-size: .7rem;
        //    line-height: .8rem;
        //    margin-top: 1rem;
        //    margin-bottom: 1rem;
        //}
        //
        //@media (max-width: 750px) {
        //    font-size: .6rem;
        //    line-height: .7rem;
        //    margin-top: 1rem;
        //    margin-bottom: 1rem;
        //}
    }
}

</style>
