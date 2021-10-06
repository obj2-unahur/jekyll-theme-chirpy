---
title: 'Clase 5 - Interacción con el "mundo real"'
date: 2021-10-05
author: faloi
categories: [Clases]
tags: [kotlin, tdd, pruebas]
videos:
  - id: nRW2Aq8Wlvo
    nombre: Encuentro sincrónico del 5 de Octubre
  - id: mFBKbBWRq_E
    nombre: Programando y testeando una aplicación de consola en Kotlin
    descripcion: >
      Una versión "objetosa" de cómo hacer una aplicación de consola, con tests incluidos.
lecturas:
  - url: https://docs.google.com/document/d/11mVR-4wEZhlQMDEqrfQeYLypEsrSqXv98dr78SA0Oq4/edit#heading=h.5bqwe0zgcgud
    title: Apunte sobre Testing
    summary: Un apunte muy completo relacionado al testing. En particular nos interesa que lean la sección sobre **impostores**, pero no vendría mal ojearlo completo.
    opcional: true
entrega:
  fecha: "2021-10-18 23:59"
  ejercicios:
  - nombre: Tareas (Kotlin)
    repo: surprograma/disenio-kt-tareas
    classroom: https://classroom.github.com/g/yua9jFCQ
    descripcion: Siguen trabajando sobre el mismo repo de la vez pasada. Los tests de la **etapa 3** necesitan algo que aún no vimos, pueden dejarlos sin hacer.
  - nombre: Tareas (TypeScript)
    repo: surprograma/disenio-ts-tareas
    classroom: https://classroom.github.com/g/cPeqtIvd
    descripcion: Siguen trabajando sobre el mismo repo de la vez pasada. Los tests de la **etapa 3** necesitan algo que aún no vimos, pueden dejarlos sin hacer.
---

## Objetivos de la clase

* Comprender los problemas que surgen al querer construir un programa que interactúa con personas o sistemas externos.
* Aplicar un mecanismo de deserialización de objetos ya persistidos.
* Incorporar interacción con usuarixs reales a través de la consola.
* Reflexionar sobre la dificultad de escribir pruebas automatizadas para un sistema con estas características.

## ¡Hola mundo!

En esta clase comenzaremos a trabajar sobre el mismo ejercicio de la clase pasada. El objetivo es explorar un poco cómo podría diseñarse un sistema "de la vida real", donde vamos a interactuar con servicios externos que no controlamos.

Vamos a enfocarnos en dos cosas: cómo hacer que los objetos del servicio externo se _adapten_ a nuestro sistema y cómo brindar una forma de que un/a usuario/a pueda interactuar mediante la consola.
