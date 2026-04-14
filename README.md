# Trabajo práctico N°2:

- Flexbox
- Grids
- Media queries
- Modularización CSS (import url(...))

## Explicación técnica

El trabajo se resolvió separando la estructura html de los estilos para poder reutilizar mejor los componentes y evitar repetir código. 
Para los bloques más simples, como navegación, botones y alineaciones internas, se usó flebox porque era más directo. 
En cambio, para armar las grillas de películas y acomodar mejor algunas secciones con varias columnas, usamos grid.
También se trabajó con media queries para adaptar las páginas a pantallas más chicas sin tener que rehacer toda la estructura. 
En la carpeta css se separaron archivos por partes para mantener el proyecto ordenado y fue más fácil tocar solo lo necesario en cada página o componente.
La idea fue que cada rama aporte una parte concreta del sitio aunque después fuimos contribuyendo sin un rol definido, apuntamos a que todo quede unido con una base visual común.

# Integrantes y contribuciones:

- Vladimir Kozik (rama: alumno1_kozik)
    - se contribuyó en la estructura base global del sitio, definiendo la navegación, el layout general y las páginas index y detalle con sus componentes reutilizables.
    - también se aplicaron classes globales y utilitarias para mantener la consistencia visual en las demás páginas del proyecto.

- Conrado Lanusse (rama: alumno2_lanusse)
    - refactoricé la estructura del CSS, módulos y archivos.
    - corregí estilos generales, eliminé clases duplicadas y agregué clases reutilizables y utilitarias
    - agregue enlace de inicio sobre el logo, enlace de login, agregue header y footer a otras paginas y corregí clases en estructura general
    - cree página de detalle de película y agregué modulo de componente movie-detail
    - agregue clases utilitarias y variantes de titulo y botones

- Laureano Kronemberger (rama: alumno3_kronemberger)
    - se terminó la página de login y se ajustaron estilos de registro usando componentes que ya estaban armados.
    - también se tocaron los estilos del formulario y de la sección principal para que login, registro y perfil quedaran más coherentes entre sí.

- Santino Aloisio (rama: alumno4_aloisio)
    - se hizo la página de registro, con su estructura y los estilos necesarios para que quedara integrada al resto del proyecto.

- Francisco Jaszczuk (rama: alumno5_jaszczuk)
    - se armó la estructura del panel de usuario, reutilizando clases globales y sumando clases propias para el perfil.