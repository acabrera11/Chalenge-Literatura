<h1 align="center"> Chalenge Literatura</h1>

![pila-libros-diseno-plano-dibujado-mano_23-2149334862](https://github.com/acabrera11/Chalenge-Literatura/assets/37312397/2cbee6ef-f2d9-4227-9d27-6ca551bbc617)


### Indice

- [Descripcion del Proyecto](#descripcion-del-projecto)

- [Funcionalidades](#funcionalidades)

- [Tecnologías utilizadas](#librerias-utilizadas)

- [Acceso al proyecto](#acceso-al-proyecto)

- [Estructura del proyecto](#estructura-del-proyecto)

  ## Descripcion del Proyecto 

<p align="justify">
 Aplicación para gestionar tu biblioteca personal. Construida obteniendo informacion de libros y sus autores con consumo de API de https://gutendex.com/ para el posterior almacenamiento de datos en una base de datos PostgreSQL

El programa permite al usuario escoger 7 opciones:

        1 - Buscar Libro por TÍtulo
        2 - Listar Libros Registrados
        3 - Listar Autores Registrados
        4 - Listar autores vivos en un determinado año
        5 - Listar Libros por idioma
        6 - Ver Top 10 Libros mas descargados
        7 - Generar Estadisticas de los libros
        0 - SALIR
                
</p>

## Funcionalidades

:heavy_check_mark: `Funcionalidad 1:` Buscar Libro por TÍtulo

:heavy_check_mark: `Funcionalidad 2:` Listar Libros Registrados

:heavy_check_mark: `Funcionalidad 3:` Listar Autores Registrados

:heavy_check_mark: `Funcionalidad 4:` Listar autores vivos en un determinado año

:heavy_check_mark: `Funcionalidad 5:` Listar Libros por idioma

:heavy_check_mark: `Funcionalidad 6:` Ver Top 10 Libros mas descargados

:heavy_check_mark: `Funcionalidad 7:` Generar Estadisticas de los libros

## Tecnologías utilizadas

:heavy_check_mark: `Java:` 17
:heavy_check_mark: `Spring Boot:` 3.3.0
:heavy_check_mark: `Postgresql`
:heavy_check_mark: `jackson-databind` 2.16.0
:heavy_check_mark: `Spring Data JPA`

## Acceso al proyecto
https://github.com/acabrera11/Chalenge-Literatura.git

## Estructura del Proyecto
- src/main/java:
  - com.alura.literalura:
    - LiteraturaApplication: Desde esta clase se llama a la clase principal que contiene la logica con los metodos de la aplicación
    - model: Contiene las clases en donde se definen los componentes para la representación de la información de los libros y autores
    - repository: Contiene la interfaz para acceder a la base de datos.
    - service: Contiene las clases que implementan la lógica para el consumo de la API y la conversion de los datos
    - principal: Contiene la clase principal de la aplicación.
- src/main/resources: Contiene los archivos de configuración para que funcione la aplicación.
- pom.xml: Contiene las dependencias utilizadas en el proyecto.
