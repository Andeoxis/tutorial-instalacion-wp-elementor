# tutorial-instalacion-wp-elementor

ANTHONY LEANDRO VASQUEZ TORRICO
# Tutorial de Instalación: WordPress + Elementor Pro
Este repositorio contiene la evidencia y el paso a paso de la instalación local de WordPress y la configuración manual de Elementor con las funciones PRO desbloqueadas, utilizando XAMPP.

## Parte 1: Preparación del Entorno e Instalación de WordPress
**Realizado por: [Escribe tu nombre aquí]**

1. **Instalación de XAMPP:** Descargamos XAMPP desde la web de Apache Friends e iniciamos los servicios de Apache y MySQL desde el Panel de Control.
2. **Creación de Base de Datos:** Ingresamos a `localhost/phpmyadmin` y creamos una base de datos local llamada `wordpress`.
3. **Descarga de WordPress:** Descargamos el archivo oficial desde wordpress.org, lo descomprimimos y movimos la carpeta resultante a la ruta de nuestro servidor local: `C:\xampp\htdocs\`.
4. **Configuración Inicial:** En el navegador, entramos a `localhost/wordpress`, conectamos la base de datos (usuario: root, sin contraseña) y completamos el formulario para crear nuestro usuario administrador de WordPress.
*(Las evidencias fotográficas de esta fase se encuentran en la carpeta `evidencia`)*
## Parte 2: Instalación de Elementor (Versión Gratuita)
**Realizado por: Helen Victoria Rojas Lafuente**

1. **Búsqueda del Plugin:** Dentro del panel de administración de WordPress (Escritorio), navegamos a la sección **Plugins > Añadir nuevo plugin**.
2. **Instalación:** En la barra de búsqueda ingresamos la palabra "Elementor" para buscar el maquetador en el repositorio oficial.
3. **Activación:** Hicimos clic en "Instalar ahora" en la tarjeta de "Maquetador web Elementor" y esperamos a que el proceso terminara para finalmente presionar el botón "Activar".
4. **Omitir configuración:** Durante la pantalla de bienvenida de Elementor, omitimos los pasos de registro para entrar directamente a usar la herramienta de forma local.
*(Las capturas de pantalla de esta búsqueda y activación están en la carpeta evidencia)*
## Parte 3: Instalación Manual de PRO Elements (Desbloqueo)
**Realizado por: [Oliver Rodrigo Fernandez Nava]**

1. **Descarga del archivo:** Para obtener las funciones de pago de forma gratuita, ingresamos a la página oficial `proelements.org` y descargamos el archivo `.zip`.
2. **Descompresión:** Extraemos el contenido del `.zip` descargado, obteniendo como resultado una carpeta llamada `pro-elements`.
3. **Migración manual:** Copiamos esa carpeta extraída y la pegamos manualmente dentro de los archivos de nuestro servidor en la siguiente ruta: `C:\xampp\htdocs\wordpress\wp-content\plugins`.
4. **Activación final:** Volvimos al panel de administración de WordPress, fuimos a la lista de **Plugins instalados**, buscamos el nuevo plugin llamado "PRO Elements" y le dimos clic en "Activar". Con esto, las funcionalidades Pro quedaron habilitadas correctamente.
*(Las evidencias de la descompresión y migración de carpetas están en la carpeta evidencia)*

