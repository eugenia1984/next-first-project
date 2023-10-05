# <img width="20" height="20" src="https://img.icons8.com/color/20/nextjs.png" alt="nextjs"/> introducción a Next.js

## ¿ Qué se ve?

### 1 - ¿ Qué es NEXT.js?

- Es un **Framework** poderoso para servir contenido estático y generado desde el lado del servidor.

- Está basado en **React**

- Al ser un marco de trabajo hay ciertos lineamientos a seguir.

- Podemos hacer todo lo que sabemos en React más **mejoras de rendimiento**, **SEO**, **Separación de código**, **router**, **dependencias** y más.

- Ya la nueva docuemtnación de React dejo de recomendar crear aplicaciones con CRA(Create React App) y recomienda utilizar **Vite** o **Gatsby** y si se quiere tener renderizados del lado del servidor usar **NEXT.js**.

- Cambia el paradigma de los SPA (Single Page Aplication) y te da opciones para trabajar tus aplicaciones. 

Ahora se cuenta con el **Sever-Side Rendering** y/o **generación estática**, y al mismo tiempo NEXT.js ofrece:

- **SRR**: Server-side rendering

- **SSG**: Static-site generation

- **CSR**: Client Side Rendering

- **ISR**: Incremental Static Regeneration

- **DR**: Dynamic Routing

Una SPA funciona así:

1. El usuario entra a un URL el cual inicia la primera solisitud (**Request**)

2. El servidor responde con una respuesta (**Response**).

3. Esa response contiene toda la aplicación o una gran parte de ella. Usualmente asi viene el documento html y referencias a otros archivos necesarios.

4. La computadora cliente interpreta la respuesta. Y aquí viene nuestro contenido de React. 

Lo cual no es malo, pero pensemos ¿qué pasaría si la persona sólo quiere ver la página del about? Cargaría completamente **toda** nuestra aplicación, y eso incluye módulos que nunca usará.

Pero quizá, el peor panorama es que **no es SEO friendly** (SEO = Search Engine Optimization), solo lo tiene para la primer pantalla, al ser SPA, las meta tags no pueden ser personalizadas acorde a la página que se ve, todo esto hace que no se posicione bien en Google.

¿Por qué es tan importante el SEO? El impacto que tienes en la red.


---

### 2 - Crear nuestro primer proyecto

### 3 - Exposición sobre cada archivo y directorio

### 4 - Componentes propios de Next (Link, Head)

### 5 - Módulos de CSS y estilos globales

### 6 - Páginas

### 7 - API generadas por defecto

### 8 - Aplicar estilos basados en rutas

### 9 - Layouts

### 10 - Layouts anidados