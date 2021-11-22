# **Sincronizar GitHub con Visual Code**
## Recorrido básico para conectar GitHub con Visual Studio Code

### Pasos: 🛠️
1.	Asegurarnos de tener instalado git en nuestro ordenador. Si no lo tenemos la url de descarga sería: [git](https://git-scm.com/)
2.	Abrimos GitBash (o consola de Git).
3.	Para configurar Git lanzamos desde la consola los comandos:
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
<p align="center">
  <img width="560" alt="img1" src="https://user-images.githubusercontent.com/9333838/142816656-f4b021fc-3774-4e07-8e6d-a3f7c933c869.png">
</p>
5.	Seguidamente copiamos la url de nuestro repositorio:
<p align="center">
  <img width="461" alt="img2" src="https://user-images.githubusercontent.com/9333838/142823125-2d1b565a-4235-4989-b809-a7814aac8310.png">
</p>
6.	Abrimos visual y cargamos una carpeta donde queramos clonar nuestro repositorio remoto.

7.	Seguidamente vamos al menú  Ver -- Paleta de comandos o  pulsamos CTRL+Mayúsc+P (en Windows).

8.	Escribimos Git Clone y añadimos la url de nuestro repositorio:
<p align="center">
  <img width="430" alt="img3" src="https://user-images.githubusercontent.com/9333838/142823146-2667d527-50cf-43dc-9b2a-90575e1e1918.png">
</p>
9. Seleccionamos clonar desde GitHub. Nos pedirá permisos de Github para permitir su acceso desde visual Code. Permitimos permisos

<img width="326" alt="img4" src="https://user-images.githubusercontent.com/9333838/142823174-850bbc81-2129-4858-9aa8-68ddee03cec2.png">

En algunas ocasiones nos da un Tokens para que pulsando en Iniciar Sesión de GitHub en visual code (barra inferior) pegamos el tokens dado por GitHub.
<p align="center">
  <img width="414" alt="img5" src="https://user-images.githubusercontent.com/9333838/142823184-4a220bee-fb22-4263-90a2-c660f08da171.png">
</p>
10.	Ahora para probar a subir nuestro código, creamos un fichero de prueba y pulsamos en el control de código fuente de la barra lateral de Visual Code.

11.	El paso más rápido para subir nuestra información sería elegir un texto identificativo para los cambios realizados hasta ahora y pulsar CTRL+ENTER en la barra superior como se puede ven en la imagen:
<p align="center">
  <img width="467" alt="img6" src="https://user-images.githubusercontent.com/9333838/142823204-38710e7c-ac57-46b2-8a22-685f177b0deb.png">
</p>
Pulsamos en agregar todos los cambios y realizar el commit directamente hasta nuestro repositorio de GitHub.
Puede que nos vuelva a pedir que nos identifiquemos
<p align="center">
  <img width="343" alt="img7" src="https://user-images.githubusercontent.com/9333838/142823216-cb7e72de-7b59-49a9-9316-0a43ee2de8f7.png">
</p>
### Nota: Si diese algún error, estando en el terminal de visual code, seleccionamos consola bash y volvemos a introducir nuestros datos:
```
git config --global user.name "Tu nombre aquí"
git config --global user.email "tu_email_aquí@example.com"
```
Automáticamente ya estarán los cambios en nuestro repositorio de GITHUB


