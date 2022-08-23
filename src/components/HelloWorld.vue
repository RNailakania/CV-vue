<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      Software Developer
      <p><a target="_blank" href="https://instagram.com/inikaniia_?igshid=YmMyMTA2M2Y=">@inikaniia_</a></p> 
      <p> <a target="_blank" href="https://github.com/RNailakania">RNailakania</a></p>
      <p> <a target="_blank" href="https://vuejs.org/">nailakaniawidia@gmail.com</a></p>
    </h3>
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
