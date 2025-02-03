# Proyecto 9 - Memorias

Electrónica II para Ingeniería Electrónica. 2024

## Objetivos

- Investigar sobre las tecnologías de memoria semiconductoras ROM de máscara, PROM, EEPROM, FLASH, SRAM, y DRAM.
- Investigar las aplicaciones de los arreglos de memoria en los sistemas de cómputo: conjuntos de registros, memoria cache, memoria principal y memoria de almacenamiento.
- Describir los circuitos integrados lógicos programables Programmable Logic Array (PLA), Generic Array Logic (GAL) y Field Programmable Gate Array (FPGA). Indicar algunos ejemplos comerciales de cada uno con sus características básicas.
- Consultar la documentación sobre los bloques de memoria disponibles en la familia de FPGA iCE40 de Lattice Semiconductor.
- Describir en VHDL y evaluar mediante simulación las siguientes memorias:
  - Memoria RAM 512x8 bit con dos puertos sincrónicos, uno de lectura y uno de escritura.
  - Memoria RAM de dos puertos de 512x32 bit con máscara de escritura para cada bloque de 8 bit (byte).
  - Conjunto de registros de 32x32 bit de tres puertos, dos de lectura y uno de escritura.

*Nota*: Las memorias descritas deben poder inicializarse desde archivos de datos conteniendo una palabra hexadecimal (escrita en ASCII) por línea

## Entregables

Las descripciones de hardware y bancos de prueba realizados. Usar este repositorio como base y añadirlos dento del subdirectorio `src`.

Un informe con la siguiente estructura:

- *Título*
- *Autor*
- *Resumen* (1 punto)
- *Introducción* (2 punto) Presenta los resultados de la investigación y las especificaciones de los componentes a desarrollar.
- *Materiales y Métodos* (2 puntos) Explica el proceso seguido para describir un arreglo de memoria.
- *Resultados* (2 puntos) Describe los resultados obtenidos. No es necesario duplicar el código vhdl, pero sí describir en forma general el contenido de cada archivo.
- *Conclusiones* (2 puntos) Explica en tus palabras que es la descripción de hardware.
- *Referencias* (1 punto) Debes utilizar citas bibliográficas durante el desarrollo siempre que emplees ideas tomadas de la bibliografía. Esta sección incluye las referencias bibliográficas correspondientes, en formato APA.
