 <template>
    <div>
       <p>Nama : {{ nama }}</p>
       <p>Umur : {{ umur }}</p>
    </div>
 </template>

<script>
export default {
    props: ['nama', 'umur'],
    data() {
        return {
            message: "Ini adalah pesan dari komponen"
        }
    },
    methods: {
        greet() {
            console.log("hallo")
        }
    },
}
</script>

<style>
h1 {
    color: blue;
}

p {
    size: 16px;
}
</style>
