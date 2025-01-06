# Practicas_ComputacionalesTP
Trabajo práctico de la materia Matemática Discreta - Lic. en Cs. de Datos -  UNSAM. -  TRANSFORMACIONES LINEALES

El cálculo exacto de áreas y volúmenes de objetos que se encuentran en el plano o en el espacio es una propiedad que solo se puede asignar a unos pocos objetos. En la mayoría de los casos, el área (o volumen) del objeto de estudio debe ser calculada de manera aproximada.
Un método posible para el cálculo de áreas (y volúmenes) consiste en generar una región que contenga al objeto de estudio y cuya área (o volúmen) sea conocida o fácilmente calculable, luego, se llena esa región con samples generados de manera aleatoria, siguiendo una distribución uniforme, y se encuentra la relación entre la cantidad total de samples generados dentro de la región ( NR ) y la cantidad de samples que cayeron dentro del objeto ( NO ). El área del objeto de estudio estará dada por,
AO≈ NO/NR * AR . 

La aproximación será más precisa cuanto mayor sea la cantidad de samples generados.

