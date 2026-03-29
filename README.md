#Login_Register

##Descripcion
Aplicacion en donde la pagina principal  es un login donde el usuario puede iniciar sesion siempre y acceder al contenido de la pagina.
El objetivo de la practica es enternder el funcionamiento de login y manejo de sesiones en PHP.

##Tecnologias
PHP
MySQL
HTML
CSS

##Uso
El usuario puede acceder a al contenido de la pagina siempre y cuando este registrado en la BD
si no lo esta, hay un link para registrarse que mostrara otra vista, llenas los campos(usuario, contraseña, confirmar contraseña)
y se registra en la BD y te devuelve a la pagina de login en donde ya podras acceder al contenido de la pagina que esta protegido, 
se usa $_SESSION para validar el acceso al usuario si no tiene una sesion activa.
El usuario puede cerrar la sesion, se desytruye la sesion y se redireccciona al login.
La BD se llama login con una tabla de usuarios y con gtres campos(id, usuario, pass)
