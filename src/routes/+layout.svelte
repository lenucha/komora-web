<script lang="ts">
	import '@fontsource/inter';
	import '@fontsource/playfair-display/400.css';
	import '@fontsource/playfair-display/700.css';
	import './style.css';
</script>

<div class="zahlavi">
	<h1>Česká komora tlumočníků znakového jazyka</h1>

	<nav>
		<ul>
			<li><a href="/">Úvodní stránka</a></li>
			<li><a href="/o-komore">O Komoře</a></li>
			<li><a href="/kurzy">Kurzy</a></li>
			<li><a href="/clenstvi">Členství</a></li>
			<li><a href="/tlumoceni">O tlumočení</a></li>
			<li><a href="/kontakty">Kontakty</a></li>
			<li><a href="/blog">Blog</a></li>
		</ul>
	</nav>
</div>

<main>
	<slot />
</main>
