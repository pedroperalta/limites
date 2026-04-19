# Límites, Derivadas e Integrales
### Libro pedagógico para el Electivo de Cálculo · MINEDUC · Bradford School

[![Estado](https://img.shields.io/badge/estado-en%20desarrollo-c8b87a?style=flat-square)](https://github.com/tu-usuario/libro-calculo)
[![Licencia](https://img.shields.io/badge/licencia-CC%20BY--SA%204.0-blue?style=flat-square)](https://creativecommons.org/licenses/by-sa/4.0/)
[![MINEDUC](https://img.shields.io/badge/alineado-Bases%20Curriculares%20MINEDUC-green?style=flat-square)](https://www.curriculumnacional.cl)

---

## ¿De qué se trata este proyecto?

Este repositorio contiene el código fuente LaTeX y el PDF compilado de un libro pedagógico diseñado para el **Electivo de Límites, Derivadas e Integrales** propuesto por el Ministerio de Educación de Chile (MINEDUC) para III y IV Medio.

El libro está pensado para estudiantes que simultáneamente cursan el **IB Diploma Programme**, por lo que incluye un enfoque riguroso pero accesible, con énfasis en comprensión conceptual y aplicaciones reales.

---

## Estructura del repositorio

```
libro-calculo/
├── index.html              ← Página web del proyecto (GitHub Pages)
├── libro.pdf               ← PDF compilado (última versión)
├── README.md               ← Este archivo
└── src/
    ├── main.tex            ← Documento principal
    ├── preambulo.tex       ← Paquetes y configuraciones
    ├── capitulos/
    │   ├── 01-limites.tex
    │   ├── 02-derivadas.tex
    │   └── 03-integrales.tex
    └── imagenes/
        └── ...
```

---

## Avance por capítulo

| Capítulo | Contenido | Estado |
|----------|-----------|--------|
| 01 | Límites y continuidad | ✅ Listo |
| 02 | La derivada | ✅ Listo |
| 03 | Reglas de derivación | 🟡 Borrador |
| 04 | Aplicaciones de la derivada | 🔵 En progreso |
| 05 | La integral | ⬜ Pendiente |

---

## Cómo usar este material

### Descargar el PDF

Haz clic en [`libro.pdf`](./libro.pdf) o en el botón de descarga en la [página del proyecto](https://tu-usuario.github.io/libro-calculo).

### Compilar desde el código fuente

Necesitas una instalación de LaTeX (TeX Live o MiKTeX) con los paquetes estándar.

```bash
git clone https://github.com/tu-usuario/libro-calculo.git
cd libro-calculo/src
pdflatex main.tex
```

O puedes abrir `src/main.tex` directamente en [Overleaf](https://overleaf.com) sin instalar nada.

### Editar colaborativamente en Overleaf

[🔗 Abrir en Overleaf (solo lectura)](https://overleaf.com/read/XXXXXXXXXX)  
*(reemplaza este link con el tuyo desde Overleaf → Share → Anyone with link)*

---

## ¿Cómo colaborar?

Este proyecto está abierto a la comunidad docente. Hay tres formas de participar:

### 1. Reportar un error o sugerir una mejora
Abre un [Issue](https://github.com/tu-usuario/libro-calculo/issues/new) describiendo:
- En qué capítulo o página está el problema
- Qué dice actualmente y qué debería decir
- Cualquier contexto adicional

### 2. Participar en la discusión pedagógica
Usa la sección de [Discussions](https://github.com/tu-usuario/libro-calculo/discussions) para:
- Proponer enfoques didácticos alternativos
- Compartir cómo estás usando el material en tu clase
- Sugerir ejercicios o ejemplos contextualizados

### 3. Proponer cambios directamente (Pull Request)
Si manejas LaTeX y Git:
1. Haz un fork de este repositorio
2. Crea una rama con tu cambio (`git checkout -b mejora-capitulo-2`)
3. Sube tus cambios y abre un Pull Request

---

## Alineamiento curricular

Este libro cubre los Objetivos de Aprendizaje del electivo **Límites, Derivadas e Integrales** de las Bases Curriculares de Matemática (MINEDUC, 2019), para estudiantes de III y IV Medio.

Es compatible con los contenidos de:
- **Matemáticas AI NM** y **AA NM** del IB Diploma Programme
- Preparación conceptual para la **PAES Matemática**

---

## Sobre el autor

Desarrollado por **[Tu Nombre]**, docente de Matemática en Bradford School, Santiago.  
Contacto: [tu@email.cl](mailto:tu@email.cl)

---

## Licencia

Este material se distribuye bajo licencia **Creative Commons BY-SA 4.0**.  
Puedes usar, adaptar y redistribuir el contenido con atribución y bajo la misma licencia.

[![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)
