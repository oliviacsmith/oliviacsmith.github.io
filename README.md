@import url("fontawesome-all.min.css");
@import url("https://fonts.googleapis.com/css?family=Raleway:400,400italic,700,800");

/*
	Highlights by HTML5 UP
	html5up.net | @ajlkn
	Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)
*/

html, body, div, span, applet, object,
iframe, h1, h2, h3, h4, h5, h6, p, blockquote,
pre, a, abbr, acronym, address, big, cite,
code, del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var, b,
u, i, center, dl, dt, dd, ol, ul, li, fieldset,
form, label, legend, table, caption, tbody,
tfoot, thead, tr, th, td, article, aside,
canvas, details, embed, figure, figcaption,
footer, header, hgroup, menu, nav, output, ruby,
section, summary, time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;}

article, aside, details, figcaption, figure,
footer, header, hgroup, menu, nav, section {
	display: block;}

body {
	line-height: 1;
}

ol, ul {
	list-style: none;
}

blockquote, q {
	quotes: none;
}

	blockquote:before, blockquote:after, q:before, q:after {
		content: '';
		content: none;
	}

table {
	border-collapse: collapse;
	border-spacing: 0;
}

body {
	-webkit-text-size-adjust: none;
}

mark {
	background-color: transparent;
	color: inherit;
}

input::-moz-focus-inner {
	border: 0;
	padding: 0;
}

input, select, textarea {
	-moz-appearance: none;
	-webkit-appearance: none;
	-ms-appearance: none;
	appearance: none;
}

/* Basic */

	html {
		box-sizing: border-box;
	}

	*, *:before, *:after {
		box-sizing: inherit;
	}

	html {
		background-color: #313a3d;
		background-attachment: fixed,						fixed;
		background-image: url("images/overlay.png"), url("../../images/bg.jpg");
		background-position: top left,					center center;
		background-repeat: repeat,						none;
		background-size: auto,						cover;
	}

	html.is-preload *, html.is-preload *:before, html.is-preload *:after {
		-moz-animation: none !important;
		-webkit-animation: none !important;
		-ms-animation: none !important;
		animation: none !important;
		-moz-transition: none !important;
		-webkit-transition: none !important;
		-ms-transition: none !important;
		transition: none !important;
	}

	html.is-touch {
		height: 100vh;
		overflow: hidden;
	}

		html.is-touch #wrapper {
			-webkit-backface-visibility: hidden;
			-webkit-overflow-scrolling: touch;
			-webkit-transform: translate3d(0, 0, 0);
			height: 100vh;
			overflow: auto;
		}

	body, input, select, textarea {
		color: #6f7577;
		font-family: "Raleway", "Helvetica", sans-serif;
		font-size: 15pt;
		font-weight: 400;
		line-height: 1.75em;
	}

	a {
		-moz-transition: color 0.2s ease-in-out, border-bottom-color 0.2s ease-in-out;
		-webkit-transition: color 0.2s ease-in-out, border-bottom-color 0.2s ease-in-out;
		-ms-transition: color 0.2s ease-in-out, border-bottom-color 0.2s ease-in-out;
		transition: color 0.2s ease-in-out, border-bottom-color 0.2s ease-in-out;
		border-bottom: dotted 1px;
		color: #8cd1a8;
		text-decoration: none;
	}

		a:hover {
			border-bottom-color: transparent !important;
			color: #8cd1a8 !important;
			text-decoration: none;
		}

	strong, b {
		color: #61686b;
		font-weight: 700;
	}

	em, i {
		font-style: italic;
	}

	p {
		margin: 0 0 2em 0;
	}

	h1, h2, h3, h4, h5, h6 {
		color: #61686b;
		font-weight: 800;
		letter-spacing: 0.075em;
		line-height: 1em;
		margin: 0 0 1em 0;
		text-transform: uppercase;
	}

		h1 a, h2 a, h3 a, h4 a, h5 a, h6 a {
			color: inherit;
			text-decoration: none;
		}

	h2 {
		font-size: 1.75em;
		line-height: 1.5em;
	}

	h3 {
		font-size: 1em;
		line-height: 1.5em;
	}

	h4 {
		font-size: 0.9em;
		line-height: 1.5em;
	}

	h5 {
		font-size: 0.8em;
		line-height: 1.5em;
	}

	h6 {
		font-size: 0.7em;
		line-height: 1.5em;
	}

	sub {
		font-size: 0.8em;
		position: relative;
		top: 0.5em;
	}

	sup {
		font-size: 0.8em;
		position: relative;
		top: -0.5em;
	}

	hr {
		border: 0;
		border-bottom: solid 1px #dddddd;
		margin: 2em 0;
	}

		hr.major {
			margin: 3em 0;
		}

	blockquote {
		border-left: solid 6px #dddddd;
		font-style: italic;
		margin: 0 0 2em 0;
		padding: 0.5em 0 0.5em 1.5em;
	}

	code {
		background: rgba(144, 144, 144, 0.075);
		font-family: "Courier New", monospace;
		font-size: 0.9em;
		margin: 0 0.25em;
		padding: 0.25em 0.65em;
	}

	pre {
		-webkit-overflow-scrolling: touch;
		font-family: "Courier New", monospace;
		font-size: 0.9em;
		margin: 0 0 2em 0;
	}

		pre code {
			display: block;
			line-height: 1.75em;
			padding: 1em 1.5em;
			overflow-x: auto;
		}

	.align-left {
		text-align: left;
	}

	.align-center {
		text-align: center;
	}

	.align-right {
		text-align: right;
	}

/* Container */

	.container {
		margin: 0 auto;
		max-width: calc(100% - 4em);
		width: 35em;
	}

		.container.xsmall {
			width: 8.75em;
		}

		.container.small {
			width: 17.5em;
		}

		.container.medium {
			width: 26.25em;
		}

		.container.large {
			width: 43.75em;
		}

		.container.xlarge {
			width: 52.5em;
		}

		.container.max {
			width: 100%;
		}

		@media screen and (max-width: 980px) {

			.container {
				width: 80% !important;
				max-width: 100% !important;
			}

		}

		@media screen and (max-width: 480px) {

			.container {
				width: 100% !important;
			}

		}

