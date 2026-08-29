# Guion para la Presentación
# Sistemas Expertos

# Link del Video:
https://youtu.be/I6_c5m0kD1w

---

# Diapositiva 1. Portada

## Introducción

Buenos días.

Mi nombre es **Raúl Eduardo Covarrubias Ballester**, estudiante de **Ingeniería en Sistemas Computacionales**, con matrícula **220952**.

El día de hoy les voy a hablar de los Sistemas Expertos: qué son, cómo están construidos por dentro, qué papel juega el conocimiento en ellos, de dónde vienen históricamente, qué variantes existen y en qué se siguen usando hoy en día.

Es común pensar que la Inteligencia Artificial es algo nuevo, sobre todo con herramientas como ChatGPT o Gemini que se volvieron populares en los últimos años. Sin embargo, los Sistemas Expertos existen desde hace más de cinco décadas y fueron de los primeros casos donde la IA realmente funcionó fuera del laboratorio, algo que muchos sectores especializados siguen aprovechando hasta la fecha.

---

# Diapositiva 3. ¿Qué es un Sistema Experto?

Empecemos por lo básico: un Sistema Experto es un software que se construyó pensando en imitar la manera en que un especialista humano razona frente a un problema, apoyándose en el conocimiento que ese experto ha acumulado con los años.

Dicho de otra forma, no busca ser inteligente "en general", sino reproducir el criterio de una persona con experiencia en un tema muy puntual, para ayudar a que otros tomen mejores decisiones.

¿Qué lo distingue de un programa cualquiera? Varias cosas:

- Está enfocado en resolver un problema concreto, no problemas de cualquier tipo.
- Su forma de razonar se basa en reglas.
- No solo da una respuesta: también puede justificar por qué llegó a ella.
- Su conocimiento no es estático, se puede ampliar o corregir con el tiempo.
- Termina proponiendo una recomendación concreta al usuario.

Un caso que seguramente conocen son los sistemas que se usan en medicina para apoyar a los médicos a la hora de diagnosticar una enfermedad.

---

# Diapositiva 4. ¿Por qué surgieron los Sistemas Expertos?

Para entender por qué nacieron, hay que ubicarnos en los años sesenta y setenta.

En ese momento, distintas organizaciones se toparon con una limitación bastante real: los especialistas con verdadero dominio de un tema eran escasos, y cuando esa persona se jubilaba o cambiaba de trabajo, todo ese conocimiento acumulado prácticamente se perdía con ella.

A eso se sumaba otro problema: formar a un nuevo experto no era cosa de meses, sino de años, y mientras tanto, resolver ciertos casos complicados tomaba demasiado tiempo.

Fue así como surgió una idea que en su momento resultó bastante innovadora: ¿por qué no capturar ese conocimiento experto y guardarlo dentro de una computadora, de modo que cualquier persona pudiera consultarlo cuando lo necesitara, sin depender de que el especialista estuviera físicamente disponible?

---

# Diapositiva 5. ¿Qué es el conocimiento?

Si hay un elemento que sostiene todo Sistema Experto, ese es el conocimiento; sin él, simplemente no hay nada que el sistema pueda usar para razonar.

Vázquez (2009) lo explica desde la óptica de la Inteligencia Artificial, señalando que el conocimiento no es una sola cosa, sino una combinación de hechos, conceptos, procedimientos, reglas y relaciones que, juntos, permiten representar cómo funciona el mundo real.

Explicado de forma más cotidiana, el conocimiento es todo aquello que una persona ha ido acumulando a lo largo de su experiencia: lo que ha estudiado, lo que ha observado, lo que ha aprendido resolviendo problemas anteriores.

Ese conocimiento es justamente lo que se traslada al Sistema Experto y se guarda en su interior, para que más adelante pueda aplicarse cuando se presente una situación parecida.

---

# Diapositiva 6. Tipos de conocimiento

Dentro de un Sistema Experto, el conocimiento no es homogéneo; se puede clasificar en tres tipos.

