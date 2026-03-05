# Flow FavManager ⭐ - Addon para Kodi


![Kodi](https://img.shields.io/badge/Kodi--blue?logo=kodi) ![Status](https://img.shields.io/badge/Estado-Activo-brightgreen) [![Roadmap](https://img.shields.io/badge/Roadmap-Ver_Metas-orange?logo=github)](./ROADMAP.md) [![Read in English](https://img.shields.io/badge/Read_in_English-🇬🇧-blue)](./README.md)

## Descripción

**Flow FavManager** es un gestor avanzado de favoritos para Kodi. Además de facilitar su organización, permite personalizar colores, iconos, formatos, las acciones que ejecutan y crear secciones; también incluye un sistema de copias de seguridad y un sistema de perfiles independientes, entre otras funciones que se detallan más adelante.

<p align="center">
  <img src="screenshots/screenshot1.png" alt="Captura 1" width="800"/>
  <!-- <img src="screenshots/screenshot2.png" alt="Captura 2" width="800"/> -->
  <!-- <img src="screenshots/screenshot3.png" alt="Captura 3" width="800"/> -->
  <!-- <img src="screenshots/screenshot4.png" alt="Captura 4" width="800"/> -->
  <!-- <img src="screenshots/screenshot5.png" alt="Captura 5" width="800"/> -->
</p>

## 📥 Instalación

> **Nota sobre el Idioma:**
> Si el addon no aparece en tu idioma tras la instalación, revisa la sección de [Releases](https://github.com/loioloio/flowfav/releases) para descargar versiones en otros idiomas.

### Opción 1: Desde el Administrador de Archivos de Kodi (Recomendado)
Este es el método más sencillo ya que no requiere descargar archivos externos manualmente y permite actualizaciones automáticas:

1. Abre Kodi y ve a **Ajustes** (icono del engranaje).
2. Entra en **Explorador de archivos** y selecciona **Añadir fuente**.
3. Haz clic en `<Ninguno>` y escribe la siguiente dirección: `https://loioloio.github.io/flowfav/`

   > ⚠️ **MUY IMPORTANTE:** Debes escribir **EXACTAMENTE** esta dirección. **NO** copies la dirección que ves en la barra de tu navegador (`github.com...`), ya que esa no funciona en Kodi y te saldrá la carpeta vacía.

4. Dale un nombre a la fuente (por ejemplo: `flowfav`) y pulsa **OK**.
5. Vuelve al menú principal, entra en **Add-ons** y haz clic en el icono de la **cajita abierta** (arriba a la izquierda).
6. Selecciona **Instalar desde archivo zip**.
   - *Nota: Si te sale un aviso de seguridad, ve a Ajustes y activa la opción "Orígenes desconocidos".*
7. Selecciona la fuente `flowfav` y elige el archivo `repository.flowfavmanager-1.0.0.zip`.
8. Espera a que aparezca la notificación de "**Add-on instalado**" (esto instala el repositorio).
9. Ahora, en el mismo menú, selecciona **Instalar desde repositorio**.
10. Entra en **Flow FavManager Repository** > **Program add-ons** > **Flow FavManager** y pulsa **Instalar**.

### Opción 2: Instalación manual mediante archivo ZIP
1. Descarga el archivo `repository.flowfavmanager-1.0.0.zip` de la última versión desde la sección de [Releases](https://github.com/loioloio/flowfav/releases).
2. En Kodi, ve a **Add-ons** > **Icono de la cajita** > **Instalar desde archivo zip**.
3. Busca en tu dispositivo el archivo descargado y selecciónalo para completar la instalación.

---

## 🧩 Características

### 1. Gestión Avanzada de Listas y Perfiles
- **Sistema de Multi-Perfiles:** Crea y gestiona perfiles ilimitados (archivos JSON independientes) para separar entornos (ej: "Niños", "Deportes", "Cine").
- **Importación y Exportación:** Comparte perfiles o muévelos entre dispositivos fácilmente mediante archivos XML.
- **Plantillas de Sistema:** Incluye listas predefinidas y editables con accesos directos a secciones y comandos útiles de Kodi.
- **Widget Dinámico:** Ruta especializada (`/widget`) para integrar tus favoritos como carpetas limpias en los widgets de skins avanzados (Aura, Arctic, Titan, etc).


### 2. Edición y Personalización Visual
- **Editor en Ventana Emergente:** Interfaz cómoda y rápida para editar las propiedades de tus favoritos.
- **Personalización Total:** Cambia el color del texto, aplica formatos (negrita/cursiva) y ajusta el tamaño de fuentes e iconos.
- **Gestión de Iconos:** Asignación automática de iconos o selección manual de imágenes personalizadas.
- **Barras Separadoras:** Inserta líneas o textos divisorios para organizar visualmente tus listas.
- **Accesibilidad:** Permite ampliar la interfaz e incluye modos de alto contraste y paletas adaptadas.

### 3. Organización y Automatización
- **Ordenación:** Permite ordenar los favoritos de forma rápida y sencilla.
- **Operaciones Masivas:** Selecciona múltiples ítems (Multiselección) para mover, borrar o colorear en grupo.
- **Agrupación Automática:** Algoritmo inteligente que agrupa favoritos por su Addon de origen con un solo clic.
- **Ordenación y Búsqueda:** Herramientas de ordenación (A-Z, Z-A, Invertir) y filtrado de texto en tiempo real para localizar contenidos rápidamente.

### 4. Creación y Manipulación
- **Creación y Edición Manual:** Crea favoritos desde cero escribiendo la ruta, edita comandos existentes o duplica entradas.
- **Selector de Addons:** Buscador integrado para añadir favoritos desde cualquier addon instalado sin salir del editor.
- **Menú Contextual Global:** Añade contenido a Flow FavManager desde cualquier lugar de Kodi usando el menú contextual (clic derecho).
- **Maximizador de Compatibilidad:** Corrige automáticamente URLs problemáticas para asegurar la ejecución de todos los favoritos.

### 5. Seguridad y Mantenimiento
- **Protección con PIN:** Bloquea el acceso al editor o perfiles con código numérico y bloqueo de sesión inteligente.
- **Sistema de Rescate:** Si olvidas tu clave, puedes recuperarla mediante tu pregunta de seguridad. Como última opción, el sistema detectará si creas un archivo llamado `reset_pass.txt` en la carpeta de datos del addon, eliminando la protección automáticamente sin borrar tus perfiles.
- **Log de Auditoría:** Registro interno de acciones críticas para un control total.
- **Sistema de Backup:** Herramientas integrales para crear copias de seguridad y restaurar tu archivo `favourites.xml`.

> **Y mucho más...** Flow FavManager está en constante desarrollo, añadiendo nuevas funciones y mejoras regularmente. ¡Descúbrelo tú mismo!

---

## 📋 Requisitos

- Compatible con Kodi.
- No requiere dependencias complejas.

---

## ⚖️ Aviso Legal

**Flow FavManager** es una herramienta de organización.

1.  **Exención de Responsabilidad**: Este software se proporciona "tal cual", sin garantía de ningún tipo. El autor no se hace responsable de posibles pérdidas de datos o mal funcionamiento derivado de su uso. Se recomienda realizar copias de seguridad regularmente.
2.  **Privacidad**: Este addon no recopila, almacena ni envía datos personales. Todo el procesamiento se realiza de forma local en tu dispositivo.


---

## 💬 Soporte

Si encuentras un fallo o tienes una sugerencia:

👉 **[Abrir una Issue en GitHub](https://github.com/loioloio/flowfav/issues)**

👉 **Formulario de Contacto**: Disponible a través del enlace web en la [página principal del perfil de GitHub](https://github.com/loioloio).


---

*Si buscas el código fuente, cambia a la rama source de este repositorio.*

---

*Fundado por RubénSDFA1labernt* - [GitHub](https://github.com/loioloio/flowfav)
