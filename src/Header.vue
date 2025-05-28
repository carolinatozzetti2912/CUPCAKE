<script setup>

</script>

<template>
  <header>
    <div class="container">
      <h1>Minha Culinária Favorita: Cupcakes</h1>
      <nav>
        <ul>
          <li><a href="#sobre">Sobre</a></li>
          <li><a href="#receitas">Receitas</a></li>
          <li><a href="#contato">Contato</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style scoped>
header {
  background: linear-gradient(135deg, #ff6b81, #ff4e50);
  color: white;
  padding: 20px 0;
  text-align: center;
}

header h1 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}
nav ul {
  list-style: none;
  padding: 10px 0;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav ul li a:hover {
  text-decoration: underline;
}
</style>
