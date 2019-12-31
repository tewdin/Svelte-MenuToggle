<script>
	let active = false;
</script>

// Add or remove class "show"
<nav id="menu" class:show={active}></nav>

// Toggle active true / false
<button id="menu-toggler" class="icon" class:icon-menu={!active} class:icon-cancel={active} on:click={ () => active = !active}></button>
