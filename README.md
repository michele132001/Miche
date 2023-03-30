# Miche

<!DOCTYPE html>
<html>
<head>
	<title>Il Mio Sito per Bambini</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<style>
		body {
			font-family: Arial, sans-serif;
		}
		header {
			background-color: #f2b9ac;
			padding: 20px;
			text-align: center;
			font-size: 2em;
			color: #fff;
		}
		nav {
			background-color: #f2b9ac;
			padding: 10px;
			text-align: center;
			color: #fff;
			font-size: 1.2em;
		}
		nav ul {
			list-style-type: none;
			margin: 0;
			padding: 0;
		}
		nav li {
			display: inline-block;
			margin-right: 20px;
		}
		nav a {
			color: #fff;
			text-decoration: none;
		}
		nav a:hover {
			text-decoration: underline;
		}
		.container {
			margin: 20px;
		}
		.card {
			display: inline-block;
			background-color: #fff;
			padding: 10px;
			border: 1px solid #ccc;
			border-radius: 5px;
			margin: 10px;
			width: 300px;
			height: 400px;
			vertical-align: top;
			box-shadow: 0px 0px 5px #ccc;
		}
		.card img {
			width: 100%;
			height: 200px;
			object-fit: cover;
			border-radius: 5px;
			margin-bottom: 10px;
		}
		.card h2 {
			font-size: 1.5em;
			margin: 0;
		}
		.card p {
			font-size: 1.2em;
			margin: 0;
		}
		.button {
			display: inline-block;
			background-color: #f2b9ac;
			color: #fff;
			padding: 10px;
			border: none;
			border-radius: 5px;
			margin-top: 10px;
			cursor: pointer;
			font-size: 1.2em;
			text-align: center;
			text-decoration: none;
		}
		.button:hover {
			background-color: #e09689;
		}
		.feedback {
			background-color: #f2b9ac;
			padding: 10px;
			text-align: center;
			color: #fff;
			font-size: 1.2em;
			margin-top: 20px;
		}
		.feedback textarea {
			width: 100%;
			height: 100px;
			margin-top: 10px;
			border-radius: 5px;
			border: none;
			padding: 5px;
			font-size: 1.2em;
		}
		.feedback input[type="submit"] {
			display: block;
			background-color: #fff;
			color: #f2b9ac;
			border: none;
			border-radius: 5px;
			padding: 10px;
			margin-top: 10px;
			cursor: pointer;
			font-size: 1.2em;
		
