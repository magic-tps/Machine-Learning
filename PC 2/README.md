# PC2_CRIPTO_GRAFO
1. Objetivo:
Representar a través de un modelo lógico el mercado de criptomonedas, que, como una situación del 
contexto de la vida real y sistema complejo, es susceptible a ser interpretado y representado utilizando 
como técnica de computación la Teoría de Grafos.
2. Situación de contexto real
El conocimiento del mercado de cripto monedas fue ampliamente investigado y desarrollado por el 
alumno durante la Practica Calificada 1 (PC1).
Este conocimiento deberá ser ahora representado como un modelo lógico utilizando la Teoría de Grafos, 
y que, como técnica de computación, le permitirá al alumno el análisis de las características (atributos) de 
los actores y sus relaciones, así como dar el primer paso a la adquisición de sus datos: identificar posibles 
fuentes, con el fin próximo de entrenar un algoritmo de Machine Learning.
Consideraciones del modelo lógico
a) Sólo se incorporarán criptomonedas o proyectos pertenecientes a la siguiente clasificación:
- Inteligencia Artificial
- Videojuegos
- RWA
- Memes
b) Se deberá identificar distintas fuentes de datos, a la par que proponer el cálculo mediante alguna 
métrica (propia o de uso universal), para ponderar el comportamiento de los proyectos 
contemplados dentro del modelo. Algunos de los factores importantes a ser considerados se 
listan a continuación:
- Valor del activo (en US$)
- Capitalización total de mercado (market cap)
- Posición en el ranking de criptomonedas
- Volumen (volumen 24h)
- Porcentaje del volumen diario (volumen 24h / market cap)
- Suministro circulante (circulating supply)
- Suministro total (total supply)
- Suministro máximo (max supply)
- Comunidad (página web, redes sociales, etc.)
- Porcentaje/ factor de difusión en redes
- Calificación

2
- Indicador (si vivió o no un halving previamente)
- Indicador de multi cadena (multichain)
- Indicador de listado o no en Exchanges Centralizados (CEX)
- Contrato del proyecto
- Billeteras soportadas
- Exploradores de Cadenas de bloques (Blockchain explorers) 
Las anteriores características provienen de las siguientes fuentes de datos:
https://coinmarketcap.com/
https://www.coingecko.com/
3. Logro del estudiante
Con el desarrollo de la Practica Calificada 2 (PC2), el estudiante logrará interpretar y representar el
conocimiento sobre los conceptos básicos, funcionamiento e importancia del mercado de las 
criptomonedas. 
Este tipo de representación del conocimiento, se considerará como pre requisito para abordar el Trabajo 
Parcial (TB1) y posteriormente el Trabajo Final (TB2) del curso, el cual se desarrollará siguiendo las etapas 
o fases del ciclo de vida de un proyecto de analítica o ciencia de datos. 
4. Entregable y presentación grupal
Se solicita un informe que no deberá exceder de 10 páginas y la estructura de su contenido se especifica 
a continuación:
Contenido del Informe:
I. Descripción de la situación/contexto real. Redactar la descripción y fundamentación del 
contexto/situación real citando fuentes.
Tener en cuenta que:
▪ Esta situación ya fue explicada y/o descrita en la PC1, considere incorporar este desarrollo 
en la presente PC2.
II. Origen de los datos. Señale y describa cuales fuentes de datos ha considerado para la adquisición 
de los mismos.
III. Elaboración del Modelo. Señale y describa como concibe el modelo lógico propuesto, quienes son 
los actores y cuales las relaciones encontradas (nodos y aristas respectivamente). ¿Como 

3
interpreta el cripto mercado? ¿Cómo calcula la ponderación de las relaciones que conectan a los 
actores? ¿Existen distintos actores a representar? (puede utilizar redes bipartitas, tripartitas, etc.)
IV. Descripción y visualización del conjunto de datos (dataset). Listar y describir las características y 
origen de los datos motivo de análisis y considerados en el modelo lógico.
Tener en cuenta:
▪ Al ser el mercado de criptomonedas un sistema complejo, considere solo representar su 
clasificación a nivel de los proyectos pertenecientes a la siguiente clasificación:
- Inteligencia Artificial
- Videojuego
- RWA
- Memes
▪ El número de nodos identificados y a representar mediante una red compleja (grafo), no 
deberá ser menor a 1000 nodos en total. Describa la técnica(s) utilizada(s) para la 
adquisición de los datos.
▪ Mostrar mediante un grafo completo y/o subgrafos los datos ejemplo recolectados.
V. Despliegue de la red. Visualizar la red creada en Python, acompañando el enlace hacia el código 
que lo sustenta y que deberá residir en un repositorio de GitHub.
5. Fecha presentación
La entrega es GRUPAL en el Aula Virtual para la actividad “PC2 – Semana 5”. 
Nombre de archivo en FORMATO PDF “PC2_XXX_YYY_ZZZ.pdf” (reemplace XXX, YYY, ZZZ por el código 
de cada estudiante integrante del grupo).
