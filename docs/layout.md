# Disposición

La plataforma tiene un diseño estandar basado en una SPA *Single page Aplication*; comuesta por una vista de ingreso con las funcionalidades públicas y metodos de acceso y una serie de vistas internas a las que podrán acceder los usuarios autenticados segun su rol.

## Vistas Públicas

Es la vista obtenida al acceder a la URL de la plataforma, desde ella se podrán realizar acciones relacionadas a al autenticación como lo son el ingreso al aplicativo o el restablecimiento de la contraseña.

Desde esta visual se también se podrá tambien acceder a recursos públicos, como es el caso de esta documentación o la *consulta expresa* de una póliza específica emitida disponible.

## Vistas Privadas

Al acceder a la plataforma se tiene una estructura definida, la cual cuenta con una *barra de navegación* a lo largo de la parte izquierda de la página, un *encabezado* en la parte superior de la misma y el *contenido* del recurso requerido

### Barra de navegación

La barra de navegacion recopila las rutas de acceso a los recursos que el usuario tiene a disposición según su rol, desde ella el usuario podrá acceder facilmente a las rutas para ver los contendios que requiera. 

??? example "Composición"
    *   **Inicio** - Redirección a vista de Inicio
    *   **Opciones** - Agrupación de recursos de apoyo
        *   **Incidencias** - Monitoreo de incidentes de la plataforma 
    *   **Cuentas** - Agrupación de recursos de cuentas personales
        *   **Usuarios** - Listado de cuentas personales
    *   **Actores** - Agrupación de recursos de cuentas corporativas
        *   **Administradores** - Listado de cuentas corporativas de rol administrador
        *   **Aseguradoras** - Listado de cuentas corporativas de rol asegurador
        *   **Intermediarios** - Listado de cuentas corporativas de rol intermediario
        *   **Tomadores** - Listado de cuentas corporativas de rol tomador
    *   **Pólizas** - Agrupación de pólizas
        *   **Generales** - Listado de pólizas generales 
        *   **Específicas** - Listado de pólizas específicas
    *   **Interesados** - Agrupación de figuras complementarias
        *   **Generadores** - Listado de generadores
    *   **Copyright** - Apartado de derechos de autor

### Encabezado

El encabezado presenta un resumen del estado actual de sesión, presenta la indicación la ubicación actual dentro de la plataforma, el rol del usuario autenticado asi como su nombre y el nombre del actor al que está vinculado y el logo (si esta definido). De igual manera presenta opciones de perfil, desde las que podrá editar la información permitida tanto personal como corporativa. Finalmente se encuentra la funcionalidad de fin de sesión. 

### Contenido

En esta seccion se presenta la interfaz gráfica para la interacción. Estas secciones podran ser infomres con graficos e indicadores de interés, compendios de datos en tablas, formularios para edicion o creacion de instancias, visuales con información de un resgistro en especifico o incluso el historial de cambios de una unidad de negocio. Cabe aclarar que solo se tendrá a disposición las acciones y elementos que le sean permitidos al rol del usuario autenticado.