# Proyecto Final - CIRCT "Circuit IR Compilers and Tools"

Presentado por: 

• Arredondo Flores Alexa Ketzali - 181080005 - https://github.com/KetzaliF

• Bohorquez Lopez Miguel Angel - 181080006 - https://github.com/AngelBLK

• Rodríguez García Jesús - 181080027 - https://github.com/jessgarcia10117

Materia - Lenguajes y Autómatas II

Impartida por el profesor: Abiel Tomas Parra Hernández

## Resumen

En los últimos años la inclinación por la arquitectura de computadoras ha abierto el paso a grandes incógnitas con respecto a la fabricación de los chips complejos con el que se realizan las computadoras, en base a esto surgen dos cuestiones centrales, las cuales son. ¿Cómo se diseñan? y ¿cómo se programan? Por eso mismo buscamos demostrar cómo las herramientas que diseñan y dan la solución a estos problemas se centra en el LLVM / LMIR para la expresión de estas abstracciones y resolver los problemas de diseño a posteriori. 

## Motivación

La industria de EDA tiene herramientas patentadas y de código abierto conocidas y ampliamente utilizadas. Sin embargo, estas herramientas son inconsistentes, tienen problemas de usabilidad y no se diseñaron juntas en una plataforma común. Además, estas herramientas generalmente se construyen con Verilog (también VHDL) como los IR que intercambian. Verilog tiene problemas de diseño y limitaciones bien conocidos, p. Ej. que sufren de un soporte de seguimiento de ubicación deficiente. 

El proyecto CIRCT es un esfuerzo (¡experimental!) Que busca aplicar MLIR y la metodología de desarrollo LLVM al dominio de las herramientas de diseño de hardware. Muchos de nosotros soñamos con tener una infraestructura reutilizable que sea modular, use técnicas de diseño basadas en bibliotecas, sea más consistente y se base en las mejores prácticas en infraestructura de compiladores y técnicas de diseño de compiladores.

Al trabajar juntos, esperamos poder construir un nuevo centro de gravedad para obtener contribuciones de la pequeña (¡pero entusiasta!) Comunidad de personas que trabajan en herramientas de hardware abierto. A su vez, esperamos que esto impulse las herramientas abiertas hacia adelante, permita nuevas abstracciones de alto nivel para el diseño de hardware y quizás algunas piezas incluso puedan ser adoptadas por herramientas propietarias a tiempo.

Para mas información ver el repositorio de CIRCT https://github.com/llvm/circt ó el sitio web https://circt.llvm.org/
