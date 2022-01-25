# Plantilla Básica de Latex para memorias e informes

Esta plantilla de LaTeX se ha creado con el propósito de facilitar la elaboración de informes de prácticas de forma más sencilla y elegante en comparación a editores de texto convencionales. La base de esta plantilla nace del trabajo de [José María Plens](https://github.com/jmrplens/TFG-TFM_EPS) orientado a la elaboración de TFG para la Escuela Politécnica Superior de la Universidad de Alicante; las diferencias entre estos trabajos son que el original contiene muchos más elementos mientras que en esta versión se han eliminado librerías, comandos y recursos específicos para dejar una plantilla básica (y aún así todavía se podrían quitar muchas más lineas, estoy abierto a sugerencias).

Si necesitas una ayuda específica sobre cómo trabajar con LaTeX, te recomiendo que consultes el enlace superior así como las ayudas de Overleaf, pero si quieres empezar a redactar ya, sigue las instrucciones de abajo. También encontrarás alguna ayuda extra lo largo del documento inicial.

1. En Overleaf, crea un proyecto nuevo y carga todos estos ficheros.
2. Antes de editar nada, ve al gestor de proyectos de Overleaf y duplica este proyecto. Así conservarás una copia original de esta plantilla cuando empieces a editar.
3. Ve a Menu y asegúrate que el compilador es XeLaTeX y el archivo principal es `main.tex`.
4.  En el archivo `main.tex` solo tienes que poner el título del trabajo, autor y fecha. Después de eso se cargarán los archivos correspondientes a cada sección con el comando `\include{}`; si quieres que cada sección comience en la misma página que donde acabó la sección anterior, cambia este comando por `\input{}`.
5. Modifica cada sección desde su fichero correspondiente, es más práctico y eficiente que tener todo tu documento en un mismo fichero. Si además creas `\section{}` y `\subsection{}`, se te irá generando un índice en la esquina inferior-izquierda de Overleaf y podrás ir rápidamente a cada apartado.

Como se ha comentado antes, esta plantilla ha derivado del trabajo de [José María Plens](https://github.com/jmrplens/TFG-TFM_EPS). Todos los agradecimientos deben ir a él pero, si por algún motivo quisieras agradecérmelo a mí directamente, puedes escuchar [mi música](https://linktr.ee/westy_music) y decirme qué te parece.
