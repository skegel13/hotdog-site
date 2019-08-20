<style>
	.footer {
		background-color: #fffde7;
		background-image: url("data:image/svg+xml,%3Csvg width='40' height='1' viewBox='0 0 40 1' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M0 0h20v1H0z' fill='%23fdd835' fill-opacity='0.15' fill-rule='evenodd'/%3E%3C/svg%3E");
		border-top: 1px solid #FDD835;
		font-size: .875rem;
		padding: 1rem;
		text-align: center;
	}

	.footer .container {
		display: flex;
		flex-direction: column;
		line-height: 2;
		justify-content: space-between;
	}

	@media (min-width: 60rem) {
		.footer .container {
			flex-direction: row;
			justify-content: space-between;
		}
	}

	.footer__contact {
		display: flex;
		flex-direction: column;
	}

	@media (min-width: 60rem) {
		.footer__contact {
			flex-direction: row;
		}
	}

	@media (min-width: 60rem) {
		.footer__contact > * {
			border-left: 1px solid hsl(49, 98%, 38%);
			padding: 0 .5rem;
		}

		.footer__contact > *:first-child {
			border-left: none;
			padding-left: 0;
		}

		.footer__contact > *:last-child {
			padding-right: none;
		}
	}

	.footer__contact a {
		color: #212121;
	}

	.footer__contact address {
		font-style: normal;
	}

	.footer .span {
		flex: 1 0 auto;
	}

	@media (min-width: 60rem) {
		.footer {
			text-align: left;
		}
	}
</style>

<footer class="footer">
	<div class="container">
		<span>
			&reg; 2019 Dirty Dogs All Rights Reserved
		</span>
		<div class="footer__contact">
			<address>
				274 Marconi Blvd. Columbus, OH 43215
			</address>
			<a href="tel:6145380095">614.538.0095</a>
			<a href="#">Contact Us</a>
		</div>
	</div>
</footer>
