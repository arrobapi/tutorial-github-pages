# Guía Paso a Paso: Cómo publicar tu web en GitHub Pages

GitHub Pages es un servicio gratuito de alojamiento web estático ofrecido por GitHub. Es ideal para publicar proyectos personales, portafolios o cualquier web hecha con HTML, CSS y JavaScript.

A continuación, encontrarás el método más rápido y sencillo para publicar la web diseñada por tu IA directamente desde la plataforma de GitHub.

---

## Requisitos previos

1. Tener una cuenta en [GitHub](https://github.com/).
2. Tener listos los archivos de tu página web generados por la IA en tu ordenador.
3. **Muy importante:** El archivo principal de tu web debe llamarse exactamente **`index.html`** (en minúsculas) para que GitHub Pages lo detecte como la página de inicio.

---

## Método: Subida directa desde la web de GitHub (El más fácil)

Este método es ideal si no tienes instalado Git en tu ordenador o si quieres publicar tu web de forma rápida y visual.

### Paso 1: Crear un nuevo repositorio
Un repositorio es como la carpeta de tu proyecto en los servidores de GitHub.

1. Entra en tu cuenta de [GitHub](https://github.com/).
2. En la barra lateral izquierda (arriba de tu lista de repositorios recientes), haz clic en el botón verde **New** (Nuevo).
3. Configura tu repositorio:
   * **Repository name (Nombre del repositorio):** Escribe el nombre de tu proyecto (por ejemplo, `mi-primera-web` o `portafolio`). Evita usar espacios o tildes; usa guiones para separar palabras.
   * **Description (Descripción):** (Opcional) Una breve descripción de tu web.
   * **Public / Private:** Debe ser **Public** (Público). GitHub Pages solo es gratuito para repositorios públicos.
   * **Initialize this repository with:** Deja todas estas opciones desmarcadas (no añadas README, .gitignore ni licencia por ahora).
4. Haz clic en el botón verde **Create repository** (Crear repositorio).

---

### Paso 2: Subir los archivos de tu web
Una vez creado el repositorio, verás una pantalla con instrucciones de configuración.

1. Busca el enlace que dice **"uploading an existing file"** (subir un archivo existente) en la sección superior y haz clic en él.
2. Abre la carpeta de tu ordenador donde guardaste los archivos que generó la IA.
3. Selecciona **todos los archivos y carpetas** de tu web (tu `index.html`, carpetas de imágenes, archivos `.css`, `.js`, etc.) y arrástralos directamente al recuadro gris de la página de GitHub.
   * *Nota: Asegúrate de arrastrar el contenido de tu carpeta, no la carpeta contenedora en sí. El archivo `index.html` debe quedar en la raíz.*
4. Espera a que se terminen de cargar todos los archivos.
5. En la parte inferior, verás la sección **Commit changes** (Confirmar cambios):
   * Escribe un título breve en el primer campo (por ejemplo: `Subida inicial de la web`).
   * Deja seleccionada la opción **Commit directly to the `main` branch** (o `master`).
6. Haz clic en el botón verde **Commit changes**.

---

### Paso 3: Activar GitHub Pages
Ahora que tus archivos están en GitHub, solo falta activar el servidor web.

1. Dentro de tu repositorio, ve a la pestaña **Settings** (Configuración) en el menú horizontal superior (icono de engranaje).
2. En el menú lateral izquierdo, busca la sección **Code and automation** y haz clic en **Pages**.
3. En la sección **Build and deployment** (Construcción y despliegue):
   * Bajo el apartado **Source** (Origen), asegúrate de que esté seleccionado **Deploy from a branch**.
   * Bajo el apartado **Branch** (Rama), cambia el desplegable que dice *None* por la rama **`main`** (o `master`).
   * Deja la carpeta en **`/ (root)`** (raíz).
4. Haz clic en el botón **Save** (Guardar).

---

### Paso 4: ¡Ver tu web publicada!
¡Todo listo! GitHub comenzará a procesar y publicar tu sitio web.

1. Espera entre 1 y 2 minutos.
2. Refresca la página de **Settings > Pages**.
3. En la parte superior de esa misma sección aparecerá un cuadro con tu URL final. Verás un mensaje como:
   > **Your site is live at:** `https://tu-usuario.github.io/nombre-del-repositorio/`
4. Haz clic en el enlace para abrir tu página web en una nueva pestaña y comprobar que todo funciona correctamente.

---

## 🔄 Cómo actualizar tu web y subir cambios en el futuro

Cuando tu IA genere una nueva versión mejorada de tu página web, o decidas hacer modificaciones en tu código tú mismo, **no necesitas crear otro repositorio**. Puedes actualizar tu web pública sobrescribiendo los archivos existentes siguiendo estos pasos detallados:

1. **Entra a tu repositorio:** Abre tu perfil en GitHub y selecciona tu repositorio actual de la lista de la izquierda.
2. **Accede a la opción de carga:** Justo encima de la lista con tus archivos actuales (a la derecha de la barra de navegación de tu repositorio), busca el botón desplegable que dice **Add file** (Añadir archivo) y haz clic en **Upload files** (Subir archivos).
3. **Sube tus nuevos archivos:** Arrastra los archivos modificados desde tu ordenador. 
   * *⚠️ Clave: Los archivos nuevos deben tener exactamente el mismo nombre que los anteriores (ej: `index.html`) para que GitHub entienda que debe reemplazarlos.*
4. **Confirma la actualización:** Desplázate hacia abajo hasta la caja de **Commit changes**, escribe una breve nota describiendo tu cambio (ej: *"Actualizado por la IA"*) y haz clic en el botón verde **Commit changes**.
5. **Verifica los cambios:** Dale un margen de unos 1-2 minutos para que los servidores de GitHub reconstruyan tu portal y refresca la URL de tu página web. ¡Los cambios ya estarán en vivo!

---

## 🏫 Créditos y Autoría

Este tutorial interactivo ha sido desarrollado y es mantenido por la **[Academia arrobaPi](https://arrobapi.com)**.

Nuestro objetivo es democratizar el aprendizaje de la tecnología, la programación y el uso de herramientas de Inteligencia Artificial para que cualquier persona pueda materializar sus ideas en la web.