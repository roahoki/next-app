# Lo que entiendo del tutorial

# TimeSTAMPS: 00:00 How to use Next JS and build some components
# 40:00 How to Style in Next JS

En la carpeta app es un app router asi que ahi iremos creando de todo
//Crear una ruta: ej: users/page.tsx
recuerda usar rafce para armar el componente exportable más rápido

ctrl M P para buscar archivos creados en el directorio

Usar componente Link para la navegación en la app está optimizado en cuanto a la carga de recursos

Inside a web app we use client components and server components because, the client ones are capable of using useEffects, maintain state plus access browser APIs, the server ones cannot.

En la carpeta public se pueden dejar las imágenes a utilizar

En root hay un montón de archivos de configuración de las distintas herramientas como next, package json, postcss, tailwind y typescript

Al trabajar con CSS preocupate de trabajar con módulos de CSS para evitar sobreescribir clases que se lleguen a llamar a igual, el formato es:

nombredelcomponente.module.css

cuando nombres las clases de css, ocupa camelCase si nombras de-esta-forma te tirará error pq javascript no lo considera un objeto válido
