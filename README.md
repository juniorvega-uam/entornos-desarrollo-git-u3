# Tecnovía Bloque 3 - Entornos de Desarrollo y Git

Proyecto desarrollado como parte de la Unidad 3 de Formación en Entornos Laborales, enfocado en la configuración de entornos de desarrollo, control de versiones con Git, trabajo con ramas, depuración de código y documentación profesional.

## Autor

**Junior Enrique Vega Solano**

## Fecha

Junio 2026

---

# Descripción

Este proyecto tiene como objetivo practicar el uso de herramientas fundamentales empleadas en entornos profesionales de desarrollo de software.

Durante el desarrollo se trabajó con:

- IntelliJ IDEA
- Java JDK 17
- Git
- GitHub
- Debugger de IntelliJ
- Markdown

Además, se aplicaron conceptos relacionados con control de versiones, creación de ramas, fusiones, resolución de conflictos y documentación técnica.

---

# Requisitos

Para ejecutar este proyecto es necesario disponer de:

- Java JDK 17 o superior
- IntelliJ IDEA Community Edition
- Git
- GitHub
- Python 3.11 o superior

Comprobar instalaciones:

```bash
java --version
javac --version
git --version
python --version
```

---

# Estructura del Proyecto

```text
entornos-desarrollo-git-u3/

├── src/
│   └── HolaMundo.java
│
├── tests/
│
├── docs/
│   └── notas.md
│
├── README.md
```

---

# Instalación

## Clonar el repositorio

```bash
git clone https://github.com/juniorvega-uam/entornos-desarrollo-git-u3.git
```

## Acceder al proyecto

```bash
cd entornos-desarrollo-git-u3
```

## Abrir en IntelliJ IDEA

1. Abrir IntelliJ IDEA.
2. Seleccionar **Open Project**.
3. Elegir la carpeta del proyecto.
4. Verificar que el JDK 17 esté configurado correctamente.

---

# Uso

## Compilar el programa

```bash
cd src
javac HolaMundo.java
```

## Ejecutar el programa

```bash
java HolaMundo
```

Salida esperada:

```text
Version Final
15
```

---

# Ejercicios Realizados

## Ejercicio 3.1 – Configuración del Entorno

- Instalación de IntelliJ IDEA.
- Instalación de Java JDK 17.
- Instalación de Python.
- Creación de estructura de proyecto.
- Ejecución de HolaMundo.java.

## Ejercicio 3.2 – Control de Versiones con Git

- Inicialización de repositorio Git.
- Creación de commits descriptivos.
- Publicación del proyecto en GitHub.

## Ejercicio 3.3 – Ramas y Fusiones

- Creación de ramas de funcionalidad.
- Trabajo independiente sobre ramas.
- Fusión mediante git merge.
- Resolución de conflictos.

## Ejercicio 3.4 – Debugging

- Uso de breakpoints.
- Inspección de variables.
- Identificación de errores lógicos.
- Corrección del código.

## Ejercicio 3.5 – Documentación

- Creación de README.md.
- Uso de Markdown.
- Documentación del proyecto.

## Ejercicio 3.6 – Proyecto Completo

- Historial Git organizado.
- Documentación completa.
- Repositorio público en GitHub.

---

# Captura de Ejecución

Guarda una captura dentro de la carpeta:

```text
docs/captura_programa.png
```

Y cuando la tengas, agrega:

```markdown
![Programa ejecutándose](docs/captura_programa.png)
```

---

# Comandos Git Utilizados

```bash
git init
git add .
git commit -m "feat: estructura inicial del proyecto"
git checkout -b feature/saludo-personalizado
git merge feature/saludo-personalizado
git log --oneline --graph --all
git push
```

---

# Conceptos Aprendidos

Durante la realización de este proyecto se reforzaron conocimientos sobre:

- Configuración de entornos de desarrollo.
- Java y JDK.
- Git.
- GitHub.
- Branches.
- Merge.
- Resolución de conflictos.
- Debugging.
- Markdown.
- Documentación de proyectos.

---

# Repositorio GitHub

Repositorio público:

https://github.com/juniorvega-uam/entornos-desarrollo-git-u3

---

# Licencia

Proyecto realizado con fines educativos y de aprendizaje.
