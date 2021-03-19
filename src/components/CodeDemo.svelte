<script>
  import { onMount } from 'svelte'

  const options = {
    readOnly: true,
    lineNumbers: false,
    mode: "javascript",
    value: "function test() {\n\t\n}"
  }

  let CodeMirror, editor

  onMount(async () => {
    const mod = await import('@joshnuss/svelte-codemirror')
    await import('codemirror/mode/javascript/javascript')

    CodeMirror = mod.default
  })

  $: if (editor) {
    editor.setCursor(1, 2)
  }
</script>

{#if CodeMirror}
  <svelte:component this={CodeMirror} {options} bind:editor/>
{/if}
