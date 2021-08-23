---
title: 'Clase 3 - Cualidades de diseño'
date: 2021-08-23
author: faloi
categories: [Clases]
tags: [kotlin, tdd, pruebas]
videos:
  - id: IcRQhgnvzeA
    nombre: Encuentro sincrónico del 23 de Agosto
  - id: VQ8V0ym2JSo
    nombre: Breve explicación del patrón Strategy
    descripcion: >
      Un español barbudo que, a nuestro juicio, explica de forma muy clara los patrones de diseño.
lecturas:
  - url: https://surprograma.github.io/libro-disenio-oop/docs/cualidades-disenio/cualidades-independientes-tecnologia/
  - url: https://refactoring.guru/es/design-patterns/strategy
    title: Patrón "Strategy"
    summary: Una forma _objetosa_ de modelar estrategias que pueden intercambiarse.
  - url: https://surprograma.github.io/libro-disenio-oop/docs/patrones-disenio/introduccion/
    opcional: true
  - url: https://surprograma.github.io/libro-disenio-oop/docs/cualidades-disenio/introduccion/
    opcional: true
entrega:
  fecha: "2021-08-29 23:59"
  ejercicios:
  - nombre: Caralibro (TypeScript)
    repo: surprograma/disenio-ts-caralibro
    classroom: https://classroom.github.com/a/WldP-mPL
    descripcion: >
      Sobre el mismo repo que ya tenían, la idea es que conviertan los permisos en un `Strategy`.
  - nombre: Semillas al viento (TypeScript)
    repo: surprograma/disenio-ts-semillas
    classroom: https://classroom.github.com/a/gre1LYQO
---

En esta clase introduciremos dos aspectos que seguiremos trabajando durante todo el curso: cualidades de diseño de software y patrones de diseño orientado a objetos.

## Objetivos de la clase

* Introducir la noción de cualidad de diseño y su utilidad para evaluar comparativamente soluciones
* Definir qué es un patron de diseño, sus ventajas y desventajas y cuándo es conveniente aplicarlo.
* Formalizar el patrón Strategy.

## No todo es programar

Como verán, esta clase viene un poco más _teórica_ que las anteriores y es que, efectivamente, no todo en este oficio es programar. También es necesario saber cuándo parar la pelota y reflexionar: ¿este problema podría resolverse de otra forma? ¿por qué, o mejor dicho, en qué aspectos esta solución es mejor que otra?

Además de profundizar en el conocimiento sobre el paradigma de objetos, en este curso nos interesa **ampliar el vocabulario** y poder **nombrar** (o sea, ponerle nombre) a cosas que hacemos habitualmente. Esto nos sirve para poder fundamentar las decisiones que tomamos, para tener discusiones de mayor calidad con nuestrxs colegas y para poder construir diseños más poderosos.

Por todo esto, la propuesta de esta clase tiene que ver sobre todo con leer dos apuntes y luego poder aplicarlos en casos concretos.

## Los famosos patrones de diseño

Probablemente ya hayan escuchado nombrarlos, probablemente estén deseando aprenderlos... o tal vez nada de eso ocurra y tendrán la primicia al leer el apunte. Lo cierto es que estos patrones están muy difundidos en la industria y creemos que es interesante conocerlos, no sin cierto escepticismo a la hora de aplicarlos.

Profundizarán sobre este aspecto con la lectura del apunte correspondiente.
