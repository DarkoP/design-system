<script>
	import welcome_fallback from '$lib/images/svelte-welcome.png';
</script>

<div class="form-group">
	<label for="input-image">Input image</label>
	<span id="input-image-hint" class="hint">Hint Text</span>
	<input id="input-image" type="image" name="image" aria-describedby="input-image-hint input-image-error" src={welcome_fallback} alt="Welcome"/>
	<span id="input-image-error" class="error" aria-live="polite">Error</span>
</div>
<pre><code>&lt;input type="image" name="image" /&gt;</code></pre>