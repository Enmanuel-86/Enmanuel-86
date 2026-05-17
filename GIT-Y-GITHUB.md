
<img src="https://images.icon-icons.com/2415/PNG/512/git_original_logo_icon_146509.png" alt = "logo de git" height= "40px" width= "40px"> <b style="font-size:50px;">GIT</b>



**GIT** es un controlador de versiones de nuestros repositorios locales.


## Configuraciones Iniciales en GIT 

Para registrar nuestro usuario en la PC en donde tengamos GIT debemos saber que existe configuración  **Global** y **Local** :

- La configuración *Global* hace referencia a que todas las carpetas de tu pc se puedan usar la misma configuracion que si usuario, email, editor de codigo etc..
 
- La configuración *Local* hace referencia a que solamente puedes utilizar esta configuración en el o los repositorios que hayas configurado, basicamente tienes que configurar cada vez que quieras iniciar un nuevo repositorio.

<hr>

### Empezaremos con la configuración inicial

1. Configuración del nombre de usuario:
		
		git config --global user.name <Nombre-de-usuario>
		
2. Configuración del correo:

		git config --global user.email "<correo>"

3. configuración del core.autocrlf:

	Dependiendo del sistema operativo la configuración es distinta

	- Para Windows usamos **TRUE
	
			git config --global core.autocrlf true

	- Para linux usaremos **INPUT

			git config --global core.autocrlf input