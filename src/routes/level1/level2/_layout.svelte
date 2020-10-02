<script context="module">
  export async function preload () {
    console.log('level2 preload')
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