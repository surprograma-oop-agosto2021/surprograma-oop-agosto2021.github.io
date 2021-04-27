---
title: 'Clase 3 - Hablemos de diseño de software'
date: 2021-04-28
author: faloi
categories: [Clases]
tags: [kotlin, diseño, patrones de diseño]
lecturas:
  - url: https://docs.google.com/document/d/14HdvHvS33WqYb6Ak0BGa0IeCTbzeCRSDKs-1Ot-qLDw/edit?usp=sharing
    title: Cualidades de diseño
    summary: Algunos criterios para analizar diseños, que vamos a utilizar como métricas para corregir los trabajos de esta materia. En particular, para esta entrega van a tener que trabajar intensamente con los que están en la sección [Cualidades que se pueden estudiar con cierta independencia tecnológica](https://docs.google.com/document/d/14HdvHvS33WqYb6Ak0BGa0IeCTbzeCRSDKs-1Ot-qLDw/edit#heading=h.5ntffpcf14xd).
  - url: https://docs.google.com/document/d/1uXPhuAKXa4wzcIhriFfnI53aB311jOZtcKfTDuiKQ8Y/edit?usp=sharing
    title: Introducción a los patrones de diseño
    summary: Qué son y qué no son los patrones de diseño. Concentra lo que vinimos diciendo desde el comienzo de la materia, con algunas reflexiones interesantes y referencias para ampliar el panorama.
  - url: https://refactoring.guru/es/design-patterns/strategy
    title: Patrón "Strategy"
    summary: Un patrón que seguramente ya usaron, formalizado con nombre y apellido.
  - url: https://refactoring.guru/es/design-patterns/singleton
    title: Patrón "Singleton"
    summary: Otro patrón que ya conocían, pero con otro nombre.
videos:
  - nombre: Encuentro sincrónico del 28 de Abril
    descripcion: >
      Hablamos de los errores comunes de la clase anterior y presentamos esta clase.
  - id: ibmQkhAzk5I
    nombre: Trabajo en equipo y resolución de conflictos de Git desde el IntelliJ Idea
    descripcion: >
      La guía definitiva (o algo así) para trabajar en equipo en Git y no morir en el intento.
  - id: AuInib0a4h0
    nombre: "Code with me: trabajo colaborativo remoto en el IntelliJ Idea"
    descripcion: >
      Una linda funcionalidad .
  - id: VQ8V0ym2JSo
    nombre: Breve explicación del patrón Strategy
    descripcion: >
      Un español barbudo que, a nuestro juicio, explica de forma muy clara los patrones de diseño. Utiliza porciones de código en Typescript (primo tipado de Javascript), que no deberían resultarles tan difícil de leer.
  - id: U4D3625aisA
    nombre: ¿Cómo implementar el patrón Singleton en Kotlin?
    descripcion: >
      Un nombre rimbombante para algo que ya sabían hacer desde Objetos 1: crear un objeto sin clase. :stuck_out_tongue:
  - id: NGUVwHb-1Fk
    opcional: true
    nombre: ¿Qué son y para qué sirven las cualidades de diseño de software?
    descripcion: >
      Lo mismo que dice el apunte, pero explicado durante una clase en vivo del 2020.
  - id: rRnpygnXhwY
    opcional: true
    nombre: Interface VERSUS clase abstracta en Kotlin
    descripcion: >
      Diferencias, similitudes y cuándo conviene usar cada una.
entrega:
  fecha: "2021-05-11 23:59"
  ejercicios:
  - nombre: Buscando defectos en el ejercicio "Semillas al viento"
    repo: obj2-unahur/semillas-al-viento-defectos
    classroom: https://classroom.github.com/g/LDdqtwJk
  - nombre: Mozo, ¡la cuenta!
    repo: obj2-unahur/semillas-al-viento-defectos
    classroom: https://classroom.github.com/g/LDdqtwJk
    descripcion: >
      Micro ejercicio para terminar de entender el patrón Strategy. Al ser tan chico, recomendamos resolverlo de manera sincrónica - una buena excusa para probar el _Code with me_. :wink:
---


## Objetivos de la clase

* Introducir la noción de cualidad de diseño y su utilidad para evaluar comparativamente soluciones
* Definir qué es un patron de diseño, sus ventajas y desventajas y cuándo es conveniente aplicarlo.
* Formalizar los patrones Strategy y Singleton.

## No todo es programar

Como verán, esta clase viene un poco más _teórica_ que las anteriores y es que, efectivamente, no todo en este oficio es programar. También es necesario saber cuándo parar la pelota y reflexionar: ¿este problema podría resolverse de otra forma? ¿por qué, o mejor dicho, en qué aspectos esta solución es mejor que otra?

Además de profundizar en el conocimiento sobre el paradigma de objetos, en este curso nos interesa **ampliar el vocabulario** y poder **nombrar** (o sea, ponerle nombre) a cosas que hacemos habitualmente. Esto nos sirve para poder fundamentar las decisiones que tomamos, para tener discusiones de mayor calidad con nuestrxs colegas y para poder construir diseños más poderosos.

Por todo esto, la propuesta de esta clase tiene que ver sobre todo con leer dos apuntes y luego poder aplicarlos en casos concretos.

## Los famosos patrones de diseño

Probablemente ya hayan escuchado nombrarlos, probablemente estén deseando aprenderlos o tal vez nada de eso ocurra y tendrán la primicia al leer el apunte. Lo cierto es que estos patrones están muy difundidos en la industria y creemos que es interesante conocerlos, no sin cierto escepticismo a la hora de aplicarlos. Profundizarán sobre este aspecto con la lectura del apunte correspondiente.

Para ir entrando en calor, les dejamos dos micro-ejercicios para trabajar con dos patrones que ya conocen: el `Strategy` y el `Singleton`.