/* Row */

	.row {
		display: flex;
		flex-wrap: wrap;
		box-sizing: border-box;
		align-items: stretch;
	}

		.row > * {
			box-sizing: border-box;
		}

		.row.gtr-uniform > * > :last-child {
			margin-bottom: 0;
		}

		.row.aln-left {
			justify-content: flex-start;
		}

		.row.aln-center {
			justify-content: center;
		}

		.row.aln-right {
			justify-content: flex-end;
		}

		.row.aln-top {
			align-items: flex-start;
		}

		.row.aln-middle {
			align-items: center;
		}

		.row.aln-bottom {
			align-items: flex-end;
		}

		.row > .imp {
			order: -1;
		}

		.row > .col-1 {
			width: 8.33333%;
		}

		.row > .off-1 {
			margin-left: 8.33333%;
		}

		.row > .col-2 {
			width: 16.66667%;
		}

		.row > .off-2 {
			margin-left: 16.66667%;
		}

		.row > .col-3 {
			width: 25%;
		}

		.row > .off-3 {
			margin-left: 25%;
		}

		.row > .col-4 {
			width: 33.33333%;
		}

		.row > .off-4 {
			margin-left: 33.33333%;
		}

		.row > .col-5 {
			width: 41.66667%;
		}

		.row > .off-5 {
			margin-left: 41.66667%;
		}

		.row > .col-6 {
			width: 50%;
		}

		.row > .off-6 {
			margin-left: 50%;
		}

		.row > .col-7 {
			width: 58.33333%;
		}

		.row > .off-7 {
			margin-left: 58.33333%;
		}

		.row > .col-8 {
			width: 66.66667%;
		}

		.row > .off-8 {
			margin-left: 66.66667%;
		}

		.row > .col-9 {
			width: 75%;
		}

		.row > .off-9 {
			margin-left: 75%;
		}

		.row > .col-10 {
			width: 83.33333%;
		}

		.row > .off-10 {
			margin-left: 83.33333%;
		}

		.row > .col-11 {
			width: 91.66667%;
		}

		.row > .off-11 {
			margin-left: 91.66667%;
		}

		.row > .col-12 {
			width: 100%;
		}

		.row > .off-12 {
			margin-left: 100%;
		}

		.row.gtr-0 {
			margin-top: 0;
			margin-left: 0em;
		}

			.row.gtr-0 > * {
				padding: 0 0 0 0em;
			}

			.row.gtr-0.gtr-uniform {
				margin-top: 0em;
			}

				.row.gtr-0.gtr-uniform > * {
					padding-top: 0em;
				}

		.row.gtr-25 {
			margin-top: 0;
			margin-left: -0.375em;
		}

			.row.gtr-25 > * {
				padding: 0 0 0 0.375em;
			}

			.row.gtr-25.gtr-uniform {
				margin-top: -0.375em;
			}

				.row.gtr-25.gtr-uniform > * {
					padding-top: 0.375em;
				}

		.row.gtr-50 {
			margin-top: 0;
			margin-left: -0.75em;
		}

			.row.gtr-50 > * {
				padding: 0 0 0 0.75em;
			}

			.row.gtr-50.gtr-uniform {
				margin-top: -0.75em;
			}

				.row.gtr-50.gtr-uniform > * {
					padding-top: 0.75em;
				}

		.row {
			margin-top: 0;
			margin-left: -1.5em;
		}

			.row > * {
				padding: 0 0 0 1.5em;
			}

			.row.gtr-uniform {
				margin-top: -1.5em;
			}

				.row.gtr-uniform > * {
					padding-top: 1.5em;
				}

		.row.gtr-150 {
			margin-top: 0;
			margin-left: -2.25em;
		}

			.row.gtr-150 > * {
				padding: 0 0 0 2.25em;
			}

			.row.gtr-150.gtr-uniform {
				margin-top: -2.25em;
			}

				.row.gtr-150.gtr-uniform > * {
					padding-top: 2.25em;
				}

		.row.gtr-200 {
			margin-top: 0;
			margin-left: -3em;
		}

			.row.gtr-200 > * {
				padding: 0 0 0 3em;
			}

			.row.gtr-200.gtr-uniform {
				margin-top: -3em;
			}

				.row.gtr-200.gtr-uniform > * {
					padding-top: 3em;
				}

		@media screen and (max-width: 1680px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-large {
					order: -1;
				}

				.row > .col-1-large {
					width: 8.33333%;
				}

				.row > .off-1-large {
					margin-left: 8.33333%;
				}

				.row > .col-2-large {
					width: 16.66667%;
				}

				.row > .off-2-large {
					margin-left: 16.66667%;
				}

				.row > .col-3-large {
					width: 25%;
				}

				.row > .off-3-large {
					margin-left: 25%;
				}

				.row > .col-4-large {
					width: 33.33333%;
				}

				.row > .off-4-large {
					margin-left: 33.33333%;
				}

				.row > .col-5-large {
					width: 41.66667%;
				}

				.row > .off-5-large {
					margin-left: 41.66667%;
				}

				.row > .col-6-large {
					width: 50%;
				}

				.row > .off-6-large {
					margin-left: 50%;
				}

				.row > .col-7-large {
					width: 58.33333%;
				}

				.row > .off-7-large {
					margin-left: 58.33333%;
				}

				.row > .col-8-large {
					width: 66.66667%;
				}

				.row > .off-8-large {
					margin-left: 66.66667%;
				}

				.row > .col-9-large {
					width: 75%;
				}

				.row > .off-9-large {
					margin-left: 75%;
				}

				.row > .col-10-large {
					width: 83.33333%;
				}

				.row > .off-10-large {
					margin-left: 83.33333%;
				}

				.row > .col-11-large {
					width: 91.66667%;
				}

				.row > .off-11-large {
					margin-left: 91.66667%;
				}

				.row > .col-12-large {
					width: 100%;
				}

				.row > .off-12-large {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0;
					margin-left: 0em;
				}

					.row.gtr-0 > * {
						padding: 0 0 0 0em;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0em;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0em;
						}

				.row.gtr-25 {
					margin-top: 0;
					margin-left: -0.375em;
				}

					.row.gtr-25 > * {
						padding: 0 0 0 0.375em;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -0.375em;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 0.375em;
						}

				.row.gtr-50 {
					margin-top: 0;
					margin-left: -0.75em;
				}

					.row.gtr-50 > * {
						padding: 0 0 0 0.75em;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -0.75em;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 0.75em;
						}

				.row {
					margin-top: 0;
					margin-left: -1.5em;
				}

					.row > * {
						padding: 0 0 0 1.5em;
					}

					.row.gtr-uniform {
						margin-top: -1.5em;
					}

						.row.gtr-uniform > * {
							padding-top: 1.5em;
						}

				.row.gtr-150 {
					margin-top: 0;
					margin-left: -2.25em;
				}

					.row.gtr-150 > * {
						padding: 0 0 0 2.25em;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -2.25em;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 2.25em;
						}

				.row.gtr-200 {
					margin-top: 0;
					margin-left: -3em;
				}

					.row.gtr-200 > * {
						padding: 0 0 0 3em;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -3em;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 3em;
						}

		}

		@media screen and (max-width: 980px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-medium {
					order: -1;
				}

				.row > .col-1-medium {
					width: 8.33333%;
				}

				.row > .off-1-medium {
					margin-left: 8.33333%;
				}

				.row > .col-2-medium {
					width: 16.66667%;
				}

				.row > .off-2-medium {
					margin-left: 16.66667%;
				}

				.row > .col-3-medium {
					width: 25%;
				}

				.row > .off-3-medium {
					margin-left: 25%;
				}

				.row > .col-4-medium {
					width: 33.33333%;
				}

				.row > .off-4-medium {
					margin-left: 33.33333%;
				}

				.row > .col-5-medium {
					width: 41.66667%;
				}

				.row > .off-5-medium {
					margin-left: 41.66667%;
				}

				.row > .col-6-medium {
					width: 50%;
				}

				.row > .off-6-medium {
					margin-left: 50%;
				}

				.row > .col-7-medium {
					width: 58.33333%;
				}

				.row > .off-7-medium {
					margin-left: 58.33333%;
				}

				.row > .col-8-medium {
					width: 66.66667%;
				}

				.row > .off-8-medium {
					margin-left: 66.66667%;
				}

				.row > .col-9-medium {
					width: 75%;
				}

				.row > .off-9-medium {
					margin-left: 75%;
				}

				.row > .col-10-medium {
					width: 83.33333%;
				}

				.row > .off-10-medium {
					margin-left: 83.33333%;
				}

				.row > .col-11-medium {
					width: 91.66667%;
				}

				.row > .off-11-medium {
					margin-left: 91.66667%;
				}

				.row > .col-12-medium {
					width: 100%;
				}

				.row > .off-12-medium {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0;
					margin-left: 0em;
				}

					.row.gtr-0 > * {
						padding: 0 0 0 0em;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0em;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0em;
						}

				.row.gtr-25 {
					margin-top: 0;
					margin-left: -0.375em;
				}

					.row.gtr-25 > * {
						padding: 0 0 0 0.375em;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -0.375em;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 0.375em;
						}

				.row.gtr-50 {
					margin-top: 0;
					margin-left: -0.75em;
				}

					.row.gtr-50 > * {
						padding: 0 0 0 0.75em;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -0.75em;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 0.75em;
						}

				.row {
					margin-top: 0;
					margin-left: -1.5em;
				}

					.row > * {
						padding: 0 0 0 1.5em;
					}

					.row.gtr-uniform {
						margin-top: -1.5em;
					}

						.row.gtr-uniform > * {
							padding-top: 1.5em;
						}

				.row.gtr-150 {
					margin-top: 0;
					margin-left: -2.25em;
				}

					.row.gtr-150 > * {
						padding: 0 0 0 2.25em;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -2.25em;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 2.25em;
						}

				.row.gtr-200 {
					margin-top: 0;
					margin-left: -3em;
				}

					.row.gtr-200 > * {
						padding: 0 0 0 3em;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -3em;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 3em;
						}

		}

		@media screen and (max-width: 736px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-small {
					order: -1;
				}

				.row > .col-1-small {
					width: 8.33333%;
				}

				.row > .off-1-small {
					margin-left: 8.33333%;
				}

				.row > .col-2-small {
					width: 16.66667%;
				}

				.row > .off-2-small {
					margin-left: 16.66667%;
				}

				.row > .col-3-small {
					width: 25%;
				}

				.row > .off-3-small {
					margin-left: 25%;
				}

				.row > .col-4-small {
					width: 33.33333%;
				}

				.row > .off-4-small {
					margin-left: 33.33333%;
				}

				.row > .col-5-small {
					width: 41.66667%;
				}

				.row > .off-5-small {
					margin-left: 41.66667%;
				}

				.row > .col-6-small {
					width: 50%;
				}

				.row > .off-6-small {
					margin-left: 50%;
				}

				.row > .col-7-small {
					width: 58.33333%;
				}

				.row > .off-7-small {
					margin-left: 58.33333%;
				}

				.row > .col-8-small {
					width: 66.66667%;
				}

				.row > .off-8-small {
					margin-left: 66.66667%;
				}

				.row > .col-9-small {
					width: 75%;
				}

				.row > .off-9-small {
					margin-left: 75%;
				}

				.row > .col-10-small {
					width: 83.33333%;
				}

				.row > .off-10-small {
					margin-left: 83.33333%;
				}

				.row > .col-11-small {
					width: 91.66667%;
				}

				.row > .off-11-small {
					margin-left: 91.66667%;
				}

				.row > .col-12-small {
					width: 100%;
				}

				.row > .off-12-small {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0;
					margin-left: 0em;
				}

					.row.gtr-0 > * {
						padding: 0 0 0 0em;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0em;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0em;
						}

				.row.gtr-25 {
					margin-top: 0;
					margin-left: -0.25em;
				}

					.row.gtr-25 > * {
						padding: 0 0 0 0.25em;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -0.25em;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 0.25em;
						}

				.row.gtr-50 {
					margin-top: 0;
					margin-left: -0.5em;
				}

					.row.gtr-50 > * {
						padding: 0 0 0 0.5em;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -0.5em;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 0.5em;
						}

				.row {
					margin-top: 0;
					margin-left: -1em;
				}

					.row > * {
						padding: 0 0 0 1em;
					}

					.row.gtr-uniform {
						margin-top: -1em;
					}

						.row.gtr-uniform > * {
							padding-top: 1em;
						}

				.row.gtr-150 {
					margin-top: 0;
					margin-left: -1.5em;
				}

					.row.gtr-150 > * {
						padding: 0 0 0 1.5em;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -1.5em;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 1.5em;
						}

				.row.gtr-200 {
					margin-top: 0;
					margin-left: -2em;
				}

					.row.gtr-200 > * {
						padding: 0 0 0 2em;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -2em;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 2em;
						}

		}

		@media screen and (max-width: 480px) {

			.row {
				display: flex;
				flex-wrap: wrap;
				box-sizing: border-box;
				align-items: stretch;
			}

				.row > * {
					box-sizing: border-box;
				}

				.row.gtr-uniform > * > :last-child {
					margin-bottom: 0;
				}

				.row.aln-left {
					justify-content: flex-start;
				}

				.row.aln-center {
					justify-content: center;
				}

				.row.aln-right {
					justify-content: flex-end;
				}

				.row.aln-top {
					align-items: flex-start;
				}

				.row.aln-middle {
					align-items: center;
				}

				.row.aln-bottom {
					align-items: flex-end;
				}

				.row > .imp-xsmall {
					order: -1;
				}

				.row > .col-1-xsmall {
					width: 8.33333%;
				}

				.row > .off-1-xsmall {
					margin-left: 8.33333%;
				}

				.row > .col-2-xsmall {
					width: 16.66667%;
				}

				.row > .off-2-xsmall {
					margin-left: 16.66667%;
				}

				.row > .col-3-xsmall {
					width: 25%;
				}

				.row > .off-3-xsmall {
					margin-left: 25%;
				}

				.row > .col-4-xsmall {
					width: 33.33333%;
				}

				.row > .off-4-xsmall {
					margin-left: 33.33333%;
				}

				.row > .col-5-xsmall {
					width: 41.66667%;
				}

				.row > .off-5-xsmall {
					margin-left: 41.66667%;
				}

				.row > .col-6-xsmall {
					width: 50%;
				}

				.row > .off-6-xsmall {
					margin-left: 50%;
				}

				.row > .col-7-xsmall {
					width: 58.33333%;
				}

				.row > .off-7-xsmall {
					margin-left: 58.33333%;
				}

				.row > .col-8-xsmall {
					width: 66.66667%;
				}

				.row > .off-8-xsmall {
					margin-left: 66.66667%;
				}

				.row > .col-9-xsmall {
					width: 75%;
				}

				.row > .off-9-xsmall {
					margin-left: 75%;
				}

				.row > .col-10-xsmall {
					width: 83.33333%;
				}

				.row > .off-10-xsmall {
					margin-left: 83.33333%;
				}

				.row > .col-11-xsmall {
					width: 91.66667%;
				}

				.row > .off-11-xsmall {
					margin-left: 91.66667%;
				}

				.row > .col-12-xsmall {
					width: 100%;
				}

				.row > .off-12-xsmall {
					margin-left: 100%;
				}

				.row.gtr-0 {
					margin-top: 0;
					margin-left: 0em;
				}

					.row.gtr-0 > * {
						padding: 0 0 0 0em;
					}

					.row.gtr-0.gtr-uniform {
						margin-top: 0em;
					}

						.row.gtr-0.gtr-uniform > * {
							padding-top: 0em;
						}

				.row.gtr-25 {
					margin-top: 0;
					margin-left: -0.25em;
				}

					.row.gtr-25 > * {
						padding: 0 0 0 0.25em;
					}

					.row.gtr-25.gtr-uniform {
						margin-top: -0.25em;
					}

						.row.gtr-25.gtr-uniform > * {
							padding-top: 0.25em;
						}

				.row.gtr-50 {
					margin-top: 0;
					margin-left: -0.5em;
				}

					.row.gtr-50 > * {
						padding: 0 0 0 0.5em;
					}

					.row.gtr-50.gtr-uniform {
						margin-top: -0.5em;
					}

						.row.gtr-50.gtr-uniform > * {
							padding-top: 0.5em;
						}

				.row {
					margin-top: 0;
					margin-left: -1em;
				}

					.row > * {
						padding: 0 0 0 1em;
					}

					.row.gtr-uniform {
						margin-top: -1em;
					}

						.row.gtr-uniform > * {
							padding-top: 1em;
						}

				.row.gtr-150 {
					margin-top: 0;
					margin-left: -1.5em;
				}

					.row.gtr-150 > * {
						padding: 0 0 0 1.5em;
					}

					.row.gtr-150.gtr-uniform {
						margin-top: -1.5em;
					}

						.row.gtr-150.gtr-uniform > * {
							padding-top: 1.5em;
						}

				.row.gtr-200 {
					margin-top: 0;
					margin-left: -2em;
				}

					.row.gtr-200 > * {
						padding: 0 0 0 2em;
					}

					.row.gtr-200.gtr-uniform {
						margin-top: -2em;
					}

						.row.gtr-200.gtr-uniform > * {
							padding-top: 2em;
						}

		}

