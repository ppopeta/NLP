# Natural Language Procesing 

Para ejecutarlo, en la Terminal del proyecto: 
1. `python -m venv _env` 
2. `python .\_env\Scripts\activate`
3. `pip install -r requerimets.txt`

---

1. Enlace de los datos
    - IMDB: [Link al dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
    - AI vs Human Text dataset: [Link al dataset](https://www.kaggle.com/datasets/ranaghulamnabi/ai-vs-human-text?resource=download)

2. Enlace con el código y resultados de la actividad
    - [GitHub](https://github.com/ppopeta/NLP)

---

### Responder las siguientes preguntas

- ¿Considera que las estrategias de normalización, eliminacion de stop words, lematización permiten mejorar los resultados de entrenamiento de modelos de IA, por favor justifique su respuesta?
    Al hablar, utilizamos muchas palabras para hacernos entender que expresan sentimiento o intención, pero computacionalmente hablando muchas de esas palabras generan ruido más que contribuir en la clasificación que se busque hacer, por eso las estrategias de normalización y eliminacion de stop words nos ayudan a mejorar los resultados de entrenamiento, ya que el modelo se puede centrar unicamente en las palabras que realmente importan. 
- ¿Tomando en cuenta los resultados de sus entrenamiento describa cuál estrategia le dio mejores resultados, y trate de explicar el porqué?
    Me dio mejores resultados el modelo lematizado, y normalizado, intuyo que funciono mejor ya que estos metodos nos dan las frases es su forma más pura y más facil de comprender para una RNA. 
