# paginas-web
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>Cadastro de aluno</title>
		<link rel="icon" href="impacta.png">
		<link rel="stylesheet" href="style.css">
	</head>
	<body>
		<h1>Faculdade Impacta</h1>
		<h2>Faça sua matricula!</h2>
		<form>
		<fieldset><legend><b>Cadastro</b></legend>
		<table>	
			<tr>
				<td>
					<label for="Nome" id="nome">Nome completo</label>
					<input type="text" name="nome" maxlength="20"  placeholder="Digite seu nome completo">
				</td>
				<td>
					<label for="cpf" id="cpf">CPF</label>
					<input type="text" name="cpf" maxlength="14" placeholder="Digite seu CPF">
				</td>
				<td>
					<label for="rg" id="rg">RG</label>
					<input type="text" name="cpf" maxlength="12" placeholder="Digite seu RG">
				</td>
			</tr>
			<tr>
				<td>
					<label for="cidade">Cidade</label>
					<input type="text" name="cidade" placeholder="Digite a cidade onde reside">
				</td>
				<td>
					<label for="endereço">Endereço</label>
					<input type="text" name="endereço" maxlength="30" placeholder="Digite o nome da rua">
				</td>
				<td>
					<label for="uf">UF</label>
					<select class="uf">
						<option>AC</option>
						<option>AL</option>
						<option>AM</option>
						<option>AP</option>
						<option>BA</option>
						<option>CE</option>
						<option>DF</option>
						<option>ES</option>
						<option>GO</option>
						<option>MA</option>
						<option>MG</option>
						<option>MS</option>
						<option>MT</option>
						<option>PA</option>
						<option>PB</option>
						<option>PE</option>
						<option>PI</option>
						<option>PR</option>
						<option>RJ</option>
						<option>RN</option>
						<option>RO</option>
						<option>RR</option>
						<option>RS</option>
						<option>SC</option>
						<option>SE</option>
						<option>SP</option>
						<option>TO</option>
					</select>
				</td>
			</tr>
			<tr>
				<td>
					<label for="e-mail">E-mail</label>
					<input type="email" name="emailaddress" placeholder="Digite seu email de contato">
				</td>
				<td>
					<label for="rede social">Rede Social</label>
					<select>
						<option>Selecione uma rede</option>
						<option>Facebook</option>
						<option>WhatsApp</option>
						<option>Twitter</option>
						<option>Outros</option>
					</select>
				</td>
				<td>
					<input type="text" name="redesocial" placeholder="Digite sua rede social">
				</td>
			</tr>
		</table>
		</fieldset>
		<fieldset><legend><b>Cursos</b></legend>
		<table>
			<tr>
				<td>
<p><input name="curso1" type="checkbox" id="ads">Análise e Desenvolvimento de Sistemas <em>IoT, DevOps & Mobile</em></p>
<p><input name="curso2" type="checkbox" id="si">Sistemas de Informação <em>Business Agility & Computação Cognitiva</em></p>
<p><input name="curso3" type="checkbox" id="redes">Redes de Computadores <em>Cloud Computing & Cyber Security</em></p>
				</td>
			</tr>
		</table>
		</fieldset>
		<fieldset><legend><b>Deixe seu comentario</b></legend>
			<label for="comentario">Conte nos o motivo da sua inscrição</label>
			<br/>
			<textarea id="cometario" maxlength="100" >
			</textarea>
		</fieldset>
		<br/>
		<br/>
		<label for="botão"></label>
		<input type="button" class="button" value="Enviar">
		</form>
	</body>
	<footer class="rodape">
		&copy; Faculdade Impacta de Tecnologia
		<center><b>Integrantes do grupo</b></center>
		<center>Valeria Pereira Victor Gonçalves</center><br/><p></p>
		</footer>
</html>

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
