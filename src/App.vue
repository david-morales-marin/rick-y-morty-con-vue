<template>
  <div id="app">
    <main>
  <RouterView></RouterView>
  </main>
  </div>

  <footer
    class="
      fixed
      bottom-0
      left-0
      w-full
      flex
      items-center
      justify-center
      bg-slate-900
      py-2
    "
  >
    <RouterLink
      to="/"
      class="
        px-4
        py-2
        rounded-lg
        bg-cyan-400
        shadow-lg shadow-lime-500/50
        border-2 border-black
        outline outline-1 outline-white
      "
    >
      Home
    </RouterLink>
  </footer>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
};
</script>
