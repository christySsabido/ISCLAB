<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import abajo from './components/abajo.vue'

</script>

<template>
  <header class="bg-sky-600">

    <div class="flex flex-wrap justify-center ">
  <img
        src="./assets/ISCLAB.png"
        class="w-2/3"
        alt=""
      />
     
</div>


    <div class="wrapper">
      <HelloWorld />
    </div>
  </header>

  <main class="flex bg-cyan-200">
    <TheWelcome />
  </main>

  <aside class="">
    <abajo/>
  </aside>

  <div class="">
    <Division/>
  </div>

</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;

}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}

.medio {
  margin-top: 60 px;
}

div .titulo1 {
  margin-top: 60 px;
}



</style>
