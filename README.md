# Práctica 1: *web scraping*

## Contexto

Primera práctica de la asignatura *Tipología y Ciclo de Vida de los Datos del Máster de Ciencia de Datos* de la Universitat Oberta de Catalunya (UOC), en la que se propone al alumno elaborar un caso práctico orientado a aprender a identificar los datos relevantes por un proyecto analítico y usar las herramientas de extracción de datos. 

La actividad que se incluye en este repositorio consiste en la creación de un *dataset* mediante *web scraping* que contiene las fichas técnicas, clasificación y valoración de las películas más populares entre la crítica y usuarios del popular sitio web de revisión y reseñas cinematográficas [Rotten Tomatoes](https://www.rottentomatoes.com/).

## Agradecimientos

Rotten Tomatoes es probablemente el agregador de reseñas de películas y programas de televisión más popular de Internet, cuyo sistema de puntuación o "[*tomatometer*](https://www.rottentomatoes.com/about)" está respaldado por las opiniones de cientos de críticos de cine y televisión. Además, Rotten Tomatoes cuenta con una extensa comunidad de usuarios que realizan sus propias reseñas y valoraciones lo que convierte en más valiosa si cabe la información de este sitio web.

Los *datasets* generados a partir de las reseñas de Rotten Tomatoes son muy populares entre la comunidad de usuarios de [Kaggle](https://www.kaggle.com), una plataforma que permite encontrar y publicar conjuntos de datos, explorar y construir modelos o participar en competiciones y desafíos en un entorno de ciencia de datos basado en la web. Uno de los *dataset* más completos es [*Rotten Tomatoes movies and critic reviews dataset*](https://www.kaggle.com/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset) creado por [Stefano Leone](https://www.kaggle.com/stefanoleone992) a partir de las reseñas de más de 17.000 películas. 

## Inspiración

Este conjunto de datos ha sido desarrollado para comprender las técnicas de *web scraping* y familiarizarse con el uso de herramientas como [*Beautiful Soup*](https://www.crummy.com/software/BeautifulSoup/) o [*Selenium WebDriver*](https://www.selenium.dev/documentation/en/webdriver/) para este fin, de manera similar a la descrita por autores como Isabella Benabaye en su artículo "[*Step-by-step Scraping Epsiode IMDb Ratings*](https://isabella-b.com/blog/scraping-episode-imdb-ratings-tutorial/)"

Entre las utilidades prácticas que puede tener este conjunto de datos está la de servir como fuente para analizar distintos algoritmos de clasificación, e incluso para desarrollar un sistema de recomendación de películas sencillo, gracias a la información que contiene sobre las películas mejor valoradas por la crítica y usuarios en diferentes categorías. Dadas sus limitaciones de tamaño y atributos recopilados, no es adecuado, sin embargo, para tareas de inteligencia artificial más complejas, como el análisis de sentimientos de datos a partir de críticas de películas. Para estas y otras actividades más sofisticadas a partir de los datos de Rotten Tomatoes es recomendable un dataset más completo como el de Stefano Leone.

## Miembros del equipo

La actividad ha sido realizada de manera individual.

## Fuentes consultadas

1. Materiales de la asignatura Tipología y Ciclo de Vida de los Datos del Máster de Ciencia de Datos de la UOC
2. C. Abad, A. Kam y L. Calva (2009) "Sistema de Recomendación de Películas" http://www.dspace.espol.edu.ec/handle/123456789/10882
3. Benabaye, I. (2020) "Step-by-step: Scraping Epsiode IMDb Ratings" https://isabella-b.com/blog/scraping-episode-imdb-ratings-tutorial/
4. Leone, Stefano (2021) "Rotten Tomatoes movies and critic reviews dataset" https://www.kaggle.com/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset
5. Python.org https://www.python.org/doc/
6. Python Package Index https://pypi.org/
7. Beautiful Soup documentation https://www.crummy.com/software/BeautifulSoup/bs4/doc/
8. Baiju Muthukandan - Selenium with Python https://selenium-python.readthedocs.io/
9. Pandas documentation https://pandas.pydata.org/docs
