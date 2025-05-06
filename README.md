# Creado por: Joel Antonio Jaquez López - 23369

# Filtro de Personajes de Rick and Morty con React y useMemo

Este proyecto es una aplicación sencilla que permite buscar y agregar personajes, utilizando React con CDN y el hook `useMemo` para optimizar el filtrado de resultados.

## Tecnologías Utilizadas

- [React 18 (CDN)](https://unpkg.com/react@18/umd/react.development.js)
- [ReactDOM 18 (CDN)](https://unpkg.com/react-dom@18/umd/react-dom.development.js)
- [Babel (CDN)](https://unpkg.com/@babel/standalone/babel.min.js)

## Descripción

La aplicación permite:

- Buscar personajes por nombre o descripción (sensitivo a mayúsculas).
- Agregar nuevos personajes con nombre y descripción.
- Visualizar una lista de personajes filtrados según la búsqueda.

El hook `useMemo` se utiliza para memorizar los resultados del filtrado, evitando cálculos innecesarios en cada renderizado.

## ¿Por qué usar `useMemo`?

`useMemo` es un hook de React que permite memorizar el resultado de una función entre renderizados. En este proyecto, se utiliza para evitar recalcular el filtrado de usuarios cada vez que el componente se renderiza, mejorando así el rendimiento.

## Cómo Ejecutar el Proyecto

1. Clona este repositorio o descarga los archivos.
2. Abre el archivo `index.html` en tu navegador.
3. Acceder al servidor mediante la siguiente ruta: http://awita.site/usuarios/jaq23369/React%20Hock%20%28useMemo%29%20CDN/React%20Hock%20%28useMemo%29%20CDN/
