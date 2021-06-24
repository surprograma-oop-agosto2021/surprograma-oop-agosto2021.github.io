---
title: 'Clase 7 - Segundo parcial'
date: 2021-06-23
author: faloi
categories: [Clases]
tags: [kotlin, diseño]
videos:
  - nombre: Encuentro sincrónico del 23 de Junio
  - id: 0euzfH_NWE0
    nombre: Inyección de dependencias e impostores en Kotlin
    descripcion: >
      Mostramos cómo adaptar el código para que los tests no dependan de ningún servicio externo.
  - id: mFBKbBWRq_E
    nombre: Programando y testeando una aplicación de consola en Kotlin
    descripcion: >
      Una versión "objetosa" de cómo hacer una aplicación de consola, con tests incluidos.
lecturas:
  - url: https://docs.google.com/document/d/11mVR-4wEZhlQMDEqrfQeYLypEsrSqXv98dr78SA0Oq4/edit#heading=h.5bqwe0zgcgud
    title: Apunte sobre Testing
    summary: Un apunte muy completo relacionado al testing. En particular nos interesa que lean la sección **9. Impostores**, pero no vendría mal ojearlo completo.
entrega:
  fecha: "2021-07-06 23:59"
  ejercicios:
  - nombre: Países impostores
    repo: obj2-unahur/impostores-paises
    classroom: https://classroom.github.com/g/azxJUVRI
    descripcion: >
      Presten especial atención a los criterios que explicamos más arriba.
---

Finalmente llegó el segundo momento menos esperado de la cursada: el segundo parcial. Haremos lo posible para que puedan transitar las siguientes dos semanas de la mejor manera posible.

## Algunos consejos

El ejercicio tiene una parte que es de características similares a los que venimos realizando durante el curso, y otra que es completamente nueva. Les recomendamos **fuertemente** que resuelvan lo más rápido posible las primeras dos étapas, para poder concentrarse en las restantes.

En esta ocasión no haremos distribución de requerimientos individuales, pero sí se mantiene la exigencia sobre la paridad en los commits.

## Criterios de evaluación

Para aprobar, tienen que resolver como mínimo los requerimientos grupales más uno de los individuales, según los lineamientos que fuimos viendo a lo largo de estas primeras semanas. La nota final será individual, considerando tanto el aporte al trabajo grupal como el desarrollo de los requerimientos individuales.

Dejamos a continuación un pequeño resumen de los aspectos que vamos a mirar en la corrección:

* **Pruebas automatizadas.** Un requerimiento se compone de dos cosas: el código que lo resuelve y las pruebas que verifican su funcionamiento. Ambas son igual de importantes para esta materia, y la ausencia de alguna de ellas invalida el requerimiento.
* **Utilización de patrones de diseño.** deberían utilizarlos si el enunciado lo amerita. :eyes: Ojo acá: ni en este ejercicio ni en ningún otro hay que forzar el uso de patrones... solo los utilizan si corresponde.
* **Cualidades de diseño.** Principalmente, acoplamiento y cohesión, que son las que (quizás sin ponerle nombre) vienen trabajando desde Objetos 1. No mezquinen en la creación de objetos y métodos, dividan en subtareas cuando haga falta.
* **Manejo de colecciones.** No es un tema específico de esta materia, pero nos interesa que puedan aprender a utilizar herramientas de mayor nivel de abstracción. Ya tendrán tiempo para desplegar sus dotes algorítmicos en otros espacios.
* **Autoría de _commits_.** Los commits de las partes grupales tienen que estar más o menos balanceados, y los de las partes individuales ser exclusivos de la persona responsable.