### Conocimiento declarativo

Este primero contesta una pregunta muy simple: **¿qué sé?**

Se trata de hechos y conceptos, información que es verdadera independientemente del contexto.

Por ejemplo: "El agua hierve aproximadamente a 100 °C."

### Conocimiento procedimental

El segundo tipo responde a otra pregunta distinta: **¿cómo se hace?**

Aquí ya no hablamos de datos sueltos, sino de la secuencia de pasos necesaria para resolver algo.

Un ejemplo sería el procedimiento que se sigue para diagnosticar una enfermedad concreta.

### Metaconocimiento

El tercero es un poco más abstracto: es "conocimiento sobre el propio conocimiento".

Gracias a él, el sistema puede decidir:

- Cuál regla conviene aplicar.
- En qué momento aplicarla.
- Qué estrategia general seguir para resolver el problema.

Este tipo de conocimiento es justamente el que utiliza el Motor de Inferencia para razonar de manera más eficiente.

---

# Diapositiva 7. Ingeniería del Conocimiento

La Ingeniería del Conocimiento es, dentro de la Inteligencia Artificial, la disciplina encargada de tomar el conocimiento de un experto y convertirlo en algo que una computadora pueda usar, pasando por adquirirlo, representarlo, validarlo, aplicarlo mediante inferencia y mantenerlo actualizado.

En pocas palabras, su trabajo es hacer de "puente": tomar lo que sabe un especialista humano y traducirlo a un formato que el sistema pueda interpretar y procesar.

En este proceso intervienen tres actores clave:

- El experto humano, que aporta el conocimiento.
- El ingeniero del conocimiento, que lo extrae y lo organiza.
- El Sistema Experto, que finalmente lo almacena y lo utiliza.

---

# Diapositiva 8. Proceso de Ingeniería del Conocimiento

Construir un Sistema Experto no es un solo paso, sino que atraviesa cinco etapas bien definidas.

1. Primero, se adquiere el conocimiento directamente del experto.
2. Después, ese conocimiento se representa en reglas o estructuras que la computadora entienda.
3. Luego viene la validación, donde se comprueba que lo que se capturó sea correcto.
4. Sigue la inferencia, es decir, la aplicación de ese conocimiento para resolver un problema real.
5. Y finalmente, la explicación, donde el sistema justifica el porqué de su conclusión.

Cada una de estas etapas funciona como un filtro de calidad: si alguna se salta o se hace mal, el sistema puede terminar dando conclusiones poco confiables.

---

# Diapositiva 9. Base de Conocimiento

Si el Sistema Experto tuviera un corazón, ese sería la Base de Conocimiento.

Ahí es donde vive toda la experiencia capturada del especialista: los hechos que se conocen, las reglas que sigue, los conceptos y los procedimientos aplicables.

Para que quede más claro, veamos un ejemplo de regla:

**SI** un paciente tiene fiebre superior a 38 °C y además presenta tos,

**ENTONCES**

se considera que existe una posible infección respiratoria.

Reglas como esta son justo lo que después toma el Motor de Inferencia para llegar a una conclusión.

---

# Diapositiva 10. Representación del Conocimiento

Una vez que ya se tiene el conocimiento del experto, el siguiente reto es organizarlo de forma que la computadora pueda trabajar con él, porque no basta con "tenerlo": hay que darle una estructura.

Para eso existen varias técnicas comunes:

- Reglas de Producción.
- Redes Semánticas.
- Árboles de Decisión.
- Frames o Marcos.

Cada técnica organiza la información de una manera distinta, y la elección depende del tipo de problema que se quiera resolver.

---

# Diapositiva 11. Motor de Inferencia

El Motor de Inferencia es la parte del sistema que toma la información que entrega el usuario y la contrasta contra las reglas que están guardadas en la Base de Conocimiento.

Su tarea central es identificar cuáles reglas aplican a ese caso concreto y, a partir de ahí, construir una conclusión lógica.

