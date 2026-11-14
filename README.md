# IXA & ÁCATL

**IXA & ÁCATL** es una aventura narrativa de plataformas, histórica y mitológica, contada principalmente en primera persona por Ixa. La historia comienza en una comunidad marítima ficticia del extremo sur de la península de California y sigue la búsqueda de origen, pertenencia y libertad de Ixa, así como la relación que construye con Ácatl.

> **Aviso de spoilers:** este documento resume el argumento planeado hasta el epílogo, incluida la muerte de Ixa, su tránsito por el Mictlán y el desenlace de su relación con Ácatl.

> **Nota de ficción histórica:** el juego combina lugares, procesos y referencias históricas con pueblos, personajes, cronologías, símbolos y acontecimientos ficticios. Las tradiciones culturales no se presentan como equivalentes entre sí. Cuando el relato hace dialogar motivos de procedencias distintas, lo hace mediante personajes, desplazamientos e interpretaciones internas del mundo narrativo.

## Estado del proyecto

El repositorio contiene un prototipo web desarrollado en HTML, CSS y JavaScript. La versión jugable contempla:

- **Capítulo 1: `tepueg (1) - k-aha-l (agua)`**, con recorrido costero, fragmentos narrativos en primera persona, recolección de conchas, objetos que modifican la puntuación y transición mediante el faro.
- **Capítulo 2: `goguó (2) · Meyibó y majibel`**, con plataformas elevadas, objetos coleccionables, monolitos y municiones.
- **Capítulo 3: `goguó (3) · Orión`**, con degradado nocturno, la constelación de Orión y plataformas y monolitos móviles.
- **Capítulo 4: `magacubugua (4) · andemajuong galamata`**, con una cueva, plataformas móviles, estalagmitas y monolitos que persiguen a Ixa.

El resto de los actos descritos en este documento pertenece al diseño narrativo y no implica que todos los episodios estén implementados.

El encabezado y el HUD muestran **PRÓLOGO · Más allá del límite de todo lo que conozco** por encima del rótulo de cada capítulo.

La introducción ofrece botones para iniciar cualquiera de los cuatro capítulos. Elegir uno directamente reinicia sus contadores; los capítulos 3 y 4 comienzan con **55 puntos de energía**. Al avanzar en orden se conserva la energía acumulada.

El fondo del capítulo 1 puede activarse mediante `fondo-costero-intimo.png`. El capítulo 2 admite una imagen independiente mediante la variable `chapter2BackgroundImagePath` dentro de `index.html`.

## Premisa

### El pueblo de Ixa

Ixa crece en **Iyen**, una comunidad marítima ficticia situada en el extremo sur de la península de California. La identidad individual no se entiende allí como una propiedad aislada: depende del nombre pronunciado por otras personas, del territorio, de las tareas compartidas, de la memoria, de los cuidados recibidos y de las responsabilidades asumidas.

La tradición fundacional de Iyen afirma que sus antepasados llegaron desde el norte después de ser derrotados en una gran contienda. Perseguidos por sus vencedores, descendieron por la península y encontraron refugio entre montañas, manantiales y costas. También conocían vestigios de pueblos anteriores: figuras humanas y animales pintadas en cuevas por habitantes de gran estatura. Sin embargo, no sabían explicar con certeza quiénes habían sido esas personas ni por qué desaparecieron.

Esta memoria colectiva no funciona como una verdad histórica absoluta. Es una narración heredada que ofrece pertenencia, pero también deja silencios. Desde el comienzo, Ixa vive entre lo que su comunidad recuerda, lo que supone y lo que no puede demostrar.

### Ixa antes del viaje

Ixa fue rescatado durante la infancia y desconoce su procedencia. Naiyá, matriarca y navegante de Iyen, lo protege y lo cría hasta el umbral de la adolescencia. Ixa se aproxima a un rito de iniciación: deberá internarse durante la noche en un territorio silvestre y regresar al amanecer. La prueba no busca demostrar fuerza física únicamente; exige orientación, prudencia, observación y capacidad para decidir sin la presencia inmediata de la comunidad.

Desde niño, Ixa observa el cielo. Algunas veces relata sueños; otras, habla consigo mismo mediante soliloquios breves. Siente una fascinación particular por un lucero brillante, semejante a Sirio, al que termina llamando **la Piedrita del Cielo**. Ixa cree que el astro podría estar relacionado con su nacimiento y con el enigma de su ilegitimidad.

El lucero ofrece orientación, pero no una respuesta inequívoca. El conflicto surge cuando Ixa transforma una señal abierta en un mandato personal. La búsqueda de las brillantes formas muertas puede guiarlo, pero la interpretación obsesiva convierte el deseo en obediencia.

