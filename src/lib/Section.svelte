<script>
  export let id
</script>

<section {id}>
  <div class="wrapper">
    <slot />
  </div>
</section>

<style>
  .wrapper {
    background: #ffffff;
    border-radius: 4px;
    box-shadow: 0 0 3px rgba(33, 33, 33, 0.33);
    padding: 0.5rem;
    height: 100%;
  }
</style>
