<script>
  export let type;
  export let mode;
</script>

<button class:inversed={mode === "inversed"} class={type}><slot /></button>

<style>
  button {
    border: none;
    color: var(--primary-font-color);
    background: var(--neutral-color);
    padding: 1rem;
    border-radius: 12px;
    width: 20rem;
    cursor: pointer;
  }
  .primary {
    background: var(--primary-color);
  }

  .primary:hover {
    color: var(--primary-color);
    background: var(--primary-font-color);
  }

  .secondary {
    background: var(--secondary-color);
  }
  .secondary:hover {
    color: var(--secondary-color);
    background: var(--primary-font-color);
  }

  .primary.inversed {
    color: var(--primary-color);
    background: var(--primary-font-color);
  }

  .secondary.inversed {
    color: var(--secondary-color);
    background: var(--primary-font-color);
  }

  .accent {
    color: var(--primary-font-color);
    background: var(--accent-color);
  }

  .accent.inversed {
    color: var(--accent-color);
    background: var(--primary-font-color);
  }
</style>
