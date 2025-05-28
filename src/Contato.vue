<script setup>

</script>

<template>
  <section id="contato">
    <div class="container">
      <h2>Contato</h2>
      <p>Quer compartilhar suas receitas ou pedir dicas? Entre em contato!</p>
      <form>
        <label for="nome">Nome:</label>
        <input type="text" id="nome" name="nome" required />
        <label for="mensagem">Mensagem:</label>
        <textarea id="mensagem" name="mensagem" required></textarea>
        <button type="submit">Enviar</button>
      </form>
    </div>
  </section>
</template>

<style scoped>
#contato {
  background-color: #fff3f3;
  padding: 40px;
  margin: 20px 0;
  text-align: center;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

#contato h2 {
  font-size: 2.5rem;
  color: #ff4e50;
  margin-bottom: 20px;
  font-family: 'Georgia', serif;
}

#contato p {
  font-size: 1.2rem;
  color: #555;
  line-height: 1.8;
  margin-bottom: 20px;
  font-family: 'Arial', sans-serif;
}

form {
  display: flex;
  flex-direction: column;
  align-items: center;
}

form label {
  font-size: 1.1rem;
  margin-bottom: 5px;
}

form input,
form textarea {
  width: 80%;
  padding: 10px;
  margin-bottom: 20px;
  border: 2px solid #ff6b81;
  border-radius: 5px;
  font-size: 1rem;
}

form button {
  padding: 10px 20px;
  background-color: #ff4e50;
  color: white;
  border: none;
  border-radius: 5px;
  font-size: 1.1rem;
  cursor: pointer;
}

form button:hover {
  background-color: #ff6b81;
}
</style>
