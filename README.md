<style>
	#main {
		font-family: monospace;
		font-size: 16px;
		color: red;
		text-align: center;
	}
	.title {
		font-family: sans-serif;
		color: blue;
		font-size: 40px;
	}
	.classy-text {
		font-family: serif;
	}
	#ball {
		background-color: green;
		border-radius: 50%;
		height: 200px;
		width: 200px;
		animation-name: changing;
		animation-duration: 4s;
		animation-iteration-count: infinite;
	}
	@keyframes changing {
		50% {
			background-color: blue;
		}
		75% {
			background-color: black;
		}
		100% {
			background-color: green;
		}
	}
</style>

<html>
	<main id="main">
		<header>
			<h1 class="title"><strong>This is a test title</strong></h1>
		</header>
		<body>
			<p>one two three. test test</p>
			
			<div id="ball"></div>
			
			<p class="classy-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. In dapibus odio ex. Praesent egestas ligula vitae iaculis lacinia. Integer sed volutpat est. Donec vitae sapien nisi. Nam interdum ligula ante, et scelerisque nisi consectetur vitae. Suspendisse diam velit, sollicitudin vel augue congue, tempus blandit sem. In a massa ipsum. Pellentesque maximus pellentesque nunc ut finibus. Mauris iaculis mauris id erat euismod, a consectetur augue hendrerit. Integer nec ante mi. Praesent ac gravida massa. Nunc pharetra elit sed neque tincidunt aliquam sit amet nec arcu. Nulla volutpat tempus mattis.

			Donec vitae nibh at ex fringilla lobortis. Integer porta vitae lacus vel suscipit. Vivamus placerat laoreet auctor. Donec non posuere nisl, nec dapibus urna. Morbi vestibulum commodo cursus. Maecenas lacinia mollis eros et imperdiet. Nullam at mauris nunc. Nam justo ligula, efficitur sit amet lacus nec, vulputate finibus nisl. Ut dapibus, odio nec eleifend ultrices, quam nisl efficitur nunc, vel efficitur leo sem ut est.

			Sed congue neque magna, eu pharetra felis ultricies sed. Donec vitae lacinia lacus. Curabitur dapibus at leo ut hendrerit. Sed faucibus arcu eget neque volutpat scelerisque. Aenean pharetra feugiat massa sit amet vehicula. Interdum et malesuada fames ac ante ipsum primis in faucibus. Vivamus at nisi dolor. Quisque efficitur vel magna at commodo. Donec eros ex, efficitur et purus eget, faucibus ultrices lacus. Nullam ullamcorper eros nibh, ut fringilla ex molestie a.

			Ut quis consequat felis. Nulla fermentum condimentum ligula quis egestas. Vestibulum facilisis sagittis varius. Suspendisse potenti. Duis commodo odio eget consectetur dignissim. Nam sit amet viverra elit. Nulla gravida pharetra libero, egestas lacinia leo commodo non. Nullam blandit massa ac nisl luctus, in lobortis libero scelerisque.

			Curabitur sit amet leo eros. Ut eget justo imperdiet, ultricies leo sed, porta augue. Etiam in malesuada ex. Aenean arcu leo, hendrerit efficitur lacinia ac, tempus in mi. Donec sit amet rutrum eros. Donec id ante a magna sagittis sollicitudin sed sed ex. Etiam a elit lacus. Aenean facilisis malesuada quam sit amet porttitor. Quisque mattis massa neque, nec sodales ipsum auctor eu. Nunc convallis varius nisl feugiat sodales. Curabitur nec felis dui. Nam nec massa a felis tincidunt efficitur. In gravida est dui, placerat tempus erat tempus vel. Integer gravida consectetur massa, ac sagittis quam feugiat vel.</p>
		</body>
	</main>
</html>
