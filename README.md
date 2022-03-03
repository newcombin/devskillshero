# Desafio Back-end

En este desafío, creará una API REST de una encuesta sobre super héroes.

## Contexto

En esencia, la API permitirá votar por un héroe y luego listar los resultados:

1. Permitir enviar un voto.
2. Listar los resultados según se requiera.

Contamos entonces con dos entidades que representan esta información:

* `heroes`: listado de héroes que se pueden votar. Los mismos se encuentran en el archivo heroes.json
* `votes`: contiene los votos realizados

> Nota: es posible votar a cada héroe múltiples veces.

# REST API

Debes crear un servicio con los siguientes endpoint:

## Permitir realizar un voto:
    ### Request Data
			{"id":14}
    ### Response Data
    	{"id":14,"superhero":"Thor","publisher":"Marvel Comics", "votes": 99}

## Listar los personajes que hayan recibido votos, ordenados de mayor a menor por sus votos:
    ### Request Data
			{}
    ### Response Data
    	[
				{"id":14,"superhero":"Thor","publisher":"Marvel Comics", "alter_ego": "Thor Odinson", "votes": 99},
				...
    	]
    	

## Listar la cantidad de votos por "Publisher":
    ### Request Data
			{}
    ### Response Data
    	[
				{"publisher":"Marvel Comics", "votes": 99},
				...
    	]

# Restricciones

1. El servicio debe estar escrito en Node.js / Python
2. El proyecto debe tener un README.md con todas las instrucciones sobre cómo ejecutar y probar el proyecto y los servicios proporcionados.
3. Subir a un repositorio git con privilegios públicos de lectura y compartir el link como resultado
4. No se debe nombrar a la empresa NewCombin en la solución propuesta.