<template>
    <div class="container">
        <p v-for="(guest, index) in guests" :key="index">
            {{ guest }}
        </p>
    </div>
</template>
<script>
export default {
    data() {
        return {
            guests: ["Manz",
                "Alejandro",
                "Brais",
                "Bárbara",
                "Daniel",
                "David",
                "Diego",
                "Guillermo",
                "Guillermo",
                "Hilario",
                "Ignacio",
                "Iván",
                "Javier",
                "José Javier",
                "Luz Marina",
                "Marta",
                "Octavian",
                "Samuel"
            ]

        }
    },
}
</script>
<style scoped>
.container {
    display: grid;
    background-color: #f9f961;
    width: 400px;
    justify-content: end;
    flex-direction: column;
    grid-template-columns: 1fr 1fr;


    & p {
        margin: 0;
        font-size: 1.5em;
        font-family: 'Dancing Script', cursive;

    }
}
</style>