# App-de-tarjeta-de-felicitaciones-con-kotlin

App Android Feliz Cumpleaños
Esta sencilla aplicación para Android que nos muestran en el curso de introducción en kotlin

#Características

Saludo de Cumpleaños: Muestra un gran y alegre mensaje de "Feliz Cumpleaños".
Firma Personalizable: Te permite agregar un mensaje personalizado al final del saludo.
Imagen Festiva: Muestra una imagen de fondo de Android en una fiesta.
Diseño Responsivo: Se adapta a diferentes tamaños de pantalla y orientaciones.

#Detalles Técnicos
Jetpack Compose: Construido completamente con Jetpack Compose, el moderno kit de herramientas de interfaz de usuario de Google para Android, que hace que la creación de interfaces de usuario sea declarativa y eficiente.
Strings de Recursos: Utiliza recursos de cadena para los mensajes para admitir fácilmente varios idiomas en el futuro.
Tema: Utiliza un tema personalizado (HappyBirthdayTheme) para un estilo consistente.

#Cómo Empezar
Clonar el Repositorio:
Bash
git clone <url-del-repositorio>
Usa el código con precaución.

Abrir en Android Studio: Importa el proyecto en Android Studio.

Compilar y Ejecutar: Haz clic en el botón "Ejecutar" para compilar e instalar la aplicación en un emulador o en tu dispositivo conectado.

#Personalización
Strings: Modifica los valores happy_birthday_text y signature_text en el archivo strings.xml para personalizar tu saludo.
Imagen: Reemplaza la imagen androidparty en la carpeta drawable con tu propia imagen festiva.
Estilo: Personaliza los colores, fuentes y otros elementos visuales de la aplicación modificando el HappyBirthdayTheme en el paquete ui.theme.

#Estructura del Código
MainActivity: La actividad principal que configura el contenido de Jetpack Compose.
GreetingImage (Composable): El elemento principal de la interfaz de usuario que combina la imagen, el mensaje de texto y la firma.
GreetingText (Composable): Responsable de mostrar el mensaje de texto y la firma en un diseño de columna.

#Contribuciones
José Minier 20200928
