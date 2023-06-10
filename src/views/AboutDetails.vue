<template>
    <h1>About Me</h1>
    <p>Nama : Muhammad Ammar Hamdi <br>Asal : Pekanbaru <br>Email : muhammadammarhamdi@student.uir.ac.id<br> {{ id }}</p>
</template>

<script>
export default {
    props: ['id'],
    // data() {
    //     return {
    //         id: this.$route.params.id
    //     }
    // }
}
</script>