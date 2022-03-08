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
    width: 10rem;
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

  .primary:hover {
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

  .accent:hover {
    color: var(--accent-color);
    background: var(--primary-font-color);
  }

  .ghost {
    color: black;
    background: var(--ghost-color);
  }

  .ghost:hover {
    color: var(--ghost-color);
    background: black;
  }

  .link {
    color: var(--primary-color);
    background: var(--ghost-color);
  }

  .link:hover {
    color: var(--ghost-color);
    background-color: var(--primary-color);
  }
</style>
