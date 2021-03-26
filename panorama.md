::: {.maketitle}
## Panorama Escritura de espacios libres e inmersivos para el performance audiovisual {#panorama-escritura-de-espacios-libres-e-inmersivos-para-el-performance-audiovisual .titleHead}

::: {.author}
[Marianne Teixido, Dorian Sotomayor, Emilio Ocelotl]{.rm-lmr-12x-x-120}
:::

\

::: {.date}
[26 de marzo de 2021]{.rm-lmr-12x-x-120}
:::
:::

::: {.abstract}
### []{#x1-1000}Resumen {#resumen .likesectionHead}

El confinamiento provocado por la pandemia de COVID-19 obligó a
artistas, gestores, instituciones públicas e industrias a replantear
maneras de compartir flujos co-presenciales y hacer performance
audiovisual en vivo.

El presente artículo describe [Panorama]{.rm-lmri-12}, un conjunto de
módulos de código y software que permiten realizar conciertos en
espacios virtuales tridimensionales alojados en la web. De manera
complementaria, enuncia discusiones que surgieron durante la activación
del espacio sobre materialidad, virtualidad, descentralización,
distribución, espacio público, arqueologías del cyberespacio, entre
otros.
:::

[Palabras clave--- ]{.rm-lmbxi-10x-x-109}[streaming, multiplayer, 3d,
]{.rm-lmr-10x-x-109}[audio, video, materialidad, virtualidad, cyborg,
]{.rm-lmr-10x-x-109}[cyberespacio, p2p]{.rm-lmr-10x-x-109}

### []{#x1-2000}[Ecosistema]{.rm-lmr-10x-x-109} {#ecosistema .likesectionHead}

