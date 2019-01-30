# paginas-web
Usando html, css e javaScript

// codigo CSS

body {
	background-color: #c0c0c0;
	padding-bottom: 90px;
	font-family: "Crimson Text", "Times New Roman", serif;
}

h1{
	text-align: center;
	background-color: #004080;
	color: #ffffff;
	padding:25px;
	border: 5px solid black;
	font-size: 60px;
}

h2, fieldset {
	font-family: "Open Sans Condensed", "ariel", sans-serif;
}

input[type=text],input[type=email], select  {	
	width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    font-size: 17px;
}

.uf {
	width: 32%;
}

table {
	padding: 12px 20px;
}

#cometario {
	width: 100%;
    height: 150px;
    padding: 12px 20px;
    margin: 8px 0;
    box-sizing: border-box;
    border: 2px solid #ccc;
    border-radius: 4px;
    background-color: #f8f8f8;
    resize: none;
}
input:focus{
	background-color: #A8C4E3;
}

.curso {
	border: 5px solid #C2CCCA;
	padding: 20px;
	width: 250px;
	margin: 20px 40 px;
}

.button {
    background-color: #004080; /* blue */
    border: none;
    color: white;
    padding: 16px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    -webkit-transition-duration: 0.4s; /* Safari */
    transition-duration: 0.4s;
    cursor: pointer;
}

.rodape {
	background-color: gray;
	color: White;
	position: fixed;
	clear: both;
	box-sizing: border-box;
	bottom: 0;
	left: 0;
	width: 100%;
}
