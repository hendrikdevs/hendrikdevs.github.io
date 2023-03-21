<header>
	<div id="left">
		<div id="avatar">
			<img src="initials.svg" alt="H.E. Initialien" />
		</div>

		<p class="center">Hendrik Eisenblätter, <br /> Cybersecurity specialist</p>
	</div>
	<div id="right">
		<h1>Portfolio</h1>
		<p>
			Welcome to my portfolio page! I am currently looking for an internship opportunity to complete
			my final internship before writing my master's thesis.
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
			<h3>Contact</h3>
			<div>
				<img src="at.svg" alt="email address identifier" />
				<a href="mailto:todo@todo.com">hendrikdevs@proton.me</a>
			</div>
		</div>
	</div>
</header>

<hr />

<main>
	<div class="item">
		<div>
			<h2>
				Comfort Mail
				<!-- (<a href="https://comfort-mail.com" target="_blank" rel="noreferrer"
					>https://comfort-mail.com</a
				>) -->
			</h2>
			<p>
				Comfort Mail allows you to receive an email each time you submit data to a specific URL.
				This can be used for contact forms, for example. To prevent spam the user must register
				before using this service.
			</p>
			<p>
				This project includes a website for registration, a backend service to manage users,
				registration status, and to handle data submissions. When data is submitted an email is sent
				out to the user's email address.
			</p>

			<p>
				Explore the source code and further information in the <a
					href="https://github.com/hendrikdevs/comfort_mail/"
					target="_blank"
					rel="noreferrer">GitHub repository.</a
				>
			</p>
		</div>
		<div>
			<span>Features:</span>
			<ul>
				<li class="bold">Fullstack</li>
				<li class="bold">Elixir</li>
				<li>Phoenix</li>
				<li>Ecto</li>
				<li class="bold">PostgreSQL</li>
				<li>Swoosh (Mailing)</li>
				<li class="bold">CI</li>
				<!-- <li class="bold">CI	/CD (fly.io)</li> -->
				<li>Unit tests</li>
				<li>Integration tests</li>
				<li class="bold">HTML5 & CSS3</li>
			</ul>
		</div>
	</div>

	<div class="item">
		<div>
			<h2>Svelte Networked Store</h2>
			<p>
				This svelte library provides a svelte store to manage (CRUD-)resources. It does so by
				helping to fetch the ressource and store an appropriate status. It provides a simple API
				that is fully tested and documented. The library is written in Typescript, so it provides
				type definitions.
			</p>

			<p>
				Explore the source code and further information in the <a
					href="https://github.com/hendrikdevs/svelte-networked-store"
					target="_blank"
					rel="noreferrer">GitHub repository.</a
				>
			</p>
		</div>
		<div>
			<span>Features:</span>
			<ul>
				<li class="bold">Library</li>
				<li class="bold">Svelte</li>
				<li class="bold">Typescript</li>
				<li class="bold">Unit tests</li>
				<li>Documented</li>
			</ul>
		</div>
	</div>

	<div class="item">
		<div>
			<h2>Portfolio Page</h2>
			<p>
				This page is also a frontend project. It was built using SvelteKit and has no other
				dependencies. It was built with best practices in mind, so it is tested and has a continuous
				integration and delivery pipeline setup.
			</p>
			<p>
				It is hosted on github pages. The resulting (prerendered) page is about 5KB in size and
				loads in under one second.
			</p>

			<p>
				Explore the source code and further information in the <a
					href="https://github.com/hendrikdevs/hendrikdevs.github.io"
					target="_blank"
					rel="noreferrer">GitHub repository.</a
				>
			</p>
		</div>
		<div>
			<span>Features:</span>
			<ul>
				<li class="bold">Frontend</li>
				<li class="bold">HTML5 & CSS3</li>
				<li class="bold">Svelte</li>
				<li class="bold">SvelteKit</li>
				<li>Prerendered</li>
				<li class="bold">CI/CD</li>
				<li class="bold">Unit tests</li>
				<li>Github Pages</li>
				<li>Super fast <br />(~5KB size)</li>
			</ul>
		</div>
	</div>
</main>

<style>
	header {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		gap: 0.5em 2em;
		justify-content: center;
		align-items: center;
		width: 95%;
		margin: 1.5em auto 0 auto;
	}

	header #left {
		width: 200px;
	}

	header #right {
		flex: 4 10 auto;
		width: min-content;
		/* min-width: 400px; */
	}

	hr {
		border: 1px solid hsl(0, 0%, 86%);
		margin: 2em 0 2.5em 0;
	}

	main {
		display: flex;
		flex-direction: column;
		row-gap: 4em;
		width: 95%;
		margin: 0 auto 4em auto;
		font-family: 'Courier New', Courier, monospace;
	}

	main h2 a {
		font-size: 1rem;
	}

	#avatar {
		border-radius: 50%;
		background-color: hsl(175, 0%, 90%);
	}

	#contact {
		margin-top: 2em;
	}

	#contact h3 {
		margin-bottom: 0.25em;
	}

	#contact div {
		display: flex;
		align-items: center;
	}

	#contact img {
		height: calc(1rem * 1.15);
	}

	.item {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: space-between;
		align-items: center;
		gap: 1em 3em;
	}

	.item div:first-child {
		/*width: 650px;*/
		flex: 4 1 auto;
		width: min-content;
		min-width: 400px;
	}

	.item div:last-child {
		width: 250px;
	}

	.center {
		text-align: center;
	}

	.bold {
		font-weight: bold;
	}
</style>