/* Loader */

	@-moz-keyframes spinner-show {
		0% {
			opacity: 0;
		}

		100% {
			opacity: 1;
		}
	}

	@-webkit-keyframes spinner-show {
		0% {
			opacity: 0;
		}

		100% {
			opacity: 1;
		}
	}

	@-ms-keyframes spinner-show {
		0% {
			opacity: 0;
		}

		100% {
			opacity: 1;
		}
	}

	@keyframes spinner-show {
		0% {
			opacity: 0;
		}

		100% {
			opacity: 1;
		}
	}

	@-moz-keyframes spinner-hide {
		0% {
			color: #464e50;
			z-index: 10001;
			-moz-transform: scale(1) rotate(0deg);
			-webkit-transform: scale(1) rotate(0deg);
			-ms-transform: scale(1) rotate(0deg);
			transform: scale(1) rotate(0deg);
		}

		99% {
			color: #313a3d;
			z-index: 10001;
			-moz-transform: scale(0.5) rotate(360deg);
			-webkit-transform: scale(0.5) rotate(360deg);
			-ms-transform: scale(0.5) rotate(360deg);
			transform: scale(0.5) rotate(360deg);
		}

		100% {
			color: #313a3d;
			z-index: -1;
			-moz-transform: scale(0) rotate(360deg);
			-webkit-transform: scale(0) rotate(360deg);
			-ms-transform: scale(0) rotate(360deg);
			transform: scale(0) rotate(360deg);
		}
	}

	@-webkit-keyframes spinner-hide {
		0% {
			color: #464e50;
			z-index: 10001;
			-moz-transform: scale(1) rotate(0deg);
			-webkit-transform: scale(1) rotate(0deg);
			-ms-transform: scale(1) rotate(0deg);
			transform: scale(1) rotate(0deg);
		}

		99% {
			color: #313a3d;
			z-index: 10001;
			-moz-transform: scale(0.5) rotate(360deg);
			-webkit-transform: scale(0.5) rotate(360deg);
			-ms-transform: scale(0.5) rotate(360deg);
			transform: scale(0.5) rotate(360deg);
		}

		100% {
			color: #313a3d;
			z-index: -1;
			-moz-transform: scale(0) rotate(360deg);
			-webkit-transform: scale(0) rotate(360deg);
			-ms-transform: scale(0) rotate(360deg);
			transform: scale(0) rotate(360deg);
		}
	}

	@-ms-keyframes spinner-hide {
		0% {
			color: #464e50;
			z-index: 10001;
			-moz-transform: scale(1) rotate(0deg);
			-webkit-transform: scale(1) rotate(0deg);
			-ms-transform: scale(1) rotate(0deg);
			transform: scale(1) rotate(0deg);
		}

		99% {
			color: #313a3d;
			z-index: 10001;
			-moz-transform: scale(0.5) rotate(360deg);
			-webkit-transform: scale(0.5) rotate(360deg);
			-ms-transform: scale(0.5) rotate(360deg);
			transform: scale(0.5) rotate(360deg);
		}

		100% {
			color: #313a3d;
			z-index: -1;
			-moz-transform: scale(0) rotate(360deg);
			-webkit-transform: scale(0) rotate(360deg);
			-ms-transform: scale(0) rotate(360deg);
			transform: scale(0) rotate(360deg);
		}
	}

	@keyframes spinner-hide {
		0% {
			color: #464e50;
			z-index: 10001;
			-moz-transform: scale(1) rotate(0deg);
			-webkit-transform: scale(1) rotate(0deg);
			-ms-transform: scale(1) rotate(0deg);
			transform: scale(1) rotate(0deg);
		}

		99% {
			color: #313a3d;
			z-index: 10001;
			-moz-transform: scale(0.5) rotate(360deg);
			-webkit-transform: scale(0.5) rotate(360deg);
			-ms-transform: scale(0.5) rotate(360deg);
			transform: scale(0.5) rotate(360deg);
		}

		100% {
			color: #313a3d;
			z-index: -1;
			-moz-transform: scale(0) rotate(360deg);
			-webkit-transform: scale(0) rotate(360deg);
			-ms-transform: scale(0) rotate(360deg);
			transform: scale(0) rotate(360deg);
		}
	}

	@-moz-keyframes spinner-rotate {
		0% {
			-moz-transform: scale(1) rotate(0deg);
			-webkit-transform: scale(1) rotate(0deg);
			-ms-transform: scale(1) rotate(0deg);
			transform: scale(1) rotate(0deg);
		}

		100% {
			-moz-transform: scale(1) rotate(360deg);
			-webkit-transform: scale(1) rotate(360deg);
			-ms-transform: scale(1) rotate(360deg);
			transform: scale(1) rotate(360deg);
		}
	}

	@-webkit-keyframes spinner-rotate {
		0% {
			-moz-transform: scale(1) rotate(0deg);
			-webkit-transform: scale(1) rotate(0deg);
			-ms-transform: scale(1) rotate(0deg);
			transform: scale(1) rotate(0deg);
		}

		100% {
			-moz-transform: scale(1) rotate(360deg);
			-webkit-transform: scale(1) rotate(360deg);
			-ms-transform: scale(1) rotate(360deg);
			transform: scale(1) rotate(360deg);
		}
	}

	@-ms-keyframes spinner-rotate {
		0% {
			-moz-transform: scale(1) rotate(0deg);
			-webkit-transform: scale(1) rotate(0deg);
			-ms-transform: scale(1) rotate(0deg);
			transform: scale(1) rotate(0deg);
		}

		100% {
			-moz-transform: scale(1) rotate(360deg);
			-webkit-transform: scale(1) rotate(360deg);
			-ms-transform: scale(1) rotate(360deg);
			transform: scale(1) rotate(360deg);
		}
	}

	@keyframes spinner-rotate {
		0% {
			-moz-transform: scale(1) rotate(0deg);
			-webkit-transform: scale(1) rotate(0deg);
			-ms-transform: scale(1) rotate(0deg);
			transform: scale(1) rotate(0deg);
		}

		100% {
			-moz-transform: scale(1) rotate(360deg);
			-webkit-transform: scale(1) rotate(360deg);
			-ms-transform: scale(1) rotate(360deg);
			transform: scale(1) rotate(360deg);
		}
	}

	@-moz-keyframes overlay-hide {
		0% {
			opacity: 1;
			z-index: 10000;
		}

		15% {
			opacity: 1;
			z-index: 10000;
		}

		99% {
			opacity: 0;
			z-index: 10000;
		}

		100% {
			opacity: 0;
			z-index: -1;
		}
	}

	@-webkit-keyframes overlay-hide {
		0% {
			opacity: 1;
			z-index: 10000;
		}

		15% {
			opacity: 1;
			z-index: 10000;
		}

		99% {
			opacity: 0;
			z-index: 10000;
		}

		100% {
			opacity: 0;
			z-index: -1;
		}
	}

	@-ms-keyframes overlay-hide {
		0% {
			opacity: 1;
			z-index: 10000;
		}

		15% {
			opacity: 1;
			z-index: 10000;
		}

		99% {
			opacity: 0;
			z-index: 10000;
		}

		100% {
			opacity: 0;
			z-index: -1;
		}
	}

	@keyframes overlay-hide {
		0% {
			opacity: 1;
			z-index: 10000;
		}

		15% {
			opacity: 1;
			z-index: 10000;
		}

		99% {
			opacity: 0;
			z-index: 10000;
		}

		100% {
			opacity: 0;
			z-index: -1;
		}
	}

	html body {
		text-decoration: none;
	}

		html body:before {
			-moz-osx-font-smoothing: grayscale;
			-webkit-font-smoothing: antialiased;
			display: inline-block;
			font-style: normal;
			font-variant: normal;
			text-rendering: auto;
			line-height: 1;
			text-transform: none !important;
			font-family: 'Font Awesome 5 Free';
			font-weight: 900;
		}

		html body:before {
			-moz-animation: spinner-show 1.5s 1 0.25s ease forwards, spinner-hide 0.25s ease-in-out forwards !important;
			-webkit-animation: spinner-show 1.5s 1 0.25s ease forwards, spinner-hide 0.25s ease-in-out forwards !important;
			-ms-animation: spinner-show 1.5s 1 0.25s ease forwards, spinner-hide 0.25s ease-in-out forwards !important;
			animation: spinner-show 1.5s 1 0.25s ease forwards, spinner-hide 0.25s ease-in-out forwards !important;
			-moz-transform-origin: 50% 50%;
			-webkit-transform-origin: 50% 50%;
			-ms-transform-origin: 50% 50%;
			transform-origin: 50% 50%;
			color: #464e50;
			content: '\f1ce';
			cursor: default;
			display: block;
			font-size: 2em;
			height: 2em;
			left: 50%;
			opacity: 0;
			line-height: 2em;
			margin: -1em 0 0 -1em;
			position: fixed;
			text-align: center;
			top: 50%;
			width: 2em;
			z-index: -1;
		}

		html body:after {
			-moz-animation: overlay-hide 1s ease-in forwards !important;
			-webkit-animation: overlay-hide 1s ease-in forwards !important;
			-ms-animation: overlay-hide 1s ease-in forwards !important;
			animation: overlay-hide 1s ease-in forwards !important;
			background: #313a3d;
			content: '';
			display: block;
			height: 100%;
			left: 0;
			opacity: 0;
			position: fixed;
			top: 0;
			width: 100%;
			z-index: -1;
		}

	html.is-preload body:before {
		-moz-animation: spinner-show 1.5s 1 0.25s ease forwards, spinner-rotate 0.75s infinite linear !important;
		-webkit-animation: spinner-show 1.5s 1 0.25s ease forwards, spinner-rotate 0.75s infinite linear !important;
		-ms-animation: spinner-show 1.5s 1 0.25s ease forwards, spinner-rotate 0.75s infinite linear !important;
		animation: spinner-show 1.5s 1 0.25s ease forwards, spinner-rotate 0.75s infinite linear !important;
		z-index: 10001;
	}

	html.is-preload body:after {
		-moz-animation: none !important;
		-webkit-animation: none !important;
		-ms-animation: none !important;
		animation: none !important;
		opacity: 1;
		z-index: 10000;
	}

	@media (-webkit-min-device-pixel-ratio: 2) {

		html body:before {
			line-height: 2.025em;
		}

	}

