# **Sincronizar GitHub con Visual Code**_
## Recorrido básico para conectar GitHub con Visual Studio Code

### Pasos: 🛠️
1.	Asegurarnos de tener instalado git en nuestro ordenador. Si no lo tenemos la url de descarga sería: [git](https://git-scm.com/)
<img width="560" alt="img1" src="https://user-images.githubusercontent.com/9333838/142816656-f4b021fc-3774-4e07-8e6d-a3f7c933c869.png">
3.	Abrimos GitBash (o consola de Git).
4.	Para configurar Git lanzamos desde la consola los comandos:
```
git config --global user.name "Tu nombre aquí"
git config --global user.email "tu_email_aquí@example.com"
```
Para saber si todo está OK lanzamos el comando:
```
git config -–global –-list
```
 

Esto lo que hace es crear un archivo llamado .gitconfig con nuestros datos. Podremos ver los datos almacenados de nuestras credenciales.

4.	Ahora nos vamos a GitHub y creamos un nuevo repositorio:
5.	Seguidamente copiamos la url de nuestro repositorio:

6.	Abrimos visual y cargamos una carpeta donde queramos clonar nuestro repositorio remoto.

7.	Seguidamente vamos al menú  Ver -- Paleta de comandos o  pulsamos CTRL+Mayúsc+P (en Windows).

8.	Escribimos Git Clone y añadimos la url de nuestro repositorio:


Seleccionamos clonar desde GitHub
Nos pedirá permisos de Github para permitir su acceso desde visual Code. Permitimos permisos

En algunas ocasiones nos da un Tokens para que pulsando en Iniciar Sesión de GitHub en visual code (barra inferior) pegamos el tokens dado por GitHub.



9.	Ahora para probar a subir nuestro código, creamos un fichero de prueba y pulsamos en el control de código fuente de la barra lateral de Visual Code.










10.	El paso más rápido para subir nuestra información sería elegir un texto identificativo para los cambios realizados hasta ahora y pulsar CTRL+ENTER en la barra superior como se puede ven en la imagen:



Pulsamos en agregar todos los cambios y realizar el commit directamente hasta nuestro repositorio de GitHub.
Puede que nos vuelva a pedir que nos identifiquemos

Nota: Si diese algún error, estando en el terminal de visual code, seleccionamos consola bash y volvemos a introducir nuestros datos:
git config --global user.name "Tu nombre aquí"
git config --global user.email "tu_email_aquí@example.com"
Automáticamente ya estarán los cambios en nuestro repositorio de GITHUB


