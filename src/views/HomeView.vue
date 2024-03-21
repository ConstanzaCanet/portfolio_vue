<template>
    <div class="content">
        <HeaderVue/>
        <AboutVue/>
        <ProyectsVue/>
        <ContactVue/>
    </div>
</template>

<script setup>

import HeaderVue from '@/components/HeaderVue.vue';
import AboutVue from '@/components/AboutVue.vue';
import ProyectsVue from '@/components/ProyectsVue.vue';
import ContactVue from '@/components/ContactVue.vue';

</script>

<style lang="scss">

.content{
    margin: 0px;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #FFFFFF;
    background: #17aecd;
    font-family: $title_fam;
}
</style>