### Disolución de la comunidad

Los primeros capítulos presentan la vida cotidiana de Iyen, su relación con el agua, la reciprocidad, la desigualdad interna, las estrategias defensivas y los contactos con comunidades vecinas. La disputa por los manantiales y las rutas introduce la apropiación de recursos, el tributo, la autoridad y la expansión política.

Un ataque provoca la dispersión de Iyen. Ixa y Naiyá escapan por mar. La destrucción de la comunidad no es solo la pérdida de un escenario: rompe la red que sostenía el nombre, la memoria y el lugar de Ixa. A partir de entonces, el protagonista intenta comprender quién puede ser cuando casi nadie conoce su historia.

### Naiyá y la primera gran pérdida

Ixa y Naiyá cruzan el golfo y llegan a la región de los esteros de Sinaloa. Allí conocen otras formas de hospitalidad, intercambio, autoridad y organización. Durante una inundación provocada por un caudillo, Ixa decide abrir un paso para rescatar a varias familias. Naiyá sostiene la salida y muere para permitir que las personas atrapadas escapen.

La decisión de Ixa es moralmente defendible, pero produce una pérdida irreparable. La culpa no demuestra que Ixa haya actuado mal; muestra que una decisión justa también puede dejar dolor. Después del funeral, Ixa continúa solo.

### Encuentro con Ácatl

Durante el viaje por marismas, sierras, mercados y rutas de tributo, Ixa conoce a Ácatl. El primer encuentro es conflictivo: Ácatl roba un fragmento del remo de Naiyá. Una persecución y un peligro compartido obligan a ambos a cooperar.

Ácatl mira hacia el futuro. Desea construir una comunidad donde nadie tenga que demostrar pureza de origen para pertenecer. Ixa mira hacia el pasado y quiere recuperar su procedencia. La amistad nace sin borrar esa diferencia. Con el tiempo, ambos se reconocen como hermanos elegidos.

### La ciudad sobre el agua y la ciudad de los signos

Ixa y Ácatl llegan a México-Tenochtitlan, presentada como una ciudad de enorme complejidad material y política: calzadas, canales, mercados, barrios, escuelas, talleres, templos, tributos y jerarquías. Ixa esperaba encontrar allí una explicación sobre el lucero, pero la señal parece conducirlo hacia el oriente.

En la **ciudad de los signos**, un centro intelectual ficticio, conocen a Yaax y a Balam Ek. Yaax es astrónoma e intérprete; Balam Ek, observador del cielo y especialista ritual. El Sabio enseña que una visión puede contener verdad y engaño al mismo tiempo. También cuenta historias de Xbalanqué como ejemplos de astucia, transformación y regreso, sin identificar esas tradiciones con el Mictlán.

Balam Ek desmonta la expectativa heroica de Ixa: Ixa no es “el elegido”, sino una intersección entre caminos, memorias y conflictos.

### Amor, manipulación y ruptura

Ácatl y Yaax construyen una relación, forman una familia y tienen dos hijos. Sin embargo, Yaax teme perder a Ácatl y comienza a interpretar la cercanía entre Ixa y Ácatl como una amenaza. Azarel intensifica inseguridades ya existentes, pero no elimina la voluntad ni la responsabilidad de nadie.

Cuando Balam Ek descubre la manipulación, Yaax lo asesina y altera las pruebas. Después acusa a Ixa y consigue que Ácatl crea que su amigo traicionó al Sabio y puso en peligro a su familia. La traición no comienza con el golpe final, sino cuando el diálogo es sustituido por una interpretación cerrada.

Ácatl confronta a Ixa y lo hiere mortalmente con obsidiana. Ixa muere preocupado por que Ácatl viva creyendo que fue odiado.

### Los nueve umbrales

Tras morir, Ixa atraviesa nueve umbrales inspirados en la estructura nahua del Mictlán. Las historias de Xbalanqué que escuchó de Balam Ek operan como aprendizaje narrativo, no como equivalencia religiosa. Un perro guía a Ixa por pruebas relacionadas con memoria, nombre, frío, jaguares, obsidiana, futuros posibles y pérdida de identidad.

Ixa no regresa porque sea elegido. Los regentes de la muerte le permiten volver bajo condiciones: cada uso extraordinario de su poder consume un recuerdo; no puede salvar todos los futuros; debe elegir personas concretas en lugar de abstracciones; y la muerte volverá a reclamarlo cuando termine su tarea.

Al regresar, descubre que ha transcurrido un año. La ciudad de los signos fue saqueada y Yaax y Ácatl se encuentran vinculados a una congregación de pueblos asociados con los hombres de hierro.

### Xochiyáotl y la segunda vida

