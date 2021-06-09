# Panorama

Escritura de espacios libres e inmersivos para el performance audiovisual.

Marianne Teixido, Dorian Sotomayor y Emilio Ocelotl 

[Texto Completo](https://github.com/piranhalab/panoramaArticulo/blob/main/panorama.pdf)

### Resumen

El confinamiento provocado por la pandemia de COVID-19 obligó a artistas, gestores, instituciones públicas e industrias a replantear maneras de compartir flujos co-presenciales y hacer performance audiovisual en vivo.

El presente artículo describe \textit{Panorama}, un conjunto de módulos de código y software que permiten realizar conciertos en espacios virtuales tridimensionales alojados en la web.

De manera complementaria, introduce discusiones que surgieron durante la activación del espacio sobre materialidad, virtualidad, descentralización, distribución, arqueologías del ciberespacio, entre otros.                       

## Estructura

- **Resumen**
- **Ecosistema.-** Antecedentes, proyectos y tecnologías similares.
- **Diseño y Escritura.-** Elementos del diseño de *Panorama*. Enunciación y descripción breve de las tecnologías implicadas.
- **Espacios y casos.-** *Notas de Ausencias*, *Pruebas proféticas* y *La Contemplación del Fin del Mundo*
- **Conclusiones.-** ¿Se cumplió la premisa/hipótesis descrita en Diseño y Escritura? ¿Qué otras cosas surgieron?
- **Notas.-** El artículo usa notas al final del texto. Aquí aparecen hipervínculos y conceptos de apoyo. 
- **Referencias.-** Referencias bibliográficas y repositorios en Git como referencias en la web. 

## Requisitos para compilar el documento

- Compilador y editor latex
- Instalar Endnotes

## Ejecución provisional

Para compilar el documento en pdf

`pdflatex -halt-on-error -output-directory out panorama.tex`

Para compilar el texto como html sin problemas de caracteres en español 

`make4ht -x panorama.tex`

Agregar el estilo manualmente y cambiar el nombre al archivo resultante.

`mv panorama.html index.html`

Para pasar de html a odt y compartirlo amigablemente

`pandoc panorama.html -o panorama.odt`

## Por hacer

- [ ] Hacer algo con la información que ya no cupo    
- [ ] Cuestionario de Pruebas Proféticas como un anexo en el repositorio  
- [ ] Recopilar recursos multimedia
- [ ] Memoria del Concierto > Distintos recursos

## Propuestas

- Mini taller de latex. 

## Referencias

- [latex-demo](https://github.com/rexmalebka/latex-demo) 
- [Modelo IMRyD](https://www.lluiscodina.com/modelo-imryd) 
- [Academic writing](https://www.unaminternacional.unam.mx/academic-writing)
- [How do you cite a Github repository](https://academia.stackexchange.com/questions/14010/how-do-you-cite-a-github-repository) 
