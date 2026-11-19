# MECP Web

**[Obrir la web](https://ferromargi.github.io/web/)**

[Català](#català) | [English](#english) | [Español](#español)

Una interfície web interactiva per al protocol MECP (Mesh Emergency Communication Protocol), dissenyada per a crear, revisar i enviar missatges d'emergència estructurats.

An interactive web interface for the **MECP** (*Mesh Emergency Communication Protocol*), designed to create, review and send structured emergency messages.

Una interfaz web interactiva para el protocolo **MECP** (*Mesh Emergency Communication Protocol*), diseñada para crear, revisar y enviar mensajes de emergencia estructurados.

---

<a id="català"></a>

## Català

### Què és MECP Web?

**MECP Web** és una aplicació web basada en el protocol **MECP** (*Mesh Emergency Communication Protocol*). Permet crear missatges d’emergència estructurats per a comunicacions mitjançant xarxes *mesh* LoRa i facilita la comunicació entre persones que parlen idiomes diferents.

Aquest projecte inclou una interfície web adaptada a partir de MECP i afegeix suport complet per al **català**.

### Funcions principals

- Selecció d’idioma de la interfície.
- Consulta dels codis MECP per categories i nivells de gravetat.
- Composició de missatges d’emergència estructurats.
- Adjunció d’informació addicional, com ara posició GPS, nombre de persones o marca de temps.
- Vista prèvia, còpia i exportació de missatges.
- Historial de missatges.
- Suport per a la traducció al català.

### Traducció al català

La traducció al català inclou:

- Els codis d’emergència.
- Les categories de missatges.
- Els nivells de gravetat.
- Els textos de la interfície.
- Les etiquetes i missatges del sistema.

S’ha utilitzat el fitxer anglès `languages/en.json` com a referència per mantenir el context i la terminologia de cada codi.

### Bandera catalana

El selector d’idiomes mostra la bandera catalana mitjançant un **SVG** amb les nou franges tradicionals de la Senyera:

```text
Groc – Vermell – Groc – Vermell – Groc – Vermell – Groc – Vermell – Groc
```

S’ha utilitzat un SVG en lloc d’un emoji de bandera perquè no existeix un emoji Unicode universal per a la bandera catalana. Això permet que la bandera es mostri de manera consistent en diferents navegadors i sistemes operatius, inclosos els navegadors basats en Chromium a Windows.

### Com utilitzar-la

1. Obre la pàgina web publicada a GitHub Pages.
2. Selecciona l’idioma al selector superior.
3. Tria el nivell de gravetat del missatge.
4. Selecciona una o més categories i codis MECP.
5. Afegeix informació addicional si cal.
6. Revisa la vista prèvia i copia o envia el missatge.



### Crèdits i llicències

Aquest projecte està basat en [MECP — Mesh Emergency Communication Protocol](https://github.com/mecp-org/MECP).

| Component | Llicència |
|---|---|
| Especificació del protocol MECP | [CC0 1.0 — domini públic](https://creativecommons.org/publicdomain/zero/1.0/) |
| Fitxers d’idioma | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Codi de l’aplicació i del motor a [mecp-app](https://github.com/mecp-org/mecp-app) | [GPLv3](https://www.gnu.org/licenses/gpl-3.0.html) |

El protocol MECP és lliure per sempre: qualsevol persona el pot implementar sense restriccions. L’especificació està dedicada al domini públic mitjançant CC0 1.0.

Els fitxers d’idioma es publiquen sota **CC BY 4.0**. Això permet copiar-los, adaptar-los i redistribuir-los, fins i tot amb finalitats comercials, sempre que es reconegui l’autoria original.

El codi de l’aplicació i del motor de [mecp-app](https://github.com/mecp-org/mecp-app) es publica sota la **GNU General Public License versió 3 (GPLv3)**. Si es distribueix una versió modificada d’aquest codi, s’han de mantenir les mateixes llibertats i condicions de la llicència.

La traducció al català inclosa en aquest projecte es publica sota **CC BY 4.0**, respectant els termes dels fitxers d’idioma originals de MECP.

La representació de la bandera catalana mitjançant SVG és una creació pròpia inclosa en aquesta interfície web.

---

<a id="english"></a>

## English

### What is MECP Web?

**MECP Web** is a web application based on the **MECP** (*Mesh Emergency Communication Protocol*). It allows users to create structured emergency messages for communication over LoRa mesh networks and helps people who speak different languages communicate effectively.

This project includes a web interface adapted from MECP and adds full support for **Catalan**.

### Main features

- Language selection.
- MECP code browsing by category and severity level.
- Structured emergency message composition.
- Additional information, such as GPS location, number of people and timestamp.
- Message preview, copy and export.
- Message history.
- Catalan translation support.

### Catalan translation

The Catalan translation includes:

- Emergency codes.
- Message categories.
- Severity levels.
- User-interface texts.
- System labels and messages.

The English file, `languages/en.json`, was used as the reference to preserve the context and terminology of each code.

### Catalan flag

The language selector displays the Catalan flag using an **SVG** with the nine traditional stripes of the Senyera:

```text
Yellow – Red – Yellow – Red – Yellow – Red – Yellow – Red – Yellow
```

An SVG was used instead of a flag emoji because there is no universal Unicode emoji for the Catalan flag. This ensures that the flag is displayed consistently across different browsers and operating systems, including Chromium-based browsers on Windows.

### How to use it

1. Open the website published on GitHub Pages.
2. Select the language using the selector at the top.
3. Choose the severity level of the message.
4. Select one or more MECP categories and codes.
5. Add additional information if needed.
6. Review the preview, then copy or send the message.


### Credits and licences

This project is based on [MECP — Mesh Emergency Communication Protocol](https://github.com/mecp-org/MECP).

| Component | Licence |
|---|---|
| MECP protocol specification | [CC0 1.0 — public domain](https://creativecommons.org/publicdomain/zero/1.0/) |
| Language files | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| App and engine code in [mecp-app](https://github.com/mecp-org/mecp-app) | [GPLv3](https://www.gnu.org/licenses/gpl-3.0.html) |

The MECP protocol is free forever: anyone may implement it without restriction. Its specification is dedicated to the public domain under CC0 1.0.

The language files are published under **CC BY 4.0**. They may be copied, adapted and redistributed, including for commercial purposes, provided that the original authorship is credited.

The application and engine code in [mecp-app](https://github.com/mecp-org/mecp-app) is published under the **GNU General Public License version 3 (GPLv3)**. If a modified version of that code is distributed, the same freedoms and licence conditions must be preserved.

The Catalan translation included in this project is published under **CC BY 4.0**, respecting the terms of the original MECP language files.

The SVG representation of the Catalan flag is an original creation included in this web interface.

---

<a id="español"></a>

## Español

### ¿Qué es MECP Web?

**MECP Web** es una aplicación web basada en el protocolo **MECP** (*Mesh Emergency Communication Protocol*). Permite crear mensajes de emergencia estructurados para comunicaciones mediante redes *mesh* LoRa y facilita la comunicación entre personas que hablan idiomas diferentes.

Este proyecto incluye una interfaz web adaptada a partir de MECP y añade soporte completo para el **catalán**.

### Funciones principales

- Selección de idioma de la interfaz.
- Consulta de los códigos MECP por categorías y niveles de gravedad.
- Composición de mensajes de emergencia estructurados.
- Adjunción de información adicional, como posición GPS, número de personas o marca de tiempo.
- Vista previa, copia y exportación de mensajes.
- Historial de mensajes.
- Soporte para la traducción al catalán.

### Traducción al catalán

La traducción al catalán incluye:

- Los códigos de emergencia.
- Las categorías de mensajes.
- Los niveles de gravedad.
- Los textos de la interfaz.
- Las etiquetas y mensajes del sistema.

Se ha utilizado el archivo inglés `languages/en.json` como referencia para mantener el contexto y la terminología de cada código.

### Bandera catalana

El selector de idiomas muestra la bandera catalana mediante un **SVG** con las nueve franjas tradicionales de la Senyera:

```text
Amarillo – Rojo – Amarillo – Rojo – Amarillo – Rojo – Amarillo – Rojo – Amarillo
```

Se ha utilizado un SVG en lugar de un emoji de bandera porque no existe un emoji Unicode universal para la bandera catalana. Esto permite que la bandera se muestre de forma consistente en distintos navegadores y sistemas operativos, incluidos los navegadores basados en Chromium en Windows.

### Cómo usarla

1. Abre la página web publicada en GitHub Pages.
2. Selecciona el idioma en el selector superior.
3. Elige el nivel de gravedad del mensaje.
4. Selecciona una o varias categorías y códigos MECP.
5. Añade información adicional si es necesario.
6. Revisa la vista previa y copia o envía el mensaje.



### Créditos y licencias

Este proyecto está basado en [MECP — Mesh Emergency Communication Protocol](https://github.com/mecp-org/MECP).

| Componente | Licencia |
|---|---|
| Especificación del protocolo MECP | [CC0 1.0 — dominio público](https://creativecommons.org/publicdomain/zero/1.0/) |
| Archivos de idioma | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Código de la aplicación y del motor en [mecp-app](https://github.com/mecp-org/mecp-app) | [GPLv3](https://www.gnu.org/licenses/gpl-3.0.html) |

El protocolo MECP es libre para siempre: cualquier persona puede implementarlo sin restricciones. La especificación está dedicada al dominio público mediante CC0 1.0.

Los archivos de idioma se publican bajo **CC BY 4.0**. Esto permite copiarlos, adaptarlos y redistribuirlos, incluso con fines comerciales, siempre que se reconozca la autoría original.

El código de la aplicación y del motor de [mecp-app](https://github.com/mecp-org/mecp-app) se publica bajo la **GNU General Public License versión 3 (GPLv3)**. Si se distribuye una versión modificada de ese código, deben mantenerse las mismas libertades y condiciones de la licencia.

La traducción al catalán incluida en este proyecto se publica bajo **CC BY 4.0**, respetando los términos de los archivos de idioma originales de MECP.

La representación de la bandera catalana mediante SVG es una creación propia incluida en esta interfaz web.