Durante el viaje, Ixa es atacado por una pantera negra. La guerrera jaguar **Xochiyáotl** lo rescata, vence al animal y utiliza la piel como parte de un atuendo ritual y militar. Xochiyáotl pertenece a un linaje ficticio asociado con relatos de Tollan y con una tradición guerrera jaguar; no se presenta como habitante literal del antiguo Estado tolteca.

Xochiyáotl acompaña a Ixa durante la recuperación, le enseña estrategia, combate, infiltración y responsabilidad colectiva. La relación se convierte en amistad, confianza y liderazgo compartido. Xochiyáotl se infiltra en la ciudad y comunica a Ácatl que Ixa sigue vivo.

### La Unión y los hombres de hierro

Ácatl huye con sus hijos y se aproxima a las alianzas orientales relacionadas con Xochiyáotl. Ixa, Ácatl y Xochiyáotl ayudan a formar **la Unión**, una alianza limitada entre comunidades que conservan diferencias y deliberan objetivos comunes.

Los hombres de hierro no se presentan como una fuerza homogénea. La invasión incluye españoles, aliados indígenas, intérpretes, cargadores, rivalidades preexistentes, tecnologías militares y diversos intereses políticos. La Unión enfrenta una estructura de conquista que aprovecha fracturas locales, resentimientos y ambiciones.

Durante una retirada inspirada en la llamada Noche Triste, Ixa puede alcanzar al jefe extranjero asociado con Hernán Cortés. Sin embargo, el centro filosófico del conflicto no consiste en asesinar a una sola persona. Azarel revela que los jefes vencidos durante el recorrido prepararon el camino hacia un enfrentamiento mayor: el dominio se reproduce cuando el miedo, la humillación y la promesa de orden son aceptados como destinos inevitables.

Azarel adopta imágenes religiosas e imperiales, promete restaurar a Naiyá, reconstruir Iyen, devolver a Ixa su origen y borrar la culpa de Ácatl. También afirma que llegarán más naves y que la conquista es inevitable. Ixa rechaza la oferta porque comprende que controlar la historia mediante una autoridad absoluta reproduciría aquello que intenta combatir.

### Desenlace

El enfrentamiento final entre Ixa y Ácatl no es una batalla física. Ácatl debe decir: “yo te maté”. La manipulación sufrida explica parte del proceso, pero no elimina la responsabilidad por haber elegido creer las acusaciones y actuar contra Ixa.

Ixa no borra el daño ni restaura la confianza de inmediato. El perdón impide que la herida determine necesariamente el siguiente acto, pero conserva la verdad, la responsabilidad y la necesidad de reparación.

La Unión resiste sin convertirse en un nuevo imperio. Ixa, Ácatl y sus aliados preparan una nave. **“Entonces no navegaré solo.”**

La voz narrativa cambia con la vida de Ixa: comienza con la sensorialidad de la infancia, atraviesa la incertidumbre adolescente, se fragmenta con la supervivencia y la muerte, se abre mediante la amistad y finalmente alcanza la perspectiva incompleta del resucitado. Ixa nunca se vuelve omnisciente. Cada comprensión nace de pérdidas, relaciones y decisiones.

## Principios de continuidad narrativa

Para mantener homogéneos los capítulos, el relato sigue estas reglas:

1. **Ixa narra desde lo que puede percibir.** No conoce motivaciones ajenas hasta que las escucha, las observa o las reconstruye con evidencia.
2. **La voz cambia gradualmente.** La infancia usa imágenes concretas; la adolescencia introduce contradicción; la supervivencia fragmenta el relato; la segunda vida incorpora memoria, responsabilidad y pérdida.
3. **Lo sobrenatural no cancela la agencia.** Los sueños, el lucero, el Mictlán y Azarel influyen, pero no sustituyen las decisiones humanas.
4. **Cada acto transforma una pregunta.** El argumento avanza cuando una idea cambia de significado, no solamente cuando Ixa llega a otro territorio.
5. **Los jefes encarnan problemas.** Una persecución, una negociación, una renuncia o una confesión pueden funcionar como enfrentamientos principales.
6. **Las culturas no son decorados intercambiables.** Cada tradición conserva contexto, lenguaje, instituciones y límites propios.
7. **El afecto no equivale a posesión.** Naiyá prepara a Ixa para elegir; Yaax convierte el miedo a perder en control; Ácatl debe aprender que sus hijos no son prolongaciones de sí mismo.
8. **La culpa no reemplaza la responsabilidad.** Sentirse culpable no demuestra inocencia ni reparación. La reparación exige verdad, reconocimiento y acciones posteriores.
9. **El origen no es destino.** La procedencia explica parte de Ixa, pero no determina su propósito.
10. **El horizonte permanece abierto.** El cierre no resuelve por completo la identidad; permite continuar sin exigir certeza absoluta.

