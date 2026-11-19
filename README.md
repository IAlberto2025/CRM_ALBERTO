# CRM Comercial Alberto – PWA

Esta carpeta contiene una versión instalable del CRM para publicarla como sitio web mediante GitHub Pages. Está preparada para abrirse desde Safari y añadirse a la pantalla de inicio del iPhone.

## Publicarlo en GitHub Pages

1. Crea un repositorio en GitHub.
2. Sube **todo el contenido de esta carpeta** a la raíz del repositorio (no solo el ZIP).
3. En GitHub, entra en **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/(root)`, y guarda.
6. Cuando GitHub facilite la dirección `https://...github.io/...`, ábrela en Safari en el iPhone.
7. Pulsa **Compartir → Añadir a pantalla de inicio**.

## Importante: privacidad de la cartera

La versión incluida contiene los datos de clientes y prospectos que estaban integrados en el CRM. **No publiques este repositorio como público**: los nombres, teléfonos, direcciones y demás datos comerciales podrían quedar expuestos. Antes de publicarlo, comprueba que el repositorio y el sitio tienen acceso privado/protegido adecuado. Un repositorio privado no garantiza por sí solo que el sitio publicado sea privado en todos los planes de GitHub.

## Clientes fidelizados

En el listado de clientes puedes pulsar **☆ Marcar fidelizado** para destacar al cliente en verde e identificarlo como cliente que requiere visitas puntuales. El mismo botón permite quitar la marca. La clasificación se conserva en los datos guardados y en las copias de seguridad exportadas.

## Clientes favoritos

Cada cliente tiene un botón **☆ Favorito**. Al marcarlo, la ficha se destaca en amarillo con una estrella y sube por encima de los demás clientes. También puedes filtrar el listado para ver solo favoritos o excluirlos. La marca se guarda con los datos del CRM y se incluye en las copias de seguridad exportadas.

## Datos y sincronización

Los cambios se guardan en el almacenamiento del navegador del dispositivo. Esta versión no sincroniza automáticamente los cambios entre iPhone y Mac ni dispone de una base de datos en la nube. Exporta copias de seguridad desde el CRM con regularidad.

## Asistente IA

El apartado de asistente sigue sin conectarse a un servicio real. No introduzcas claves API en este proyecto ni en el navegador; para activarlo hará falta un pequeño servidor seguro.

## Nota técnica

La aplicación conserva el CRM actual y añade manifiesto, iconos y service worker para su instalación como PWA. El mapa y otras funciones que dependen de servicios externos necesitan conexión a Internet.
