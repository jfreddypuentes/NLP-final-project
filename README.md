# Proyecto Final NLP
Proyecto final de la clase de NLP.

## ¿De qué se trata?
El proyecto final de la clase de NLP se trata de un [chat](https://nlpchat.web.app/) que censura vulgaridades. La censura se realiza mediante la librería [spanlp](https://github.com/jfreddypuentes/spanlp) (tambien construida en clase). Internamente, los mensajes pasan por un proceso de análisis de sentimientos y de extracción de caracteristicas linguisticas que se pueden visualizar en [este dashboard](https://datastudio.google.com/reporting/b71e7558-2022-4057-99a7-5a02348db65b/page/dvqqB).

## Componentes
1. [Chat](https://nlpchat.web.app/) - Aplicación web construida en Angular y desplegada en Firebase Hosting.
2. [Dashboard](https://datastudio.google.com/reporting/b71e7558-2022-4057-99a7-5a02348db65b/page/dvqqB)
3. [Spanlp](https://github.com/jfreddypuentes/spanlp) - librería Python para detectar, censurar y limpiar groserías, vulgaridades, palabras de odio, racismo, xenofobia y bullying en textos escritos en Español.
4. **API Backend**. Conjunto de servicios REST que soportan el envio, la recepción, procesamiento y almacenamiento de los mensajes, sentimientos y caracteristicas linguisticas.

## Diagrama de Arquitectura
![Diagrama de Arquitectura](img_diagrama_arquitectura.png)

## Componentes de API
![Componentes de API](img_componentes_backend.png)

## Chat
### Home
![Chat-1](img_chat_1.png)

### Chat
![Chat-2](img_chat_2.png)

## Tecnología usada
* **Lenguajes de Programación**: [Python](https://www.python.org/) y [Javascript](https://devdocs.io/javascript/)
* **Base de datos**: [Algolia](https://www.algolia.com/), [Google BigQuery](https://cloud.google.com/bigquery)
* **Aplicación Web**: [Angular Framework](https://angular.io/)
* **Análisis de Sentimientos**: [Datatul](https://datatul.com/)
* **Visualización de Datos**: [Google Datastudio](https://datastudio.google.com/overview)
* **Librería In-House**: [Spanlp](https://github.com/jfreddypuentes/spanlp)


## Team
* [@normacalamartinez](https://github.com/normacalamartinez/) en Github (BI Developer) - Contribución al dataset de vulgaridades por país de habla hispana.
* [@jfreddypuentes](https://github.com/jfreddypuentes) - Esta cuenta. 

## Docente
* [@vivianamarquez](https://github.com/vivianamarquez) en Github, [@vivmarquez](https://twitter.com/vivmarquez) en Twitter (Data Scientist & Mathematician)