## El título y sus protagonistas

### Ixa

Protagonista y conciencia narrativa principal. Criado por Naiyá en una comunidad marítima, mira hacia el origen y teme que abandonar la búsqueda equivalga a traicionar a sus muertos. Su arco lo lleva de obedecer al lucero a observarlo, interpretarlo y decidir por sí mismo.

### Ácatl

Mejor amigo, hermano elegido, rival y segundo protagonista. Es carismático, práctico, impulsivo y sensible a la humillación. Mientras Ixa desea recuperar el origen, Ácatl quiere construir una comunidad futura donde nadie deba demostrar pureza para pertenecer. La manipulación explica parte de su caída, pero no elimina su responsabilidad.

### El signo «&»

El signo no presenta a los protagonistas como mitades incompletas ni como una sola persona. Nombra una relación que atraviesa diferencia, intimidad, traición, separación y conflicto. Ixa y Ácatl conservan identidades propias, pero lo que construyen juntos no podría existir del mismo modo por separado.

## Personajes centrales

### Naiyá, la protectora

Matriarca y navegante que rescató y crió a Ixa. Sabe que otras personas siguieron el lucero y desaparecieron. Su cuidado prepara a Ixa para elegir en vez de retenerlo. Muere durante el rescate de familias atrapadas por la inundación de un estero.

### Yaax, la intérprete

Astrónoma, intérprete, figura afectiva y agente política. Ama a Ácatl, pero confunde conservar el vínculo con controlar el futuro. Asesina a Balam Ek y manipula pruebas contra Ixa. Azarel explota sus temores, pero Yaax conserva responsabilidad por sus decisiones.

### Balam Ek, el Sabio

Observador del cielo, especialista ritual y guía intelectual. Enseña que una visión puede ser verdadera y engañosa a la vez. Compara relatos, distingue tradiciones y alerta sobre nombres falsos. Transmite historias de Xbalanqué como inspiración para enfrentar pruebas y transformaciones.

### Xochiyáotl, la Jaguar

Guerrera de un linaje ficticio asociado con relatos de Tollan y una tradición militar jaguar. Es instructora, aliada y conciencia crítica. Ayuda a Ixa a sanar, informa a Ácatl que su amigo sigue vivo y participa en la construcción de la Unión.

### Azarel, el Soberano de las Mil Máscaras

Antagonista conocido por un nombre que emplea ante Ixa, no necesariamente por su nombre verdadero. También recibe títulos como el Lucero, el Consejero de los Imperios y el Adversario. Imita símbolos y voces, agranda heridas existentes y presenta el miedo, la ambición y la expansión como destino. No crea el mal ni controla completamente la voluntad: necesita conflicto previo, mentira parcial y aceptación.

## Estructura narrativa

La historia planeada comprende un prólogo, dieciséis actos y un epílogo. Los episodios enumerados pertenecen al diseño narrativo y no equivalen todavía a niveles implementados.

| Sección | Capítulos | Eje principal | Transformación de Ixa |
|---|---:|---|---|
| Prólogo | 1–2-3-4 | Agua, Tiempo, Tierra y Mente | Ixa deberá internarse durante la noche en un territorio silvestre y regresar al amanecer |
| Acto I | 5–10 | Identidad, comunidad y territorio | Descubre que su nombre depende de relaciones |
| Acto II | 11–17 | Separación, miedo y supervivencia | Aprende a renunciar para sobrevivir |
| Acto III | 18–29 | Hospitalidad, extranjería y pérdida | Actúa moralmente y pierde a Naiyá |
| Acto IV | 30–35 | Soledad y alteridad | Su nombre cambia frente a otras miradas |
| Acto V | 36–43 | Amistad y diferencia | Elige caminar con Ácatl sin compartir el mismo fin |
| Acto VI | 44–52 | Estado, tributo e imperio | Reconoce el costo político de la prosperidad |
| Acto VII | 53–61 | Interpretación y verdad | Descubre que no es el elegido |
| Acto VIII | 62–70 | Amor, posesión y miedo | Ve cómo el cuidado puede transformarse en cerrojo |
| Acto IX | 71–78 | Traición y muerte | Pierde la vida sin poder cerrar el vínculo |
| Acto X | 79–83 | Descomposición del ser | Regresa sin recuperar una identidad intacta |
| Acto XI | 84–93 | Verdad, sanación y rescate | Aprende a vivir después de su propia muerte |
| Acto XII | 94–98 | Alianza e invasión | Construye poder sin exigir uniformidad |
| Acto XIII | 99–108 | Historia e inevitabilidad | Enfrenta la tentación de controlar el curso histórico |
| Acto XIV | 109–115 | Libertad y responsabilidad | Rechaza la victoria absoluta ofrecida por Azarel |
| Acto XV | 116–122 | Perdón y reparación | Reconoce el daño sin dejar que determine el futuro |
| Acto XVI | 123–133 | Esperanza sin garantía | Aprende a navegar acompañado y sin certeza |
| Epílogo | 134.1–134.7 | Persistencia y horizonte | Comprende el origen como construcción compartida |

