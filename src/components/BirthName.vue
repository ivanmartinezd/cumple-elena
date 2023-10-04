<template>
    <div class="text-container">
        <h1>Feliz Cumple {{ username }}</h1>
        <p>ya tienes un año menos de Garantia
            Juvenil</p>
    </div>
</template>
<script>
export default {
    name: "BirthName",
    props: {
        username: {
            type: String

        }
    }


}
</script>
<style scope>
h1 {
    margin: 0;
    margin-top: 4rem;
    font-family: 'Dancing Script', cursive;
    color: rgb(250, 114, 186);
    text-shadow: 2px 2px 0 rgb(20, 20, 20);
}

.text-container {
    font-size: 2em;
    display: flex;
    flex-direction: column;
    align-items: center;
}
</style>