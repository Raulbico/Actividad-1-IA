# Punto 7 resumen de los PDF de los siguientes

1. `0-ingenieria-del-conocimiento.pdf`
2. `C-sistemasExpertosBasadosEnReglas.pdf`

A continuación, presento un resumen detallado de los dos documentos proporcionados sobre la Ingeniería del Conocimiento y los Sistemas Expertos:

## **1. Ingeniería del Conocimiento (Documento 0)**

Este documento se centra en definir la **Ingeniería del Conocimiento (IC)** como una rama de la Inteligencia Artificial encargada de la adquisición, representación y procesamiento del conocimiento para construir **Sistemas Expertos (SE)**.

- **Conceptos Clave:** Define el **conocimiento** como una combinación de estructuras de datos y procedimientos interpretativos que permiten un comportamiento inteligente. Se distinguen tres tipos: **declarativo** (hechos), **procedural** (reglas de solución) y **metaconocimiento** (conocimiento sobre el propio conocimiento).

- **Roles Fundamentales:**
  - **Ingeniero del Conocimiento (ICO):** Especialista que extrae el conocimiento del experto y lo implementa en el sistema.
  - **Experto Humano:** Persona que aporta su experiencia y prestigio para el sistema.

- **Procesos de la IC:** El desarrollo consta de tres fases principales: **Adquisición** (extracción), **Representación** (codificación) y creación de la **Base de Conocimiento** (almacenamiento).

- **Etapas de Adquisición:** Identificación del problema, entendimiento de conceptos, formalización de la base, implementación (programación) y pruebas de validez.

- **Esquemas de Representación:** Para que el conocimiento sea inteligible por la computadora, se utilizan métodos como **lógica simbólica**, **redes semánticas**, **árboles de decisión**, **frames (marcos)** y **gráficos conceptuales**.

- **Métodos de Adquisición:** Pueden ser **manuales** (entrevistas, análisis de protocolos), **semiautomatizados** (herramientas de apoyo al experto o al ICO) o **automatizados** (inducción de reglas y aprendizaje automático).

## **2. Sistemas Expertos Basados en Reglas (Documento 1)**

Este documento profundiza en la estructura y el funcionamiento lógico de los **sistemas basados en reglas**, ideales para situaciones regidas por reglas deterministas.

- **Componentes del Sistema:**
  - **Base de Conocimiento:** Contiene las **reglas** (información permanente y estática).
  - **Memoria de Trabajo:** Almacena los **hechos** (información dinámica y específica de una situación).
  - **Motor de Inferencia:** Aplica la lógica para sacar conclusiones a partir de hechos y reglas.

- **Las Reglas:** Se definen mediante la estructura **"Si premisa (antecedente), entonces conclusión (consecuente)"**. Existen reglas simples y compuestas. Se menciona la **sustitución de reglas** para simplificar expresiones complejas sin perder generalidad.

- **Mecanismos de Inferencia:**
  - **Modus Ponens:** Se mueve hacia adelante, de la premisa a la conclusión.
  - **Modus Tollens:** Se mueve hacia atrás; si la conclusión es falsa, la premisa también lo es.
  - **Mecanismo de Resolución:** Combina y simplifica expresiones lógicas de múltiples reglas para obtener conclusiones compuestas.

- **Estrategias de Encadenamiento:**
  - **Encadenamiento de reglas (Hacia adelante):** Se parte de los hechos conocidos para generar nuevos hechos hasta alcanzar una conclusión.
  - **Encadenamiento orientado a un objetivo (Hacia atrás):** Se selecciona una variable objetivo y el sistema busca los hechos necesarios para validarla.

- **Control de Coherencia:** Es vital evitar información contradictoria tanto en las reglas como en los hechos aportados por el usuario para no obtener conclusiones absurdas.

- **Explicación de Conclusiones:** El sistema debe ser capaz de justificar sus resultados mostrando la lista de hechos y las reglas utilizadas para llegar a ellos.

- **Incertidumbre:** El documento concluye señalando que, aunque estos sistemas son deterministas, pueden extenderse mediante modelos probabilísticos para manejar la incertidumbre.