<script>
  import { Link } from '@inertiajs/inertia-svelte'
  export let quote
</script>

<div
  class="flex h-screen flex-col items-center justify-center space-y-8 text-center text-gray-700"
>
  <p class="text-xl">{quote}</p>
  <Link href="/" class="text-purple-600 underline">Back to Home</Link>
</div>
