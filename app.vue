<template>
  <div class="container mx-auto">
    <QCard 
      title="The Coldest Sunset"
      description="lorem ipsum dolar"
      :clicked="klik"
    >
    </QCard>
  </div>
</template>

<script setup>
const klik = () => {
  console.log('klik')
}
</script>
<style scoped>
</style>
