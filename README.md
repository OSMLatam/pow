# pow

[PoW](https://en.wikipedia.org/wiki/Proof_of_work) quiere decir Proof of Work, o prueba de trabajo. Este repositorio busca solo utilizar la funcionalidad de tiquetes (issues) de GitHub para reportar algún problema de mapeo identificado en el mapa.

Para el proceso hay tres roles:

* **"usuario"**.
* **"analizador"**.
* **"creador"**.

El flujo es:

* Un **"usuario"** revisando el mapa ve algo anormal.
  * Pueden ser cambios masivos, borrados sin motivo, un cambio drástico y el comentario del cambio no ofrece mucho soporte que sustente el cambio.
* El **"usuario"** identifica el id feature del objeto o del changeset.
* El **"usuario"** crea un tiquete aquí, explicando por qué considera que no es un cambio normal.
  * Como parte del tiquete le pone la etiqueta del país.
* El reporte es revisado por las **"analizadores"** que están suscritos a este repositorio.
  * Preferíblemente un **"analizador"** del país involucrado lo revisa.
* Después del análisis del cambio, el **"analizador"** documenta esto en el tiquete.
* Si se concluye que el cambio creó un problema, el **"analizador"** o el **"usuario"** escribe el resultado del análisis como comentario del changeset.
  * Se puede hacer referencia al tiquete para sustentación técnica.
  * Esto le da tiempo al **"creador"** del cambio de revisarlo y tomar las acciones necesarias.
* Si después de 2 semanas, no se ve respuesta del **"creador"**, se hace un revert.
  * Lo puede hacer el **"analizador"** o el **"usuario"**.
* Se cierra el tiquete.
  * Lo puede hacer el **"analizador"** o el **"usuario"**.
