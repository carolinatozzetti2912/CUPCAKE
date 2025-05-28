<script setup>

</script>

<template>
  <section id="receitas">
    <div class="container">
      <h2>Receitas Populares</h2>
      <ul>
        <li>Chocolate</li>
        <li>Baunilha</li>
        <li>Red Velvet</li>
        <li>Limão Siciliano</li>
      </ul>
    </div>
  </section>
</template>

<style scoped>
#receitas {
  background-color: #fff;
  padding: 40px;
  margin: 20px 0;
  text-align: center;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

#receitas h2 {
  font-size: 2.5rem;
  color: #ff4e50;
  margin-bottom: 20px;
  font-family: 'Georgia', serif;
}

#receitas ul {
  list-style: none;
  font-size: 1.2rem;
  color: #555;
  line-height: 1.8;
  margin: 0;
  padding: 0;
}

#receitas ul li {
  margin: 10px 0;
}
</style>