/* Section/Article */

	section.special, article.special {
		text-align: center;
	}

	header p {
		color: #a8b0b3;
		letter-spacing: 0.05em;
		text-transform: uppercase;
	}

	header h1 + p {
		margin-top: -1em;
	}

	header h2 + p {
		margin-top: -1em;
	}

	header h3 + p {
		margin-top: -0.8em;
	}

	header h4 + p,
	header h5 + p,
	header h6 + p {
		font-size: 0.8em;
		margin-top: -0.6em;
	}

	header.major {
		text-align: center;
	}

		header.major h1, header.major h2, header.major h3, header.major h4, header.major h5, header.major h6 {
			position: relative;
		}

			header.major h1:after, header.major h2:after, header.major h3:after, header.major h4:after, header.major h5:after, header.major h6:after {
				background: #dddddd;
				content: '';
				display: block;
				height: 2px;
				margin: 0.75em auto 0 auto;
				position: relative;
				width: 4em;
			}

		header.major p {
			margin-top: 0;
		}

/* Form */

	form {
		margin: 0 0 2em 0;
	}

	label {
		color: #61686b;
		display: block;
		font-size: 0.9em;
		font-weight: 700;
		margin: 0 0 1em 0;
	}

	input[type="text"],
	input[type="password"],
	input[type="email"],
	select,
	textarea {
		-moz-appearance: none;
		-webkit-appearance: none;
		-ms-appearance: none;
		appearance: none;
		background: rgba(144, 144, 144, 0.15);
		border-radius: 0;
		border: none;
		color: inherit;
		display: block;
		outline: 0;
		padding: 0 1em;
		text-decoration: none;
		width: 100%;
	}

		input[type="text"]:invalid,
		input[type="password"]:invalid,
		input[type="email"]:invalid,
		select:invalid,
		textarea:invalid {
			box-shadow: none;
		}

		input[type="text"]:focus,
		input[type="password"]:focus,
		input[type="email"]:focus,
		select:focus,
		textarea:focus {
			box-shadow: inset 0 0 0 2px #8cd1a8;
		}

	select {
		background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='40' height='40' preserveAspectRatio='none' viewBox='0 0 40 40'%3E%3Cpath d='M9.4,12.3l10.4,10.4l10.4-10.4c0.2-0.2,0.5-0.4,0.9-0.4c0.3,0,0.6,0.1,0.9,0.4l3.3,3.3c0.2,0.2,0.4,0.5,0.4,0.9 c0,0.4-0.1,0.6-0.4,0.9L20.7,31.9c-0.2,0.2-0.5,0.4-0.9,0.4c-0.3,0-0.6-0.1-0.9-0.4L4.3,17.3c-0.2-0.2-0.4-0.5-0.4-0.9 c0-0.4,0.1-0.6,0.4-0.9l3.3-3.3c0.2-0.2,0.5-0.4,0.9-0.4S9.1,12.1,9.4,12.3z' fill='%23a8b0b3' /%3E%3C/svg%3E");
		background-size: 1.25rem;
		background-repeat: no-repeat;
		background-position: calc(100% - 1rem) center;
		height: 3em;
		padding-right: 3em;
		text-overflow: ellipsis;
	}

		select option {
			color: #61686b;
			background: #fff;
		}

		select:focus::-ms-value {
			background-color: transparent;
		}

		select::-ms-expand {
			display: none;
		}

	input[type="text"],
	input[type="password"],
	input[type="email"],
	select {
		height: 3em;
	}

	textarea {
		padding: 0.75em 1em;
	}

	input[type="checkbox"],
	input[type="radio"] {
		-moz-appearance: none;
		-webkit-appearance: none;
		-ms-appearance: none;
		appearance: none;
		display: block;
		float: left;
		margin-right: -2em;
		opacity: 0;
		width: 1em;
		z-index: -1;
	}

		input[type="checkbox"] + label,
		input[type="radio"] + label {
			text-decoration: none;
			color: #6f7577;
			cursor: pointer;
			display: inline-block;
			font-size: 1em;
			font-weight: 400;
			padding-left: 2.55em;
			padding-right: 0.75em;
			position: relative;
		}

			input[type="checkbox"] + label:before,
			input[type="radio"] + label:before {
				-moz-osx-font-smoothing: grayscale;
				-webkit-font-smoothing: antialiased;
				display: inline-block;
				font-style: normal;
				font-variant: normal;
				text-rendering: auto;
				line-height: 1;
				text-transform: none !important;
				font-family: 'Font Awesome 5 Free';
				font-weight: 900;
			}

			input[type="checkbox"] + label:before,
			input[type="radio"] + label:before {
				background: rgba(144, 144, 144, 0.15);
				content: '';
				display: inline-block;
				font-size: 0.8em;
				height: 2.25em;
				left: 0;
				line-height: 2.25em;
				position: absolute;
				text-align: center;
				top: 0;
				width: 2.25em;
			}

		input[type="checkbox"]:checked + label:before,
		input[type="radio"]:checked + label:before {
			background: #313a3d;
			color: #ffffff;
			content: '\f00c';
		}

		input[type="checkbox"]:focus + label:before,
		input[type="radio"]:focus + label:before {
			box-shadow: inset 0 0 0 2px #8cd1a8;
		}

	input[type="radio"] + label:before {
		border-radius: 100%;
	}

	::-webkit-input-placeholder {
		color: #a8b0b3 !important;
		opacity: 1.0;
	}

	:-moz-placeholder {
		color: #a8b0b3 !important;
		opacity: 1.0;
	}

	::-moz-placeholder {
		color: #a8b0b3 !important;
		opacity: 1.0;
	}

	:-ms-input-placeholder {
		color: #a8b0b3 !important;
		opacity: 1.0;
	}

