<template>
<mycomponent nama="Angga" umur="17"></mycomponent>
<footer sms="ini footer"></footer>      
<latihancomponent name="Febri" age="20"></latihancomponent>
<Latihanduacomponent></Latihanduacomponent>
<whatcherscomponent nama="johan" umur="92"></whatcherscomponent>
 </template>

<script setup>
import mycomponent from './mycomponent.vue';
import footer from './footer.vue';
import latihancomponent from './latihancomponent.vue';
import Latihanduacomponent from './latihanduacomponent.vue';
import latihanduacomponent from './latihanduacomponent.vue';
import whatcherscomponent from './whatcherscomponent.vue';

// event
import { ref } from 'vue';
const nama = ref('John');
const umur = ref(25);

const onGreeted = () => {
    console.log('Kamu udah disapa bro!')
}

</script>

<style>

</style>