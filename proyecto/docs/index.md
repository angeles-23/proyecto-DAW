# Bienvenido a mi Proyecto MkDocs

¡Hola! 👋
Bienvenida/o a la documentación oficial de mi **Práctica con Docker, MkDocs y GitHub Pages** realizada para el módulo **Despliege de Aplicaciones Web (DAW)**.

---

## 📌 ¿Qué encontrarás en este sitio?

Este sitio ha sido generado utilizando:

* **MkDocs**
* **Theme Material for MkDocs**
* **Docker** para ejecutar MkDocs sin instalar nada en el sistema
* **GitHub Pages** para publicar el sitio web estático

El objetivo es comprender cómo:

1. Crear un proyecto MkDocs
2. Añadir contenido en formato Markdown
3. Ejecutar MkDocs dentro de un contenedor Docker
4. Publicar la documentación en GitHub Pages

---

## 📚 Lenguajes que he utilizado en mis prácticas

Aquí tienes algunos lenguajes de programación:

### Python

### Java

### JS

### CSS

### MySQL

---

## 🚀 ¿Cómo se generó este sitio?

Para iniciar el servidor local:

```
docker run --rm -it -p 8000:8000 -v "${PWD}:/docs" squidfunk/mkdocs-material
```

Para generar el sitio estático:

```
docker run --rm -it -v "${PWD}:/docs" squidfunk/mkdocs-material build
```

Para publicarlo en GitHub Pages:

```
docker run --rm -it -v "$env:USERPROFILE\.ssh:/root/.ssh" -v "${PWD}:/docs" squidfunk/mkdocs-material gh-deploy
```

---

## ✔ Estado del proyecto

Este sitio se encuentra en constante mejora mientras avanzo en mis estudios de **DAW**.

¡Gracias por visitar esta documentación!
