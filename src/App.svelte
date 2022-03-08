<script>
  import Button from "./Button.svelte";
  import Footer from "./Footer.svelte";
</script>

<!-- Button section -->
<h1>Buttons</h1>

<div class="buttons">
  <Button type="primary">Primary</Button>
  <Button type="secondary">Secondary</Button>
  <Button type="accent">Accent</Button>
  <Button type="ghost">Ghost</Button>
  <Button type="link">Link</Button>
</div>

<!-- Footer section  -->

<Footer />

<style>
  .buttons {
    display: flex;
    flex-wrap: wrap;
    justify-content: start;
    gap: 1rem;
  }
</style>
