<script lang="ts">
  const fs = () => {
    document.documentElement.requestFullscreen()
  }
</script>

<main on:click={fs}>
  <div>
    <p class="kao">:(</p>
    <p class="content">Your PC ran into a problem and needs to restart. We're just collecting some error info, and then we'll restart for you.</p>
    <p class="content">0% complete</p>
    <p>For more information about this issue and possible fixes, visit our website.</p>
  </div>
</main>

<style>
  main {
    min-height: 100vh;
    display: flex;
    align-items: center;
    background-color: #1f67b1;
    color: white;
    font-family: sans-serif;
  }

  main div {
    padding: 5rem;
  }

  .kao {
    font-size: 6rem;
    margin-bottom: 1rem;
  }

  p {
    margin-bottom: 1.5rem;
  }

  .content {
    font-size: 1.25rem;
  }
</style>
