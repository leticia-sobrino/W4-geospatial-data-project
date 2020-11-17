# Madrid 💪 vs. 💪 London

### ÍNDICE
#### 1. INTRODUCCION 🔍
#### 2. ESTRUCTURA 💀
#### 3. ANÁLISIS 🚀
#### 5. CONCLUSIÓN 🎉
#### 5. COMENTARIOS Y RECOMENDACIONES  ⚡


### 1. INTRODUCCION 🔍
Este proyecto cosiste en la limpieza y análisis de un dataset mediante la utilización de la herramienta Mongo y la Api de "Foursquare Developers". 
A partir de estas dos herramienta se tomará la decsión de dónde es mejor lanzar nuestra nueva empresa, en este caso en Madrid o Londres. Esto lo hemos conseguido mediante herramientas de geocalización tanto como de de pandas, como la de cartoframes y follium.

#### 2. ESTRUCTURA 💀
La estructura de este proyecto está compuesta por:
    1. Una carpeta de notebooks:
        a) Madrid vs London
            En este notebook nos encontraremos la limpieza y selección de las empresas que queremos tener a nuestro al rededor mediante la utilización de la herramienta mongo y, en donde se proprocionarán mapas visuales realizados mediante el uso de la libreria cartoframes. 
        b) API
            En este notebook se realizará la llamada a la Api de "Foursquare Developers", de donde sacaremos unas condciones preferentes donde queremos que nuestra empresa este ubicada.
        c) Coclusiones Madrid
            Este notebook muestra tablas finales y limpias de las cuales podremos empezar a pintar mapas para tener una pre-visualización de donde podremos ubicar nuestra nueva empresa. 
            Para mayor precisión se utiliza una función que calcula la distancia entre nuestra condiciones favorables y nuestros puntos de empresas.
            También se muestran unas conclusiones finales en donde se comprenderá la toma de decsión de unas coordenadas exactas para nuestra nueva empresa basados en datos totalmente razonados.
        d) Conclusiones Londres
            Muestra tablas finales y limpias de las cuales podremos empezar a pintar mapas para tener una pre-visualización de donde podremos ubicar nuestra nueva empresa. 
            Para mayor precisión se utiliza una función que calcula la distancia entre nuestra condiciones favorables y nuestros puntos de empresas.
            También se muestran unas conclusiones finales en donde se comprenderá la toma de decsión final de unas coordenadas exactas para nuestra nueva empresa basados en datos totalmente razonados.
    Los notebooks se encuentran completamente detallados y explicados desde el principio hasta el final.
    2. Una carpeta de outputs 
    Donde podrás encontrar todas las tablas importadas y guardadas en formato csv.
    3. Una carpeta de inputs
    En donde podrás encontrar todos los mapas finales creados.

#### 3. ANÁLISIS 🚀
El motivo de este proyecto era elegir que ubicación era mejor para lanzar tu empresa. Yo, por motivos personales me he decido a investigar y comparar entre Madrid y Londres. 
Lo primero de todo ha sido analizar donde estban las empresas que me gustaría convivir tanto en madrid como en Londres y por ello he sacado la información filtrando el dataset mediante aquellas empresas:
    - Ubicadas en Madrid y Londres
    - Cuya actividad empresarial esté relacionada con el ecommerce
    - Y cuyo año de fundación haya sido a partir del 2005. Me hubiera gustado incluso encontrar empresas más jóvenes pero el daset no tenía información de empresas fundadas más tarde del 2015. 
Mediante el uso de la Api he querido meter determinadas condiciones que me limitaban más la ubicación de dónde querñía lanzar mi empresa. He determinado mi búsqueda dependiendo de:
    - Si había bares por los alrededores de mi futura ubicación.
    - Si se realizaban conferencia y enventos para que los trabjadores de la empresa puedan acudir para ampliar su formación y se lancen a la innovación.
    - Y, he determidado que me gustaría tener colegios cercanos para facilitar a los padres y madres de mi empresa ha poder ir a recoger a sus hijos al colegio.

#### 5. CONCLUSIÓN 🎉
Tras todo el análisis y el estudio anterior la toma de deción no ha sido fácil pero, me he decantado por Londres con coodenadas:
    Latitud: 51.500152
    Longitud: -0.126236
(las conclusiones argumentadas y razonadas se encontrarán en el notebook correspondiente)

#### 5. COMENTARIOS Y RECOMENDACIONES  ⚡
Si tienes recomendaciones, mejoras sobre el proyecto o incluso quieres debatir sobre las conclusiones finales ¡no dudes en dejar tu comentario!



