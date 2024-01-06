<div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-10 text-center flex flex-col items-center">
		<h2 class="h2">Witaj na Kreacie!</h2>
		<div class="flex justify-center space-x-2">
			<a
				class="btn variant-filled"
				href="https://drive.google.com/drive/folders/1zq7WwiIaIR7UC3AkkqMx1EdMR4-a3YiV?usp=sharing"
				target="_blank"
				rel="noreferrer"
			>
				Pobierz Kreata! - Build 0.1v
			</a>
		</div>
		<br />
		(WIP - Obecnie nie działa)
		<div class="space-y-2">
			<p>Jak zainstalować?</p>
			<a href="/macos">MacOS</a> |
			<a href="/win">Windows</a>
		</div>
	</div>
</div>

<style lang="postcss">
	figure {
		@apply flex relative flex-col;
	}
	figure svg,
	.img-bg {
		@apply w-64 h-64 md:w-80 md:h-80;
	}
	.img-bg {
		@apply absolute z-[-1] rounded-full blur-[50px] transition-all;
		animation:
			pulse 5s cubic-bezier(0, 0, 0, 0.5) infinite,
			glow 5s linear infinite;
	}
	@keyframes glow {
		0% {
			@apply bg-primary-400/50;
		}
		33% {
			@apply bg-secondary-400/50;
		}
		66% {
			@apply bg-tertiary-400/50;
		}
		100% {
			@apply bg-primary-400/50;
		}
	}
	@keyframes pulse {
		50% {
			transform: scale(1.5);
		}
	}
</style>
