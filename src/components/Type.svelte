<script lang="ts">
import '../app.css';

type FontWeight = 'BOLD' | 'MEDIUM';
export let fontWeight: FontWeight = 'BOLD';
</script>

<div style={fontWeight} class="p-4 text-blue-500">
    <slot />
</div>
