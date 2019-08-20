<style>
	.header {
		background-color: #212121;
		position: relative;
		z-index: 1;
	}

	.header__image {
		background-color: #212121;
		background-image:
			linear-gradient(180deg, rgba(0, 0, 0, .8) 0%, rgba(0, 0, 0, .6) 20%, rgba(0, 0, 0, 0) 60%),
			url('img/head.png');
		background-position: 50%;
		background-size: cover;
		height: 16rem;
		margin: 0 auto;
	}

	@media (min-width: 90rem) {
		.header__image {
			background-repeat: repeat-x;
			background-size: contain;
			height: 30rem;
		}
	}

	.header__top-bar {
		align-items: center;
		display: flex;
		justify-content: space-between;
		padding: 1rem;
	}

	.header__title h1 {
		color: #D84315;
		font-size: 1.75rem;
		font-weight: 900;
		letter-spacing: 0.25rem;
		line-height: 1;
		margin: 0;
		text-shadow: 2px 2px 1px #FDD835, 0 2px 4px hsla(0, 0%, 0%, .9);
		text-transform: uppercase;
	}

	.header__social a {
		align-items: center;
		color: #fff;
		display: flex;
		font-size: .875rem;
	}

	.header__social-icon {
		fill: currentColor;
		margin-right: .25rem;
		height: 1.25rem;
		width: 1.25rem;
	}

	.header__nav {
		background-color: #FFFDE7;
		letter-spacing: 0.05em;
		text-transform: uppercase;
	}

	.header__nav ul {
		align-content: center;
		display: flex;
		list-style-type: none;
		flex-direction: column;
		font-size: .875rem;
		font-weight: 500;
		justify-content: center;
		max-width: 60rem;
		margin: 0 auto;
		padding: 1rem;
	}

	.header__nav li {
		padding: .5rem;
		text-align: center;
	}

	@media (min-width: 30rem) {
		.header__nav ul {
			flex-direction: row;
			font-size: 1.25rem;
			height: 5rem;
			justify-content: space-around;
			padding: 0;
		}

		.header__nav li {
			padding: 0;
		}
	}

	.header__nav a {
		align-items: center;
		border-bottom: 4px solid transparent;
		color: #212121;
		display: inline-flex;
		height: 100%;
		padding-left: 1rem;
		padding-right: 1rem;
		text-align: center;
		transition: all .3s ease-in-out;
	}

	.header__nav a:hover {
		color: #D84315;
		text-decoration: none;
	}

	@media (min-width: 30rem) {
		.header__nav a:hover {
			border-bottom: 4px solid #E64A19;
		}
	}
</style>

<header class="header">
	<div class="header__image">
		<div class="header__top-bar">
			<div class="header__title">
				<h1>Dirty Dogs</h1>
			</div>
			<div class="header__social">
				<a href="#">
					<svg
						aria-hidden="true"
						role="img"
						xmlns="http://www.w3.org/2000/svg"
						viewBox="0 0 448 512"
						class="header__social-icon"
					>
						<path fill="currentColor" d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z" class=""></path>
					</svg>
					#hotdogs
				</a>
			</div>
		</div>
	</div>
	<nav class="header__nav">
		<ul>
			<li>
				<a href="#">Menu</a>
			</li>
			<li>
				<a href="#">Catering</a>
			</li>
			<li>
				<a href="#">About</a>
			</li>
			<li>
				<a href="#">Contact</a>
			</li>
		</ul>
	</nav>
</header>
