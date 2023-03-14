# 📊 Cuadro de mandos Streamlit 

## Despliegue de la aplicación - [Enlace web]()

## Temática

Los datos tratan sobre diferentes juegos compatibles con el programa geforce now, un programa con la función de optimizar las opciones 
gráficas de los diferentes juegos

## Procedencia de los datos

He extraido los datos desde un archivo excel convertido en csv
procedente de un foro de nvidia (https://www.reddit.com/r/GeForceNOW/comments/ez698b/full_list_of_available_games_in_json/).
Este json contiene todo tipo de informacion de cada juego.

## Campos que contiene cada elemento

- ID del juego - `string`

- Título del juego - `string`

- Highlights Supported?(Se trata de la compatibilidad para capturar videos del juego) - `string con utilidad de booleano (Y/N)`

- Fully Optimized?(Se trata de la compatibilidad para optimizar el juego) - `string con utilidad de booleano (Y/N)`

- URL de compra(no utilizado) - `string`

- Empresa que ha publicado el juego - `string`

- Género del juego - `array`

- Estado del juego - `int con utilidad de booleano (1/0)`

## Librerías utilizadas



