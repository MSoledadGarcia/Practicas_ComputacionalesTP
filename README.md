# Practicas_ComputacionalesTP
## Trabajo práctico de la materia Matemática Discreta - Lic. en Cs. de Datos -  UNSAM. -  TRANSFORMACIONES LINEALES

El cálculo exacto de áreas y volúmenes de objetos que se encuentran en el plano o en el espacio es una propiedad que solo se puede asignar a unos pocos objetos. En la mayoría de los casos, el área (o volumen) del objeto de estudio debe ser calculada de manera aproximada.
Un método posible para el cálculo de áreas (y volúmenes) consiste en generar una región que contenga al objeto de estudio y cuya área (o volúmen) sea conocida o fácilmente calculable, luego, se llena esa región con samples generados de manera aleatoria, siguiendo una distribución uniforme, y se encuentra la relación entre la cantidad total de samples generados dentro de la región ( NR ) y la cantidad de samples que cayeron dentro del objeto ( NO ). El área del objeto de estudio estará dada por,

$A_O \approx \frac{N_O}{N_R} A_R \ .$

La aproximación será más precisa cuanto mayor sea la cantidad de samples generados.
_____________________________________________________________________________________________________________________________________
## Tarea:

A continuación, se proporcionan 3 arrays diferentes de numpy en formato .txt. Subir estos archivos a un script de Python y analizar la forma de cada uno de ellos. Notará que son matrices de 2xN, es decir, cada matriz está compuesta por N puntos, donde las componentes x e y de los puntos están dadas por la primera y segunda fila. Realizar un gráfico (plot) para visualizar cómo se distribuyen los puntos correspondientes a cada una de las matrices en el espacio. Notará que las figuras resultantes son bien conocidas, algunas de las cuales pertenecen a la familia de las secciones cónicas.

__________________________________________________________________________________________________________________________________________

# Área de un círculo:

![image](https://github.com/user-attachments/assets/d8ca8757-e6e4-4015-b4e6-5b06e205b882)

![image](https://github.com/user-attachments/assets/6934ee93-781f-4215-9db4-039e35add483)

![image](https://github.com/user-attachments/assets/201741e7-73e3-42f6-a409-6d808e8c2279)

![image](https://github.com/user-attachments/assets/74366a06-7a85-4ee8-824b-03c1dc23ddf0)

# Área de un triángulo:

![image](https://github.com/user-attachments/assets/f6dfa3ee-6e0c-4607-987f-fa411acc4309)

![image](https://github.com/user-attachments/assets/3443cdf1-fa82-4fb9-acfb-042328fdef59)

![image](https://github.com/user-attachments/assets/671bb39d-9141-446d-b12a-b6fb6185da5e)


# Área de un paralelogramo

![image](https://github.com/user-attachments/assets/72b4dc17-7739-43bd-bada-4e2a885abf9d)

![image](https://github.com/user-attachments/assets/aa2924fc-efb1-4fe7-b3d5-7805582834ab)

![image](https://github.com/user-attachments/assets/b2f43f0d-d895-46df-8b12-e6548b8a442a)






