# webscraping-steam
## _Analítica predictiva y prescriptiva - Predicción de videojuegos exitosos_

#### Descripción

Este proyecto analiza los factores determinantes del éxito en videojuegos, enfocándose en géneros, calificaciones, cantidad de reseñas y plataformas. Utilizando un enfoque de analítica predictiva y prescriptiva, se desarrolló un modelo basado en Random Forest que clasifica videojuegos como exitosos o no exitosos, considerando métricas como porcentaje de positividad y cantidad de reseñas.

El estudio incluye la creación de un dataset de 4236 videojuegos obtenidos mediante web scraping desde Steam, procesados en Google Colab. Los resultados no solo identifican géneros con mayores probabilidades de éxito, sino que también ofrecen recomendaciones estratégicas para desarrolladores, como priorizar géneros rentables, innovar en juegos de acción y evitar secuelas de títulos con bajo desempeño.

Se realizaron evaluaciones exhaustivas del modelo mediante métricas como precisión, recall, F1-score, curva ROC y validación cruzada, obteniendo un rendimiento sobresaliente con una precisión promedio del 98.94%. Además, se exploraron acciones prescriptivas para verificar los resultados con la  plataforma externa "Metacritic", maximizando el impacto en el competitivo mercado de videojuegos.


## Contenido

- Modelo predictivo videojuegos.ipynb: Codigo realizado para la manipulacion previa de los datos, la creacion y verifación del modelo y el poster analisis prescritivos de los resultados.
  
- Analisis predictivo y prescriptivo videojuegos.pdf: Informe realizado en latex donde se menciona todo el desarrollo del proyecto y el porqué se escogieron ciertos parametros.
  
- data.csv: Archivo que contiene los datos extraidos de la pagina de steam, especificamente la sección de novedades del 20 de Noviembre del 2024, (4327 juegos y 8 columna de datos)


## Teconologías aplicadas 
- Python
- Google Colab
- Random Forest
- Steam (Web Scraping)
- Metacritic
- Scikit-learn
- OneHotEncoder
- ColumnTransformer

```sh
!pip install -U scikit-learn
!pip install pandas
!pip install --upgrade matplotlib seaborn
!pip install plotly
```
>Este proyecto fue creado y aplicado %100 en colab, facilitando su implementación remota y sencilla.

## Uso

## _Modelo predictivo videojuegos.ipynb_:  

Este notebook cuenta con una breve manipulación de los datos y posterior creacion del modelo random forest, además de sus resultados y comprobación del modelo atravez de metricas y el analisis prescriptivo.

## _data.csv_:

Este archivo csv poviene del web scraping de la pagina web steam realizado en el proyecto "webscraping-steam" realizado con anterioridad, y para este caso se actualizó con 4237 datos de videojuegos y 7 columnas de variables.


## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

## Autores

Proyecto realizado por **Thiare Guerrero** [Thivre](https://github.com/thivre) y **Sebastián Celedón** [sceledon00](https://github.com/sceledon00)

**2024-s2 ANALÍTICA INFB6100**
