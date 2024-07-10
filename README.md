# TPN-1
Trabajo Practico N°1

Autor: Aristimuño,Gustavo A 

email:profesor.aristimuno@gmail.com

github cuenta:ProfAristi

Objetivo: Desarrollar un sistema PLC (Controlador Lógico Programable) que me permita automatizar pequeños dispositivos en el aula en colegios secundarios y/o terciarios.
## Descripción:
El sistema debe conectarse con distintos Sensores y Actuadores de 24V de CC, en esta 1er etapa se conectarán en forma discreta. 8 entradas Digitales OptoAisladas  y 4 Salidas Relé.
## IMPORTANTE
Cada un segundo se enciende y se apaga un LED que indica que el sistema está activo y funcionando bien.
Cada un segundo se envía a través del puerto (serie , USB, ethernet) un resumen del estado del sistema, que será parametrizable:
## Plataforma de desarrollo: NUCLEO-F439ZI
Periféricos a utilizar 1er Etapa:
● ENTRADAS: MARCA OPENMOLO , MODULO DE  8 ENTRADAS DISCRETAS, DIGITALES OPTOAISLADAS
● SALIDAS: MODULO 4 SALIDAS RELE
● UART: Se utiliza para enviar información de estado del sistema a la PC
DIAGRAMA EN BLOQUES 