/* Box */

	.box {
		border: solid 2px #dddddd;
		margin-bottom: 2em;
		padding: 1.5em;
	}

		.box > :last-child,
		.box > :last-child > :last-child,
		.box > :last-child > :last-child > :last-child {
			margin-bottom: 0;
		}

		.box.alt {
			border: 0;
			border-radius: 0;
			padding: 0;
		}

/* Icon */

	.icon {
		text-decoration: none;
		border-bottom: none;
		position: relative;
	}

		.icon:before {
			-moz-osx-font-smoothing: grayscale;
			-webkit-font-smoothing: antialiased;
			display: inline-block;
			font-style: normal;
			font-variant: normal;
			text-rendering: auto;
			line-height: 1;
			text-transform: none !important;
			font-family: 'Font Awesome 5 Free';
			font-weight: 400;
		}

		.icon > .label {
			display: none;
		}

		.icon:before {
			line-height: inherit;
		}

		.icon.solid:before {
			font-weight: 900;
		}

		.icon.brands:before {
			font-family: 'Font Awesome 5 Brands';
		}

		.icon.major {
			display: block;
			margin: 0 0 1em 0;
		}

			.icon.major:before {
				font-size: 2.5em;
			}

/* Image */

	.image {
		border: 0;
		display: inline-block;
		position: relative;
	}

		.image:before {
			background: url("images/overlay.png");
			content: '';
			display: block;
			height: 100%;
			left: 0;
			position: absolute;
			top: 0;
			width: 100%;
		}

		.image img {
			display: block;
		}

		.image.left {
			float: left;
			margin: 0 1.5em 1em 0;
			top: 0.25em;
		}

		.image.right {
			float: right;
			margin: 0 0 1em 1.5em;
			top: 0.25em;
		}

		.image.left, .image.right {
			max-width: 40%;
		}

			.image.left img, .image.right img {
				width: 100%;
			}

		.image.fit {
			display: block;
			margin: 0 0 2em 0;
			width: 100%;
		}

			.image.fit img {
				width: 100%;
			}

