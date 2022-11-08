<script lang="ts">
  // ...

  function focusInput() {
    inputEl.focus()
  }

  onMount(async () => {
    // ...
    focusInput()
  })
</script>

<style lang="scss">
  .game {
    .input {
      position: absolute;
      opacity: 0;
    }

    /* ... */
  }
</style>
