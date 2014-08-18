<html lang="es">
<head>
	<meta charset="UTF-8">
</head>
<body>
	<h1>Ejemplo de deploy con Git y Github</h1>
	<ol>
		<li>Crea el repositorio local -> git init</li>
		<li>Crea la llave ssh local -> ssh-keygen</li>
		<li>Añade la llave ssh local en GitHub: id_rsa.pub</li>
		<li>Crea un repositorio vacío en GitHub</li>
		<li>Añade el repositorio remoto a tu repositorio local: git remote add origin https://github.com/marionava/ejemplo.git</li>
		<li>Sube los archivos locales a GitHub: git push origin master. Te pedirá usuario y contraseña de GitHub</li>
		<li>Crea el repositorio en tu server -> git init</li>
		<li>Crea la llave ssh en tu server -> ssh-keygen</li>
		<li>Añade la llave ssh de tu server a GitHub: id_rsa.pub</li>
		<li>Añade el repositorio remoto a tu repositorio en el server: git remote add origin https://github.com/marionava/ejemplo.git</li>
		<li>Obtén la información de GitHub a tu server: git pull origin master</li>
	</ol>
</body>
</html>