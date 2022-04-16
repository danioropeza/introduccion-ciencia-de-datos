# Introducción a la Ciencia de Datos
## Sobre el código
Este es un breve curso introductorio en Python a la Ciencia de Datos.

Sitio web con el contenido: [danioropeza.github.io/introduccion-ciencia-de-datos](https://danioropeza.github.io/introduccion-ciencia-de-datos/intro.html)

Para agregar cambios, se debe: 

1. Instalar los siguientes paquetes:

```
pip install -U jupyter-book
pip install ghp-import
```

2. Limpiar los archivos compilados existentes, si es que hubiesen:

```
jupyter-book clean Web\ Application/ --all
```

3. Compilar de nuevo el código ejecutando el siguiente comando en el root del repositorio:

```
jupyter-book build Web\ Application/
```

4. Deployar los cambios ejecutando el siguiente comando:

```
ghp-import -n -p -f Web\ Application/_build/html
```

## Sobre la página web

### Introducción
El futuro pertenece a la ciencia de datos y a quienes la entiendan. Al igual que el petróleo y el gas impulsaron las economías de los siglos XX y XXI, los datos impulsan cada vez más la innovación y la economía global a medida que avanzamos hacia una nueva era denominada la revolución digital.

Las empresas que están cambiando a una mentalidad de datos van a obtener primero una enorme ventaja competitiva.

En esta página web aprenderás desde un inicio cómo funciona la ciencia de datos. Exploraremos de a poco los conceptos del contenido usando Python a través de la lectura, ejemplos y ejercicios que podrás facilmente ver, copiar y probar en tu propio entorno. Todo esto gracias a la herramienta de Jupyter Book que nos permite enlazar varios Jupyter Notebooks en uno solo usando HTML.

### Contenido
1. Pandas
2. Web Scraping
3. Procesamiento del lenguage Natural
4. Análisis exploratorio de datos
5. Feature Engineering
6. Feature Selection
7. Modelos predictivos
8. Arboles de decisión

### Acerca de los autores
El contenido de los notebooks fue creado y estructurado por nuestro docente Marcelo Rocabado quién nos compartió los archivos en su clase de "Sistemas de información III" durante el semestre I-2020. Daniel Oropeza y Sebastian Jordan, agregaron algunas mejoras como ser: refatorizaciones de código, mejora de la redacción de los textos, ejercicios resueltos durante la matería y unimos todo los archivos de su clase con Jupyter Book para publicarlo en internet.

### Contacto de información
Daniel Oropeza: https://www.linkedin.com/in/dani-oropeza/
Sebastian Jordan: https://www.linkedin.com/in/jordanmontt/

