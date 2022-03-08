<script>
  import Button from "./Button.svelte";
</script>

<footer>
  <div>
    <h3>Services</h3>
    <p>Branding</p>
    <p>Design</p>
    <p>Marketing</p>
    <p>Advertisement</p>
  </div>
  <div>
    <h3>Services</h3>
    <p>Branding</p>
    <p>Design</p>
    <p>Marketing</p>
    <p>Advertisement</p>
  </div>
  <div>
    <h3>Services</h3>
    <p>Branding</p>
    <p>Design</p>
    <p>Marketing</p>
    <p>Advertisement</p>
  </div>
</footer>

<style>
  footer {
    background: #212121;
    display: grid;
    grid-template-columns: repeat(3);
  }

  div {
    grid-column: auto;
  }
  h3 {
    color: slategrey;
  }

  p {
    color: grey;
  }
</style>
