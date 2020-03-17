# Gatsby Hotel

## Aplicación creada con React, Gatsby y obteniendo datos de la plataforma DatoCMS

Gatsby ultimamente se está haciendo muy popular ya que es un rápido generador de sitios estáticos para React, en su núcleo implementa la arquitectura JAMSTACK (Javascript API Markup), lo que hace que las aplicaciones construidas sean las más veloces.

El ejemplo de la aplicación lo puedes ver trabajando en un Delploy hacia Zeit.co (Creadores de Next) en este link `https://gatsbyhotel.now.sh`, y muestra datos construidos en la plataforma DatoCMS.

Gatsby te permite obtener los datos usando GraphQL (Lenguaje de consulta para APIs), este no depende en nada de HTTP (a diferencia de REST), lo que le permite construir sitios web con la data que se requiera mostrar desde una o mas fuentes (CMSs, SaaS, APIs, Bases de datos, sistemas de archivos, entre otros).

Clona el repo.

Crea una cuenta en DatoCMS `https://www.datocms.com/`
Construye una nueva app
Crea dos colecciones nuevas una llamada "paginas" y otra llamada "habitaciones"
En cada una de las colecciones crea las siguientes columnas:

- Titulo
- Contenido
- Imagen
- Slug

Luego busca en el apartado Explorador de API el token de DatoCMS y copiarlo

En el archivo `gatsby-config-example.js` donde dice `gatsby-source-datocms` cambiar el valor de `option` por el token de DatoCMS.

Cambiar el nombre del archivo `gatsby-config-example.js` a `gatsby-config.js`

Al hacer esto ya debería estar conectando gatsby con datoCMS

Luego correr el comando `$ gatsby develop`

y listo. Enjoy 😀!!!

Saludos

Antonio Rodríguez
FullStack Developer
