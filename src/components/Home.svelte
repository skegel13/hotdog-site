<style>
	.home {
		border-top: 1px solid #FDD835;
		padding: 2rem 1rem;
	}

	@media (min-width: 60rem) {
		.home {
			align-items: center;
			display: grid;
			grid-template-columns: repeat(2, minmax(1rem, 44rem));
			grid-row-gap: 1rem;
			justify-content: center;
		}
	}

	.home__description {
		backface-visibility: hidden;
		background-color: #FDD835;
		border-radius: .25rem;
		box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
		color: hsl(49, 98%, 18%);
		display: flex;
		flex-direction: column;
		-moz-osx-font-smoothing: grayscale;
		justify-content: center;
		margin: 0 auto;
		padding: 1rem;
		position: relative;
		z-index: 1;
		transform: translateZ(0);
		transition:transform 0.25s ease-out;
		width: 90%;
	}

	.home__description:not(:first-of-type) {
		margin-top: -2rem;
	}

	.home__description h2 {
		font-size: 1.25rem;
		font-weight: 600;
		margin-bottom: 1rem;
		margin-top: 0;
	}

	.home__description p {
		margin: 0;
	}

	@media (min-width: 60rem) {
		.home__description {
			height: 20rem;
			padding: 2rem;
			width: 100%;
		}

		.home__description:hover {
			transform: scale(1.05);
		}

		.home__description:not(:first-of-type) {
			margin-top: -4rem;
		}

		.home__description h2 {
			font-size: 1.75rem;
		}

		.home__description h2:before {
			content: '\2014';
			position: relative;
			display: inline-block;
			width: 2.5rem;
		}

		.home__description p {
			margin: 0 0 0 2.5rem;
		}
	}

	.home__image {
		background-position: 50%;
		background-size: cover;
		border-radius: .25rem;
		box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
		height: 25rem;
		width: 100%;
		margin: 0 auto;
		margin-top: -2rem;
	}

	.home__image--all-beef {
		background-image: url('./img/all-beef.jpg');
	}

	.home__image--vegan {
		background-image: url('./img/vegan.jpg');
	}

	.home__image--vegetarian {
		background-image: url('./img/vegetarian.jpg');
	}

	@media (min-width: 60rem) {
		.home__image {
			height: 30rem;
			margin: 0;
			width: 100%;
		}

		.home__image--all-beef {
			transform: translateX(-4rem);
		}

		.home__image--vegan {
			margin-top: -4rem;
			transform: translateX(4rem);
		}

		.home__image--vegetarian {
			margin-top: -4rem;
			transform: translateX(-4rem);
		}

		.home__image--vegan {
			grid-column: 1 / 2;
			grid-row: 2 / 2;
		}
	}
</style>

<div class="home container">
	<div class="home__description">
		<h2>Gourmet All Beef Hotdogs</h2>
		<p>
			Necessitatibus voluptatum nesciunt. Quam saepe optio quo. Corrupti ut
			blanditiis et et nostrum debitis repudiandae. Rerum tempora temporibus.
			Et eum libero harum aut unde vel.
		</p>
	</div>
	<div class="home__image home__image--all-beef"></div>
	<div class="home__description">
		<h2>Vegan Hotdogs</h2>
		<p>
			Necessitatibus voluptatum nesciunt. Quam saepe optio quo. Corrupti ut
			blanditiis et et nostrum debitis repudiandae. Rerum tempora temporibus.
			Et eum libero harum aut unde vel.
		</p>
	</div>
	<div class="home__image home__image--vegan"></div>
	<div class="home__description">
		<h2>Vegetarian Hotdogs</h2>
		<p>
			Necessitatibus voluptatum nesciunt. Quam saepe optio quo. Corrupti ut
			blanditiis et et nostrum debitis repudiandae. Rerum tempora temporibus.
			Et eum libero harum aut unde vel.
		</p>
	</div>
	<div class="home__image home__image--vegetarian"></div>
</div>
