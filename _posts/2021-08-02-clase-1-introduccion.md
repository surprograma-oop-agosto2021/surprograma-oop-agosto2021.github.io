---
title: 'Clase 1 - Introducción'
date: 2021-08-02
author: faloi
categories: [Clases]
tags: [typescript]
lecturas:
  - url: https://surprograma.github.io/libro-disenio-oop/docs/pruebas-automatizadas/elaborar-casos-prueba/
    title: ¿Cómo elaborar casos de prueba?
    summary: Una guía práctica de cómo armar buenas pruebas automatizadas.
videos:
  - id: 3kHdzWSJjuM
    nombre: Encuentro sincrónico del 2 de Agosto
entrega:
  fecha: "2021-08-08 23:59"
  ejercicios:
  - nombre: Vendedores
    repo: surprograma/disenio-ts-vendedores
    classroom: https://classroom.github.com/a/iX1dIZnM
---

Te damos la bienvenida a este curso llamado oficialmente **Diseño de software orientado a objetos**. Si aún no lo hiciste, es sumamente importante que leas la [bienvenida]({{ '/' | relative_url }}), donde hemos concentrado toda la información sobre la modalidad de cursada.

## Objetivos de la clase

* Instalar y configurar los entornos de desarrollo que utilizaremos durante toda la cursada.
* Familiarizarse con el sitio y la dinámica de trabajo del curso.
* Conocer la sintaxis básica de Typescript y/o Kotlin.
* Formalizar la noción de _tipo_, imprescindible para trabajar en lenguajes con tipado estático.

## Cómo organizar el estudio

### Material disponible

En este artículo se concentra todo lo que, en esta modalidad de cursada, llamaremos "una clase". Puede que a primera vista te resulte un montón de información junta (y puede que en efecto lo sea) pero recordá que tenés 1 semana para completar las actividades.

Nuestra sugerencia es que le eches un vistazo por encima a todo el material que te proponemos, incluida la consigna del ejercicio que tenés que realizar, y que comiences a trabajar lo antes posible. Los enunciados que proponemos **son largos** y están pensados para trabajarse durante una semana, tenés que encontrar la forma de ir avanzando con el material y el ejercicio _en paralelo_ - y claro, no dejarlo para la noche anterior a la entrega.

Obviamente, podrás volver acá todas las veces que te sean necesarias: mirar nuevamente los videos, mirar qué apuntes relacionados hay, etcétera. Una buena organización de tus tiempos es de vital importancia para llevar adelante una cursada a distancia. :muscle: :timer_clock:

Para esta clase, y todas las que siguen, vas a necesitar:
* tener configurado Git,
* para TypeScript: instalarte el entorno de desarrollo [Visual Studio Code](https://code.visualstudio.com/) o [VSCodium](https://vscodium.com/),
* para Kotlin: instalarte el entorno de desarrollo [IntelliJ Idea](https://www.jetbrains.com/idea/).

### Entregas semanales

Todas las entregas del curso se harán mediante la plataforma [GitHub](https://github.com), y bastará con hacer un `git push` al repositorio correspondiente antes de la fecha de entrega para considerar el trabajo como entregado.

Al final de cada clase vas a encontrar una tarjeta por cada ejercicio obligatorio, con dos enlaces:
* `{{ site.data.label.entrega.clonar }}`: la primera vez que ingreses, realiza una copia del código inicial del ejercicio para que puedas comenzar a trabajar. Si volvés a ingresar, te lleva al repositorio que ya creaste.
* `{{ site.data.label.entrega.ver_enunciado }}`: enlace directo al repositorio que sirve de plantilla para la entrega. Puede ser útil acceder para ver cómo era el código inicial que venía, o leer el enunciado actualizado (en caso de que se haya corregido algo durante la semana).

Para armar las entregas utilizamos una herramienta llamada [GitHub Classroom](https://classroom.github.com), que al ingresar por primera vez te va a solicitar que elijas tu nombre de una lista. De ahí en adelante, se trabaja como con cualquier otro repositorio (`commit`, `push`, etc.), con la diferencia de que en este caso va a quedar en una organización propia de la materia y no en tu cuenta personal. Esto nos facilita a nosotros algunas cuestiones de gestión y automatización de la corrección.

### Sobre los videos

En cada clase incluiremos uno o varios videos, que subiremos a YouTube en el canal [El Sur también programa](https://www.youtube.com/channel/UCfrRa43tBrOYYYfgJqsJ7qg). Además de la grabación de los encuentros sincrónicos, habrá videos cortos para explicar cosas puntuales y videos más largos donde mostramos, por ejemplo, cómo resolver alguna parte de un ejercicio (o incluso un ejercicio completo).

Para encontrarlos más facilmente, todos los videos irán quedando en una lista de reproducción llamada [Diseño orientado a objetos en Kotlin y TypeScript](https://www.youtube.com/playlist?list=PL7q-McYJyHliqlpNGSVe-Y3EHDIma_H9U). Recomendamos enfáticamente **NO** hacer una maratón de los videos del canal, sino ir mirándolos a medida que aparezcan en las clases.

## Ahora sí: ¡hola Kotlin y Typescript!

Para transmitir los conceptos de la materia hemos elegido utilizar dos lenguajes: [Kotlin](https://kotlinlang.org/) y [TypeScript](https://www.typescriptlang.org/), y el objetivo principal de esta primera clase es que te familiarices con alguno de ellos. Además de ser el nombre de una [isla rusa :ru:](https://es.wikipedia.org/wiki/Isla_de_Kotlin), Kotlin es un lenguaje de programación orientada a objetos con tipado estático, bastante utilizado hoy en día para el desarrollo de aplicaciones móviles en Android.

En cuanto a TypeScript, podemos decir que es "el primo tipado" de [JavaScript](https://developer.mozilla.org/en-US/docs/Web/javascript), y que últimamente viene pisando fuerte en la industria. Puede utilizarse en los mismos lugares que JavaScript: frontend, NodeJS, aplicaciones móviles con React Native, etc.

Ambos tienen una sintaxis sencilla y bastante parecida, con la principal característica de que hay que explicitar los tipos de _algunas cosas_: principalmente parámetros y valores de retorno de los métodos. Sin ponernos demasiado formales, podemos decir que un _tipo_ define a un grupo de objetos con características similares, por ejemplo:

* el tipo `Int` (Kotlin) o `number` (TypeScript) para los números enteros, con los cuales se puede sumar, restar, multiplicar...
* el tipo `String` (Kotlin) o `string` (TypeScript) para las cadenas de texto, las cuales se pueden pasar a mayúsculas, recortar, consultar su longitud...
* el tipo `Golondrina` para las aves como la querida Pepita :bird:, a las cuales se le puede preguntar su energía, pedirles que vuelen y etcétera.
