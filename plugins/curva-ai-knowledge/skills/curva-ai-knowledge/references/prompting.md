# Prompting: fórmulas, patrones y técnicas

## Fórmulas de prompt - catálogo

> [!abstract] En una línea
> Todas las fórmulas de prompt de las lecturas en una tabla, para elegir según la tarea.

| Fórmula | Letras | Cuándo se usa | Fuente |
|---|---|---|---|
| **RTF** | Role, Task, Format | Tareas sencillas del día a día; solo ahorrar tiempo | Tec - ALIADO Prompt Engineering, PMI - Workbook Talking to AI |
| **CTF** | Context, Task, Format | Un caso o situación específica | Tec - ALIADO Prompt Engineering |
| **PECRA** | Purpose, Expectation, Context, Request, Action | La solicitud tiene un motivo que explicar | Tec - ALIADO Prompt Engineering |
| **CREATE** (Tec) | Character, Request, Examples, Adjustments, Type of output, Extras | Evitar contestar una y otra vez; interacciones eficientes | Tec - ALIADO Prompt Engineering |
| **CREATE** (PMI) | Character, Request, Examples, Adjustments & constraints, Types of output, **Evaluation & steps** | Tareas complejas | PMI - Workbook Talking to AI |
| **PAIN** | Problem, Action, Information, Next steps | Soluciones específicas paso a paso | Tec - ALIADO Prompt Engineering |
| **GRADE** | Goal, Request, Action, Detail, Examples | Respuesta de forma muy específica con ejemplos | Tec - ALIADO Prompt Engineering |
| **COAST** | Context, Objective, Actions, Scenario, Task | Solicitud compleja que cubre todo, del contexto a la tarea | Tec - ALIADO Prompt Engineering |
| **SPARK** | Situation, Problem, Aspiration, Results, Kismet | Explicar a fondo una situación y anticipar resultados | Tec - ALIADO Prompt Engineering |
| **SMART** | Specific, Measurable, Achievable, Relevant, Time-bound | Objetivos medibles para la IA | PMI - Workbook Talking to AI |
| **STAR** | Situation, Task, Action, Result | Entrevistas conductuales | PMI - Workbook Talking to AI |
| **ABCD** | Antecedent, Behavior, Consequences, Decision | Analizar conductas y decisiones | PMI - Workbook Talking to AI |
| **PEAR** | Problem, Experience, Action, Result | Reflexión estructurada del proyecto | PMI - Workbook Talking to AI |
| **SCARF** | Status, Challenges, Actions, Results, Feelings | Dinámica y motivación del equipo | PMI - Workbook Talking to AI |
| **Siete pasos de Emiliano Lombardero** | Contexto, rol, objetivo (SMART), tarea, segmento, tono de voz, formato | Prompt completo para trabajo real | Asistentes para ChatGPT (Lombardero, 2024) |
| **Cinco pasos de Google (TCREI)** | Tarea, contexto, referencias, evaluar, iterar | Prompting memorizable | Benchmark - Google |
| **Siete ingredientes** | Claridad, contexto, tono, público, palabras clave, resultado, retroalimentación | Público no técnico | Convierte Más - Guía para comunicarte con ChatGPT |

## Regla práctica (síntesis de Claude)
Tarea simple → RTF. Caso concreto → CTF. Algo complejo con formato exacto → CREATE o COAST. Con pasos → PAIN. Ver Un buen prompt es un brief completo.

## ⚠️ Pinzas
- Hay **dos CREATE distintos**: no mezclar.
- CREO y ROSES aparecen en el menú de Tec sin explicación en el archivo.
- Las letras de PEAR y STAR repiten parte del contenido de PAIN y SPARK: son variaciones, no marcos independientes validados.

## Patrones y técnicas de prompt

> [!abstract] En una línea
> Ocho patrones de conversación y tres técnicas que se mezclan «como ingredientes de una receta».

## Patrones (PMI)
| Patrón | Para qué |
|---|---|
| **Persona** | «Actúa como X»: la respuesta desde un rol |
| **Refinamiento de la pregunta** | La IA te propone una mejor pregunta |
| **Interacción invertida** | La IA **te pregunta** una por una hasta tener suficiente |
| **Enfoques alternativos** | Comparar opciones con pros y contras |
| **Verificador cognitivo** | Partir una pregunta compleja en preguntas más chicas y recombinar |
| **Lista de hechos** | Generar los hechos en que se basa la respuesta, con fuentes |
| **Generador de visualizaciones** | Pedir un prompt para otra herramienta de imagen |
| **Reflexión** | Explicar el razonamiento y los supuestos |

Más patrones del workbook: cadena de pensamiento, **cadena de retroalimentación**, árbol de pensamiento, autoconsistencia, ReAct, exploración de escenarios, matriz de riesgos y **rompe-rechazos** (pedirle que explique por qué no puede y proponga alternativas).

## Técnicas
**Zero-shot** (sin ejemplos), **few-shot** (con ejemplos de salida), **cadena de pensamiento** (pasos de razonamiento). Y **encadenar prompts**: dividir una tarea en subtareas, una o dos por vez.

## Para enseñar
Un buen sistema de prompts guardado y reutilizable es el paso siguiente: ver Skills de CURVA.

## ⚠️ Pinzas
- En el reporte de PMI, los ejemplos de la tabla de técnicas no ilustran la técnica (el de «few-shot» no trae ejemplos).
- En el workbook, «ReAct» y «Scenario exploration» tienen el mismo texto: parece error.