Por esa razón, muchas veces se le describe como el "cerebro" del Sistema Experto: es la parte que efectivamente razona.

---

# Diapositiva 12. Métodos de Inferencia

Para razonar, el Motor de Inferencia puede apoyarse en dos estrategias distintas.

### Encadenamiento hacia adelante

Este método parte de los datos que ya se tienen disponibles y va aplicando reglas de manera sucesiva hasta llegar a una conclusión.

### Encadenamiento hacia atrás

Este otro funciona al revés: se parte de una hipótesis y luego se buscan evidencias que confirmen o descarten si esa hipótesis es correcta.

Con cualquiera de los dos métodos, el sistema logra llegar a decisiones de forma ordenada y lógica.

---

# Diapositiva 13. Arquitectura de un Sistema Experto

En conjunto, un Sistema Experto está integrado por cinco piezas principales:

- El usuario.
- La interfaz de usuario.
- La Base de Conocimiento.
- El Motor de Inferencia.
- El Módulo de explicación.

Ninguna de estas piezas funciona sola: es la combinación de todas ellas la que permite resolver problemas específicos de manera efectiva.

---

# Diapositiva 14. Línea del tiempo

Para entender cómo llegamos hasta aquí, conviene repasar brevemente la historia.

Todo arranca en 1956, año en que se reconoce oficialmente el nacimiento de la Inteligencia Artificial como disciplina, durante la famosa Conferencia de Dartmouth.

Años después, en 1965, aparece DENDRAL, que se considera el primer Sistema Experto que realmente tuvo éxito.

Para 1972 llega MYCIN, capaz de apoyar el diagnóstico de enfermedades infecciosas con un nivel de precisión notable.

Durante los años ochenta, los Sistemas Expertos vivieron su etapa de mayor expansión dentro del mundo empresarial.

Sin embargo, más adelante llegó lo que se conoce como el "AI Winter", un periodo donde el interés y la inversión cayeron debido a lo costoso que resultaba desarrollar estos sistemas.

Hoy en día, esa tecnología no desapareció, sino que se combina con enfoques más recientes como Machine Learning, Big Data e Inteligencia Artificial Generativa.

---

# Diapositiva 15. Tipos de Sistemas Expertos

No todos los Sistemas Expertos funcionan igual; existen distintas variantes según cómo procesan el conocimiento.

Están los basados en reglas, que trabajan con la lógica clásica de **SI... ENTONCES**.

Están los basados en casos, que en lugar de reglas fijas comparan el problema actual con experiencias previas ya resueltas.

Están los de lógica difusa, pensados para manejar información que no es exacta, sino aproximada.

Están los basados en redes neuronales, que aprenden a partir del entrenamiento con datos.

Y por último están los sistemas híbridos, que combinan varias de estas técnicas al mismo tiempo para obtener resultados más precisos.

De hecho, justo estos sistemas híbridos son, hoy en día, una de las líneas más relevantes dentro de la Inteligencia Artificial.

---

# Diapositiva 16. Bibliografía

Para armar esta presentación, la fuente principal fue el material complementario de Ingeniería del Conocimiento que se compartió durante el curso.

A eso se sumó bibliografía especializada sobre Inteligencia Artificial y Sistemas Expertos, que sirvió para reforzar tanto la parte histórica como los conceptos técnicos.

## Referencias

- Vázquez, J. (2009). *Ingeniería del conocimiento*. Material complementario del curso.

- Russell, S. J., & Norvig, P. (2021). *Artificial Intelligence: A Modern Approach* (4th ed.). Pearson.

- Feigenbaum, E. A. (1983). *The Art of Artificial Intelligence: Themes and Case Studies of Knowledge Engineering*. Stanford University.

- Jackson, P. (1998). *Introduction to Expert Systems* (3rd ed.). Addison-Wesley.

---

# Cierre

Con esto termino mi presentación.

Muchas gracias por su atención.
