---
title: 'Clase 6 - Interacción con el mundo real'
date: 2021-09-14
author: faloi
categories: [Clases]
tags: [kotlin, tdd, pruebas]
entrega:
  fecha: "2021-09-17 23:59"
  ejercicios:
  - nombre: Servidor web
    repo: surprograma/disenio-ts-servidor-web
    classroom: https://classroom.github.com/a/7eJeQCQ2
    descripcion: >
      Lo más importante del ejercicio son los analizadores. Si no les da el tiempo, traten de implementar al menos dos de ellos.
---

## Objetivos de la clase

* Introducir el patrón _???_.
* Reflexionar sobre los problemas que aparecen al integrar nuestros programas con sistemas externos.
* Conocer otra posible forma de comunicación entre componentes.

## Interacción con el mundo real

Tarde o temprano, nuestros programas van a necesitar comunicarse de alguna manera con el entorno: leer un archivo, mostrar algo por pantalla, reaccionar a interacciones de lxs usuarixs o interactuar con alguna API.

Esos componentes que incorporemos tendrán su propia interfaz, desarrollada por alguien más, y que puede o no ajustarse a nuestros criterios de diseño. En esta clase comenzaremos a ver estrategias para lidiar con estos componentes sin por ello tener que resignar todo lo que aprendimos de diseño.