## Resumen de los actos

### Prólogo — La voz en el cielo

Desde un momento posterior a su regreso de la muerte, Ixa recuerda los luceros de la infancia y la voz del abuelo en sueños. El mandato “sígueme” inicia la obsesión. El Abuelo de Luz es un encuentro onírico; el jugador puede acercarse, huir, preguntar o callar.

### Acto I — El lugar donde yo tenía un nombre

Ixa conoce su lugar en Iyen, el cuidado de Naiyá, el agua como responsabilidad y el conflicto por recursos. El ataque dispersa la comunidad y obliga a Ixa a escapar por mar.

### Acto II — El mar que no quería dejarnos pasar

Ixa y Naiyá cruzan el golfo con hambre, heridas y orientación incierta. Azarel utiliza la voz del abuelo para atraer a Ixa al agua. Una tormenta obliga a renunciar a pertenencias para sobrevivir.

### Acto III — La tierra de los esteros

Ambos conocen a la comunidad totorame y a Chiametlán. La hospitalidad convive con disputas por rutas y recursos. Ixa rescata a familias durante una inundación; Naiyá muere sosteniendo el paso.

### Acto IV — Los caminos que cambiaban mi nombre

Ixa viaja solo por marismas, sierras, valles de obsidiana y rutas de tributo. Aprende cooperación, escucha, lectura de registros, deuda y límites de la imagen.

### Acto V — Ácatl

Ácatl roba el fragmento del remo de Naiyá. El peligro compartido convierte la persecución en alianza. Ambos reconocen que desean futuros distintos, pero deciden caminar juntos.

### Acto VI — La ciudad sobre el agua

México-Tenochtitlan muestra organización, prosperidad, tributo, exclusión y obediencia militar. Ixa no encuentra una respuesta definitiva y continúa hacia el oriente.

### Acto VII — La ciudad de los signos

Ixa y Ácatl conocen a Yaax y Balam Ek. El Sabio cuestiona las interpretaciones cerradas y revela que Ixa no es el elegido, sino una intersección.

### Acto VIII — El amor que quiso convertirse en cerrojo

Ácatl y Yaax forman una familia. El miedo de Yaax transforma el cuidado en control. Balam Ek descubre la manipulación; Yaax lo asesina y altera las pruebas.

### Acto IX — La muerte de Ixa

Ácatl cree las acusaciones contra Ixa. La confrontación escala hasta que Ácatl lo hiere mortalmente. Ixa muere sin poder reparar el vínculo.

### Acto X — Los nueve umbrales de la muerte

Ixa atraviesa el Mictlán y pierde posesiones, certezas, nombres y futuros ideales. Regresa bajo condiciones que limitan su poder y preservan el costo de la muerte.

### Acto XI — La Jaguar y las ciudades del oriente

Xochiyáotl rescata y entrena a Ixa. Juntos recorren territorios asociados con Puebla, Cholula y Tlaxcala. La verdad sobre Balam Ek confronta a Ácatl con su responsabilidad.

### Acto XII — Los hombres de hierro

La invasión combina tecnología, alianzas, traducción y conflictos locales. Ixa, Ácatl y Xochiyáotl construyen la Unión, una alianza que distribuye decisiones y conserva diferencias.

### Acto XIII — La Noche Triste de los conquistadores

Durante el sitio y la retirada bajo la lluvia, Ixa puede alcanzar al jefe extranjero. El lucero desciende y Azarel abandona el rostro del abuelo.

### Acto XIV — Los dioses que abrieron la puerta

Azarel afirma que las fracturas entre poderes antiguos hicieron posible su influencia. Ofrece restauraciones imposibles y una victoria absoluta. Ixa rechaza controlar la historia mediante otro imperio.

### Acto XV — Ixa & Ácatl

Ácatl reconoce: “yo te maté”. Ixa no borra el daño, pero evita que la herida determine todo lo que serán. La responsabilidad abre la posibilidad de reparación.

### Acto XVI — La nave del horizonte

La victoria es incompleta. Permanecen personas, relatos, hijos, rutas y decisiones. Ixa, Ácatl y sus aliados preparan una nave hacia un destino no revelado.

