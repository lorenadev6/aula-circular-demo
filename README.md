# Aula Circular v1.4.0 — demostración visual

Demo estática independiente con datos ficticios. Este repositorio contiene únicamente la demostración pública. GitHub Pages no se ha activado como parte de esta subida.

## Cómo verla

Abre index.html con Chrome, Edge o Firefox. Conserva los archivos juntos. No necesita instalaciones, conexión a Internet, Node.js ni PostgreSQL.

Utiliza «Ver como»: Visitante, Alumno o Docente, sin contraseña. Para Mi espacio selecciona Alumno; para Panel docente selecciona Docente. Al recargar vuelve a Visitante.

## Secciones

Inicio; biblioteca y libros con búsqueda, filtros y fichas; documentación; Mi espacio con intercambios, publicaciones, solicitudes, préstamos y avisos; propuesta y aceptación de intercambios; borrador de publicación; panel docente con cuentas pendientes, revisión, recursos, operaciones, intercambios y trazabilidad.

Las operaciones muestran un mensaje explicativo. No envían ni guardan datos. Los documentos y recursos digitales son ejemplos visuales sin descarga real. No introduzcas información personal.

## Compatibilidad con GitHub Pages

El punto de entrada es index.html. Las hojas de estilo y JavaScript utilizan rutas relativas (`./estilos.css`, `./demo.css`, `./demo.js`). La navegación utiliza fragmentos (`#biblioteca`, `#mi-espacio`, etc.), sin rutas que requieran un servidor de aplicación o reglas de redirección. Compatible con la base `/aula-circular-demo/`. No hay imágenes externas ni archivos de imagen necesarios: el favicon es una URL de datos vacía.

## Archivos y privacidad

Archivos públicos: index.html, estilos.css, demo.css, demo.js, README.md y .gitignore. Sin dependencias ni recursos externos.

Revisión del contenido completo y de archivos ocultos: no se han encontrado credenciales, contraseñas, tokens, bases de datos ni datos personales reales. Los registros de alumnado y docentes son ficticios. No utiliza almacenamiento del navegador ni llamadas de red. La política CSP bloquea conexiones de datos y envíos de formularios.

El .gitignore excluye archivos de entorno, claves, bases de datos, dependencias, carpetas privadas, registros, temporales y archivos comprimidos habituales. Antes de añadir contenido nuevo es necesario volver a revisar los archivos; .gitignore no sustituye esa revisión.

## Verificación de esta subida

Sintaxis de JavaScript validada con `node --check demo.js`. Referencias locales revisadas y resueltas bajo `/aula-circular-demo/`. Revisión de la navegación y de los formularios: los enlaces son fragmentos y las acciones de formulario se interceptan sin enviar datos. Esta revisión no incluye una prueba visual nueva en navegador ni una comprobación de una web desplegada.

El proyecto original y el repositorio privado aula-circular no se modifican.
