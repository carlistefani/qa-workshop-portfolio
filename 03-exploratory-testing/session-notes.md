# Sesión 1
## Charter
Explorar la funcionalidad de la barra de busqueda usando datos conocidos del sitio y valores limite para descubrir la capacidad de busqueda del sitio y posibles errores
## ÁREAS
- JPetStore
- OS | MacOS 26.3.1
- Plataforma | Web (Chrome 146.0.7680.80)
- Estrategia | Exploracion Funcional
## INICIO
17/04/2026 17:00
## TESTER
Carlina Stefani
## DESGLOSE DE TAREAS
### Duracion: 
40 minutos

### Diseño y ejecución de pruebas
100

### Investigacion y reporte de defectos


### Preparacion de la sesion

## ARCHIVOS DE DATOS

## NOTAS DE PRUEBA
Se realizan pruebas con distintos tipos de datos para verificar la respuesta de la barra de busqueda:
### Datos a Considerar:
- Coleccion de nombres de items existentes
- Coleccion de codigos de productos
- Coleccion de codigos de items
- Secciones de la pagina

## LISTA DE RIESGOS 
- Malfuncinamiento de la barra puede enviar al usuario a una pagina rota
- Resultados incompletos o erroneos

## DEFECTOS (BUGS) 
- BUG BB 01: La busqueda no devuelve resultados con el codigo del item o producto
- BUG BB 02: La descripcion de cada resultado es un enlace al producto
- BUG BB 03: Los resultados son en funcion al producto en lugar de en funcion al item
- BUG BB 04: La barra de busqueda permanece populada luego de realizar la busqueda

## INCIDENTES (ISSUES) 
- No contamos con un documento de requerimientos que nos indique el alcance de la funcion de la busqueda