<script setup lang="ts"></script>

<template>
  <div class="greetings">
    <h1 class="green">Gamercafe Awards</h1>
    <p>
      <strong>Una vez más <span class="text-gc">Gamercafe</span> se complace en
      presentar una nueva entrega de los
      <span class="text-gc">Gamercafe Awards</span>, la elección democrática a
      los mejores (<em>y peores</em>) juegos del 2017 que se realizan a través
      de nuestro formulario que incluye “recomendaciones” y solamente eso, ya
      que como siempre puedes votar por cualquier juego mientras haya
      aparecido durante el 2017.</strong>
    </p>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
