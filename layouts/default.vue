<template>
  <div>
    <header>
        <TopInfo />
        <TopNav/>
    </header>
    <main>
      <div class="container">
        <slot />
      </div>
    </main>
  </div>
  <footer class="footer">
    <div class="container has-text-centered">
      <p>
        <strong>Example Site</strong> by <a href="https://example.com">Your Name</a>. The source code is licensed
        <a href="http://opensource.org/licenses/mit-license.php">MIT</a>. The website content
        is licensed <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY NC SA 4.0</a>.
      </p>
    </div>
  </footer>
</template>

<script setup>

</script>

<style scoped lang="scss">
.footer {
  background-color: #363636; /* Dark background */
  color: white; /* White text color */

  strong,
  a {
    color: #F5F5F5; /* Lighter color for links */
  }
}

</style>