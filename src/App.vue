<center></center>
<script setup>
import { ref } from 'vue'

let message = "Ini warna merah"
let rawHtml = "<li>Gimana Kabarmu lek?</li>"

</script>

<template>
  <div id="app">
    <h1>{{ message }}</h1>
    <span v-html="rawHtml"></span>
    <span v-html="message" style="color: red"></span> <br>
    <button :disabled="isButtonDisabled" onclick="alert('mana hutang mu?')">Baek</button>
    <button :disabled="isButtonDisabled" onclick="alert('kabar baik? tapi hutang ga dibayar? MANA PATEN')">Allhamdulillah lek</button> <br>

    <a v-bind:href="url">Klik lah lek link nya</a> <br>
    
    <input type="email" placeholder="Masukkan email anda"> <br>
    <input type="password" placeholder="Masukkan password">
  </div>
</template>