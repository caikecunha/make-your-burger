<template>
  <Banner />
  <div class="main-container">
    <h1>Gerenciar pedidos</h1>
    <Dashboard />
  </div>
</template>

<script>
  import Banner from '@/components/Banner.vue';
  import Dashboard from '@/components/Dashboard.vue';

  export default {
    components: {
      Banner,
      Dashboard,
    }
  }
</script>
