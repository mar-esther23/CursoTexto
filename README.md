# No es lo mismo que lo mesmo
[__Mariana Esther Martínez-Sánchez__](https://github.com/mar-esther23/)

Un problema común es comparar secuencias de texto que pueden tener pequeñas diferencias, ya sea por la forma de captura o por errores de ortografía. En este taller veremos tres estrategias de limpieza y análisis de datos: 
* __Comparación de strings__: usar [operaciones de strings](https://www.w3schools.com/python/python_ref_string.asp), [expresiones regulares](https://docs.python.org/2/library/re.html) básicas y [unidecode](https://pypi.org/project/Unidecode/) para manejar carácteres especiales
* __Estandarizar con catálogo__: usar [Fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy), una herramienta para determinar cuán similares son dos secuencias de texto usando la [distancia de Levenshtein](https://es.wikipedia.org/wiki/Distancia_de_Levenshtein), para estandarizar datos a un catálogo predefinido
* __Stemming__: un método para reducir una palabra a su raíz o [stem](https://nlp.stanford.edu/IR-book/html/htmledition/stemming-and-lemmatization-1.html) usando [NLTK](https://www.nltk.org/api/nltk.stem.html) y [Snowball](https://www.nltk.org/_modules/nltk/stem/snowball.html).

__Requisitos__: Computadora con [anaconda](https://www.anaconda.com/distribution/) instalado e instalar los paquetes de [requierements.txt](https://stackoverflow.com/questions/51042589/conda-version-pip-install-r-requirements-txt-target-lib/51043636).

__Impartido__: Marzo 2, 2020. Pyladies. [WIDS-Mexico](https://www.eventbrite.com/e/wids-mexico-city-tickets-94914460707)

## Como usar este tutorial

1. Descarga e instala anaconda usando las [instrucciones](https://www.anaconda.com/distribution/)
2. Descarga este tutorial con el boton de _Download_ o con `git clone https://github.com/mar-esther23/CursoTexto.git`
3. Abre anaconda y su terminal.
4. En la terminal crea un nuevo entorno (por ejemplo _CursoTexto_), instala los paquetes necesarios y activalo usando:
```
conda create -y --name CursoTexto
conda activate CursoTexto
conda install -c conda-forge --file requirements.txt
```
5. Usando anaconda abre el jupyter notebook _StringMatching.ipynb_ `jupyter notebook`
6. Al acabar puedes desactivar el environment con: `conda deactivate`

