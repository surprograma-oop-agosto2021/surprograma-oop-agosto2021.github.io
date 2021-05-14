---
title: 'Clase 4 - Primer parcial'
date: 2021-05-12
author: faloi
categories: [Clases]
tags: [kotlin, diseño]
videos:
  - id: 1wocpTNQ_yw
    nombre: Encuentro sincrónico del 12 de Mayo
entrega:
  fecha: "2021-05-25 23:59"
  ejercicios:
  - nombre: Ventas aéreas
    repo: obj2-unahur/ventas-aereas
    classroom: https://classroom.github.com/g/3kYcvZwW
    descripcion: >
      Presten especial atención a la distribución de requerimientos que explicamos más arriba.
---

Finalmente llegó el momento menos esperado de la cursada: el primer parcial. Haremos lo posible para que puedan transitar las siguientes dos semanas de la mejor manera posible.

## Algunos consejos

El ejercicio es de características similares a los que venimos realizando durante el curso, solo que un poco más extenso y con una distribución particular de las tareas, que explicaremos más abajo. La mayor extensión que tiene se compensa con que no se introduce nada que no hayan hecho en los ejercicios pasados, de forma tal que pueden resolverlo tranquilamente con lo que ya saben.

Para las partes que son grupales, les recomendamos que trabajen de la forma que les haya resultado buena hasta ahora, no es momento para innovar. Lo que sí les pedimos (una vez más) es que si trabajan con el Code with me o haciendo videollamada, roten cada cierto tiempo la persona que escribe. Lógicamente, en esta ocasión vamos a prestar mayor atención a quién hizo cada commit.

## Distribución de requerimientos

El enunciado tiene algunos requerimientos para resolver en equipo y otros para resolver de manera individual. Estos últimos están divididos en dos grupos, que llamamos (creativamente) A y B. Ustedes deciden quién es la persona A y quién la persona B, lo único que les pedimos es que cuando terminen comenten el _pull request_ explicitando quién asumió cada rol.

La distribución de requerimientos es la siguiente:

* **Requerimientos 1 al 5**: los resuelven en equipo.
* **Requerimientos 6 y 7**: los resuelve _solamente_ la persona A.
* **Requerimientos 8, 9 y 10**: los resuelve _solamente_ la persona B.
* **Bonus**: opcionales. En caso de realizarlos, los hacen de manera individual.

**Aclaración importante:** en todos los casos van a trabajar sobre el mismo repositorio, la división de requerimientos está armada de forma tal que no van a necesitar interactuar demasiado con la otra persona para implementarlos.

## Criterios de evaluación

Para aprobar, tienen que resolver como mínimo los requerimientos grupales más uno de los individuales, según los lineamientos que fuimos viendo a lo largo de estas primeras semanas. La nota final será individual, considerando tanto el aporte al trabajo grupal como el desarrollo de los requerimientos individuales.

Dejamos a continuación un pequeño resumen de los aspectos que vamos a mirar en la corrección:

* **Pruebas automatizadas.** Un requerimiento se compone de dos cosas: el código que lo resuelve y las pruebas que verifican su funcionamiento. Ambas son igual de importantes para esta materia, y la ausencia de alguna de ellas invalida el requerimiento.
* **Utilización de patrones de diseño.** Por ahora solo hablamos de `Strategy`, `Singleton` y `Companion object`, y deberían utilizarlos si el enunciado lo amerita. :eyes: Ojo acá: ni en este ejercicio ni en ningún otro hay que forzar el uso de patrones... solo los utilizan si corresponde.
* **Cualidades de diseño.** Principalmente, acoplamiento y cohesión, que son las que (quizás sin ponerle nombre) vienen trabajando desde Objetos 1. No mezquinen en la creación de objetos y métodos, dividan en subtareas cuando haga falta.
* **Manejo de colecciones.** No es un tema específico de esta materia, pero nos interesa que puedan aprender a utilizar herramientas de mayor nivel de abstracción. Ya tendrán tiempo para desplegar sus dotes algorítmicos en otros espacios.
* **Autoría de _commits_.** Los commits de las partes grupales tienen que estar más o menos balanceados, y los de las partes individuales ser exclusivos de la persona responsable.
