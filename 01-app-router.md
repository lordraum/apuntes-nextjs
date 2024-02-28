# App Router

Sistema de enrutamiento en el que las páginas que estén dentro de la carpeta /app seran las rutas o paths.

## page.jsx

Es el archivo que identifica nextjs cómo el que contiene la web

## layout.js

Archivo plantilla para las páginas, cuándo no existe, nextjs lo crea automáticamente. El componente se suele llamar `RootLayout`. Debe utilizarse props (ej children) para indicar donde se colocarán los componentes tipo page.

## Crear una nueva ruta

Crear una nueva carpeta dentro de /app y un nuevo archivo page.jsx

## Anidamiento de rutas

Cada carpeta que esté dentro de otra será una nueva ruta que contendrá el path propio y el de la carpeta a la cual pertenece --> `tienda/categorias/laptop`

## Anidamiento de layouts

Cada página dentro de un directorio será envuelta por el layout del mismo nivel y de los anteriores.

## metadata

Onjeto que permite acceder al elemento head en los layout

```js
export const metadata {
    title: 'Next.js',
    description: 'Generated ny Next.js'
}
``` 

<!-- https://youtu.be/_SPoSMmN3ZU?t=1431 -->

















