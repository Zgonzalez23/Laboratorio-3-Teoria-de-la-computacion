# Laboratorio-3-Teoria-de-la-computacion

La siguiente gramática libre de contexto corresponde a una simplificación del programa de referencia,
el cual solo tiene soporte para: `<asignacion_expresion>`, porque JFLAP no permite separar la fase lexica 
de la sintactica.

Lo que nos llevo a tomar la decición anterior fue:

1. La gran cantidad de tiempo que se tardaba en interpretar una entrada.
2. El desperdicio de memoria al momemto de interpretar una entrada.
3. Los cierre forzados del programa que surgieron a causa de los puntos anteriores.

