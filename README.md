![PoW](https://github.com/OSMLatam/pow/blob/main/pow.png)

# pow

Este repositorio busca solo utilizar la funcionalidad de tiquetes (issues) de GitHub para reportar algún problema de mapeo identificado en el mapa.

[PoW](https://en.wikipedia.org/wiki/Proof_of_work) quiere decir Proof of Work, o prueba de trabajo.

Se invita a los interesados en el mapa, a darle "watch" (arriba a la derecha), para que sean notificados ante los reportes, y poder responder tempránamente a la solicitud.

# Roles

Para el proceso hay tres roles:

* **"usuario"**.
* **"analizador"**.
* **"creador"**.

# Flujo

El flujo es:

* Un **"usuario"** mientra está revisando el mapa ve algo anormal.
  * Pueden ser cambios masivos, borrados sin motivo, un cambio drástico, algo inexistente, exposición de datos personales y el comentario del cambio(s) no ofrece mucho soporte que sustente el cambio. Finalmente, es algo que no concuerda, pueden ser otras cosas diferentes a las que se acaban de indicar, pero hay algo de "sospechoso".
* El **"usuario"** identifica el id feature del objeto o del changeset. Pueden notificarse varios al tiempo.
* El **"usuario"** crea un tiquete aquí, explicando por qué considera que no es un cambio(s) normal.
  * Como parte del tiquete le pone la etiqueta del país.
* El reporte es revisado por los **"analizadores"** que están suscritos a este repositorio.
  * Un **"analizador"** lo revisa. Preferiblemente, un **analizador** del mismo país del problema, para que haya conocimiento local en la revisión.
* Después del análisis técnico del cambio, el **"analizador"** documenta esto en el tiquete. Este análisis puede incluir lo siguiente:
  * Etiquetas usadas si fue una adición o cambio.
  * Ver los cambios anteriores y posteriores en la historia del usuario.
  * Análisis de fotos satelitales de Bing o EOx (cloudless). Inclusive de Google, ya que no se está mapeando directamente, sino viendo diferencias.
  * Fotos de terreno de Mapillary, KartaView o Google StreetView.
  * Búsqueda de la zona en Internet (páginas web del lugar), imágenes, etc.
* Si se concluye que el cambio sí creó un problema en el mapa, el **"analizador"** o el **"usuario"** notifica al **creador** por medio de un mensaje en el chageset. En este mensaje se le indica que el cambio se considera sospechoso.
  * Como parte del mensaje, se puede hacer referencia al tiquete para sustentación técnica.
  * Esto le da tiempo al **"creador"** del cambio de revisarlo y tomar las acciones necesarias.
  * Además del changeset, se puede contactar al **creador** por mensaje directo, o por algún otro medio de comunicación. Es importante que le comunique sobre el análisis, o sea la URL del tiquete en *PoW*.
* Si después de 2 semanas, no se ve respuesta del **"creador"**, se hace un revert ( documentado ) o se le notifica al DWG.
  * Lo puede hacer el **"analizador"** o el **"usuario"**.
* Si se involucra al DWG, se pueden agregar las comunicaciones públicas con ellos: correos en listas de correo.
* Una vez hecho el revert, se cierra el tiquete.
  * Lo puede hacer el **"analizador"** o el **"usuario"**.

Es importante que el **usuario** y el **analizador** escriban bastante soporte técnico. Esto le permitirá al creador entender por qué se considera sospechoso el cambio, y mejore sus habilidades de mapeo. Por otro lado, una buen cantidad de texto, permite tener una base documental, para que otras personas aprendar a identificar cambios sospechosos, y por qué no, que la comunidad mapee mejor.

Se recuerda a las personas que participen en el proceso mantener la [etiqueta](https://wiki.openstreetmap.org/wiki/ES:Etiqueta) de OSM. Conservando los buenos términos, y con la suposición de la buena fé de la gente.
