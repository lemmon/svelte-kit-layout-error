<script context="module">
export async function load({ page }) {
  if (page.params.foo !== 'okay') {
    return
  }
  return {}
}
</script>

<p>&larr; <a href="/">back</a></p>

<slot />
