# Nombre-de-herramienta
Este repositorio contiene el código y la documentación de Nombre de herramienta, una herramienta de análisis de sesgos en LLMs producto de mi Trabajo de Fin de Grado del Grado de Ingeniería Informática en la Universidad Complutense de Madrid.

## Introducción
-Nombre de herramienta y estructura (librería de python, huggingface)
-Objetivo y motivación
-Qué se puede hacer exactamente
-Cómo te da los resultados

## Limitaciones

-La herramienta solo se ha probado con machismo
-Muchos LLMs pequeños pueden no entender lo que es el sesgo y dar resultados al azar, ver sus resultados condicionados por prompts anteriores o ser propensos a dar los mismos valores
-La forma de medición del sesgo es simple y puede dar lugar a malentendidos. Los sesgos son temas sensibles y que presentan muchas facetas y matices, por lo que la medición del 1 al 10 simplifica mucho la medición del sesgo de una frase determinada. Esta herramienta no pretende ser una forma empírica de entender los sesgos que presenta un LLM, sino un indicador general del nivel de sesgo y de percepción de él que puede presentar. (Mencionar frases de ejemplo 1 y 10)
-Actualmente solo se pueden utilizar LLMs que se encuentren en huggingface
-

## Futuro

Como producto de un trabajo de fin de grado, esta herramienta presenta muchas posibilidades de ser expandida, mejorada y optimizada de muchas formas. A continuación se encuentran algunas de las propuestas de mejora a futuro sobre Nombre, muchas de ellas ligadas a sus limitaciones:

-Detección simultánea de múltiples sesgos.
-Mejora del sistema de evaluación de las frases.
-Posibilidad de utilización de APIs de LLMs como chatgpt, deepseek o gemini.
-Creación de bancos de frases por defecto para otros sesgos.
-

## Funcionamiento y modo de uso

Para empezar a utilizar la herramienta de forma local, el primer paso es instalar la herramienta en la máquina local con el siguiente comando:

```Bash
pip install Nombre
```

Y posteriormente importar la librería a nuestro archivo de python: 
```Python
import Nombre
```

Una vez importada la librería en nuestro proyecto, solo es necesario llamar a la función "función" con los parámetros necesarios para poder evaluar nuestros LLMs. A continuación se encuentra una lista de los argumentos de la función y sus propósitos.

-Hola

## Documento del tfg
