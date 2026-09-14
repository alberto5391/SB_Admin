# SB Admin - Dashboard Template Replica

Este repositorio contiene la réplica y maquetación del panel de administración basado en la plantilla oficial de [SB Admin (Start Bootstrap)](https://startbootstrap.com/template/sb-admin).

El proyecto fue desarrollado de forma colaborativa utilizando **Git** y **GitHub**, aplicando un flujo de trabajo ramificado para dividir responsabilidades entre desarrolladores.

---

## Colaboradores y Roles

* **Developer 1:** Estructura semántica, maquetación HTML base (`index.html`, `pagina_uno.html`, etc.) y arquitectura de directorios. (elaborado por JOSE ALBERTO RODRIGUEZ GERONIMO)
* **Developer 2:** Hojas de estilo personalizadas (CSS), diseño visual, responsividad y componentes visuales. (elaborado por KEYLA DEL CARMEN DE LA CRUZ GARCIA)
* **Developer 3:** Funcionalidades avanzadas, scripts de interactividad y vistas adicionales (`pagina_dos.html`). (elaborado por EDUARDO ANTONIO SANCHEZ SANTOS)

---

## Flujo de Trabajo en Git

Para garantizar un desarrollo ordenado e independiente, se establecieron las siguientes ramas:

* `main`: Rama de producción estable que contiene el código integrado y final. (JARG)
* `developer1`: Rama de trabajo para la maquetación del esqueleto HTML. (JARG)
* `developer2`: Rama de trabajo para los estilos CSS y apariencia visual. (KDCG)
* `features`: Rama de trabajo para componentes e interactividad adicional. (EASS)

### Ciclo de Integración:

1. Cada desarrollador realizó sus cambios en su respectiva rama (`developer1` / `developer2`).
2. Se subieron los cambios a GitHub mediante `git push origin <rama>`.
3. Se integraron las ramas hacia `main` a través de **Pull Requests / Merge**.

---

## Estructura del Proyecto

```text
sbadmin/
├── assets/          Recursos gráficos, iconos e imágenes
├── js/              Scripts de interactividad y plugins
├── index.html       Vista principal del panel de administración
├── pagina_uno.html  Vista secundaria de contenidos
├── pagina_dos.html  Vista de datos estructurados y tablas
└── README.md        Documentación del proyecto