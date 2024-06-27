<script lang="ts">
  import { encodeBase58Address } from "@bitauth/libauth";

  export function trySomething() {
    return encodeBase58Address("p2pkh", new Uint8Array());
  }
</script>

<h1>Welcome to SvelteKit</h1>
<p>
  Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
</p>