/* List */

	ol {
		list-style: decimal;
		margin: 0 0 2em 0;
		padding-left: 1.25em;
	}

		ol li {
			padding-left: 0.25em;
		}

	ul {
		list-style: disc;
		margin: 0 0 2em 0;
		padding-left: 1em;
	}

		ul li {
			padding-left: 0.5em;
		}

		ul.alt {
			list-style: none;
			padding-left: 0;
		}

			ul.alt li {
				border-top: solid 1px #dddddd;
				padding: 0.5em 0;
			}

				ul.alt li:first-child {
					border-top: 0;
					padding-top: 0;
				}

	dl {
		margin: 0 0 2em 0;
	}

/* Icons */

	ul.icons {
		cursor: default;
		list-style: none;
		padding-left: 0;
	}

		ul.icons li {
			display: inline-block;
			padding: 0 1.5em 0 0;
		}

			ul.icons li:last-child {
				padding-right: 0;
			}

			ul.icons li .icon:before {
				font-size: 1.5em;
			}

/* Icons Grid */

	ul.icons-grid {
		list-style: none;
		padding: 0;
		position: relative;
	}

		ul.icons-grid li {
			display: block;
			float: left;
			padding: 3em 0;
			width: 50%;
		}

			ul.icons-grid li h3 {
				margin: 0;
			}

			ul.icons-grid li:nth-child(2n + 1) {
				box-shadow: inset -1px 0 0 0 #dddddd, 1px 0 0 0 #dddddd;
			}

			ul.icons-grid li:nth-child(2n + 3):before {
				background: #dddddd;
				content: '';
				display: block;
				height: 2px;
				margin-top: -3em;
				position: absolute;
				width: 100%;
			}

		ul.icons-grid:after {
			clear: both;
			content: '';
			display: block;
		}

