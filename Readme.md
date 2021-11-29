# Base de datos de Ejercicios Fitness

El Objetivo de este repositorio es servir como base de datos y API para una lista de alreadedor de 900 ejercicios de fitness bien documentados y con dos imagenes que sirve como base para cualquier aplicación.


# Motivación

Este repositorio esta basado en la versión para NodeJS y PLSQL de la base de datos open source publica de **workouts/exercises:** [Link Aquí](https://github.com/wrkout/exercises.json)

## Estructura del Repositorio

La estructura es super simple, existe una carpeta llamada images y un archivo llamado ejercicios.json, en el archivo exercises.json esta definido un array de ejercicios que sigue el siguiente formato:

    Exercises:[]

    export interface Exercise {
          name: string
          force: string
          level: string
          mechanic: string
          equipment: string
          primaryMuscles: string[]
          secondaryMuscles: string[]
          instructions: string[]
          category: string
          images: string[]
          id: string
    }

Cada ejercicio contiene dos imagenes que se encuentran en la carpeta images con la siguiente nomenclatura: `id_1.jpg ` y `id_2.jpg`

## Contribution
Si quieres añadir o crear nuevos ejercicios, sientente libre de hacerlo en este [repositorio](https://github.com/wrkout/exercises.json) ya que este es un repositorio autogenerado.