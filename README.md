# 💿 Dyler Music · Escarba el catálogo

Una web para **escarbar vinilos desde el celular**, como pasar discos en una caja de tienda: deslizas, ves la carátula, eliges y pides por WhatsApp.

Esta es una **demo con 10 discos** de la colección de Dyler Music. Es una página estática: un `index.html` y unas imágenes, sin servidor ni base de datos.

**Ver la demo:** https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/

## Qué puedes hacer

- **Escarbar la caja:** desliza con el dedo, o arrastra con el mouse y usa las flechas ← → en el computador.
- **Cambiar la vista** entre la caja y una lista en cuadrícula.
- **Buscar** por artista o título, y **filtrar** por nuevo o sellado, prensado en el exterior y rango de precio.
- **Al azar:** que la caja te sorprenda con un disco.
- **Escuchar en Spotify:** cada disco abre su búsqueda en Spotify.
- **Comprar por WhatsApp:** un disco directo, o varios juntos desde "Mi caja", con el total ya sumado.

## Cómo está hecha

- Un solo `index.html` con HTML, CSS y JavaScript, sin frameworks ni dependencias.
- Las carátulas están en la carpeta `img/`.
- Los discos están en el propio `index.html` (busca `const RAW=`), con nombre, precio y observación.
- Funciona en cualquier hosting estático. La demo corre en GitHub Pages.

## Úsala para tu propia tienda

1. Haz un **fork** de este repositorio o descárgalo.
2. Abre `index.html` y cambia tu número en `const WA="";`, con indicativo del país y sin + ni espacios (por ejemplo `"573001234567"`).
3. Cambia los discos en `const RAW=` y pon tus imágenes en `img/`, enlazadas en `const COVERS=`.
4. Publica: **Settings → Pages → Deploy from a branch → `main` / `(root)`**.

## Cómo colaborar

Las ideas y mejoras son bienvenidas. Puedes abrir un *issue* o un *pull request*. Algunas ideas:

- Buscar en todo el catálogo a la vez, no solo en un apartado.
- Etiqueta de "pieza única" y consulta de disponibilidad.
- Leer el catálogo desde una hoja de cálculo para actualizarlo sin tocar código.
- Mejoras de accesibilidad y de velocidad de carga.

Antes de enviar cambios, revisa que la página se vea bien en celular y que respete el modo claro y el oscuro.

## Créditos

- Colección y catálogo: **Dyler Music**.
- Las carátulas pertenecen a sus respectivos artistas y sellos, y se muestran solo como referencia de cada disco.

## Licencia

Código bajo licencia **MIT**. Las carátulas y los nombres de discos no están cubiertos por esta licencia.
