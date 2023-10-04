<template>
    <div class="container">
        <BirthName username="Elena" />
        <BirthCake />
        <BirthdayGuests />
    </div>
</template>

<script>
import BirthCake from '@/components/BirthCake.vue';
import BirthName from '@/components/BirthName.vue';
import BirthdayGuests from '@/components/BirthdayGuests.vue';

export default {
    name: "App",

    components: {
        BirthCake,
        BirthName,
        BirthdayGuests
    },
    data() {

        return {



        }

    },

}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap');

body {
    background-color: #3E86F5;
}
</style>