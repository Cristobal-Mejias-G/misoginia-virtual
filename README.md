# Misoginia Digital: Lenguaje y Género en Reddit

**Métodos Computacionales para las Ciencias Sociales**  
Profesor: Klaus Lehmann M. · Ayudante: Matías Gallardo V.  
Autores: Felipe Vega G. & Cristóbal Mejías G.

---

## Descripción

Este repositorio contiene los materiales de una investigación computacional
en dos etapas sobre lenguaje, género y misoginia en Reddit,
utilizando los subreddits **r/AskMen*** y **r/AskWomen*** como caso de estudio.

La **primera etapa** (octubre 2025) establece la fuente de datos,
describe el proceso de extracción mediante la API de Reddit (PRAW)
y realiza un análisis descriptivo comparativo del lenguaje según género.

La **segunda etapa** (noviembre 2025) profundiza el análisis aplicando
modelos de procesamiento de lenguaje natural (NLP) para detectar misoginia
y clasificar emociones en los comentarios, y contrasta cuatro hipótesis
mediante pruebas estadísticas.

---

## Documentos

### Etapa 1 — Lenguaje y género en Reddit

| Documento                                                                                    | Descripción                                                             |
| -------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| [Tutorial 1](https://cristobal-mejias-g.github.io/misoginia-virtual/tutorial-1.html)         | Extracción de datos con PRAW, procesamiento en R y análisis descriptivo |
| [Presentación 1](https://cristobal-mejias-g.github.io/misoginia-virtual/presentacion-1.html) | Diapositivas de la primera etapa                                        |

### Etapa 2 — Misoginia digital: lenguaje y emociones

| Documento                                                                                    | Descripción                                                         |
| -------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| [Tutorial 2](https://cristobal-mejias-g.github.io/misoginia-virtual/tutorial-2.html)         | Marco teórico, NLP con BERTweet y DistilBERT, análisis de hipótesis |
| [Presentación 2](https://cristobal-mejias-g.github.io/misoginia-virtual/presentacion-2.html) | Diapositivas de la segunda etapa                                    |

---

## Estructura del repositorio

```
Misoginia-Virtual/
├── data/ # Bases de datos procesadas
├── images/ # Imágenes
├── tutorial-1.qmd # Fuente Tutorial 1
├── tutorial-2.qmd # Fuente Tutorial 2
├── presentacion-1.qmd # Fuente Presentación 1
├── presentacion-2.qmd # Fuente Presentación 2
└── styles.css # Estilo
```


---

## Herramientas utilizadas

- **Python**: extracción de datos con PRAW, modelos NLP (Hugging Face Transformers)
- **R**: procesamiento de datos (dplyr, tidyr), visualización (ggplot2), tablas (gt)
- **Quarto**: generación de documentos HTML y presentaciones RevealJS
- **Modelos NLP**: `NLP-LTU/bertweet-large-sexism-detector` · `bhadresh-savani/distilbert-base-uncased-emotion`
