<style>
  .hero {
    align-items: center;
		background-color: #FFF59d;
    display: flex;
    flex-direction: column;
		justify-content: center;
    padding: 5rem 1rem;
	}

  .hero__image {
    display: block;
    height: auto;
		margin: 0 auto 1rem auto;
		filter: brightness(.4) drop-shadow(.125rem .125rem .125rem hsla(14, 80%, 50%, 0.5));
	}

	.hero__title {
		font-size: 2rem;
		font-weight: 200;
		margin: 0;
		margin-bottom: 2rem;
		max-width: 60rem;
		line-height: 1.25;
		text-align: center;
	}

	@media (min-width: 60rem) {
		.hero__title {
			font-size: 3rem;
		}
	}

	.hero__button {
		align-items: center;
		background-color: #E64A19;
		color: hsl(14, 88%, 96%);
		border-radius: .25rem;
		border-bottom: 4px solid #BF360C;
		display: flex;
		font-size: 1rem;
		height: 3.5rem;
		justify-content: center;
		text-align: center;
		padding: .5rem 1rem;
	}

	.hero__button:hover {
		border-bottom-width: 2px;
		background-color: #D84315;
		color: #fff;
		cursor: pointer;
		transform: translateY(1px);
		text-decoration: none;
		transition: all .2s ease-in-out;
	}

	@media (min-width: 60rem) {
		.hero__button {
			font-size: 1.25rem;
		}
	}
</style>

<div class="hero">
  <img alt="Hot Dog" class="hero__image" src="img/hot-dog-icon.png" />
  <h1 class="hero__title">Dirty Dogs serves all-beef, vegan and vegetarian hot dogs.</h1>
	<a class="hero__button" href="#">
		More Dogs 'n Make Em Hot
	</a>
</div>
