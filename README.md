# NSS-Electiva02 ✨

**Práctica 1 de Electiva 2 (DevOps) - ITLA**

Hecha por Nicole Alejandra Santana Sánchez, matrícula 2025-1213.

Profesor: Elvys Cruz.

## ¿De qué trata?

La práctica consiste en crear un repositorio público con dos ramas: una principal (`main`) y una de desarrollo (`dev`). Yo le agregué una página web sencilla con mi Hola Mundo 👋

## ¿Para qué sirve cada rama?

- **`main`** → la rama principal, o sea, la versión estable del proyecto. Es la que "sale a producción".
- **`dev`** → la rama de desarrollo. Aquí hago y pruebo los cambios antes de pasarlos a `main`.

¿Y por qué trabajar así? Pues porque si algo sale mal en `dev`, la versión buena en `main` queda intacta. Y con Git siempre se sabe quién cambió qué, cuándo y por qué.

## ¿Qué tiene?

- Una página `index.html` con mi Hola Mundo, hecha con HTML y CSS.
- Colores negro, dorado, crema y un toquecito fucsia.
- Letras de Google Fonts: cursiva para el título y redondita para el texto.
- Se adapta al celular.

## ¿Cómo está organizado?

```
NSS-Electiva02/
├── index.html   → la página con el Hola Mundo
└── README.md    → esto que estás leyendo
```

## ¿Cómo lo veo?

Puedes verla en vivo aquí: https://nicky-ss19.github.io/NSS-Electiva02/
O si prefieres, descarga el repositorio y abre `index.html` en tu navegador.

## ¿Cómo se publica sola? (Práctica 3) 🚀

La página está conectada a GitHub Pages desde la rama `main`. O sea, el flujo es así:

1. Hago los cambios en `dev`.
2. Los paso a `main` con un Pull Request.
3. GitHub corre solito el flujo *pages build and deployment*, que se puede ver en la pestaña **Actions**.
4. En un minutito, la página nueva ya está en vivo.

Nadie sube archivos a mano a ningún servidor, todo es automático 🙌