/* Actions */

	ul.actions {
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		cursor: default;
		list-style: none;
		margin-left: -1em;
		padding-left: 0;
	}

		ul.actions li {
			padding: 0 0 0 1em;
			vertical-align: middle;
		}

		ul.actions.special {
			-moz-justify-content: center;
			-webkit-justify-content: center;
			-ms-justify-content: center;
			justify-content: center;
			width: 100%;
			margin-left: 0;
		}

			ul.actions.special li:first-child {
				padding-left: 0;
			}

		ul.actions.stacked {
			-moz-flex-direction: column;
			-webkit-flex-direction: column;
			-ms-flex-direction: column;
			flex-direction: column;
			margin-left: 0;
		}

			ul.actions.stacked li {
				padding: 1.3em 0 0 0;
			}

				ul.actions.stacked li:first-child {
					padding-top: 0;
				}

		ul.actions.fit {
			width: calc(100% + 1em);
		}

			ul.actions.fit li {
				-moz-flex-grow: 1;
				-webkit-flex-grow: 1;
				-ms-flex-grow: 1;
				flex-grow: 1;
				-moz-flex-shrink: 1;
				-webkit-flex-shrink: 1;
				-ms-flex-shrink: 1;
				flex-shrink: 1;
				width: 100%;
			}

				ul.actions.fit li > * {
					width: 100%;
				}

			ul.actions.fit.stacked {
				width: 100%;
			}

		@media screen and (max-width: 480px) {

			ul.actions:not(.fixed) {
				-moz-flex-direction: column;
				-webkit-flex-direction: column;
				-ms-flex-direction: column;
				flex-direction: column;
				margin-left: 0;
				width: 100% !important;
			}

				ul.actions:not(.fixed) li {
					-moz-flex-grow: 1;
					-webkit-flex-grow: 1;
					-ms-flex-grow: 1;
					flex-grow: 1;
					-moz-flex-shrink: 1;
					-webkit-flex-shrink: 1;
					-ms-flex-shrink: 1;
					flex-shrink: 1;
					padding: 1em 0 0 0;
					text-align: center;
					width: 100%;
				}

					ul.actions:not(.fixed) li > * {
						width: 100%;
					}

					ul.actions:not(.fixed) li:first-child {
						padding-top: 0;
					}

					ul.actions:not(.fixed) li input[type="submit"],
					ul.actions:not(.fixed) li input[type="reset"],
					ul.actions:not(.fixed) li input[type="button"],
					ul.actions:not(.fixed) li button,
					ul.actions:not(.fixed) li .button {
						width: 100%;
					}

						ul.actions:not(.fixed) li input[type="submit"].icon:before,
						ul.actions:not(.fixed) li input[type="reset"].icon:before,
						ul.actions:not(.fixed) li input[type="button"].icon:before,
						ul.actions:not(.fixed) li button.icon:before,
						ul.actions:not(.fixed) li .button.icon:before {
							margin-left: -0.5em;
						}

		}

/* Table */

	.table-wrapper {
		-webkit-overflow-scrolling: touch;
		overflow-x: auto;
	}

	table {
		margin: 0 0 2em 0;
		width: 100%;
	}

		table tbody tr {
			border: solid 1px #dddddd;
			border-left: 0;
			border-right: 0;
		}

			table tbody tr:nth-child(2n + 1) {
				background-color: rgba(144, 144, 144, 0.075);
			}

		table td {
			padding: 0.75em 0.75em;
		}

		table th {
			color: #61686b;
			font-size: 0.9em;
			font-weight: 700;
			padding: 0 0.75em 0.75em 0.75em;
			text-align: left;
		}

		table thead {
			border-bottom: solid 2px #dddddd;
		}

		table tfoot {
			border-top: solid 2px #dddddd;
		}

		table.alt {
			border-collapse: separate;
		}

			table.alt tbody tr td {
				border: solid 1px #dddddd;
				border-left-width: 0;
				border-top-width: 0;
			}

				table.alt tbody tr td:first-child {
					border-left-width: 1px;
				}

			table.alt tbody tr:first-child td {
				border-top-width: 1px;
			}

			table.alt thead {
				border-bottom: 0;
			}

			table.alt tfoot {
				border-top: 0;
			}

/* Button */

	input[type="submit"],
	input[type="reset"],
	input[type="button"],
	button,
	.button {
		-moz-appearance: none;
		-webkit-appearance: none;
		-ms-appearance: none;
		appearance: none;
		-moz-transition: background-color 0.2s ease-in-out, color 0.2s ease-in-out;
		-webkit-transition: background-color 0.2s ease-in-out, color 0.2s ease-in-out;
		-ms-transition: background-color 0.2s ease-in-out, color 0.2s ease-in-out;
		transition: background-color 0.2s ease-in-out, color 0.2s ease-in-out;
		background-color: transparent;
		border-radius: 0;
		border: 0;
		box-shadow: inset 0 0 0 2px #dddddd;
		color: #61686b !important;
		cursor: pointer;
		display: inline-block;
		font-weight: 700;
		height: 3em;
		letter-spacing: 0.05em;
		line-height: 3.15em;
		padding: 0 2em;
		text-align: center;
		text-decoration: none;
		text-transform: uppercase;
		white-space: nowrap;
	}

		input[type="submit"]:hover,
		input[type="reset"]:hover,
		input[type="button"]:hover,
		button:hover,
		.button:hover {
			background-color: rgba(144, 144, 144, 0.075);
			color: #61686b !important;
		}

		input[type="submit"]:active,
		input[type="reset"]:active,
		input[type="button"]:active,
		button:active,
		.button:active {
			background-color: rgba(144, 144, 144, 0.15);
			color: #61686b !important;
		}

		input[type="submit"].icon,
		input[type="reset"].icon,
		input[type="button"].icon,
		button.icon,
		.button.icon {
			padding-left: 1.35em;
		}

			input[type="submit"].icon:before,
			input[type="reset"].icon:before,
			input[type="button"].icon:before,
			button.icon:before,
			.button.icon:before {
				color: #a8b0b3;
				margin-right: 0.5em;
			}

		input[type="submit"].fit,
		input[type="reset"].fit,
		input[type="button"].fit,
		button.fit,
		.button.fit {
			width: 100%;
		}

		input[type="submit"].small,
		input[type="reset"].small,
		input[type="button"].small,
		button.small,
		.button.small {
			font-size: 0.8em;
		}

		input[type="submit"].large,
		input[type="reset"].large,
		input[type="button"].large,
		button.large,
		.button.large {
			font-size: 1.35em;
		}

		input[type="submit"].primary,
		input[type="reset"].primary,
		input[type="button"].primary,
		button.primary,
		.button.primary {
			background-color: #8cd1a8;
			border: 0;
			box-shadow: none;
			color: #ffffff !important;
		}

			input[type="submit"].primary:hover,
			input[type="reset"].primary:hover,
			input[type="button"].primary:hover,
			button.primary:hover,
			.button.primary:hover {
				background-color: #9ed8b6;
			}

			input[type="submit"].primary:active,
			input[type="reset"].primary:active,
			input[type="button"].primary:active,
			button.primary:active,
			.button.primary:active {
				background-color: #7aca9a;
			}

			input[type="submit"].primary.icon:before,
			input[type="reset"].primary.icon:before,
			input[type="button"].primary.icon:before,
			button.primary.icon:before,
			.button.primary.icon:before {
				color: #d1eddc;
			}

		input[type="submit"].disabled, input[type="submit"]:disabled,
		input[type="reset"].disabled,
		input[type="reset"]:disabled,
		input[type="button"].disabled,
		input[type="button"]:disabled,
		button.disabled,
		button:disabled,
		.button.disabled,
		.button:disabled {
			background-color: #6f7577 !important;
			box-shadow: none !important;
			color: #fff !important;
			cursor: default;
			opacity: 0.25;
		}

/* Main BG */

	.main-bg {
		-moz-transition: opacity 0.5s ease-out;
		-webkit-transition: opacity 0.5s ease-out;
		-ms-transition: opacity 0.5s ease-out;
		transition: opacity 0.5s ease-out;
		background-attachment: fixed,							fixed;
		background-position: top left,						center center;
		background-repeat: repeat,							none;
		background-size: auto,							cover;
		height: 100%;
		left: 0;
		opacity: 0;
		position: fixed;
		top: 0;
		width: 100%;
		z-index: -1;
	}

		.main-bg.active {
			opacity: 1;
		}

