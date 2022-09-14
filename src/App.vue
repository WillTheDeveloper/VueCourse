<template>
  <header>
    <nav>
      <ul>
        <li class=""><a class="nav-item" href="#">Home</a></li>
        <li><a class="nav-item" href="#">About</a></li>
        <li><a class="nav-item" href="#">Contact</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <HelloWorld/>
  </main>
</template>

<script>
import HelloWorld from './home/HelloPage.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
body {
  background: linear-gradient(to bottom, grey, white);
  height: 1024px;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

main {
  margin: 0 auto;
  padding: 30px;
  width: 1024px;
}
</style>
