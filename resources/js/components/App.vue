<template>
    <section class="bg-gray-50 dark:bg-gray-900">
        <Navbar></Navbar>
        <div class="flex flex-col items-center justify-center px-6 py-8 mx-auto md:h-screen lg:py-0">
          
        </div>
    </section>
</template>

<script>
import Card from './Card/Card.vue';
import Navbar from './Navbar/Navbar.vue';

export default{
    components: {
        Card, Navbar
    }
}
</script>