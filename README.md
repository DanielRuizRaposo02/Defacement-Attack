# Defacement-Attack
Fundamentación teórica
¿Qué es un defacement?

Un website defacement es un tipo de ataque para aplicaciones web que consiste en cambiar la apariencia y/o el contenido de un sitio web y sus diferentes subdirectorios o subdominios. Este tipo de ataque es habitualmente usado por hacktivistas o ciberdelincuentes para dejar algún tipo de mensaje en la página web que hayan hackeado. Por ejemplo, los atacantes podrían subir texto, imágenes o contenido multimedia para expresar alguna firma o idea.

Esta técnica es habitualmente utilizada como forma de protesta, en casos de hacktivismo, o simplemente por "molestar", en casos de ciberdelincuencia. Además, se ha usado en ciberataques a grandes organizaciones, con el fin de dejar evidencia de la intrusión al sistema.

## Objetivos del proyecto

Este proyecto tiene por objetivo principal evaluar el grado de asimilación de los conceptos sobre el análisis forense de sistemas linux. Este objetivo podemos desgranarlo en los siguientes:

    Extraer, decodificar y analizar las pruebas conservando la cadena de custodia.
    Documentar el proceso realizado de manera metódica
    Elaborar un informe de conclusiones a nivel técnico.

## Descripción del proyecto.

El propietario de una empresa es notificado por parte de clientes suyos que al acceder a la web de la empresa les aparece una web diferente a la original. Cuando lo comprueba, ve que ha sufrido un ataque defacement, es decir, una manipulación o cambio de una página web lícita sin la autorización correspondiente.

Rápidamente pone este hecho en vestro conocimiento ya que, como responsables de seguridad de la información de la empresa debéis averiguar qué ha ocurrido. Vuestro trabajo es realizar una investigación forense de las evidencias aportadas, así como presentar un resumen ejecutivo dirigido a la gerencia de la empresa explicando los hechos ocurridos para que ésta, neófita en materia informática, sea adecuadamente informada.

Para realizar lo anteriormente mencionado se os proporcionan dos evidencias:

    Captura de la memoria RAM realizada por el administrador del servidor.
    Adquisición del disco del servidor.

### Parte 1. Análisis de la memoria RAM

Sobre la captura de RAM recibida, previo análisis, deberéis elaborar una memoria de trabajo. Es importante que todas las evidencias recogidas en dicha memoria se encuentren adecuadamente descritas: nombre del archivo, localización, mac time del archivo, tamaño, valor hash, así como cualquier otro atributo característico que, como analista, consideres de interés.

Asimismo, es interesante que la memoria de trabajo refleje, en la medida de ol posible, la cronología de los acontecimientos, y ordene y relacione, en caso que sea posible todas las evidencias digitales que se han localizado.

Finalmente, también debes reflejar aquellas pruebas que has realizado, el resultado de las cuales haya sido negativo.

### Parte 2. Análisis de disco

Sobre la imagen de disco recibida, previo análisis, deberéis elaborar una memoria de trabajo. Es importante que todas las evidencias recogidas en dicha memoria se encuentren adecuadamente descritas: nombre del archivo, localización, mac time del archivo, tamaño, valor hash, así como cualquier otro atributo característico que, como analista, consideres de interés.

Asimismo, es interesante que la memoria de trabajo refleje, en la medida de ol posible, la cronología de los acontecimientos, y ordene y relacione, en caso que sea posible todas las evidencias digitales que se han localizado.

Finalmente, también debes reflejar aquellas pruebas que has realizado, el resultado de las cuales haya sido negativo.

### Parte 3. Informe ejecutivo

El informe ejecutivo consiste en un resumen del análisis efectuado pero empleando una explicación no técnica, con lenguaje común, en el que se expondrá los hechos más destacables de lo ocurrido en el sistema analizado. Constará de pocas páginas, entre tres y cinco, y será de especial interés para exponer lo sucedido a personal no especializado en sistemas informáticos, como pueda ser el departamento de Recursos Humanos, Administración, e incluso algunos directivos.

En este informe deberá, donde se describirá, al menos, lo siguiente:

    Antecedentes del incidente.
    Resultados del análisis.
    Desarrollo de la intrusión.
    Representación gráfica del incidente. Incluirá una topología de la red, así como todos los dispositivos, aplicaciones y/o sujetos implicados, y sus correspondientes identificaciones (dirección ip, versión, etc...)
    Cronología (timeline). Se realizará en formato tabla incluyendo como mínimo las columnas: evento, cuando ocurrió, artefacto del que se ha extraido la información, número de evidencia.
    Recomendaciones.

Para la valoración del resumen ejecutivo se tendrán en cuenta aspectos de su redactado, como por ejemplo, ortografía, puntuación, redacción, presentación, etc, así como que no exceda del límite de páginas establecido.

Anotación. Estos puntos no quiere decir que sean los únicos a incluir, se deberá incluir todos aquellos apartados que sean necesarios en éste tipo de análisis.
Presentación de las evidencias

Para la presentación o descripción de las evidencias localizadas deberá indicarse, para cada una de ellas, los siguientes elementos:

    Ruta de localización completa de la evidencia localizada en el dispositivo o soporte original.
    Contenido del fichero: es decir, en caso que el contenido del fichero se pueda mostrar (una fotografía, una hoja de cálculo, etc.), debe incluirse en este apartado.
    MAC time.
    Tamaño lógico del fichero.
    Valor hash del fichero.

El índice de todas las evidencias localizadas, con la descripción que acabamos de ver, debe ser incorporado como anexo del informe pericial. No es necesario extraer las evidencias, es decir, obtener los ficheros, pero sí mostrar sus contenidos.
Normativas y estándares

No olvidéis revisar las normas UNE/ISO/RFC comentadas en clase, elegir la que gustéis, tenerla bien a mano y revisarla de vez en cuando para aseguraros que estamos siguiendo el proceso adecuado y manteniendo adecuadamente la cadena de custodia.

No sabemos cuando un caso puede acabar en los tribunales, siguiendo unos principios básicos nos aseguramos que si eso ocurre no tendremos que rehacer todo nuestro trabajo para adecuarlo a un proceso judicial.
