* Funcionalidades implementadas
  
1. Barra superior (App Bar / Toolbar)

Título centrado.

Botón de volver (flecha atrás).

Menú superior con:

Acerca de

Añadir película (solo XML)

2. Lista de películas (ListView + XML)

Se muestran varias películas con imagen, título y director.

Al pulsar una película:

Se muestra un Toast con el título y director.

3. Añadir películas

El menú Añadir película agrega una película nueva a la lista.

Se actualiza automáticamente el ListView.

4. Menú contextual (ActionMode)

Pulsación larga sobre un elemento permite seleccionar varios.

Aparece la barra de acciones en la parte superior.

Se puede borrar las películas seleccionadas.

5. Pantalla Acerca de

Accesible desde el menú superior.

Muestra información de la práctica.

6. Pantalla de edición (Compose)

Formulario en Jetpack Compose con:

Título

Director

Año

Género

Formato

Enlace a IMDB

Notas

El botón Guardar cierra la pantalla (no persiste datos, tal como pide la práctica).

* Estructura relevante del proyecto

FilmListActivity.kt → Lista y manejo de menús

FilmListAdapter.kt → Adaptador del ListView

FilmDataSource.kt → Datos iniciales

menu_film_list.xml → Menú superior

menu_film_list_context_delete.xml → Menú contextual

activity_film_list.xml → Toolbar + ListView

FilmEditComposeActivity.kt → Pantalla de edición en Compose

LO QUE SE PIDE:

La aplicación cumple con todos los puntos solicitados para la práctica de:

Menús, App Bar, Toolbar, Menú contextual y acciones básicas.
