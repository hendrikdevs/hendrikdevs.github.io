<header>
	<div>
		<div id="avatar">
			<img src="initials.svg" alt="H.E. Initialien" />
		</div>

		<p class="center">Hendrik Eisenblätter <br /> Cybersecurity specialist</p>
	</div>
	<div>
		<h1>Portfolio</h1>
		<p>
			Welcome to my portfolio page! I will soon absolve my internship and write my master's thesis.
		</p>
		<p>
			In my spare time I do a lot of development and tinkering. Some of these projects I would like
			to highlight on this portfolio page.
		</p>
		<p>
			Please feel free to contact me if you have any questions about these projects, if you have an
			interesting project of your own, or if you would like to discuss the possibility of an
			internship or master's thesis!
		</p>
		<div id="contact">
			<h2>Contact</h2>
			<div>
				<img src="at.svg" alt="email address identifier" />
				<a href="mailto:todo@todo.com">todo@todo.com</a>
			</div>
		</div>
	</div>
</header>

<hr />

<main>
	<div>
		<h2>Comfort Mail</h2>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem, eum ut? Quibusdam cum
			repudiandae animi earum quos modi eos, nobis porro in perspiciatis, vel fugit, rem aspernatur
			quod magnam? Omnis.
		</p>
		<span>Stack:</span>
		<ul>
			<li>Fullstack</li>
			<li>Elixir</li>
			<li>Phoenix</li>
			<li>Ecto</li>
			<li>PostgreSQL</li>
			<li>Swoosh (Mailing)</li>
			<li>CI/CD (fly.io)</li>
			<li>...</li>
		</ul>
	</div>

	<div>
		<h2>Svelte Networked Store</h2>
		<p>
			Lorem ipsum, dolor sit amet consectetur adipisicing elit. Doloremque, accusantium nostrum.
			Deserunt quibusdam aperiam itaque architecto fugiat consequatur asperiores accusamus laborum
			dolore excepturi, eum, assumenda, amet rem dolor laboriosam? Vel.
		</p>
		<span>Stack:</span>
		<ul>
			<li>Svelte Library</li>
			<li>Typescript</li>
			<li>Tested (Mocha, ..)</li>
			<li>...</li>
		</ul>
	</div>

	<div>
		<h2>Portfolio Page</h2>
		<p>This page...</p>
		<span>Stack:</span>
		<ul>
			<li>HTML</li>
			<li>CSS</li>
			<li>Svelte</li>
			<li>Prerendered</li>
			<li>CI/CD</li>
			<li>Github Pages</li>
		</ul>
	</div>
</main>

<style>
	header {
		margin-top: 1.5em;
		display: flex;
		flex-direction: row;
		gap: 0.5em 2em;
		justify-content: space-around;
	}

	hr {
		border: 1px solid hsl(0, 0%, 88%);
	}

	main {
		display: flex;
		flex-direction: column;
		row-gap: 2em;
	}

	main * :not(h2) {
		font-family: 'Courier New', Courier, monospace;
	}

	#avatar {
		border-radius: 50%;
		background-color: hsl(175, 0%, 90%);
		padding: 2em 2em 0 2em;
	}

	#contact {
		margin-top: 2em;
	}

	#contact h2 {
		margin-bottom: 0.25em;
	}

	#contact div {
		display: flex;
		align-items: center;
	}

	#contact img {
		height: calc(1rem * 1.15);
	}

	.center {
		text-align: center;
	}
</style>
