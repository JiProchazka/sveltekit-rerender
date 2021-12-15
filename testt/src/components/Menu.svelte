<script lang="ts">
  import { goto } from "$app/navigation"

  function handle(page) {
    goto(page)
  }
</script>

<a href="#" on:click|preventDefault={() => handle("/app")}>Home</a>
<a href="#" on:click|preventDefault={() => handle("/app/about")}>About</a>