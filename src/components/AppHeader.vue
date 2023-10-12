<template>
    <header class="v-app-header" >
        <img
            class="v-app-header__logo"
            src="../assets/logo_cinematographe.svg"
            alt="logo cinematographe.ch"
        />
        <div
            class="v-app-header__info"
        >OUVERTURE EN MARS&nbsp;2024</div>
    </header>
</template>





<script lang="ts" setup>

</script>





<style lang="scss" scoped >
.v-app-header {
    background-color: rgba(255, 255, 255, .94);
    height: var(--lc-header-height);
    flex-direction: column;
    display: flex;
    justify-content: center;
    align-items: center;
}

.v-app-header__logo {
    display: block;
    height: 1.5rem;
    margin: 0 auto;
    max-width: 90vw;
}

.v-app-header__info {
    font-size: .6rem;
    line-height: .6rem;
    color: var(--lc-color);
    text-align: center;
}
</style>
