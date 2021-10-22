---
title: 'Clase 6 - Comunicación entre componentes'
date: 2021-10-19
author: faloi
categories: [Clases]
tags: [kotlin, tdd, pruebas]
videos:
  - id: otcEhvtMENw
    nombre: Encuentro sincrónico del 19 de Octubre
    descripcion: >
      Las diapositivas de la clase pueden verse en [este link](https://obj2-unahur.github.io/encuentros-sincronicos/clase6).
  - id: 0euzfH_NWE0
    nombre: Inyección de dependencias e IMPOSTORES ¿cómo testear servicios externos en Kotlin con MockK?
lecturas:
  - url: https://refactoring.guru/es/design-patterns/observer
    title: Patrón "Observer"
    summary: El patrón de comunicación que comentamos durante el encuentro sincrónico, que debería servirles para resolver el ejercicio.
  - url: https://surprograma.github.io/libro-disenio-oop/docs/kotlin/herramientas-lenguaje/manejo-fechas/
  - url: https://surprograma.github.io/libro-disenio-oop/docs/kotlin/herramientas-lenguaje/manipulacion-strings/
entrega:
  fecha: "2021-11-01 23:59"
  ejercicios:
  - nombre: Servidor web (Kotlin)
    repo: surprograma/disenio-kt-servidor-web
    classroom: https://classroom.github.com/a/diCiqpc4
  - nombre: Servidor web (TypeScript)
    repo: surprograma/disenio-ts-servidor-web
    classroom: https://classroom.github.com/a/rwucon8I
---

## Objetivos de la clase

* Introducir el patrón _Observer_.
* Utilizar impostores para probar código que depende de componentes ajenos a nuestro programa.
* Conocer otra posible forma de comunicación entre componentes.
