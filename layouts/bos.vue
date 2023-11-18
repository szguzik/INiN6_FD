<template>
  <div class="bos_bg">
    <!-- Możesz dodać pasek nawigacji -->
    <header>
      <nav>
        <TopNav/>
      </nav>
    </header>

    <!-- Zawartość strony zostanie wstrzyknięta tutaj -->
    <main>
      <div class="container">
        <slot />
      </div>
    </main>

    <!-- Możesz dodać stopkę -->

  </div>
  <footer>
    <h3>to jest stopka</h3>
    <!-- Stopka -->
  </footer>
</template>

<script setup>
// Tu można dodać logikę JavaScript
</script>

<style scoped lang="scss">
/* Style CSS dla layoutu */
.bos_bg {
  nav {
    background-color: dodgerblue;
    width: 100%;
    color: white;
    border-bottom: 2px solid yellow;
  }
}
</style>