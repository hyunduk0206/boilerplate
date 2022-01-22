<script lang="ts">
	import TodoItem from '$lib/todo-item.svelte';
	const title = 'Todo';
</script>

<svelte:head>
	<title>{title}</title>
</svelte:head>

<h1>{title}</h1>

<form action="" method="">
	<input type="text" name="" aria-label="Add a todo" placeholder="+ type to a todo" />
</form>
<TodoItem />
