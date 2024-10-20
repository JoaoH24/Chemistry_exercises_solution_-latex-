[linkedin]: https://www.linkedin.com/in/joaoh24/
[github]: https://github.com/JoaoH24
[pdf]: https://github.com/JoaoH24/Chemistry_exercises_solution_-latex-/blob/main/COMPENDIO%DE%2DA%PRACTICA%DIRIGIDA%2023-2.pdf
[sol]: https://github.com/JoaoH24/Chemistry_exercises_solution_-latex-/tree/main/out/content.md

# Solucionario de Ejercicios - Química I

- [Compendio de ejercicios en pdf][pdf]
- [Solucionario de ejercicios][sol]

## Descripción

Colección de soluciones detalladas para el segundo compendio de ejercicios del curso Química I de la Facultad de Ingeniería Industrial y de Sistemas (UNI). El material cubre problemas fundamentales de química cuántica y estructura atómica.

## Contenido

- Compendio de ejercicios de la segunda práctica dirigida.

## Información Académica

- Universidad: Universidad Nacional de Ingeniería (UNI)
- Facultad: Ingeniería Industrial y de Sistemas
- Curso: Química I

## Cómo compilar este documento

`-syntex`: Genera un archivo .synctex.gz que permite la sincronización entre el archivo fuente (.tex) y el PDF resultante

`-interaction`: Controla cómo pdflatex interactúa cuando encuentra errores

`-aux-directory`: Especifica el directorio para archivos auxiliares/temporales

`-output-directory`: Especifica dónde se guardará el archivo PDF final

`include-directory`: Especifica dónde buscar archivos incluidos/importados

El siguiente comando resume la compilación del documento haciendo uso de pdflatex sobre la distribución MiKTeX:

```bash
pdflatex -synctex=1 -interaction=nonstopmode -aux-directory=".\logs\" -output-directory=".\out\" -include-directory=".\src\" ".\src\content.tex"
```

**_Sígueme en:_**

- [Linkedin][linkedin]

- [GitHub][github]
