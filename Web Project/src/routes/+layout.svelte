<!--scr/routes/+layout.svelte-->
<script>
// @ts-nocheck

  import Navigation from "$lib/Navigation.svelte";

</script>
<Navigation /><Navigation


<slot  /> <!-- This preserves the content of the pages -->
<footer>This should be on every page - layout file</footer>