# Desafio Back-end

En este desafío, creará una API REST de una encuesta sobre super héroes.

## Contexto

En esencia, la API permitirá votar por un héroe y luego listar los resultados:

1. Permitir enviar un voto.
2. Listar los resultados según se requiera.

Contamos entonces con dos entidades que representan esta información:

* `heroes`: listado de heroes que se pueden votar. Los mismos se encuentran en el archivo heroes.json
* `votes`: contiene los votos realizados

> Nota: es posible votar a cada heroe multiples veces.

## Requisitos

Debes crear un servicio con los siguientes endpoint:

1. Permitir realizar un voto:
    * Id Heroe

2. Listar los personajes que allan recibido votos, ordenados de mayor a menor por sus votos:
    * Id Heroe
    * Superhero
    * Publisher
    * Alter Ego
    * Votes

3. Listar la cantidad de votos por "Publisher":
    * Publisher
    * Votes

## Restricciones

1. El servicio debe estar escrito en Node.js / Python
2. El proyecto debe tener un README.md con todas las instrucciones sobre cómo ejecutar y probar el proyecto y los servicios proporcionados.
3. Subir a un repositior git con privilegios publicos de lectura y compartir el link como resultado
4. No se debe nombrar a la empresa NewCombin en la solución propuesta.