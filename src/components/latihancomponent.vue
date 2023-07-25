<template>
    <div v-if="age > 18">
        <b>Selamat Datang {{ name }}</b>
    </div>
    <div v-else>
        <b>Maaf Kamu Belum Cukup Umur</b>
    </div>
    <button @click="greet">Sapa</button>
</template>

<script>
export default {
    props: ['name', 'age'],
    methods: {
        greet() {
            alert(" Hallo " + this.name);
        }
    },
}

</script>