### Epílogo — La Unión y las mil máscaras

Azarel adopta otra máscara frente a otro gobernante. En la nave, la confianza sigue herida. La Piedrita parece dividirse en dos. Ixa comprende que el origen también vive en aquello que todavía pueden construir juntos.

## Diseño narrativo y sistema de jefes

Los jefes representan problemas y estructuras, no solamente enemigos con mayor resistencia:

- **Territoriales:** agua, alimento, rutas, tributo, propiedad y fronteras.
- **Comunitarios:** autoridad, obediencia, tradición, exclusión y control social.
- **Espirituales:** miedo, culpa, deseo, memoria, muerte e interpretación.
- **Relacionales:** conflictos que no siempre deben resolverse mediante la muerte.
- **Históricos:** ejércitos, alianzas, tecnologías e instituciones.
- **Ontológicos:** pruebas que exigen aceptar una verdad, renunciar a una identidad, preservar un recuerdo o elegir sin garantías.

Una persecución, una negociación, un rescate, una confesión o una renuncia pueden tener la misma relevancia que un combate. Azarel no es derrotado físicamente de manera definitiva; se debilita cuando las personas dejan de convertir heridas y deseos en mandatos inevitables.

## Marco ontológico

### Identidad

La identidad de Ixa se compone de herencia, comunidad, lengua, territorio, memoria, relaciones, pérdidas y decisiones. Su arco pasa de “nací en mi pueblo” a “sobreviví a mi pueblo” y finalmente a “decido qué hacer con lo que sobrevivió dentro de mí”.

### Relación entre Ixa y Ácatl

Los protagonistas no son mitades incompletas. El vínculo significa cercanía sin fusión, diferencia sin enemistad, responsabilidad sin propiedad y amistad sin obediencia. **Ixa + Ácatl no es una sola persona; Ixa & Ácatl es una relación transformadora entre dos libertades.**

### La estrella

La Piedrita existe como fenómeno celeste, obsesión, símbolo cultural y abertura metafísica aprovechada por Azarel. El antagonista se interpone entre la señal y quien la observa, y reviste el mensaje con recuerdos ajenos.

### Profecía y libertad

La profecía no describe necesariamente un futuro cerrado; induce conductas:

```text
lucero → interpretación → obsesión → viaje → encuentro → conflicto → acontecimiento
```

Ixa recupera agencia cuando distingue lo observado, lo escuchado, lo interpretado y lo decidido.

### Cuidado

Naiyá representa un cuidado que prepara a otra persona para vivir sin ella. Proteger no significa retener, sino enseñar a elegir.

### Culpa y responsabilidad

La culpa de Ixa nace de salvar a otras personas y perder a Naiyá. La culpa de Ácatl nace de matar a Ixa. La primera es trágica; la segunda es moral y relacional. La manipulación sufrida por Ácatl no elimina la responsabilidad por sus actos.

### Amor

El relato distingue amor comunitario, protector, fraternal, romántico, posesivo, responsable y liberador. El amor deja de ser cuidado cuando destruye la libertad del otro para conservarlo.

### Muerte

La muerte descompone las identidades de Ixa. El protagonista pierde posesiones, origen único, interpretaciones cómodas, recuerdos, control, futuros ideales, nombre y certeza. Persiste la capacidad de responder ante otra persona.

### Estado e imperio

El Estado puede organizar, proteger, registrar, construir y educar; también puede recaudar, castigar y conquistar. El imperio aparece como una relación de:

```text
concentración de poder + subordinación + extracción + relato legitimador
```

### Mal

Azarel es parasitario, no omnipotente:

```text
poder de Azarel = conflicto previo + mentira parcial + aceptación
```

Su arma más eficaz es una verdad incompleta.

### Perdón

Perdonar no significa olvidar, justificar ni restaurar de inmediato la confianza:

```text
herida → verdad → responsabilidad → reparación posible
```

### Unión

La Unión es una alternativa al imperio. Reconoce diferencias, distribuye decisiones, delibera, acuerda y limita sus objetivos. Al no depender de un centro único, resiste mejor la manipulación y la decapitación del poder.

### Origen y horizonte

La isla ancestral puede explicar de dónde viene Ixa, pero no quién debe ser. **El origen explica la procedencia, no determina el propósito.** El horizonte representa el límite móvil entre lo conocido, lo imaginado y lo posible. La madurez no consiste en alcanzarlo, sino en navegar sin exigir que deje de desplazarse.

## Prototipo jugable y controles

### Capítulo 1

- Rótulo actual del HUD: **`tepueg (1) - k-aha-l (agua)`**.
- Trayecto extendido hasta el faro.
- Siete diálogos interiores de Ixa, activados al alcanzar su posición `X` y una vez por recorrido:

