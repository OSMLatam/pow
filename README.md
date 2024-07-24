![PoW](https://github.com/OSMLatam/pow/blob/main/pow.png)

# pow

Este repositorio busca solo utilizar la funcionalidad de tiquetes (issues) de GitHub para reportar algún problema de mapeo identificado en el mapa.

[PoW](https://en.wikipedia.org/wiki/Proof_of_work) quiere decir Proof of Work, o prueba de trabajo.

Invitamos a los interesados en el mapa, a darle "watch" (arriba a la derecha), para que sean notificados de los reportes, y poder responder tempránamente a estos.

Este espacio puede considerarse una alternativa (en español) del canal de Discord OSM-World > #questionable-edits (https://discord.com/channels/413070382636072960/763192797775265864/1265749609997930517).

# Quieres reportar un cambio sospechoso

* Tienes que tener cuenta en GitHub. Realmente es fácil crearla.
* Vete al área de Issues: https://github.com/OSMLatam/pow/issues
* Ahí seleccionas "New Issue". 
* En la lista de tipos de issues, selecciona: "Reporte de un problema en el mapa".
  * También puedes ir directamente haciendo [click aquí](https://github.com/OSMLatam/pow/issues/new?assignees=&labels=help+wanted&template=map-change-issue.md&title=Cambio+sospechoso).
* En el formulario, ponle un título corto sobre el problema.
* En la descripción, describe por qué es un cambio sospechoso.
  * Agrega la mayor descripción para entender mejor tu problema.
  * Si has detectado esto gracias a algún proceso automatizado, también lo puedes incluir.
  * Incluye tanta información como quieras (referencia a sitios externos, otros reportes).
* Agrega el "id del objeto y tipo de objeto" o "el id del cambio (changeset)". Puedes reportar varios objetos o changeset al tiempo, siempre y cuando estén relacionados con el mismo problema.
* Ponle la etiqueta (label) del país donde es el problema.
* ¡Listo! Espera un tiempo, que un analizador revisará tu reporte y comenzará a trabajar contigo.

# Quieres ser un **Analizador**

* Tienes que tener cuenta en GitHub. Realmente es fácil crearla.
* Lo primero que debes hacer es darle Watch a este repositorio. Con eso te llegarán las notificaciones de los nuevos reportes.
* Revisa la página de [Issues](https://github.com/OSMLatam/pow/issues) y si te interesa un reporte, comienza a analizarlo técnicamente y documentarlo en el tiquete.
* Si concluyes que es un problema, puedes escribirle al **creador**.
  * Escribe en el changeset(s). Incluye la URL del tiquete, donde están los resultados de tus análisis.
  * Puede usar otros medios de comunicación, como la [mensajería de OSM](https://www.openstreetmap.org/messages/inbox), listas de distribución, [Wiki](https://wiki.openstreetmap.org/), [canales de Telegram](https://wiki.openstreetmap.org/wiki/List_of_OSM_centric_Telegram_accounts), [communities](https://community.openstreetmap.org/).
  * Si después de dos semanas no recibes respuesta del **creador**, entonces puedes reversar el cambio. Pero procura documentar tanto como puedas todo el proceso.
* Si consideras que no es un problema, puedes discutir al respecto con el **usuario** que reportó. Con esto se lleva a un acuerdo de cómo proceder.
* Si ya no hay más que hacer, cierra el tiquete.

# Roles

Para el proceso hay tres roles:

* **"usuario"**: es la persona que está creando un reporte aquí. Es la persona que identificó un problema en el mapa.
* **"analizador"**: es la persona que analiza los reportes y se concluye sobre el cambio sospechoso.
* **"creador"**: es la persona que creó o hizo un cambio en el mapa, el cual se considera un cambio sospechoso.

# Flujo

El flujo es:

* Un **"usuario"** mientra está revisando el mapa ve algo anormal.
  * Pueden ser cambios masivos, borrados sin motivo, un cambio drástico, algo inexistente, exposición de datos personales y el comentario del cambio(s) no ofrece mucho soporte que sustente el cambio. Finalmente, es algo que no concuerda, pueden ser otras cosas diferentes a las que se acaban de indicar, pero hay algo de "sospechoso".
* El **"usuario"** identifica el id feature del objeto o del changeset.
* El **"usuario"** crea un tiquete aquí, explicando por qué considera que no es un cambio(s) normal. Pueden notificarse varios objetos o changesets al tiempo.
  * El título por defecto lo puedes cambiar o extender para dar una idea general de qué es.
  * Como parte del tiquete le pone la etiqueta del país (labels).
* El reporte es revisado por los **"analizadores"** que están suscritos a este repositorio.
  * Preferiblemente, un **analizador** del mismo país del problema, para que haya conocimiento local en la revisión.
* Después del análisis técnico del cambio, el **"analizador"** documenta esto en el tiquete. Este análisis puede incluir lo siguiente:
  * Etiquetas usadas si fue una adición o cambio.
  * Ver los cambios anteriores y posteriores en la historia del usuario.
  * Análisis de fotos satelitales de Bing o EOx (cloudless). Inclusive de Google, ya que no se está mapeando directamente, sino viendo diferencias, por lo tanto no se viola licencia.
  * Fotos de terreno de Mapillary, KartaView o Google StreetView.
  * Búsqueda de la zona en Internet (páginas web del lugar), imágenes, etc.
* Si se concluye que el cambio sí creó un problema en el mapa, el **"analizador"** o el **"usuario"** notifica al **creador** por medio de un mensaje en el chageset. En este mensaje se le indica que el cambio se considera sospechoso.
  * Como parte del mensaje, se debe hacer referencia al tiquete para sustentación técnica.
  * Además del changeset, se puede contactar al **creador** por mensaje directo, o por algún otro medio de comunicación. Es importante que le comunique sobre el análisis, o sea la URL del tiquete en *PoW*.
  * Esto le da tiempo al **"creador"** del cambio de revisarlo y tomar las acciones necesarias.
  * En el tiquete, el **analizador** pone "/remind me check in 2 weeks" para que GitHub le recuerde del tiquete en 2 semanas.
  * Si después de 2 semanas, no se ve respuesta del **"creador"**, se hace un revert ( documentado ) o se le notifica al DWG.
    * Lo puede hacer el **"analizador"** o el **"usuario"**.
  * Si se involucra al DWG, se pueden agregar las comunicaciones públicas con ellos: correos en listas de correo.
  * Una vez hecho el revert, se cierra el tiquete.
    * Lo puede hacer el **"analizador"** o el **"usuario"**.
* Si no se concluye que el cambio creó un problema en el mapa, se habla con el **usuario** para aclarar por qué se reportó. Esta discusión conlleva a otro análisis o a cerrar el tiquete.


# Etiqueta

Es importante que el **usuario** y el **analizador** escriban bastante soporte técnico. Esto le permitirá al creador entender por qué se considera sospechoso el cambio, y mejore sus habilidades de mapeo. Por otro lado, una buen cantidad de texto, permite tener una base documental, para que otras personas aprendar a identificar cambios sospechosos, y por qué no, que la comunidad mapee mejor.

Se recuerda a las personas que participen en el proceso mantener la [etiqueta](https://wiki.openstreetmap.org/wiki/ES:Etiqueta) de OSM. Conservando los buenos términos, y con la suposición de la buena fé de la gente.
