<script>
let count = $state(0)
</script>

<div class="space-y-5">
    <h1>Welcome to SvelteKit</h1>

    <button onclick={()=> count++} class="bg-blue-600 px-6 py-2 rounded text-white cursor-pointer" >Click Count = {count}</button>
</div>


