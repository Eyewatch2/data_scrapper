# Nicestream Scraper

## Instalación
**Pasos de Instalación:**

1. **Descargar la Extensión:**
   - En una carpeta a la cual accedas fácilmente, clona el repositorio con el comando 
   ```git clone https://github.com/Eyewatch2/data_scrapper.git```
   en una terminal o descarga el archivo .zip del mismo.

2. **Descomprimir la Extensión:**
   - Si la extensión se descargó como un archivo .zip, descomprímelo en una ubicación accesible en tu computadora.

3. **Acceder a la Página de Extensiones de Chrome:**
   - Abre Google Chrome en tu computadora.

4. **Habilitar el Modo de Desarrollador:**
   - Haz clic en el icono de tres puntos verticales en la esquina superior derecha de la ventana del navegador.
   - En el menú desplegable, selecciona "Extensiones" y luego "Administrar extensiones".
   - En la página de extensiones, busca la opción "Modo de desarrollador" en la esquina superior derecha de la ventana y actívala si aún no está habilitada.

5. **Cargar la Extensión:**
   - En la página de extensiones de Chrome, haz clic en el botón "Cargar descomprimida".
   - Selecciona la carpeta donde se encuentra la extensión (la carpeta principal que contiene el archivo manifest.json) que descomprimiste en el paso 2.

6. **Confirmar la Instalación:**
   - Una vez cargada la extensión, debería aparecer en la lista de extensiones instaladas en la página de extensiones de Chrome.
   - Asegúrate de que la casilla de verificación junto a la extensión esté marcada para habilitarla.

7. **Listo para Usar:**
   - Todo listo, ahora puedes ir a cualquier página y activar la extensión, la cual se desplegará en una ventana emergente.

## Uso
**Cómo Usarlo:**
1. Abre la primera página de resultados de listados (productos, directorio, etc.) en tu navegador.
2. Activa la extensión.
3. La extensión intentará adivinar dónde se encuentran tus datos. Si no estás satisfecho, utiliza el botón "Probar otra tabla" para intentarlo de nuevo.
4. Descarga un archivo CSV o Excel desde la primera página si eso es todo lo que necesitas. O haz clic para localizar el botón "Siguiente" y marcar el enlace/botón "Siguiente" en un sitio web.
5. Haz clic en "Comenzar a rastrear" para empezar a rastrear a través de múltiples páginas de un sitio web. La extensión mostrará estadísticas sobre lo que se está recolectando.
6. Descarga el archivo Excel o CSV en cualquier momento durante el rastreo.
7. Limpia los archivos Excel o CSV: es probable que tengan algunos campos adicionales no deseados que fueron extraídos de la página. Probablemente también tendrás que cambiar los nombres de las columnas.
8. Prueba otra tabla: la IA intentará adivinar una tabla alternativa si la suposición inicial no fue la que querías.

**Otras Características:**

- **Localizar botón de "Siguiente":** presiona este botón y marca la ubicación del botón o enlace "Siguiente" en un sitio web. Esto se utilizará para extraer datos de múltiples páginas en un solo archivo.
- **Delay de Rastreo:** tiempo en segundos antes de pasar a la siguiente página. El valor predeterminado es de 1 segundo, pero puede aumentarse cuando las páginas cargan información dinámicamente.
- **Botones de Descarga de CSV y XLSX:** están activos de inmediato cuando se encuentra algún dato.
- **Scroll Infinito:** la extensión puede desplazarse hacia abajo en páginas donde se carga más información dinámicamente. Detecta automáticamente cuando se detiene la carga de nuevos datos.

> :ADVERTENCIA: **Esta extensión es solamente para el uso interno de la empresa. No se debe distribuir.
