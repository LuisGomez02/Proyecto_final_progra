# Proyecto Final 
## Presencia de especies de Costa Rica
### Elaborado por Luis Carlos Gómez y Marget Martínez

Para efectos de este trabajo, se utilizaron los registros de presencia de felinos en el país. Al igual que en el trabajo anterior, se procesaron mediante bibliotecas como folium y plotly para realizar la tabla, los gráficos y el mapa interactivo. Por último, se utilizó Streamlit para darle características más interactivas a la plataforma informativa generada.

Se generaron cuatro partes:
Primera corresponde a una tabla que muestra los resgistros de presencia de la especie seleccionada.
Segunda y Tercera corresponden a gráficos en plotly que muestran los registros de la especie en cada provincia y cantón del país respectivamente.
Cuarta corresponde a un mapa con varias capas de información, 2 mapas bases, 2 de cloropletas con la información de las secciones 2 y 3 y por último una capa de puntos agrupados correspondiente a los registros de la especie seleccionada que información relevante (nombre, especie, provincia y fecha).

De acuerdo a los resultados, en la tabla se muestra la columna de *locality* en su mayoría vacía, no se pudo tener control sobre ello debido a que así vienen los datos. Y en el mapa final, a pesar de utilizar los mismos datos de los gráficos para su realización, muestra resultados distintos.

[Enlace de visualización de Streamlit](https://luisgomez02-proyecto-final-progra-main-5ngwp8.streamlit.app/)

*Los datos fueron tomados de:*
- Para las divisiones territoriales fueron datos tomados del [SNIT](https://www.snitcr.go.cr/ico_servicios_ogc_info?k=bm9kbzo6MjY=&nombre=IGN%20Cartograf%C3%ADa%201:5mil)
- Para los registros de presencia de felinos [GBIF](https://www.gbif.org/occurrence/download/0141580-220831081235567).