/* Main */

	.main {
		position: relative;
	}

		.main .image.primary {
			display: none;
		}

		.main .container {
			padding: 5em 2.5em 8em 2.5em ;
			background: rgba(255, 255, 255, 0.95);
			box-shadow: inset 0 1px 0 0 #dddddd;
		}

			.main .container:before {
				min-height: calc( 100vh - 13em);
				content: '';
				display: inline-block;
				vertical-align: middle;
				width: 1px;
			}

			.main .container .content {
				display: inline-block;
				margin-right: 1px;
				vertical-align: middle;
				width: calc(100% - 10px);
			}

		.main .goto-next {
			-moz-transition: background-color 0.2s ease-in-out;
			-webkit-transition: background-color 0.2s ease-in-out;
			-ms-transition: background-color 0.2s ease-in-out;
			transition: background-color 0.2s ease-in-out;
			background-color: rgba(144, 144, 144, 0.075);
			background-image: url("images/arrow.svg");
			background-position: center center;
			background-repeat: no-repeat;
			border-radius: 100%;
			border: 0;
			bottom: 3em;
			display: block;
			height: 4em;
			left: 50%;
			line-height: 4em;
			margin-left: -2em;
			overflow: hidden;
			position: absolute;
			text-indent: 4em;
			white-space: nowrap;
			width: 4em;
		}

			.main .goto-next:hover {
				background-color: rgba(144, 144, 144, 0.15);
			}

/* Header */

	#header {
		height: 100vh;
		position: relative;
		text-align: center;
	}

		#header:after {
			content: '';
			display: inline-block;
			height: 100vh;
			vertical-align: middle;
		}

		#header header {
			color: rgba(255, 255, 255, 0.5);
			display: inline-block;
			padding-bottom: 8em;
			vertical-align: middle;
		}

			#header header h1, #header header h2, #header header h3, #header header h4, #header header h5, #header header h6, #header header strong, #header header b {
				color: #ffffff;
			}

			#header header a {
				color: inherit;
			}

				#header header a:hover {
					color: #ffffff !important;
				}

			#header header h1 {
				font-size: 3em;
				line-height: 1.25em;
				margin: 0;
			}

				#header header h1:after {
					margin-top: 0.5em;
				}

			#header header p {
				color: #ffffff;
				font-weight: 700;
				margin: 1.5em 0 0 0;
			}

		#header .container {
			background: rgba(255, 255, 255, 0.95);
			bottom: 0;
			left: 50%;
			margin-left: -17.5em;
			padding: 2.5em;
			position: absolute;
		}

			#header .container > :last-child {
				margin-bottom: 0;
			}

			#header .container .button {
				min-width: 12em;
			}

/* Footer */

	#footer {
		min-height: 100vh;
		padding: 0 0 12em 0;
		position: relative;
		text-align: center;
	}

		#footer .container {
			padding: 5em 2.5em 3em 2.5em ;
			background: rgba(255, 255, 255, 0.95);
			box-shadow: inset 0 1px 0 0 #dddddd;
		}

		#footer footer {
			bottom: 2em;
			color: rgba(255, 255, 255, 0.5);
			left: 0;
			position: absolute;
			text-align: center;
			width: 100%;
		}

			#footer footer h1, #footer footer h2, #footer footer h3, #footer footer h4, #footer footer h5, #footer footer h6, #footer footer strong, #footer footer b {
				color: #ffffff;
			}

			#footer footer a {
				color: inherit;
			}

				#footer footer a:hover {
					color: #ffffff !important;
				}

			#footer footer .copyright {
				font-size: 0.8em;
				line-height: 1em;
				padding: 0;
			}

				#footer footer .copyright li {
					border-left: solid 1px rgba(255, 255, 255, 0.2);
					display: inline-block;
					margin: 0 0 0 1em;
					padding: 0 0 0 1em;
				}

					#footer footer .copyright li:first-child {
						border-left: 0;
						margin-left: 0;
						padding-left: 0;
					}

/* Large */

	@media screen and (max-width: 1680px) {

		/* Basic */

			body, input, select, textarea {
				font-size: 12pt;
			}

	}

/* Medium */

	@media screen and (max-width: 980px) {

		/* Main BG */

			.main-bg {
				display: none;
			}

		/* Main */

			.main .image.primary {
				display: block;
				margin: 0 0 4em 0;
			}

			.main .container {
				padding: 3em 3em 8em 3em ;
			}

				.main .container:before {
					display: none;
				}

		/* Header */

			#header header {
				padding-bottom: 9em;
				width: 80%;
			}

			#header .container {
				margin-left: -40%;
				padding: 3em;
			}

		/* Footer */

			#footer {
				min-height: 0;
				padding: 0;
			}

				#footer .container {
					padding: 3em 3em 1em 3em ;
				}

				#footer footer {
					padding: 3em 3em 1em 3em ;
					bottom: auto;
					position: relative;
				}

	}

/* Small */

	@media screen and (max-width: 736px) {

		/* Basic */

			h2 {
				font-size: 1.35em;
			}

		/* Main */

			.main .container {
				padding: 3em 1.5em 1em 1.5em ;
			}

				.main .container .image.primary:first-child {
					margin: -1.5em 0 2.5em 0;
				}

			.main .goto-next {
				display: none;
			}

		/* Header */

			#header {
				height: 80vh;
			}

				#header:after {
					height: 80vh;
				}

				#header header {
					padding-bottom: 0;
				}

					#header header h1 {
						font-size: 2em;
					}

					#header header p {
						margin-top: 1em;
					}

				#header .container {
					display: none;
				}

		/* Footer */

			#footer .container {
				padding: 3em 1.5em 1em 1.5em ;
			}

	}

/* XSmall */

	@media screen and (max-width: 480px) {

		/* Basic */

			html, body {
				min-width: 320px;
			}

		/* List */

			ul.actions {
				margin: 0 0 2em 0;
			}

				ul.actions li {
					display: block;
					padding: 1em 0 0 0;
					text-align: center;
					width: 100%;
				}

					ul.actions li:first-child {
						padding-top: 0;
					}

					ul.actions li > * {
						margin: 0 !important;
						width: 100%;
					}

				ul.actions.small li {
					padding: 0.5em 0 0 0;
				}

					ul.actions.small li:first-child {
						padding-top: 0;
					}

			ul.icons-grid li {
				box-shadow: inset 0 1px 0 0 #dddddd !important;
				float: none;
				margin: 2em 0 0 0;
				padding: 2em 0 0 0;
				width: 100%;
			}

				ul.icons-grid li:first-child {
					box-shadow: none !important;
					margin-top: 0;
					padding: 1em 0 0 0;
				}

				ul.icons-grid li:nth-child(2n + 1) {
					box-shadow: none;
				}

				ul.icons-grid li:nth-child(2n + 3):before {
					display: none;
				}

		/* Button */

			input[type="submit"],
			input[type="reset"],
			input[type="button"],
			button,
			.button {
				padding: 0;
			}

				input[type="submit"].icon,
				input[type="reset"].icon,
				input[type="button"].icon,
				button.icon,
				.button.icon {
					padding-left: 0;
				}

		/* Main */

			.main .container {
				padding: 3em 1em 1em 1em ;
			}

				.main .container .image.primary:first-child {
					margin: -2em 0 2.5em 0;
				}

		/* Footer */

			#footer .container {
				padding: 3em 1em 1em 1em ;
			}

			#footer footer .copyright {
				line-height: inherit;
			}

				#footer footer .copyright li {
					border-left: 0;
					display: block;
					margin: 0;
					padding: 0;
				}

	}
