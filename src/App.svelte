<script lang="ts">
  import { onMount } from "svelte";
  let value = $state(0);
</script>

<div class="main">
  <sp-label>{value}</sp-label>

  <sp-action-button size="s">Generate</sp-action-button>
</div>