[Panorama
]{.rm-lmri-10x-x-109}[(]{.rm-lmr-10x-x-109}[[rexmalebka]{.rm-lmr-10x-x-109}](#Xpanorama)[, ]{.rm-lmr-10x-x-109}[[2020]{.rm-lmr-10x-x-109}](#Xpanorama)[)
fue un programa ]{.rm-lmr-10x-x-109}[escrito por
]{.rm-lmr-10x-x-109}[PiranhaLab]{.rm-lmri-10x-x-109}^[[1]{.cmr-8}](#ennote-1){#enmark-1}^[,
implementado en el ]{.rm-lmr-10x-x-109}[marco de eventos
institucionales, independientes y ]{.rm-lmr-10x-x-109}[comisiones
específicas. La hipótesis/premisa ]{.rm-lmr-10x-x-109}[central de este
proyecto buscó que los usuarios ]{.rm-lmr-10x-x-109}[pudieran compartir
una experiencia ligera para el ]{.rm-lmr-10x-x-109}[navegador de manera
co-presencial, aprovechando ]{.rm-lmr-10x-x-109}[las posibilidades de
las tecnologías de transmisión ]{.rm-lmr-10x-x-109}[de audio y video.
Hemos decidido delimitar el ]{.rm-lmr-10x-x-109}[desarrollo de Panorama
en torno a estos eventos y ]{.rm-lmr-10x-x-109}[en particular, a
]{.rm-lmr-10x-x-109}[EDGES]{.rm-lmri-10x-x-109}^[[2]{.cmr-8}](#ennote-2){#enmark-2}^[.
Los eventos realizados en ]{.rm-lmr-10x-x-109}[el marco de este ciclo se
llevaron a cabo del 6 de ]{.rm-lmr-10x-x-109}[agosto al 19 de noviembre
de 2020. Algunos eventos ]{.rm-lmr-10x-x-109}[independientes sucedieron
ligeramente antes o ]{.rm-lmr-10x-x-109}[después de estas
fechas.]{.rm-lmr-10x-x-109}

[Este proyecto de investigación considera una
]{.rm-lmr-10x-x-109}[selección de eventos como casos de estudio para la
]{.rm-lmr-10x-x-109}[comprobación de la hipótesis/premisa principal del
]{.rm-lmr-10x-x-109}[software desarrollado: ]{.rm-lmr-10x-x-109}[Notas
de Ausencia]{.rm-lmri-10x-x-109}^[[3]{.cmr-8}](#ennote-3){#enmark-3}^
[de ]{.rm-lmr-10x-x-109}[Marianne Teixido, ]{.rm-lmr-10x-x-109}[La
Contemplación del Fin del
]{.rm-lmri-10x-x-109}[Mundo]{.rm-lmri-10x-x-109}^[[4]{.cmr-8}](#ennote-4){#enmark-4}^
[de Dorian Sotomayor y
]{.rm-lmr-10x-x-109}[threecln]{.rm-lmri-10x-x-109}^[[5]{.cmr-8}](#ennote-5){#enmark-5}^
[de Emilio ]{.rm-lmr-10x-x-109}[Ocelotl. Complementamos la descripción
con algunos ]{.rm-lmr-10x-x-109}[espacios y eventos adicionalmente
seleccionados: ]{.rm-lmr-10x-x-109}[Pruebas
Proféticas]{.rm-lmri-10x-x-109}[,
]{.rm-lmr-10x-x-109}[Distopia]{.rm-lmri-10x-x-109}[,
]{.rm-lmr-10x-x-109}[Underborders ]{.rm-lmri-10x-x-109}[y
]{.rm-lmr-10x-x-109}[4NT1]{.rm-lmri-10x-x-109}[.]{.rm-lmr-10x-x-109}

[El artículo aporta elementos a una discusión ]{.rm-lmr-10x-x-109}[para
la reflexión transversal (técnica, estética y de
]{.rm-lmr-10x-x-109}[investigación académica) y utiliza conceptos que
]{.rm-lmr-10x-x-109}[nos permiten desplazarnos entre estos hilos para
]{.rm-lmr-10x-x-109}[entretejer la investigación transdisciplinaria. Se
]{.rm-lmr-10x-x-109}[adscribe a los planteamientos de los estudios
]{.rm-lmr-10x-x-109}[del software y busca extender la discusión del
]{.rm-lmr-10x-x-109}[terreno técnico y descriptivo. A lo largo del
]{.rm-lmr-10x-x-109}[texto buscamos problematizar el papel que juega
]{.rm-lmr-10x-x-109}[la computadora (local o en servidores) en la
]{.rm-lmr-10x-x-109}[realización de actividades musicales y
peformáticas.]{.rm-lmr-10x-x-109}

[La primera parte de este apartado describe una
]{.rm-lmr-10x-x-109}[serie de plataformas, paralelas
a]{.rm-lmr-10x-x-109}[Panorama]{.rm-lmri-10x-x-109}[, que
]{.rm-lmr-10x-x-109}[permitieron realizar conciertos audiovisuales
]{.rm-lmr-10x-x-109}[en el navegador con entornos tridimensionales.
]{.rm-lmr-10x-x-109}[Los puntos de coincidencia entre espacios que
]{.rm-lmr-10x-x-109}[la investigación detectó fueron: audio y video
]{.rm-lmr-10x-x-109}[transmitido en tiempo real y la posibilidad de
]{.rm-lmr-10x-x-109}[posicionar pantallas, audio, avatares y escenarios
en ]{.rm-lmr-10x-x-109}[el espacio. La alusión a las plataformas que
]{.rm-lmr-10x-x-109}[compartieron ecosistema con
]{.rm-lmr-10x-x-109}[Panorama ]{.rm-lmri-10x-x-109}[se delimita
]{.rm-lmr-10x-x-109}[proyectos con cercanía performática, la mayoría de
]{.rm-lmr-10x-x-109}[ellos escritos e implementados en la Ciudad de
]{.rm-lmr-10x-x-109}[México.]{.rm-lmr-10x-x-109}

[En el contexto de la programación al vuelo ]{.rm-lmr-10x-x-109}[o
]{.rm-lmr-10x-x-109}[live coding]{.rm-lmri-10x-x-109}[, los Algoraves
organizados por
]{.rm-lmr-10x-x-109}[Algo:ritmi]{.rm-lmr-10x-x-109}^[[6]{.cmr-8}](#ennote-6){#enmark-6}^
[iniciaron el interés por los espacios
]{.rm-lmr-10x-x-109}[tridimensionales de realidad virtual para lidiar
conel distanciamiento social de la pandemia. Estos
]{.rm-lmr-10x-x-109}[eventos tuvieron lugar en Mozilla
Hubs]{.rm-lmr-10x-x-109}^[[7]{.cmr-8}](#ennote-7){#enmark-7}^[. Esta
]{.rm-lmr-10x-x-109}[plataforma resuelve el backend de la experiencia y
]{.rm-lmr-10x-x-109}[permite al diseñador de espacio centrarse en el
]{.rm-lmr-10x-x-109}[frontend, el montaje del escenario al que acceden
]{.rm-lmr-10x-x-109}[los usuarios.]{.rm-lmr-10x-x-109}

[Para el caso de la comunidad creativa en ]{.rm-lmr-10x-x-109}[México,
algunos otros casos de implementación de ]{.rm-lmr-10x-x-109}[espacios
virtuales en situaciones de concierto ]{.rm-lmr-10x-x-109}[fueron
propuestas por TOPLAP México. De ]{.rm-lmr-10x-x-109}[manera similar a
Algo:ritmi, Algoraves eventos ]{.rm-lmr-10x-x-109}[relacionados con la
escena de la programación ]{.rm-lmr-10x-x-109}[al
vuelo]{.rm-lmr-10x-x-109}^[[8]{.cmr-8}](#ennote-8){#enmark-8}^ [fueron
organizados en FabricaVR, ]{.rm-lmr-10x-x-109}[la plataforma de realidad
virtual dedicada de ]{.rm-lmr-10x-x-109}[TOPLAP México. Ambos casos
forman parte de ]{.rm-lmr-10x-x-109}[comunidades que antes de la
pandemia, realizaban ]{.rm-lmr-10x-x-109}[conciertos con tecnologías de
transmisión de audio ]{.rm-lmr-10x-x-109}[y
video]{.rm-lmr-10x-x-109}^[[9]{.cmr-8}](#ennote-9){#enmark-9}^[.]{.rm-lmr-10x-x-109}

[Adicionalmente, otras plataformas plantearon
]{.rm-lmr-10x-x-109}[eventos similares con módulos de software
distintos. ]{.rm-lmr-10x-x-109}[Tal fue el caso de la plataforma OXXXO
de Carlos ]{.rm-lmr-10x-x-109}[Pesina que en co-participación con el
festival ]{.rm-lmr-10x-x-109}[Ceremonia permitió la realización de
eventos ]{.rm-lmr-10x-x-109}[digitales para afrontar la cancelación de
conciertos
]{.rm-lmr-10x-x-109}[presenciales.]{.rm-lmr-10x-x-109}^[[10]{.cmr-8}](#ennote-10){#enmark-10}^

[A-frame]{.rm-lmri-10x-x-109}^[[11]{.cmr-8}](#ennote-11){#enmark-11}^
[fue una solución alternativa a Mozilla ]{.rm-lmr-10x-x-109}[Hubs para
la realización de eventos virtuales.
]{.rm-lmr-10x-x-109}[Sinestesia]{.rm-lmri-10x-x-109}^[[12]{.cmr-8}](#ennote-12){#enmark-12}^
[y ]{.rm-lmr-10x-x-109}[ZeYX
Lab]{.rm-lmri-10x-x-109}^[[13]{.cmr-8}](#ennote-13){#enmark-13}^
[implementaron este ]{.rm-lmr-10x-x-109}[entorno.
Three.js]{.rm-lmr-10x-x-109}^[[14]{.cmr-8}](#ennote-14){#enmark-14}^
[fue otro ]{.rm-lmr-10x-x-109}[framework ]{.rm-lmri-10x-x-109}[elegido
]{.rm-lmr-10x-x-109}[para realizar este tipo de experiencias para el
]{.rm-lmr-10x-x-109}[navegador. En este sentido destacamos el caso
]{.rm-lmr-10x-x-109}[de
]{.rm-lmr-10x-x-109}[Calindros]{.rm-lmri-10x-x-109}^[[15]{.cmr-8}](#ennote-15){#enmark-15}^
[de Hugo Solís. Este marco de ]{.rm-lmr-10x-x-109}[trabajo resuelve el
render gráfico, el resto de ]{.rm-lmr-10x-x-109}[los complementos
(comunicación entre pares, ]{.rm-lmr-10x-x-109}[transmisión y
procesamiento de señales de audio y ]{.rm-lmr-10x-x-109}[video) debe ser
resuelto de manera independiente.]{.rm-lmr-10x-x-109}

[Finalmente, ]{.rm-lmr-10x-x-109}[federacion-de-codigo-al-vuelo
]{.rm-lmri-10x-x-109}[(]{.rm-lmr-10x-x-109}[[federaciondecodigoalvuelo]{.rm-lmr-10x-x-109}](#Xen-vivo)[, ]{.rm-lmr-10x-x-109}[[2020]{.rm-lmr-10x-x-109}](#Xen-vivo)[)
fue el parteaguas ]{.rm-lmr-10x-x-109}[de algunas ideas centrales que
desembocaron en ]{.rm-lmr-10x-x-109}[Panorama ]{.rm-lmri-10x-x-109}[pero
también en otros dos proyectos: Zona ]{.rm-lmr-10x-x-109}[hipermedial y
Camposónico]{.rm-lmr-10x-x-109}^[[16]{.cmr-8}](#ennote-16){#enmark-16}^
[(]{.rm-lmr-10x-x-109}[[diegodvc]{.rm-lmr-10x-x-109}](#Xcamposonico)[, ]{.rm-lmr-10x-x-109}[[2020]{.rm-lmr-10x-x-109}](#Xcamposonico)[).
La ]{.rm-lmr-10x-x-109}[experiencia de colaboración con la
]{.rm-lmr-10x-x-109}[federación ]{.rm-lmri-10x-x-109}[permitió concebir
el entramado de módulos de ]{.rm-lmr-10x-x-109}[código que pudieran
resolver aspectos específicos. ]{.rm-lmr-10x-x-109}[Tal es el caso de un
chat o alguna forma de ]{.rm-lmr-10x-x-109}[escritura en tiempo real o
la transmisión de gestos ]{.rm-lmr-10x-x-109}[de un avatar que
extiendieran las posibilidades de ]{.rm-lmr-10x-x-109}[desplazamiento y
movimiento corporal en el ]{.rm-lmr-10x-x-109}[espacio. La búsqueda por
un espacio personalizado ]{.rm-lmr-10x-x-109}[de los proyectos que se
desprendieron de la ]{.rm-lmr-10x-x-109}[federación
]{.rm-lmri-10x-x-109}[se estableció con el objetivo de resolver
]{.rm-lmr-10x-x-109}[problemáticas de rendimiento que las plataformas
]{.rm-lmr-10x-x-109}[de alto nivel resolvían de una manera poco
]{.rm-lmr-10x-x-109}[transparente.]{.rm-lmr-10x-x-109}

[Los eventos anteriormente enunciados resolvieron
]{.rm-lmr-10x-x-109}[la transmisión de audio y video con plataformas
]{.rm-lmr-10x-x-109}[privativas de streaming como YouTube y Twitch;
]{.rm-lmr-10x-x-109}[plataformas para envío bidireccional de señales
]{.rm-lmr-10x-x-109}[de audio como Sagora, jacktrip y Sonobus y
]{.rm-lmr-10x-x-109}[plataformas para el montaje de servidores de
]{.rm-lmr-10x-x-109}[audio y video como Icecast o LiquidSoap. Esta
]{.rm-lmr-10x-x-109}[última experiencia apuntó a la escritura de un
]{.rm-lmr-10x-x-109}[servidor personalizado de streaming de audio y
]{.rm-lmr-10x-x-109}[video.]{.rm-lmr-10x-x-109}

[De la experiencia como asistentes, como ejecutantes
]{.rm-lmr-10x-x-109}[y como incipientes investigadores/escritores de
]{.rm-lmr-10x-x-109}[código en plataformas y eventos que implicaron
]{.rm-lmr-10x-x-109}[estas resoluciones fue que el proyecto de
]{.rm-lmr-10x-x-109}[PiranhaLab ]{.rm-lmri-10x-x-109}[empezó a
delimitarse. Adicionalmente, sugieron ]{.rm-lmr-10x-x-109}[discusiones
sobre estos entornos, de las piezas y ]{.rm-lmr-10x-x-109}[eventos que
contuvieron e incluso del momento en ]{.rm-lmr-10x-x-109}[el que espacio
y e interpretación se desdibujan.]{.rm-lmr-10x-x-109}

### []{#x1-3000}[Diseño y escritura]{.rm-lmr-10x-x-109} {#diseño-y-escritura .likesectionHead}

[El diseño de ]{.rm-lmr-10x-x-109}[Panorama
]{.rm-lmri-10x-x-109}[consideró:]{.rm-lmr-10x-x-109}

-   [Escritura de una experiencia ligera: tiempo ]{.rm-lmr-10x-x-109}[de
    carga, percepción de movimiento del ]{.rm-lmr-10x-x-109}[punto de
    vista de la cámara y percepción de ]{.rm-lmr-10x-x-109}[otros
    usuarios en un espacio tridimensional.]{.rm-lmr-10x-x-109}
-   [Utilización sencilla, adaptable a distintos
    ]{.rm-lmr-10x-x-109}[dispositivos y a la capacidad técnica de los
    ]{.rm-lmr-10x-x-109}[usuarios.]{.rm-lmr-10x-x-109}
-   [Transmisión ]{.rm-lmr-10x-x-109}[audiovisual en vivo que permitiera
    simular ]{.rm-lmr-10x-x-109}[la experiencia de asistencia a
    conciertos ]{.rm-lmr-10x-x-109}[para eventos recurrentes y no
    recurrentes.]{.rm-lmr-10x-x-109}
-   [Autonomía en el uso de recursos: el sistema ]{.rm-lmr-10x-x-109}[no
    implicó un registro y buscó evadir el ]{.rm-lmr-10x-x-109}[análisis
    del ]{.rm-lmr-10x-x-109}[streaming ]{.rm-lmri-10x-x-109}[o de la
    conexión ]{.rm-lmr-10x-x-109}[entre módulos para evitar
    transmisiones ]{.rm-lmr-10x-x-109}[silenciadas por el uso de
    materiales con ]{.rm-lmr-10x-x-109}[derechos de
    autor.]{.rm-lmr-10x-x-109}
-   [Sistemas fáciles de instalar, recrear y
    ]{.rm-lmr-10x-x-109}[escalar.]{.rm-lmr-10x-x-109}
-   [Tecnologías normalizadas, no privativas, ]{.rm-lmr-10x-x-109}[con
    una marcada preferencia por el software
    ]{.rm-lmr-10x-x-109}[libre.]{.rm-lmr-10x-x-109}
-   [Generación de experiencias personalizadas ]{.rm-lmr-10x-x-109}[que
    respondiera a ]{.rm-lmr-10x-x-109}[las necesidades performativas,
    posibilidades ]{.rm-lmr-10x-x-109}[futuras abiertas y
    adaptables.]{.rm-lmr-10x-x-109}

[Panorama ]{.rm-lmri-10x-x-109}[se escribió para entornos web, no
]{.rm-lmr-10x-x-109}[requiere instalación de software adicional, más
allá ]{.rm-lmr-10x-x-109}[de un navegador web actual. Los avances en la
]{.rm-lmr-10x-x-109}[tecnología web permiten la homogeneización de la
]{.rm-lmr-10x-x-109}[experiencia y pueden abarcar un gran público. El
]{.rm-lmr-10x-x-109}[sistema utiliza
WebGL]{.rm-lmr-10x-x-109}^[[17]{.cmr-8}](#ennote-17){#enmark-17}^ [para
la renderización de ]{.rm-lmr-10x-x-109}[imagen en el navegador. Este
entorno permite la ]{.rm-lmr-10x-x-109}[generación de espacios virtuales
y tridimensionales ]{.rm-lmr-10x-x-109}[donde se pueden alojar
experiencias visuales, ]{.rm-lmr-10x-x-109}[auditivas y presenciales.
Javascript es el lenguaje de ]{.rm-lmr-10x-x-109}[programación principal
del proyecto debido a su ]{.rm-lmr-10x-x-109}[uso normalizado en
navegadores y aplicaciones web. ]{.rm-lmr-10x-x-109}[Para fines
prácticos, este sistema permite conectar ]{.rm-lmr-10x-x-109}[las partes
del sistema entero.]{.rm-lmr-10x-x-109}

[Three.js como ]{.rm-lmr-10x-x-109}[framework
]{.rm-lmri-10x-x-109}[implementa webGL y ]{.rm-lmr-10x-x-109}[asegura la
rápida codificación y reutilización de ]{.rm-lmr-10x-x-109}[código.
Además, es posible importar modelos ]{.rm-lmr-10x-x-109}[hechos en
programas de modelado tridimensional, ]{.rm-lmr-10x-x-109}[efectos y
módulos para la reproducción de audio ]{.rm-lmr-10x-x-109}[en web con
Web Audio
API]{.rm-lmr-10x-x-109}^[[18]{.cmr-8}](#ennote-18){#enmark-18}^ [y
conceptos ]{.rm-lmr-10x-x-109}[convencionales y compartidos de
materiales y ]{.rm-lmr-10x-x-109}[geometrías relacionados a programas de
modelado ]{.rm-lmr-10x-x-109}[en tes dimensiones. Como un punto
adicional, este ]{.rm-lmr-10x-x-109}[marco de trabajo cuenta con
documentación ]{.rm-lmr-10x-x-109}[actualizada y constante. La
implementación ]{.rm-lmr-10x-x-109}[de
WebAssembly]{.rm-lmr-10x-x-109}^[[19]{.cmr-8}](#ennote-19){#enmark-19}^
[ha permitido la generación ]{.rm-lmr-10x-x-109}[de sistemas rápidos y
eficientes, sin capas de ]{.rm-lmr-10x-x-109}[abstracción de software
innecesarias.]{.rm-lmr-10x-x-109}

[El diseño del módulo de ]{.rm-lmr-10x-x-109}[streaming
]{.rm-lmri-10x-x-109}[presentó ]{.rm-lmr-10x-x-109}[una discusión sobre
lo legal, la reproducción ]{.rm-lmr-10x-x-109}[de audio y video en la
web y uso de recursos. ]{.rm-lmr-10x-x-109}[Las restricciones que
imponen los servidores ]{.rm-lmr-10x-x-109}[privados al contenido
remixeado fue una de ]{.rm-lmr-10x-x-109}[las motivaciones para
implementar un sistema ]{.rm-lmr-10x-x-109}[personalizado. De esta
manera, el sistema evita el ]{.rm-lmr-10x-x-109}[mercado exclusivo de
servicios de streaming ]{.rm-lmr-10x-x-109}[privados, con licencias de
paga o limitados. De ]{.rm-lmr-10x-x-109}[manera complementaria, el
sistema de ]{.rm-lmr-10x-x-109}[streaming
]{.rm-lmri-10x-x-109}[personalizado permite controlar la cantidad
]{.rm-lmr-10x-x-109}[de recursos usados y usuarios conectados. Los
]{.rm-lmr-10x-x-109}[formatos para la transmisión de video en web
]{.rm-lmr-10x-x-109}[explorados fueron: RTMP (Real Time Messaging
]{.rm-lmr-10x-x-109}[Protocol), FLV (Flash Video), HLS (HTTP Live
]{.rm-lmr-10x-x-109}[Streaming), video a través de
WebSockets]{.rm-lmr-10x-x-109}^[[20]{.cmr-8}](#ennote-20){#enmark-20}^[,
]{.rm-lmr-10x-x-109}[WebRTC (Web Real-Time Communication) y
]{.rm-lmr-10x-x-109}[MPEG-DASH (Dynamic Adaptive Streaming over
]{.rm-lmr-10x-x-109}[HTTP).]{.rm-lmr-10x-x-109}

[Las características actuales presentes en HTML5
]{.rm-lmr-10x-x-109}[(Quinta versión de HyperText Markup Language)
]{.rm-lmr-10x-x-109}[permiten utilizar formatos de streaming no nativos
]{.rm-lmr-10x-x-109}[con ]{.rm-lmr-10x-x-109}[frameworks
]{.rm-lmri-10x-x-109}[de decodificación para el despliegue
]{.rm-lmr-10x-x-109}[de video en formatos soportados por el navegador.
]{.rm-lmr-10x-x-109}[Panorama ]{.rm-lmri-10x-x-109}[utiliza RTMP debido
a 1) la robustez del ]{.rm-lmr-10x-x-109}[protocolo, 2) la rapidez de
transmisión de datos, 3) ]{.rm-lmr-10x-x-109}[la documentación que
existe sobre
NGINX]{.rm-lmr-10x-x-109}^[[21]{.cmr-8}](#ennote-21){#enmark-21}^ [RTMP
]{.rm-lmr-10x-x-109}[y 4) el uso de
FFmpeg]{.rm-lmr-10x-x-109}^[[22]{.cmr-8}](#ennote-22){#enmark-22}^ [para
la recodificación y ]{.rm-lmr-10x-x-109}[redimensión de video en la web.
La plataforma ]{.rm-lmr-10x-x-109}[utiliza FLV debido a la velocidad del
protocolo (no ]{.rm-lmr-10x-x-109}[se descarta el uso de otros
protocolos en el futuro). ]{.rm-lmr-10x-x-109}[Para el uso de FLV en el
navegador, se utilizó ]{.rm-lmr-10x-x-109}[FLV.js.]{.rm-lmr-10x-x-109}

[Para la interacción entre usuarios se utilizó
]{.rm-lmr-10x-x-109}[WebSockets. Esto implicó: 1) uso de chat, 2)
]{.rm-lmr-10x-x-109}[compartición en tiempo real de eventos gestuales
]{.rm-lmr-10x-x-109}[(rotación y posición) del avatar utilizado y 3)
]{.rm-lmr-10x-x-109}[personalización de modelo, textura y nombre de
]{.rm-lmr-10x-x-109}[cada usuario.]{.rm-lmr-10x-x-109}

[Del lado del servidor se usaron balanceadores de
]{.rm-lmr-10x-x-109}[carga junto con modelos de configuración para la
]{.rm-lmr-10x-x-109}[instalación y eliminación de recursos, haciendo
]{.rm-lmr-10x-x-109}[independientes los servidores dedicados al
]{.rm-lmr-10x-x-109}[streaming ]{.rm-lmri-10x-x-109}[y a servicios web.
Esto permite que los espacios ]{.rm-lmr-10x-x-109}[puedan ser escritos,
eliminados o mantenidos según ]{.rm-lmr-10x-x-109}[el diseño del evento
en cuestión.]{.rm-lmr-10x-x-109}

### []{#x1-4000}[Notas y Pruebas]{.rm-lmr-10x-x-109} {#notas-y-pruebas .likesectionHead}

[Notas de Ausencia
]{.rm-lmri-10x-x-109}[(]{.rm-lmr-10x-x-109}[[MarianneTeixido]{.rm-lmr-10x-x-109}](#Xnotasdeausencia)[, ]{.rm-lmr-10x-x-109}[[2020]{.rm-lmr-10x-x-109}](#Xnotasdeausencia)[)
es un ]{.rm-lmr-10x-x-109}[ensayo generativo en la web. Utiliza el texto
]{.rm-lmr-10x-x-109}[dato que por medio de la computadora como
]{.rm-lmr-10x-x-109}[agente resignificante, deconstruye estructuras
]{.rm-lmr-10x-x-109}[discursivas para resemantizar la narrativa sobre
las ]{.rm-lmr-10x-x-109}[desapariciones de mujeres en México y América
]{.rm-lmr-10x-x-109}[Latina.]{.rm-lmr-10x-x-109}

[El tiempo y espacio virtual conforman una
]{.rm-lmr-10x-x-109}[partitura para la memoria y la denuncia. La
]{.rm-lmr-10x-x-109}[narrativa, semi autónoma, argumenta a partir de
]{.rm-lmr-10x-x-109}[textos tomados de tweets, poemarios, libros y
]{.rm-lmr-10x-x-109}[artículos feministas que explican desde la teoría
]{.rm-lmr-10x-x-109}[las desapariciones forzadas, el feminicidio y la
]{.rm-lmr-10x-x-109}[violencia de género. Lo cuales están presente como
]{.rm-lmr-10x-x-109}[texto, imagen y sonido.]{.rm-lmr-10x-x-109}

[La narrativa de la pieza está articulada ]{.rm-lmr-10x-x-109}[mediante
la intervención de dos bots. El primero ]{.rm-lmr-10x-x-109}[comparte
tuits que localiza con hashtag como:
]{.rm-lmr-10x-x-109}[\#MéxicoFeminicida, \#MadresEnBúsqueda,
]{.rm-lmr-10x-x-109}[\#ViolenciadeGenero, \#NiUnaMenos, entre
otros.]{.rm-lmr-10x-x-109}^[[23]{.cmr-8}](#ennote-23){#enmark-23}^ [Así
como con un bot de generación de texto
]{.rm-lmr-10x-x-109}[automático.]{.rm-lmr-10x-x-109}

[Esta exploración permitió a Marianne Teixido ]{.rm-lmr-10x-x-109}[en
colaboración con ]{.rm-lmr-10x-x-109}[PiranhaLab
]{.rm-lmri-10x-x-109}[encontrar en ]{.rm-lmr-10x-x-109}[Three.js la
solución para implementar espacios ]{.rm-lmr-10x-x-109}[tridimensionales
como la parte visible de piezas y
]{.rm-lmr-10x-x-109}[espacios.]{.rm-lmr-10x-x-109}

[Pruebas Proféticas ]{.rm-lmri-10x-x-109}[fue el evento piloto que
]{.rm-lmr-10x-x-109}[implementó por primera vez dos tipos de tecnologías
]{.rm-lmr-10x-x-109}[específicas: exploración multijugador y
]{.rm-lmr-10x-x-109}[streaming
]{.rm-lmri-10x-x-109}[personalizado.]{.rm-lmr-10x-x-109}

[Este espacio de prueba consistió en un incipiente
]{.rm-lmr-10x-x-109}[modo de exploración co-presencial que guardaba
]{.rm-lmr-10x-x-109}[una relación entre la posición y la rotación de la
]{.rm-lmr-10x-x-109}[cámara, controlada por medio del ratón y el teclado
]{.rm-lmr-10x-x-109}[de la computadora. Para el control se utlizaron las
]{.rm-lmr-10x-x-109}[teclas WASD y flechas siguiendo la convención de
]{.rm-lmr-10x-x-109}[la cámara de videojuegos en primera persona.
]{.rm-lmr-10x-x-109}[La información de posición y rotación fueron
]{.rm-lmr-10x-x-109}[compartidas y podían visualizar el movimiento
deavatares que representaban a los asistentes en el
]{.rm-lmr-10x-x-109}[espacio digital.]{.rm-lmr-10x-x-109}

[La transmisión de audio y video fue un aspecto que
]{.rm-lmr-10x-x-109}[el planteamiento de ]{.rm-lmr-10x-x-109}[PiranhaLab
]{.rm-lmri-10x-x-109}[buscó solucionar. ]{.rm-lmr-10x-x-109}[Es posible
utilizar servicios gratuitos o de paga ]{.rm-lmr-10x-x-109}[para la
transmisión de datos audiovisuales, sin ]{.rm-lmr-10x-x-109}[embargo, en
menor o mayor medida, el flujo ]{.rm-lmr-10x-x-109}[audiovisual generado
es analizado y en caso de que ]{.rm-lmr-10x-x-109}[se detecte algún
extacto de audio proveniente con ]{.rm-lmr-10x-x-109}[derechos de autor,
el stream es silenciado. Este ]{.rm-lmr-10x-x-109}[artículo no busca
centrarse en discusiones sobre ]{.rm-lmr-10x-x-109}[derechos de autor
sino en la usabilidad de un ]{.rm-lmr-10x-x-109}[streaming
audiovisual.]{.rm-lmr-10x-x-109}

[La concatenación de software estuvo delimitado ]{.rm-lmr-10x-x-109}[por
la experiencia de usuarios hipotéticos. Esto ]{.rm-lmr-10x-x-109}[nos
llevo a plantear los posibles agentes que se
]{.rm-lmr-10x-x-109}[involucraban con la experiencia inmersiva. Como la
]{.rm-lmr-10x-x-109}[propuesta partió de eventos performáticos tipo
]{.rm-lmr-10x-x-109}[concierto, la figura de intérpretes/artistas fue
]{.rm-lmr-10x-x-109}[central. El mantenimiento del flujo performático
]{.rm-lmr-10x-x-109}[expresado a partir de una transmisión de audio
]{.rm-lmr-10x-x-109}[y video delimitó el aspecto técnico y estético
]{.rm-lmr-10x-x-109}[del espacio: El primer objetivo a resolver fue el
]{.rm-lmr-10x-x-109}[streaming que pudiera ser estable, eficiente,
]{.rm-lmr-10x-x-109}[compatible con la convención de transmisión
]{.rm-lmr-10x-x-109}[personalizada ejecutada con programas de interfaz
]{.rm-lmr-10x-x-109}[gráfica como OBS (Open Broadcaster
Software).]{.rm-lmr-10x-x-109}

[El segundo tipo de agente fue el público que
]{.rm-lmr-10x-x-109}[navegaba en el espacio y que realizaba gestos
]{.rm-lmr-10x-x-109}[corporales virtuales sencillos: posición y
rotación.]{.rm-lmr-10x-x-109}

[Un tercer tipo de agente se involucró con los
]{.rm-lmr-10x-x-109}[aspectos fuera del escenario, la lógistica de la
]{.rm-lmr-10x-x-109}[transmisión y el mantenimiento del sistema en
]{.rm-lmr-10x-x-109}[tiempo real visibilizó la figura del
]{.rm-lmr-10x-x-109}[staff]{.rm-lmri-10x-x-109}[. En este
]{.rm-lmr-10x-x-109}[sentido la labor tecnológica virtual del equipo de
]{.rm-lmr-10x-x-109}[PiranhaLab ]{.rm-lmri-10x-x-109}[fue cercana a la
logística y a la ]{.rm-lmr-10x-x-109}[división del trabajo de un
escenario para conciertos
]{.rm-lmr-10x-x-109}[presenciales.]{.rm-lmr-10x-x-109}

[La experiencia con ]{.rm-lmr-10x-x-109}[Pruebas Proféticas
]{.rm-lmri-10x-x-109}[abrió ]{.rm-lmr-10x-x-109}[camino para el diseño
de la edición 2020 de ]{.rm-lmr-10x-x-109}[EDGES. El concepto curatorial
de ]{.rm-lmr-10x-x-109}[EDGES ]{.rm-lmri-10x-x-109}[estuvo
]{.rm-lmr-10x-x-109}[definido por Marianne Teixido y guardó una
]{.rm-lmr-10x-x-109}[estrecha relación con los planteamientos de
]{.rm-lmr-10x-x-109}[Notas ]{.rm-lmri-10x-x-109}[de
Ausencia]{.rm-lmri-10x-x-109}[, considera las posibilidades de creación
]{.rm-lmr-10x-x-109}[planteandonos desde el feminismo intereseccional,
]{.rm-lmr-10x-x-109}[perspectiva desde la cual se problematiza el uso
]{.rm-lmr-10x-x-109}[de la tecnología teniendo en consideración las
]{.rm-lmr-10x-x-109}[condiciones de raza, género y clase, a partir de la
]{.rm-lmr-10x-x-109}[cuales se establece una crítica las herramientas
]{.rm-lmr-10x-x-109}[hegemónicas ya dadas para apuntar a la creación de
]{.rm-lmr-10x-x-109}[estas otras herramientas, construídas desde
]{.rm-lmr-10x-x-109}[dinámicas de organización colectiva y conocimientos
]{.rm-lmr-10x-x-109}[situados. ]{.rm-lmr-10x-x-109}[EDGES 2020
]{.rm-lmri-10x-x-109}[como propuesta curatorial
]{.rm-lmr-10x-x-109}[contempla la participación en su mayoría de
]{.rm-lmr-10x-x-109}[mujeres y persona no binaries. Las obras dialogan
]{.rm-lmr-10x-x-109}[con las hibridaciones e-corporales en espacios
]{.rm-lmr-10x-x-109}[virtuales ficcionados desde las subjetividades
]{.rm-lmr-10x-x-109}[feministas y transfeministas que toman internet
]{.rm-lmr-10x-x-109}[como territorio y espacio de intercambio
cultural.]{.rm-lmr-10x-x-109}

### []{#x1-5000}[Contemplación y EDGES]{.rm-lmr-10x-x-109} {#contemplación-y-edges .likesectionHead}

[Distopía]{.rm-lmri-10x-x-109}[, ]{.rm-lmr-10x-x-109}[NLXS +
NK]{.rm-lmri-10x-x-109}[,
]{.rm-lmr-10x-x-109}[Interconexión]{.rm-lmri-10x-x-109}[,
]{.rm-lmr-10x-x-109}[setInterval() ]{.rm-lmri-10x-x-109}[y
]{.rm-lmr-10x-x-109}[La Contemplación del Fin del Mundo
]{.rm-lmri-10x-x-109}[fueron los ]{.rm-lmr-10x-x-109}[eventos realiados
en el marco de
]{.rm-lmr-10x-x-109}[EDGES]{.rm-lmri-10x-x-109}[.]{.rm-lmr-10x-x-109}

[La Contemplación del Fin del Mundo ]{.rm-lmri-10x-x-109}[es un
]{.rm-lmr-10x-x-109}[performance a modo de ejuego, último evento de la
]{.rm-lmr-10x-x-109}[serie ]{.rm-lmr-10x-x-109}[EDGES
]{.rm-lmri-10x-x-109}[que destruye el escenario de manera
]{.rm-lmr-10x-x-109}[simbólica para dar por finalizado el ciclo de
]{.rm-lmr-10x-x-109}[conciertos. Los asistentes podían presenciar el fin
]{.rm-lmr-10x-x-109}[del mundo con la destrucción del escenario y otros
]{.rm-lmr-10x-x-109}[eventos como inundaciones, objetos celestiales
]{.rm-lmr-10x-x-109}[y finalmente la dispersión de los colores del
]{.rm-lmr-10x-x-109}[escenario, dejando a los objetos del espacio sin
]{.rm-lmr-10x-x-109}[razgos reconocibles.]{.rm-lmr-10x-x-109}

[La idea principal sirvió como vehículo para la
]{.rm-lmr-10x-x-109}[exploración del espacio como característica del
]{.rm-lmr-10x-x-109}[performance, el mundo explorable, la persecución
]{.rm-lmr-10x-x-109}[en forma de figuras celestiales que ocupaban todo
el ]{.rm-lmr-10x-x-109}[espacio o que se expandían e iluminaban todo así
]{.rm-lmr-10x-x-109}[como las inundaciociones. También permitió la
]{.rm-lmr-10x-x-109}[exploración del uso de pantallas distribuidas a
]{.rm-lmr-10x-x-109}[lo largo de todo el mundo, permitiendo a los
]{.rm-lmr-10x-x-109}[usuarios presenciar el performance desde cualquier
]{.rm-lmr-10x-x-109}[ubicación.]{.rm-lmr-10x-x-109}

[Uno de los aspectos a destacar de este concierto
]{.rm-lmr-10x-x-109}[es el uso de acciones colectivas lanzadas por
]{.rm-lmr-10x-x-109}[el artista, que durante el trascurso del evento
]{.rm-lmr-10x-x-109}[podía cambiar las características del ambiente
]{.rm-lmr-10x-x-109}[de manera similar entre los participantes. La
]{.rm-lmr-10x-x-109}[experiencia de los usuarios fue se transformaba
]{.rm-lmr-10x-x-109}[en el trancurso del evento, fue homogénea y
]{.rm-lmr-10x-x-109}[compartida. Adicionalmente se implementó Hydra
]{.rm-lmr-10x-x-109}[(]{.rm-lmr-10x-x-109}[[ojack]{.rm-lmr-10x-x-109}](#Xhydra)[, ]{.rm-lmr-10x-x-109}[[2020]{.rm-lmr-10x-x-109}](#Xhydra)[)
como un framework externo para la ]{.rm-lmr-10x-x-109}[creación de
visuales.]{.rm-lmr-10x-x-109}

[Las dificultad de las experiencias compartidas
]{.rm-lmr-10x-x-109}[radica en la sincronización de eventos, tanto para
]{.rm-lmr-10x-x-109}[los usuarios que ingresan desde el inicio o los
]{.rm-lmr-10x-x-109}[usuarios ocasionales, sin importar ubicación
]{.rm-lmr-10x-x-109}[geográfica o dispositivo. Esta posibilidad permite
la ]{.rm-lmr-10x-x-109}[interacción del artista y genera situaciones que
]{.rm-lmr-10x-x-109}[añadan dinámica al juego, donde los asistentes se
]{.rm-lmr-10x-x-109}[desplazan de ser observadores a ser participantes
]{.rm-lmr-10x-x-109}[activos.]{.rm-lmr-10x-x-109}

### []{#x1-6000}[Three y 4NT1]{.rm-lmr-10x-x-109} {#three-y-4nt1 .likesectionHead}

[THREE.studies
]{.rm-lmri-10x-x-109}[(]{.rm-lmr-10x-x-109}[[EmilioOcelotl]{.rm-lmr-10x-x-109}](#Xthreestudies)[, ]{.rm-lmr-10x-x-109}[[2020b]{.rm-lmr-10x-x-109}](#Xthreestudies)[)
hereda ]{.rm-lmr-10x-x-109}[discusiones referentes al punto de vista, la
]{.rm-lmr-10x-x-109}[co-presencia, el envío de información gestual a
]{.rm-lmr-10x-x-109}[través de la web, la transmisión de flujos de
]{.rm-lmr-10x-x-109}[audio y video a partir de servidores y el uso
]{.rm-lmr-10x-x-109}[de fuentes sonoras en un espacio virtual. Se
]{.rm-lmr-10x-x-109}[relaciona con ]{.rm-lmr-10x-x-109}[4NT1
]{.rm-lmri-10x-x-109}[(]{.rm-lmr-10x-x-109}[[EmilioOcelotl]{.rm-lmr-10x-x-109}](#Xanti)[, ]{.rm-lmr-10x-x-109}[[2020a]{.rm-lmr-10x-x-109}](#Xanti)[)
y ]{.rm-lmr-10x-x-109}[tres-estudios-abiertos
]{.rm-lmri-10x-x-109}[(]{.rm-lmr-10x-x-109}[[EmilioOcelotl]{.rm-lmr-10x-x-109}](#Xtresestudios)[, ]{.rm-lmr-10x-x-109}[[2020c]{.rm-lmr-10x-x-109}](#Xtresestudios)[)
y ]{.rm-lmr-10x-x-109}[forma parte de un proyecto de investigación
]{.rm-lmr-10x-x-109}[doctoral que aborda nuevas prácticas artísticas
]{.rm-lmr-10x-x-109}[audiovisuales en el navegador a partir de lenguajes
]{.rm-lmr-10x-x-109}[de programación.]{.rm-lmr-10x-x-109}

[La primera instancia de
]{.rm-lmr-10x-x-109}[THREE.studies]{.rm-lmri-10x-x-109}[,
]{.rm-lmr-10x-x-109}[threecln]{.rm-lmri-10x-x-109}[,
]{.rm-lmr-10x-x-109}[es un performance audiovisual para el navegador.
]{.rm-lmr-10x-x-109}[Las señales de audio y video se encuentran en un
]{.rm-lmr-10x-x-109}[espacio diseñado para el evento. Los elementos del
]{.rm-lmr-10x-x-109}[escenario interactúan con las señales y proveen de
]{.rm-lmr-10x-x-109}[retroalimentación sonora y visual al intérprete
]{.rm-lmr-10x-x-109}[musical.]{.rm-lmr-10x-x-109}

[El espacio se fusiona con la interpretación y
]{.rm-lmr-10x-x-109}[resulta en una pieza para el navegador / partitura
]{.rm-lmr-10x-x-109}[gráfica que se transforma a sí misma cada vez que
]{.rm-lmr-10x-x-109}[se interpreta. La obra involucra a un intérprete
]{.rm-lmr-10x-x-109}[musical, para el caso que revisamos en este
]{.rm-lmr-10x-x-109}[artículo, de violonchelo eléctrico, el operador de
la ]{.rm-lmr-10x-x-109}[electrónica en vivo y el equipo que mantiene la
]{.rm-lmr-10x-x-109}[estabilidad del espacio.]{.rm-lmr-10x-x-109}

[El intérprete musical envía un ]{.rm-lmr-10x-x-109}[stream
]{.rm-lmri-10x-x-109}[que es ]{.rm-lmr-10x-x-109}[espacializado y que
interactúa con los elementos ]{.rm-lmr-10x-x-109}[visuales de la escena.
El resultado es una obra / ]{.rm-lmr-10x-x-109}[partitura que puede
explorarse en tiempo real por ]{.rm-lmr-10x-x-109}[el
público.]{.rm-lmr-10x-x-109}

[Por otro lado, ]{.rm-lmr-10x-x-109}[4NT1 ]{.rm-lmri-10x-x-109}[busca
problematizar las ]{.rm-lmr-10x-x-109}[relaciones que existen entre
usuarios y plataformas ]{.rm-lmr-10x-x-109}[tecnológicas; es un paso
hacia la realización de ]{.rm-lmr-10x-x-109}[usuarixs que desdibujan las
fronteras de la pasividad ]{.rm-lmr-10x-x-109}[política y económica
teniendo como epicentro lo ]{.rm-lmr-10x-x-109}[sensible. El proyecto
parte de la composición visual ]{.rm-lmr-10x-x-109}[conducida por datos.
Aprovecha la investigación y ]{.rm-lmr-10x-x-109}[el desarrollo de tres
estudios abiertos, un proyecto ]{.rm-lmr-10x-x-109}[doctoral sobre
nuevas prácticas artísticas en el ]{.rm-lmr-10x-x-109}[navegador y
librerías de síntesis granular para ]{.rm-lmr-10x-x-109}[audio y
video.]{.rm-lmr-10x-x-109}

[La obra toma en cuenta la transformación de ]{.rm-lmr-10x-x-109}[flujos
de audio y video y se retroalimenta con la ]{.rm-lmr-10x-x-109}[acción
de agentes externos. Con técnicas de ]{.rm-lmr-10x-x-109}[aprendizaje
automático, detecta gestos faciales queson intepretados como un flujo de
datos. El ]{.rm-lmr-10x-x-109}[proyecto problematiza este flujo con el
uso de ]{.rm-lmr-10x-x-109}[tecnologías que implican una responsabilidad
]{.rm-lmr-10x-x-109}[de los datos de usuarixs. De esta manera el
]{.rm-lmr-10x-x-109}[proyecto pplantea una discusión que parte de la
]{.rm-lmr-10x-x-109}[instagramización de la política y la estetización
de ]{.rm-lmr-10x-x-109}[la resistencia para desembocar en la política de
la ]{.rm-lmr-10x-x-109}[representación.]{.rm-lmr-10x-x-109}

[4NT1 ]{.rm-lmri-10x-x-109}[es un pedazo de software que puede
]{.rm-lmr-10x-x-109}[utilizarse en la vida cotidiana y que desplaza
]{.rm-lmr-10x-x-109}[la ofuscación en el uso de tecnologías que
]{.rm-lmr-10x-x-109}[funcionan como cajas negras al desarrollo de capas
]{.rm-lmr-10x-x-109}[estéticas para la evasión. El proyecto contempla
]{.rm-lmr-10x-x-109}[la comparación de dos caminos que permitan
]{.rm-lmr-10x-x-109}[plantear una crítica al software como caja negra.
]{.rm-lmr-10x-x-109}[Es un primer estudio de reflexión tecno-social.
]{.rm-lmr-10x-x-109}[Retoma la idea de modularidad y se adscribe a los
]{.rm-lmr-10x-x-109}[estudios del software, esto quiere decir que la
obra ]{.rm-lmr-10x-x-109}[se complementa con la programación, lectura,
]{.rm-lmr-10x-x-109}[escritura y pensamiento con
software.]{.rm-lmr-10x-x-109}

### []{#x1-7000}[Discusión]{.rm-lmr-10x-x-109} {#discusión .likesectionHead}

[La investigación detectó funcionalidad y
]{.rm-lmr-10x-x-109}[experimentación como dos posibilidades de un
]{.rm-lmr-10x-x-109}[continuo para la escritura de software en un marco
]{.rm-lmr-10x-x-109}[artístico y performático. EDGES como plataforma
]{.rm-lmr-10x-x-109}[explicita el papel experimental de los actos,
]{.rm-lmr-10x-x-109}[la plataforma tecnológica también podría ser
]{.rm-lmr-10x-x-109}[experimental e incluso podría desdibujarse en pos
]{.rm-lmr-10x-x-109}[de la integración performance-espacio bajo la
]{.rm-lmr-10x-x-109}[misma premisa de la
experimentación.]{.rm-lmr-10x-x-109}

[Los eventos realizados en esta diversidad de
]{.rm-lmr-10x-x-109}[plataformas han utilizado ligas a internet que de
]{.rm-lmr-10x-x-109}[acuerdo a la fecha consultada, redireccionan a
]{.rm-lmr-10x-x-109}[distintos espacios virtuales. A diferencia de los
]{.rm-lmr-10x-x-109}[sitios que utilizan texto y entornos de
programación ]{.rm-lmr-10x-x-109}[web como HTML, la mezcla de módulos y
el uso de ]{.rm-lmr-10x-x-109}[frameworks dedicados que utilizan
renderizadores ]{.rm-lmr-10x-x-109}[3d como webGL, motores de audio como
Web ]{.rm-lmr-10x-x-109}[Audio API o plataformas de transmisión de audio
]{.rm-lmr-10x-x-109}[y video personalizadas y efímeras dificultan
]{.rm-lmr-10x-x-109}[la documentación convencional. La labor se
]{.rm-lmr-10x-x-109}[complica cuando el mantenimiento de estos espacios
]{.rm-lmr-10x-x-109}[sobrepasa los alcances temporales o económicos del
]{.rm-lmr-10x-x-109}[proyecto. El reto metodológico que esto supone es
]{.rm-lmr-10x-x-109}[un asunto pendiente para las investigaciones que
]{.rm-lmr-10x-x-109}[hacen referencia a tecnología. En este sentido,
]{.rm-lmr-10x-x-109}[la referencia a repositorios de código públicos
]{.rm-lmr-10x-x-109}[podrían arrojar soluciones para la documentación y
]{.rm-lmr-10x-x-109}[arqueología de los desarrollos tecnológicos. Una
]{.rm-lmr-10x-x-109}[alternativa para la documentación de estos procesos
]{.rm-lmr-10x-x-109}[es ]{.rm-lmr-10x-x-109}[Wayback
Machine]{.rm-lmri-10x-x-109}^[[24]{.cmr-8}](#ennote-24){#enmark-24}^[.]{.rm-lmr-10x-x-109}

[Una de las reflexiones que estuvo presente desde
]{.rm-lmr-10x-x-109}[el inicio del proyecto partió de las distinciones
más ]{.rm-lmr-10x-x-109}[inmediatas: mundos virtuales / mundos reales,
]{.rm-lmr-10x-x-109}[materialidad / inmaterialidad. Consideramos
]{.rm-lmr-10x-x-109}[que procesos como los de
]{.rm-lmr-10x-x-109}[Panorama ]{.rm-lmri-10x-x-109}[transitan
]{.rm-lmr-10x-x-109}[entre la extensión de la fisicalidad hacia la
]{.rm-lmr-10x-x-109}[virtualidad]{.rm-lmr-10x-x-109}^[[25]{.cmr-8}](#ennote-25){#enmark-25}^
[(]{.rm-lmr-10x-x-109}[[Frazer]{.rm-lmr-10x-x-109}](#Xcyberspace)[, ]{.rm-lmr-10x-x-109}[[2013]{.rm-lmr-10x-x-109}](#Xcyberspace)[)
y la reconfiguración ]{.rm-lmr-10x-x-109}[de la
materialidad]{.rm-lmr-10x-x-109}^[[26]{.cmr-8}](#ennote-26){#enmark-26}^
[(]{.rm-lmr-10x-x-109}[[Sosa]{.rm-lmr-10x-x-109}](#Xandreasosa)[, ]{.rm-lmr-10x-x-109}[[2017]{.rm-lmr-10x-x-109}](#Xandreasosa)[)
de cara al ]{.rm-lmr-10x-x-109}[giro digital que posibilita la
continuación y ]{.rm-lmr-10x-x-109}[contraposición estéticas y formas de
organización ]{.rm-lmr-10x-x-109}[social.]{.rm-lmr-10x-x-109}

[Señalamos la naturaleza efímera de obras y
]{.rm-lmr-10x-x-109}[espacios en la lógica digital, y consideramos que
el ]{.rm-lmr-10x-x-109}[reto técnico, investigativo y de (re)activación
]{.rm-lmr-10x-x-109}[está abierto y en constante discusión. En este
]{.rm-lmr-10x-x-109}[sentido, la formación de artistas capaces de
]{.rm-lmr-10x-x-109}[interactuar y ejecutar estas piezas podría apuntar
a ]{.rm-lmr-10x-x-109}[la consideración de estos aspectos en los
programas ]{.rm-lmr-10x-x-109}[de interpretación musical con nuevas
tecnologías. ]{.rm-lmr-10x-x-109}[Adicionalmente el aspecto formativo
podría ]{.rm-lmr-10x-x-109}[extenderse hacia la investigación y
escritura de ]{.rm-lmr-10x-x-109}[software.]{.rm-lmr-10x-x-109}

[La presente investigación estuvo relacionada ]{.rm-lmr-10x-x-109}[con
la gamificación
emergente]{.rm-lmr-10x-x-109}^[[27]{.cmr-8}](#ennote-27){#enmark-27}^
[tácita en la ]{.rm-lmr-10x-x-109}[escritura de proyectos como
]{.rm-lmr-10x-x-109}[Panorama]{.rm-lmri-10x-x-109}[. Esto
]{.rm-lmr-10x-x-109}[implica 1) tecnología, por ejemplo pantallas,
]{.rm-lmr-10x-x-109}[combinaciones de teclas para la exploración de
]{.rm-lmr-10x-x-109}[espacios pero también dispositivos de realidad
]{.rm-lmr-10x-x-109}[virtual, 2) diseño visual y sonoro de los espacios,
]{.rm-lmr-10x-x-109}[objetos digitales en espacios tridimensionales,
audio ]{.rm-lmr-10x-x-109}[inmersivo, 3) intercambio de información para
la ]{.rm-lmr-10x-x-109}[co-presencia en tiempo real dentro de espacios
]{.rm-lmr-10x-x-109}[digitales o el multijugador e incluso 4) narrativas
e ]{.rm-lmr-10x-x-109}[imaginarios convenidos, explorados desde el
]{.rm-lmr-10x-x-109}[diseño de la experiencia y esperados del lado del
]{.rm-lmr-10x-x-109}[público.]{.rm-lmr-10x-x-109}

[El término
cyberespacio]{.rm-lmr-10x-x-109}^[[28]{.cmr-8}](#ennote-28){#enmark-28}^
[puede ser un punto de ]{.rm-lmr-10x-x-109}[partida para describir la
actividad relacionada con
]{.rm-lmr-10x-x-109}[Panorama]{.rm-lmri-10x-x-109}[. Puede ser
contrapuesto con diversos ]{.rm-lmr-10x-x-109}[conceptos que coinciden
en la práctica, en la ]{.rm-lmr-10x-x-109}[arquitectura de intercambio
de información, en la ]{.rm-lmr-10x-x-109}[denominación conceptual y en
la convergencia de ]{.rm-lmr-10x-x-109}[tecnologías expresamente
mercantilizadas para la ]{.rm-lmr-10x-x-109}[distribución de
experiencias de Realidad Virtual ]{.rm-lmr-10x-x-109}[(VR) como Oculus
Rift. VR también puede ser un ]{.rm-lmr-10x-x-109}[concepto inicial,
socialmente convenido para ]{.rm-lmr-10x-x-109}[describir la experiencia
de ]{.rm-lmr-10x-x-109}[Panorama ]{.rm-lmri-10x-x-109}[pero para
]{.rm-lmr-10x-x-109}[evitar contradicciones en la conducción de una
]{.rm-lmr-10x-x-109}[experiencia en el cyberespacio hacia exploraciones
]{.rm-lmr-10x-x-109}[hacia dispositivos/interfaces para la interacción
en ]{.rm-lmr-10x-x-109}[estos espacios, el presente artículo decide
retomar ]{.rm-lmr-10x-x-109}[la noción de inmersividad. Consideramos que
la ]{.rm-lmr-10x-x-109}[relación entre cyberespacio como una noción
]{.rm-lmr-10x-x-109}[narrativa y de inmersividad como una forma de
]{.rm-lmr-10x-x-109}[resolución técnica de exploración de una cámara en
]{.rm-lmr-10x-x-109}[un espacio tridimensional, con audio
posicionado]{.rm-lmr-10x-x-109}^[[29]{.cmr-8}](#ennote-29){#enmark-29}^[,
]{.rm-lmr-10x-x-109}[puede arrojar algunas ideas sobre la actividad
]{.rm-lmr-10x-x-109}[realizada en el marco de
]{.rm-lmr-10x-x-109}[Panorama]{.rm-lmri-10x-x-109}[.]{.rm-lmr-10x-x-109}

[Manifiestos, posturas políticas y alternativas en
]{.rm-lmr-10x-x-109}[la organización que dialogan con la escritura de
]{.rm-lmr-10x-x-109}[software como desarrollo tecnológico y como acto
]{.rm-lmr-10x-x-109}[creativo. Por ejemplo ]{.rm-lmr-10x-x-109}[live
coding ]{.rm-lmri-10x-x-109}[y la transparencia ]{.rm-lmr-10x-x-109}[de
los procesos o el uso de interfaces de texto
]{.rm-lmr-10x-x-109}[(]{.rm-lmr-10x-x-109}[[Collins
]{.rm-lmr-10x-x-109}[et
al.]{.rm-lmri-10x-x-109}](#XcollinsLivecoding)[, ]{.rm-lmr-10x-x-109}[[2003]{.rm-lmr-10x-x-109}](#XcollinsLivecoding)[),
el manifiesto de una servidora ]{.rm-lmr-10x-x-109}[feminista
(]{.rm-lmr-10x-x-109}[[Feminist-Server-Summit]{.rm-lmr-10x-x-109}](#Xfeministserver)[, ]{.rm-lmr-10x-x-109}[[2014]{.rm-lmr-10x-x-109}](#Xfeministserver)[)
o la ]{.rm-lmr-10x-x-109}[arquitectura de distribución de información
]{.rm-lmr-10x-x-109}[par a
par]{.rm-lmr-10x-x-109}^[[30]{.cmr-8}](#ennote-30){#enmark-30}^ [que
persigue la distribución y la ]{.rm-lmr-10x-x-109}[descentralización en
redes que posibilitan espacios ]{.rm-lmr-10x-x-109}[virtuales
(]{.rm-lmr-10x-x-109}[[Frazer]{.rm-lmr-10x-x-109}](#Xcyberspace)[, ]{.rm-lmr-10x-x-109}[[2013]{.rm-lmr-10x-x-109}](#Xcyberspace)[)
y que incluso puede ]{.rm-lmr-10x-x-109}[extenderse al autocuidado y
formas alternativas de ]{.rm-lmr-10x-x-109}[expresar relaciones sociales
en red
(]{.rm-lmr-10x-x-109}[[Choi]{.rm-lmr-10x-x-109}](#Xdwc)[, ]{.rm-lmr-10x-x-109}[[2018]{.rm-lmr-10x-x-109}](#Xdwc)[).]{.rm-lmr-10x-x-109}

[Estas perspectivas pueden extenderse hacia ]{.rm-lmr-10x-x-109}[una
postura para la investigación de tecnología ]{.rm-lmr-10x-x-109}[y el
papel que juegan en la política de los ]{.rm-lmr-10x-x-109}[espacios
físicos y virtuales, como el cuarto propio
]{.rm-lmr-10x-x-109}[(]{.rm-lmr-10x-x-109}[[Zafra]{.rm-lmr-10x-x-109}](#Xcuartopropio)[, ]{.rm-lmr-10x-x-109}[[2020]{.rm-lmr-10x-x-109}](#Xcuartopropio)[)
o el buen conocer (cita platohedro). ]{.rm-lmr-10x-x-109}[Podríamos
relacionar estos procesos con el giro de ]{.rm-lmr-10x-x-109}[los nuevos
medios descrito por
]{.rm-lmr-10x-x-109}[[Manovich]{.rm-lmr-10x-x-109}](#Xmanovichlanguage)[ (]{.rm-lmr-10x-x-109}[[2001]{.rm-lmr-10x-x-109}](#Xmanovichlanguage)[),
]{.rm-lmr-10x-x-109}[las implicaciones sociales de este giro y sobre
todo, ]{.rm-lmr-10x-x-109}[las consecuencias estéticas que a partir de
este se ]{.rm-lmr-10x-x-109}[abren y desenvuelven en el performance
musical ]{.rm-lmr-10x-x-109}[por medio de la computadora y otras
prácticas ]{.rm-lmr-10x-x-109}[afines.]{.rm-lmr-10x-x-109}

[De este mapa ¿Podríamos establecer un corpus ]{.rm-lmr-10x-x-109}[de
conceptos y estéticas
(]{.rm-lmr-10x-x-109}[[Shanken]{.rm-lmr-10x-x-109}](#XshankenCanon)[, ]{.rm-lmr-10x-x-109}[[2010]{.rm-lmr-10x-x-109}](#XshankenCanon)[)
que ]{.rm-lmr-10x-x-109}[pudieran explicar las nuevas prácticas
artísticas ]{.rm-lmr-10x-x-109}[con medios que implican a la música pero
también ]{.rm-lmr-10x-x-109}[a otros campos, que además pudiera
considerar ]{.rm-lmr-10x-x-109}[aspectos sociales y políticos implicados
en la ]{.rm-lmr-10x-x-109}[música y expresiones cercanas a ésta? ¿Cómo
se ]{.rm-lmr-10x-x-109}[vincularía este giro con las implicaciones
políticas ]{.rm-lmr-10x-x-109}[y estéticas de la programación de
software y ]{.rm-lmr-10x-x-109}[su ejecución (]{.rm-lmr-10x-x-109}[[Cox
y
McLean]{.rm-lmr-10x-x-109}](#XspeakingCode)[, ]{.rm-lmr-10x-x-109}[[2012]{.rm-lmr-10x-x-109}](#XspeakingCode)[)
de cara a ]{.rm-lmr-10x-x-109}[expresiones más claramente delimitadas
hacia la ]{.rm-lmr-10x-x-109}[música y la tecnología que la
posibilita?]{.rm-lmr-10x-x-109}

### []{#x1-8000}[Conclusiones]{.rm-lmr-10x-x-109} {#conclusiones .likesectionHead}

[Los usuarios pudieron compartir una experiencia
]{.rm-lmr-10x-x-109}[ligera para el navegador de manera co-presencial,
]{.rm-lmr-10x-x-109}[aprovechando las posibilidades de las tecnologías
]{.rm-lmr-10x-x-109}[de transmisión de audio y video. Destacamos la
]{.rm-lmr-10x-x-109}[importancia de plantear soluciones compartibles en
]{.rm-lmr-10x-x-109}[lo que respecta a la transmisión de audio-imagen.
]{.rm-lmr-10x-x-109}[La escritura de esta parte de
]{.rm-lmr-10x-x-109}[Panorama ]{.rm-lmri-10x-x-109}[fue
]{.rm-lmr-10x-x-109}[utilizado en el marco de otros eventos y
ciclos.]{.rm-lmr-10x-x-109}

[El proyecto no tuvo un plan de acción específico
]{.rm-lmr-10x-x-109}[para la realización de mediciones durante los
]{.rm-lmr-10x-x-109}[conciertos, a pesar de que el control del servidor
lo ]{.rm-lmr-10x-x-109}[permitió. Sin embargo, la lectura de información
a ]{.rm-lmr-10x-x-109}[partir de una simulación del evento arroja datos
]{.rm-lmr-10x-x-109}[importantes en este sentido.]{.rm-lmr-10x-x-109}

[Sobre las impresiones del público, fue posible
]{.rm-lmr-10x-x-109}[realizar un cuestionario durante
]{.rm-lmr-10x-x-109}[Pruebas
Proféticas]{.rm-lmri-10x-x-109}[.]{.rm-lmr-10x-x-109}

[La importancia de una infraestructura tecnológica
]{.rm-lmr-10x-x-109}[y social. Esto se puede entretejer a partir de
]{.rm-lmr-10x-x-109}[decisiones curatoriales que vinculan potencial
]{.rm-lmr-10x-x-109}[tecnológico con alianzas entre
actores.]{.rm-lmr-10x-x-109}

[Del lado teórico es necesario convenir y reforzar
]{.rm-lmr-10x-x-109}[un corpus de conceptos para la investigación sobre
]{.rm-lmr-10x-x-109}[Tecnología Musical. Detección de campos y
]{.rm-lmr-10x-x-109}[persectivas de investigación: las agencias que
están ]{.rm-lmr-10x-x-109}[presentes en eventos que se desenvuelven con
]{.rm-lmr-10x-x-109}[tecnología.]{.rm-lmr-10x-x-109}

[Destacamos el giro de los nuevos medios como un
]{.rm-lmr-10x-x-109}[cambio de paradigma que la tecnología musical debe
]{.rm-lmr-10x-x-109}[considerar por las implicaciones de los
usos/críticas ]{.rm-lmr-10x-x-109}[de las tecnologías de la información,
las tendencias ]{.rm-lmr-10x-x-109}[para la resolución de problemas
relacionados con ]{.rm-lmr-10x-x-109}[gestión de datos y las
consecuencias estéticas que a ]{.rm-lmr-10x-x-109}[veces se empalman y
otras rebasan a la música y las ]{.rm-lmr-10x-x-109}[perspectivas de
investigación asociadas a esta
]{.rm-lmr-10x-x-109}[disciplina.]{.rm-lmr-10x-x-109}

[El rodeo o la realización de un motivo tecnológico
]{.rm-lmr-10x-x-109}[como una perspectiva de investigación que
]{.rm-lmr-10x-x-109}[pueda aportar en el aspecto tecnológico y
]{.rm-lmr-10x-x-109}[teórico-metodológico, sobre todo en campos
]{.rm-lmr-10x-x-109}[que lo permiten como humanidades, artes y
]{.rm-lmr-10x-x-109}[específicamente, investigación que implica musica y
]{.rm-lmr-10x-x-109}[expresiones audiovisuales con
tecnología.]{.rm-lmr-10x-x-109}

### []{#x1-9000}[Notas]{.rm-lmr-10x-x-109} {#notas .likesectionHead}

[^[1]{.cmr-7}^](#enmark-1){#ennote-1}["PiranhaLab es un laboratorio
interdisciplinario ]{.rm-lmr-10}[que trabaja en las tripas del
]{.rm-lmr-10}[software".
]{.rm-lmr-10}[[https://piranhalab.github.io/]{.rm-lmr-10}](https://piranhalab.github.io/){.url}
[(Consultado ]{.rm-lmr-10}[el 26 de marzo de 2021)]{.rm-lmr-10}

[^[2]{.cmr-7}^](#enmark-2){#ennote-2}["Plataforma de experimentación y
difusión de ]{.rm-lmr-10}[proyectos audiovisuales en vivo" impulsada por
]{.rm-lmr-10}[el Laboratorio de Imágenes en Movimiento del
]{.rm-lmr-10}[Centro Multimedia del Centro Nacional de las
Artes.]{.rm-lmr-10}
[[https://www.facebook.com/events/209679013466792]{.rm-lmr-10}](https://www.facebook.com/events/209679013466792){.url}
[(Consultado el 26 de marzo de 2021)]{.rm-lmr-10}

[^[3]{.cmr-7}^](#enmark-3){#ennote-3}[[https://notasdeausencia.cc]{.rm-lmr-10}](https://notasdeausencia.cc){.url}
[(Consultado el 26 de ]{.rm-lmr-10}[marzo de 2021)]{.rm-lmr-10}

[^[4]{.cmr-7}^](#enmark-4){#ennote-4}[[https://edges.piranhalab.cc]{.rm-lmr-10}](https://edges.piranhalab.cc){.url}
[(Consultado el 26 de ]{.rm-lmr-10}[marzo de 2021)]{.rm-lmr-10}

[^[5]{.cmr-7}^](#enmark-5){#ennote-5}[[https://threecln.piranhalab.cc]{.rm-lmr-10}](https://threecln.piranhalab.cc){.url}[(Consultado
el ]{.rm-lmr-10}[26 de marzo de 2021)]{.rm-lmr-10}

[^[6]{.cmr-7}^](#enmark-6){#ennote-6}[[https://www.facebook.com/AlgoritmiTorino/about/]{.rm-lmr-10}](https://www.facebook.com/AlgoritmiTorino/about/){.url}
[(Consultado el 26 de marzo de 2021)]{.rm-lmr-10}

[^[7]{.cmr-7}^](#enmark-7){#ennote-7}[[https://hubs.mozilla.com/]{.rm-lmr-10}](https://hubs.mozilla.com/){.url}
[(Consultado el 26 de ]{.rm-lmr-10}[marzo de 2021)]{.rm-lmr-10}

[^[8]{.cmr-7}^](#enmark-8){#ennote-8}[TOPLAP México: VR
Algorave]{.rm-lmr-10}
[[https://networkmusicfestival.org/programme/performances/toplap-mexico-vr-algorave/]{.rm-lmr-10}](https://networkmusicfestival.org/programme/performances/toplap-mexico-vr-algorave/){.url}
[(Consultado el 26 de marzo de 2021)]{.rm-lmr-10}

[^[9]{.cmr-7}^](#enmark-9){#ennote-9}[[https://www.youtube.com/c/Eulerroom/videos]{.rm-lmr-10}](https://www.youtube.com/c/Eulerroom/videos){.url}[(Consultado
]{.rm-lmr-10}[el 26 de marzo de 2021)]{.rm-lmr-10}

[^[10]{.cmr-7}^](#enmark-10){#ennote-10}[La documentación es escasa.
Ver:]{.rm-lmr-10}
[[https://www.instagram.com/p/B]{.rm-lmr-10}\_[bdw]{.rm-lmr-10}\_[TlrKa]{.rm-lmr-10}](https://www.instagram.com/p/B_bdw_TlrKa){.url}
[(Consultado el 26 de marzo de 2021), también:]{.rm-lmr-10}
[[https://medium.com/\@desyfree/musicaenvivocovid19-79e570a8f321]{.rm-lmr-10}](https://medium.com/@desyfree/musicaenvivocovid19-79e570a8f321){.url}
[(Consultado el 26 de marzo de 2021)]{.rm-lmr-10}

[^[11]{.cmr-7}^](#enmark-11){#ennote-11}[A-frame ]{.rm-lmri-10}[es "un
marco de trabajo ]{.rm-lmr-10}[para construir experiencias de realidad
virtual(VR)".]{.rm-lmr-10}
[[https://aframe.io/docs/1.2.0/introduction/]{.rm-lmr-10}](https://aframe.io/docs/1.2.0/introduction/){.url}
[(Consultado el 26 de marzo de 2021)]{.rm-lmr-10}

[^[12]{.cmr-7}^](#enmark-12){#ennote-12}["Laboratorio de
Experimentación, ]{.rm-lmr-10}[Improvisación y Nuevos
Medios".]{.rm-lmr-10}
[[https://www.instagram.com/si.nestes.ia/]{.rm-lmr-10}](https://www.instagram.com/si.nestes.ia/){.url}[(Consultado
]{.rm-lmr-10}[el 26 de marzo de 2021)]{.rm-lmr-10}

[^[13]{.cmr-7}^](#enmark-13){#ennote-13}[[https://zeyxlab.com/]{.rm-lmr-10}](https://zeyxlab.com/){.url}[(Consultado
el 26 de ]{.rm-lmr-10}[marzo de 2021)]{.rm-lmr-10}

[^[14]{.cmr-7}^](#enmark-14){#ennote-14}["El proyecto de three.js apunta
a la creación de ]{.rm-lmr-10}[una librería 3D fácil de usar, ligera,
multinavegador, ]{.rm-lmr-10}[multipropósito".
]{.rm-lmr-10}[[https://threejs.org/]{.rm-lmr-10}](https://threejs.org/){.url}
[(Consultado el ]{.rm-lmr-10}[26 de marzo de 2021)]{.rm-lmr-10}

[^[15]{.cmr-7}^](#enmark-15){#ennote-15}[[https://calindros.site/]{.rm-lmr-10}](https://calindros.site/){.url}
[(Consultado el 26 de ]{.rm-lmr-10}[marzo de 2021)]{.rm-lmr-10}

[^[16]{.cmr-7}^](#enmark-16){#ennote-16}[[https://echoic.space/]{.rm-lmr-10}](https://echoic.space/){.url}
[(Consultado el 26 de ]{.rm-lmr-10}[marzo de 2021)]{.rm-lmr-10}

[^[17]{.cmr-7}^](#enmark-17){#ennote-17}[[https://www.khronos.org/webgl/]{.rm-lmr-10}](https://www.khronos.org/webgl/){.url}[(Consultado
el ]{.rm-lmr-10}[26 de marzo de 2021)]{.rm-lmr-10}

[^[18]{.cmr-7}^](#enmark-18){#ennote-18}["La API de Audio Web provee un
sistema ]{.rm-lmr-10}[poderoso y versatil para controlar audio en
]{.rm-lmr-10}[la Web, permitiendo a los desarrolladores
]{.rm-lmr-10}[escoger fuentes de audio, agregar efectos al
]{.rm-lmr-10}[audio, crear visualizaciones de audios, aplicar
]{.rm-lmr-10}[efectos espaciales (como paneo) y mucho más."]{.rm-lmr-10}
[[https://developer.mozilla.org/es/docs/Web/API/Web]{.rm-lmr-10}\_[Audio]{.rm-lmr-10}\_[API]{.rm-lmr-10}](https://developer.mozilla.org/es/docs/Web/API/Web_Audio_API){.url}
[(Consultado el 26 de marzo de 2021)]{.rm-lmr-10}

[^[19]{.cmr-7}^](#enmark-19){#ennote-19}["WebAssembly es un nuevo tipo
de código que ]{.rm-lmr-10}[puede ser ejecutado en navegadores modernos
--- ]{.rm-lmr-10}[es un lenguaje de bajo nivel, similar al lenguaje
]{.rm-lmr-10}[ensamblador, con un formato binario
compacto".]{.rm-lmr-10}
[[https://developer.mozilla.org/es/docs/WebAssembly]{.rm-lmr-10}](https://developer.mozilla.org/es/docs/WebAssembly){.url}
[(Consultado el 26 de marzo de 2021)]{.rm-lmr-10}

[^[20]{.cmr-7}^](#enmark-20){#ennote-20}["WebSockets es una tecnología
avanzada que hace ]{.rm-lmr-10}[posible abrir una sesión de comunicación
interactiva ]{.rm-lmr-10}[entre el navegador del usuario y un
servidor."]{.rm-lmr-10}
[[https://developer.mozilla.org/es/docs/Web/API/WebSockets]{.rm-lmr-10}\_[API]{.rm-lmr-10}](https://developer.mozilla.org/es/docs/Web/API/WebSockets_API){.url}[(Consultado
]{.rm-lmr-10}[el 26 de marzo de 2021)]{.rm-lmr-10}

[^[21]{.cmr-7}^](#enmark-21){#ennote-21}["Nginx es un servidor web/proxy
inverso ligero de ]{.rm-lmr-10}[alto rendimiento".]{.rm-lmr-10}
[[https://es.wikipedia.org/wiki/Nginx]{.rm-lmr-10}](https://es.wikipedia.org/wiki/Nginx){.url}[(Consultado
el ]{.rm-lmr-10}[26 de marzo de 2021)]{.rm-lmr-10}

[^[22]{.cmr-7}^](#enmark-22){#ennote-22}["FFmpeg es el marco de trabajo
multimedia líder ]{.rm-lmr-10}[capaz de decodificar, codificar,
transcodificar, mux, ]{.rm-lmr-10}[demux, transmitir, filtrar y
reproducir casi cualquier ]{.rm-lmr-10}[cosa que los humanos o las
máquinas hayan creado".]{.rm-lmr-10}
[[https://www.ffmpeg.org/about.html]{.rm-lmr-10}](https://www.ffmpeg.org/about.html){.url}[(Consultado
el ]{.rm-lmr-10}[26 de marzo de 2021)]{.rm-lmr-10}

[^[23]{.cmr-7}^](#enmark-23){#ennote-23}[[https://twitter.com/notasausencia]{.rm-lmr-10}](https://twitter.com/notasausencia){.url}
[(Consultado el ]{.rm-lmr-10}[26 de marzo de 2021)]{.rm-lmr-10}

[^[24]{.cmr-7}^](#enmark-24){#ennote-24}["]{.rm-lmr-10}[The Wayback
Machine ]{.rm-lmri-10}[es una iniciative de ]{.rm-lmr-10}[Internet
Archive para construir una librería digital ]{.rm-lmr-10}[de sitios de
Internet y otros artefactos culturales en ]{.rm-lmr-10}[formato
digital".
]{.rm-lmr-10}[[http://web.archive.org/]{.rm-lmr-10}](http://web.archive.org/){.url}
[(Consultado el 26 de marzo de 2021)]{.rm-lmr-10}

[^[25]{.cmr-7}^](#enmark-25){#ennote-25}['la trascendencia de la
fisicalidad del mundo ]{.rm-lmr-10}[virtual nos permite extender nuestro
modo de ]{.rm-lmr-10}[operación en el mundo físico. Nuevas formas de
viaje, ]{.rm-lmr-10}[una nueva forma de comunicación, una nueva forma
]{.rm-lmr-10}[de operación, un nuevo medio de expresión"pp.
49]{.rm-lmr-10}

[^[26]{.cmr-7}^](#enmark-26){#ennote-26}["el arte no solamente podría
ser performeado en el ]{.rm-lmr-10}[plano sensorial, sino también en el
plano inteligible. ]{.rm-lmr-10}[Las estéticas de la participación y la
constitución ]{.rm-lmr-10}[de los medios digitales podrían intepretarse
como la ]{.rm-lmr-10}[continuación de algunos de esos prinicipios."pp
190]{.rm-lmr-10}

[^[27]{.cmr-7}^](#enmark-27){#ennote-27}[O Ludificación, del inglés
]{.rm-lmr-10}[gamification]{.rm-lmri-10}[. Para]{.rm-lmr-10}
[[Hamari]{.rm-lmr-10}](#Xgamificacion)[ (]{.rm-lmr-10}[[2019]{.rm-lmr-10}](#Xgamificacion)[)
existe la gamificación intencional y ]{.rm-lmr-10}[emergente. El
presente artículo hace referencia a ]{.rm-lmr-10}[la segunda: "la
gamificación se puede definir como ]{.rm-lmr-10}[un proceso cultural
gradual y emergente, aunque no ]{.rm-lmr-10}[intencional, derivada del
compromiso cada vez más ]{.rm-lmr-10}[generalizado con los juegos e
interacciones lúdicas."]{.rm-lmr-10}

[^[28]{.cmr-7}^](#enmark-28){#ennote-28}["El término cyberespacio puede
ser usado ]{.rm-lmr-10}[vagamente para describir la interconexión
espacial e ]{.rm-lmr-10}[invisible de computadoras en el Internet y es
aplicado ]{.rm-lmr-10}[a casi cualquier experiencia espacial y virtual
creada ]{.rm-lmr-10}[en una computadora"
(]{.rm-lmr-10}[[Frazer]{.rm-lmr-10}](#Xcyberspace)[, ]{.rm-lmr-10}[[2013]{.rm-lmr-10}](#Xcyberspace)[)]{.rm-lmr-10}

[^[29]{.cmr-7}^](#enmark-29){#ennote-29}["En ]{.rm-lmr-10}[Web
Audio]{.rm-lmri-10}[, espacializaciones complejas en ]{.rm-lmr-10}[3D
son creadas utilizando PannerNode, que en ]{.rm-lmr-10}[términos legos
básicamente son muchas matemáticas ]{.rm-lmr-10}[cool
]{.rm-lmri-10}[para hacer que el audio aparezca en un
]{.rm-lmr-10}[espacio 3D. Piensa en el audio volando sobre de
]{.rm-lmr-10}[ti, trepando atras de ti, moviéndose enfrente de
]{.rm-lmr-10}[ti"]{.rm-lmr-10}[[https://developer.mozilla.org/en-US/docs/Web/API/Web]{.rm-lmr-10}\_[Audio]{.rm-lmr-10}\_[API/Web]{.rm-lmr-10}\_[audio]{.rm-lmr-10}\_[spatialization]{.rm-lmr-10}\_[basics]{.rm-lmr-10}](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Web_audio_spatialization_basics){.url}
[(Consultado el 26 de marzo de 2021)]{.rm-lmr-10}

[^[30]{.cmr-7}^](#enmark-30){#ennote-30}[P2P ]{.rm-lmri-10}[(par a par)
por sus siglas en inglés. ]{.rm-lmr-10}["La arquitectura de una red
distribuida puede ]{.rm-lmr-10}[ser llamada Par a Par (P-to-P, P2P,
\...) si los ]{.rm-lmr-10}[participantes comparten una parte de los
recursos ]{.rm-lmr-10}[de su propio software (poder de procesamiento,
]{.rm-lmr-10}[capacidad de almacenamiento, capacidad de conexión
]{.rm-lmr-10}[a la red, impresoras,\...) Estos recursos compartidos
]{.rm-lmr-10}[son necesarios para proveer el Servicio y el contenido
]{.rm-lmr-10}[ofrecido por la red\... Estos son accedidos por
]{.rm-lmr-10}[otros pares directamente sin pasar por entidades
]{.rm-lmr-10}[intermediarias."(]{.rm-lmr-10}[[Schollmeier]{.rm-lmr-10}](#Xp2p)[, ]{.rm-lmr-10}[[2001]{.rm-lmr-10}](#Xp2p)[)]{.rm-lmr-10}
[]{#Q1-1-10}

### []{#x1-10000}[Referencias]{.rm-lmr-10x-x-109} {#referencias .likesectionHead}

::: {.thebibliography}
[ []{#Xdwc} [[   ]{.rm-lmr-10x-x-109}]{.bibsp} ]{.biblabel}[Choi, T.
(2018). Distributed web of care.]{.rm-lmr-10x-x-109}
[[http://distributedweb.care/]{.rm-lmr-10x-x-109}](http://distributedweb.care/){.url}[.]{.rm-lmr-10x-x-109}

[ []{#XcollinsLivecoding} [[   ]{.rm-lmr-10x-x-109}]{.bibsp}
]{.biblabel}[Collins, N., McLean, A., Rohruber, J., y
]{.rm-lmr-10x-x-109}[Ward, A. (2003). Live coding techniques for
]{.rm-lmr-10x-x-109}[laptop performance. ]{.rm-lmr-10x-x-109}[Organised
Sound]{.rm-lmri-10x-x-109}[, 8(3).]{.rm-lmr-10x-x-109}

[ []{#XspeakingCode} [[   ]{.rm-lmr-10x-x-109}]{.bibsp}
]{.biblabel}[Cox, G. y McLean, A. (2012). ]{.rm-lmr-10x-x-109}[Speaking
]{.rm-lmri-10x-x-109}[Code: Coding as Aesthetic and Political
]{.rm-lmri-10x-x-109}[Expression]{.rm-lmri-10x-x-109}[. The MIT
Press.]{.rm-lmr-10x-x-109}

[ []{#Xcamposonico} [[   ]{.rm-lmr-10x-x-109}]{.bibsp}
]{.biblabel}[diegodvc (2020). Camposonico.]{.rm-lmr-10x-x-109}
[[https://github.com/diegovdc/camposonico]{.rm-lmr-10x-x-109}](https://github.com/diegovdc/camposonico){.url}[.]{.rm-lmr-10x-x-109}

[ []{#Xanti} [[   ]{.rm-lmr-10x-x-109}]{.bibsp}
]{.biblabel}[EmilioOcelotl (2020a). anti.]{.rm-lmr-10x-x-109}
[[https://github.com/EmilioOcelotl/anti]{.rm-lmr-10x-x-109}](https://github.com/EmilioOcelotl/anti){.url}[.]{.rm-lmr-10x-x-109}

[ []{#Xthreestudies} [[   ]{.rm-lmr-10x-x-109}]{.bibsp}
]{.biblabel}[EmilioOcelotl (2020b). Three.studies.]{.rm-lmr-10x-x-109}
[[https://github.com/EmilioOcelotl/THREE.studies]{.rm-lmr-10x-x-109}](https://github.com/EmilioOcelotl/THREE.studies){.url}[.]{.rm-lmr-10x-x-109}

[ []{#Xtresestudios} [[   ]{.rm-lmr-10x-x-109}]{.bibsp}
]{.biblabel}[EmilioOcelotl (2020c).
]{.rm-lmr-10x-x-109}[tres-estudios-abiertos.]{.rm-lmr-10x-x-109}
[[https://github.com/EmilioOcelotl/tres-estudios-abiertos]{.rm-lmr-10x-x-109}](https://github.com/EmilioOcelotl/tres-estudios-abiertos){.url}[.]{.rm-lmr-10x-x-109}

[ []{#Xen-vivo}[[   ]{.rm-lmr-10x-x-109}]{.bibsp}
]{.biblabel}[federaciondecodigoalvuelo (2020).
en-vivo.]{.rm-lmr-10x-x-109}
[[https://github.com/federacion-de-codigo-al-vuelo/en-vivo]{.rm-lmr-10x-x-109}](https://github.com/federacion-de-codigo-al-vuelo/en-vivo){.url}[.]{.rm-lmr-10x-x-109}

[ []{#Xfeministserver}[[   ]{.rm-lmr-10x-x-109}]{.bibsp}
]{.biblabel}[Feminist-Server-Summit (2014). ]{.rm-lmr-10x-x-109}[A
feminist server manifesto 0.01.]{.rm-lmr-10x-x-109}
[[https://areyoubeingserved.constantvzw.org/Summit]{.rm-lmr-10x-x-109}\_[afterlife.xhtml]{.rm-lmr-10x-x-109}](https://areyoubeingserved.constantvzw.org/Summit_afterlife.xhtml){.url}[.]{.rm-lmr-10x-x-109}

[ []{#Xcyberspace}[[   ]{.rm-lmr-10x-x-109}]{.bibsp}
]{.biblabel}[Frazer, J. (2013). The architectural
]{.rm-lmr-10x-x-109}[relevance of cyberspace (1995). En Carpo,
]{.rm-lmr-10x-x-109}[M., editor, ]{.rm-lmr-10x-x-109}[The Digital Turn
in Architecture ]{.rm-lmri-10x-x-109}[1992--2012]{.rm-lmri-10x-x-109}[,
pp. 48--56. John Wiley and Sons,
]{.rm-lmr-10x-x-109}[Ltd.]{.rm-lmr-10x-x-109}

[ []{#Xgamificacion}[[   ]{.rm-lmr-10x-x-109}]{.bibsp}
]{.biblabel}[Hamari, J. (2019). Gamification. En
]{.rm-lmr-10x-x-109}[The ]{.rm-lmri-10x-x-109}[Blackwell Encyclopedia of
Sociology]{.rm-lmri-10x-x-109}[, pp. 1--3. ]{.rm-lmr-10x-x-109}[American
Cancer Society.]{.rm-lmr-10x-x-109}

[ []{#Xmanovichlanguage}[[   ]{.rm-lmr-10x-x-109}]{.bibsp}
]{.biblabel}[Manovich, L. (2001). ]{.rm-lmr-10x-x-109}[The Language of
New ]{.rm-lmri-10x-x-109}[Media]{.rm-lmri-10x-x-109}[. Leonardo (Series)
(Cambridge, Mass.). ]{.rm-lmr-10x-x-109}[MIT Press.]{.rm-lmr-10x-x-109}

[ []{#Xnotasdeausencia}[[   ]{.rm-lmr-10x-x-109}]{.bibsp}
]{.biblabel}[MarianneTeixido (2020).
notasdeausencia.]{.rm-lmr-10x-x-109}
[[https://github.com/MarianneTeixido/notasdeausencia]{.rm-lmr-10x-x-109}](https://github.com/MarianneTeixido/notasdeausencia){.url}[.]{.rm-lmr-10x-x-109}

[ []{#Xhydra}[[   ]{.rm-lmr-10x-x-109}]{.bibsp} ]{.biblabel}[ojack
(2020). hydra.]{.rm-lmr-10x-x-109}
[[https://github.com/ojack/hydra]{.rm-lmr-10x-x-109}](https://github.com/ojack/hydra){.url}[.]{.rm-lmr-10x-x-109}

[ []{#Xpanorama} [[   ]{.rm-lmr-10x-x-109}]{.bibsp}
]{.biblabel}[rexmalebka (2020). p2p-game-networking.]{.rm-lmr-10x-x-109}
[[https://github.com/rexmalebka/p2p-game-networking]{.rm-lmr-10x-x-109}](https://github.com/rexmalebka/p2p-game-networking){.url}[.]{.rm-lmr-10x-x-109}

[ []{#Xp2p} [[   ]{.rm-lmr-10x-x-109}]{.bibsp} ]{.biblabel}[Schollmeier,
R. (2001). A definition of ]{.rm-lmr-10x-x-109}[peer-to-peer networking
for the classification ]{.rm-lmr-10x-x-109}[of peer-to-peer
architectures and applications. ]{.rm-lmr-10x-x-109}[pp. 101 --
102.]{.rm-lmr-10x-x-109}

[ []{#XshankenCanon} [[   ]{.rm-lmr-10x-x-109}]{.bibsp}
]{.biblabel}[Shanken, E. A. (2010). Historicizing art
]{.rm-lmr-10x-x-109}[and technology: Forging a method and firing
]{.rm-lmr-10x-x-109}[a canon. En Grau, O., editor,
]{.rm-lmr-10x-x-109}[Media Art
]{.rm-lmri-10x-x-109}[Histories]{.rm-lmri-10x-x-109}[, pp. 43--70. The
MIT Press.]{.rm-lmr-10x-x-109}

[ []{#Xandreasosa} [[   ]{.rm-lmr-10x-x-109}]{.bibsp} ]{.biblabel}[Sosa,
A. (2017). Hello, world. The artist's ]{.rm-lmr-10x-x-109}[palette using
new media among atoms, bits, ]{.rm-lmr-10x-x-109}[and
]{.rm-lmr-10x-x-109}[connectivity. En Julián Jaramillo Arango,
]{.rm-lmr-10x-x-109}[Andrés Burbano, F. C. L. y Mejía, G. M.,
]{.rm-lmr-10x-x-109}[editores, ]{.rm-lmr-10x-x-109}[Proceedings of the
23rd International ]{.rm-lmri-10x-x-109}[Symposium on Electronic
Arts]{.rm-lmri-10x-x-109}[, pp. 187--201.
]{.rm-lmr-10x-x-109}[Departament of Visual Design, Universidad de
]{.rm-lmr-10x-x-109}[Caldas, ISEA International.]{.rm-lmr-10x-x-109}

[ []{#Xcuartopropio} [[   ]{.rm-lmr-10x-x-109}]{.bibsp}
]{.biblabel}[Zafra, R. (2020). Un cuarto propio
]{.rm-lmr-10x-x-109}[conectado. feminismo y creación
]{.rm-lmr-10x-x-109}[desde la esfera público-privada
online.]{.rm-lmr-10x-x-109}
[[https://www.remedioszafra.net/text]{.rm-lmr-10x-x-109}\_[rzafra10.pdf]{.rm-lmr-10x-x-109}](https://www.remedioszafra.net/text_rzafra10.pdf){.url}[.]{.rm-lmr-10x-x-109}
:::