<script>
  const throwError = () => {
   throw new Error('simulate error');
  }
 </script>
 
 <button on:click={throwError} class="rounded p-2 bg-violet-400">throw error</button>
  