| X | Título | Contexto |
|---:|---|---|
| 1 | Las manos que me hicieron un lugar | Ixa inicia su camino hacia la madurez, habla de las piedritas del costal e invita a acompañarlo al faro. |
| 700 | Auka Sum/San (Hola hermano(a)) | El nombre de Ixa también vive en las voces de quienes lo corrigen y esperan su regreso. |
| 1650 | Aguina (Vive) | Ixa recuerda que siguió caminando aunque nadie respondiera quién era. |
| 2800 | Lo que una huella no dice | Naiyá le enseña a observar las huellas sin imponerles una interpretación. |
| 4050 | El agua de quienes aún no nacen | Ixa reflexiona sobre cuidar el agua y el mundo para las generaciones futuras. |
| 5350 | Hablar y ser escuchado | Ixa reconoce que, en su comunidad, algunas voces pesan más que otras. |
| 6500 | La parte de mí que mira lejos | Ixa expresa su temor y emoción ante la posibilidad de partir o quedarse. |

- Perlas azules: **+10**.
- Objetos rojos provisionales: **−7**.
- Cada objeto se contabiliza una sola vez.
- La energía acumulada se conserva al pasar al capítulo 2.
- El faro marca el final del recorrido y la transición narrativa al capítulo 2.

### Capítulo 2

- Rótulo actual del HUD: **`goguó (2) · Meyibó y majibel`**.
- Plataformas elevadas.
- Perlas azules coleccionables.
- Perlas rojas que restan energía.
- Monolitos que hacen retroceder a Ixa.
- Municiones lanzables: el capítulo comienza explicando que se pueden disparar con `F`, `X` o el botón táctil para derribar los monolitos.
- Cada monolito desaparece al recibir **13 impactos**; los demás permanecen. Al destruir cada uno, otorga **10 puntos de energía**.
- Se comienza con **13 municiones**. Al alcanzar **100 puntos de energía**, la capacidad aumenta a **21**. Las municiones se recargan automáticamente 5 segundos después del último disparo.
- La energía acumulada en el capítulo 1 se conserva al entrar; también se conserva al pasar al capítulo 3.
- El pozo marca el final del recorrido.
- Siete diálogos interiores, activados al alcanzar su posición `X` y una vez por recorrido:

| X | Título | Contexto |
|---:|---|---|
| 1 | Hola de nuevo | Introduce las municiones, los controles de disparo, la recarga, que cada monolito desaparece tras 13 impactos y la recompensa por destruirlo. |
| 700 | *(sin título)* | Ixa reflexiona sobre su identidad y el paso del tiempo a través de los nombres de quienes lo esperan. |
| 1650 | El alma inamovible | Ixa percibe un amor profundo y recuerda a quien lo vio crear. |
| 2800 | Ante la adversidad soñar curará las heridas. | Ixa piensa en adaptarse al espíritu del tiempo para enfrentar la adversidad. |
| 4050 | El vaivén de las olas | Soltar se compara con entregarse al mar y dejar ir lo que ya no se puede sostener. |
| 5350 | Ese lindo rincón en el cielo | Ixa pregunta quién debe ser y reconoce que su origen no determina su futuro. |
| 6500 | Intensa gratitud | Ixa agradece la compañía y reflexiona sobre empezar a soltarse. |

### Capítulo 3

- Rótulo actual del HUD: **`goguó (3) · Orión`**.
- Fondo nocturno de degradado oscuro, estrellas y una representación de la constelación de Orión.
- Plataformas elevadas y monolitos que se desplazan durante el recorrido.
- La energía se conserva desde el capítulo 2. Las perlas azules y la derrota de los monolitos suman **10**; las perlas rojas restan **7**. Caer o chocar con un monolito resta **5**.
- Los disparos se pueden lanzar con `F`, `X` o el botón táctil. Cada monolito desaparece al recibir **13 impactos**; los demás siguen activos. Destruir cada uno otorga **10 puntos de energía**.
- La capacidad inicia en **13 municiones** y aumenta a **21** al alcanzar **100 puntos de energía**.
- Si la energía llega a **0**, Ixa muere y el recorrido se reinicia desde el inicio del capítulo 3, restaurando la energía con la que entró a ese capítulo.
- La entrada de la cueva marca el final del recorrido. Al completarlo aparece el final, con opción para repetir este capítulo.
- Siete diálogos interiores, activados al alcanzar su posición `X` y una vez por recorrido:

