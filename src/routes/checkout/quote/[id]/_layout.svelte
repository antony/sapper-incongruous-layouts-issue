<script context="module">
  export async function preload () {
    console.log('innermost preload')
  }
</script>

<div>
  <slot></slot>
</div>

<style>
  div {
    background-color: yellow;
  }
</style>