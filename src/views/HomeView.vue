<template>
  <header>
    <Navbar></Navbar>
    <Header></Header>
  </header>
</template>

<script>
import Navbar from '@/components/home/header/NavbarModal.vue';
import Header from '@/components/home/header/HeaderContent.vue';

export default {
  name: 'HomeView',
  components: {
    Navbar,
    Header,
  },
};
</script>