| X | Título | Contexto |
|---:|---|---|
| 1 | Bajo el cielo de Orión | Presenta las plataformas y los monolitos móviles, el sistema de energía, las perlas y las reglas de munición. |
| 1150 | Dar forma a lo que necesito | Ixa reconoce sus necesidades y piensa en el ikigai como una estructura flexible para orientar sus decisiones. |
| 2300 | Dos fuerzas que aprenden a convivir | Reflexiona sobre integrar sus energías masculina y femenina sin quedar limitado por estereotipos. |
| 3450 | La sensibilidad también me guía | Convierte su sensibilidad en una herramienta de comprensión, cuidando sus propios límites. |
| 4600 | Cuidar el lugar que compartimos | Vincula el bienestar y la seguridad de la comunidad con la confianza y el cuidado colectivo. |
| 5750 | Elegir cómo responder | Explora la asertividad, la pausa y el momento de tener conversaciones incómodas. |
| 6900 | Atender mis heridas sin perder el rumbo | Reconoce heridas y traumas sin reducirse a ellos, y propone entrenar a diario la consciencia y la atención. |

### Capítulo 4

- Rótulo: **`magacubugua (4) · andemajuong galamata (Ha llovido en la noche)`**.
- Fondo de cueva y plataformas móviles.
- No hay perlas azules. Las estalagmitas y los monolitos restan **5 puntos de energía**; los monolitos se desplazan hacia Ixa.
- Las municiones comienzan en **13** y aumentan a **21** al alcanzar **100 puntos de energía**. Cada monolito desaparece tras **13 impactos** y devuelve **10 puntos de energía**.
- Al recibir daño, el estado inferior muestra una frase de duda o tristeza acompañada de una respuesta que anima a avanzar con cuidado y buscar apoyo.
- La energía se conserva al llegar desde el capítulo 3; al elegir el capítulo directamente comienza con **55 puntos de energía**. Si llega a **0**, el recorrido se reinicia desde el comienzo del capítulo.
- Siete diálogos interiores, activados al alcanzar su posición `X` y una vez por recorrido:

| X | Título | Contexto |
|---:|---|---|
| 1 | Lo que temo nombrar | Ixa reconoce el temor de entrar en la cueva y se permite avanzar despacio y escuchar lo que siente. |
| 1100 | La tristeza que guardo | Nombra una tristeza silenciosa y recuerda que merece compañía y descanso. |
| 2200 | El miedo a perderme | Observa el temor a perder nombres, voces y lugares, sin dejar que decida cada paso. |
| 3300 | Mi cuerpo también recuerda | Reconoce la memoria corporal del miedo y elige un paso que la cuide. |
| 4400 | Lo que necesito decir | Se permite hablar de su tristeza y pedir compañía. |
| 5500 | No soy solo mis pérdidas | Acepta que sus pérdidas forman parte de su historia, pero no la definen por completo. |
| 6600 | Un paso en la oscuridad | Avanza con cuidado sin exigirse dejar de sentir miedo. |

### Controles

- `A` / `D` o flechas: caminar.
- `W`, flecha arriba o barra espaciadora: saltar.
- `F` o `X`: lanzar munición en los capítulos 2, 3 y 4.
- En dispositivos táctiles aparecen controles en pantalla, incluido el botón para disparar.

## Archivos del juego

Mantén los recursos utilizados por `index.html` en la raíz del repositorio:

```text
index.html
ixa-sprites-v4.png
plataforma-costera.png
fondo-costero-intimo.png
README.md
```

Otros fondos, como `fondo-atardecer.png`, `fondo-costero.png` y `fondo-costero-v2.png`, pueden conservarse como recursos alternativos si el código los utiliza explícitamente.

## Publicación en GitHub Pages

1. Sube los archivos a la rama `main`.
2. Abre **Settings > Pages** en el repositorio.
3. Selecciona **Deploy from a branch**.
4. Elige la rama `main` y la carpeta `/ (root)`.
5. Guarda los cambios.

## Referencias de desarrollo

- [Vocabulario cochimí](https://es.scribd.com/document/648492995/vocablo-cochimies#google_vignette)
- [Ejemplo de raycasting en JavaScript](https://github.com/chrisgamedev/javascript-raycaster/blob/10b0683be841f77b633836a1bc056df36a6b4d71/Raycaster/js/functions.js)

## Criterio para futuras revisiones

Antes de integrar un nuevo capítulo, conviene verificar cuatro continuidades:

1. **Cronológica:** edad de Ixa, tiempo transcurrido, desplazamientos y consecuencias previas.
2. **Epistemológica:** qué sabe Ixa, cómo lo sabe y qué permanece como interpretación.
3. **Ontológica:** qué idea sobre identidad, libertad o responsabilidad transforma el capítulo.
4. **Mecánica:** qué acción jugable expresa esa transformación sin reducirla a una explicación textual.
