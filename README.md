# Informe-Laboratorio5

<div align="center">

# UNIVERSIDAD DE LAS FUERZAS ARMADAS ESPE

AUTORES

Coba Flores Víctor Steve

Quichimbo Simba Andrea Estefania

Titoaña Tigse Leslie Brigitte

NRC
  
5412

INGENIERO

Ing. Darwin Omar Alulema Flores

# PRÁCTICA No. 5 TEOREMA DE THÉVENIN
  
</div>

# 1 OBJETIVOS

**1.1. OBJETIVO DE LA PRÁCTICA**

1.1.1. Objetivo general

- simplificar los cálculos de un sistema eléctrico complejo por un circuito eléctrico equivalente mucho mas simple, constituido por una fuente de tensión y una resistencia, supongamos un circuito eléctrico lineal complejo y queremos establecer el circuito de Thévenin entre los dos terminales A y B. 

1.1.2. Objetivos específicoso

- Conocer los fundamentos básicos de estos teoremas y su aplicación.
- Analizar el circuito DC mediante la aplicación de los Teorema Thevenin.
- Verificar los parametros Vth, Rth, Int, Rnt, determinados para los teoremas de thevenin y norton
- Comprobar experimentalmente que se cumplan los teoremas en estudio.

**1.2. REQUISITOS PREVIOS**

Para el circuito mostrado en la figura 5.1:

a) Determine el valor de voltaje y corriente en el resistor R5. Anote los resultados en la tabla 5.2.

b) Obtenga los valores del circuito equivalente de Thévenin y anótelos en la tabla 5.1.

**1.3. INFORMACIÓN GENERAL**

A través de la aplicación del teorema de Thevenin, se logra que un circuito complejo se convierta en uno más simple. De esta manera, se expresa que al estar existir dos terminales A y B dentro de la estructura de un circuito eléctrico lineal, es posible convertirlo a un circuito equivalente más simple. La teoría expresa que a través de la resistencia del circuito transformado la corriente seguirá circulando.

El hallazgo de esta idea data para el año1853. Fue el científico alemán Hermman von Helmholtz quien por primera vez dio evidencia del procedimiento que demostraba válido el postulado. Pero no hubo ningún interés para el momento acerca de esta teoría, y quedó en el olvido hasta el año 1883, cuando el francés León Charles Thévenin, un ingeniero en telégrafos, redescubre el teorema, siendo bautizado bajo su apellido.

# 2 MARCO TEÓRICO

<div align="center">
  
![image](https://user-images.githubusercontent.com/84430867/127091201-c6fa2ec1-d94c-47a3-9ee8-9186b49b899e.png)

</div>

# 3 MATERIAL Y EQUIPO REQUERIDO

<div align="center">
     
|**CANTIDAD**|       **MATERIAL O EQUIPO**      |
|    :---:   |              :---:               | 
|      2     |     Fuente de Voltaje de C.D.    |
|      2     |       Multímetros Digitales      |
|      1     |        Resistor de 560 Ω         |
|      1     |        Resistor de 4.7 kΩ        |
|      1     |         Resistor de 330 Ω        |
|      1     |         Resistor de 100 Ω        |
|      1     |         Resistor de 1 kΩ         |
|      1     |Potenciómetro de precisión de 1 kΩ|
|      1     |            Protoboard            |
</div>

# 4 EXPLICACIÓN DEL PROCEDIMIENTO

**4.5 PROCEDIMIENTO**

**4.5.1. Arme el circuito que se muestra en la figura 5.1.**

<div align="center">
  
![image](https://user-images.githubusercontent.com/84430867/126659397-327db8d7-cb83-48f9-a45a-8dd9c84153d4.png)

</div>

**4.5.2. Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.2.**

Seleccionamos los materiales para proceder armar el circuito.

<div align="center">

![image](https://user-images.githubusercontent.com/84430867/126660652-6724e45b-5b9d-495a-a591-32cbc3e0bdc1.png)

</div>

Colocamos las resistencias al Protoboard siguiendo el diagrama espermático dado.

<div align="center">

![image](https://user-images.githubusercontent.com/84430867/126661089-4018068c-3e93-4273-ace3-f011863fa549.png)

</div>

Interconectamos las resistencias en el Protoboard siguiendo el circuito dado.

<div align="center">

![image](https://user-images.githubusercontent.com/84430867/126932226-5017a55d-6fa4-4b2c-8738-d23c0f34758f.png)

</div>

Conectamos el Protoboard a la fuente de alimentación (rojo+,negro -)e iniciamos la simulación con el circuito terminado.

<div align="center">

![image](https://user-images.githubusercontent.com/84430867/126932554-57636826-7c6b-4813-b1de-f5771894b01c.png)
 
</div>

**4.5.3. Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor
medido en la tabla 5.1.**

<div align="center">
  
![image](https://user-images.githubusercontent.com/84430867/126933172-484b9561-1913-4b98-bef9-5767a9c1aa15.png)
 
</div>

**4.5.4. Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito
abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 5.1.**

<div align="center">

![image](https://user-images.githubusercontent.com/84430867/127095126-bdf468eb-f513-4302-b6eb-7484ca6733de.png)

</div>

**4.5.5. Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la
corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2.**
 
<div align="center">

![image](https://user-images.githubusercontent.com/84587293/127081283-f27dcc7d-163f-42f9-aeae-0412a16e3159.png)
  
Tabla 5.1. Valores del Circuito Equivalente de Thévenin
     
|  VTH (V)  |            |     RTH (Ω)   |           |
|    :---:  |    :---:   |     :---:     |   :---:   |    
| Calculado |  5.05 V    |   Calculado   | 298.85 Ω  |  
|   Medido  |  5.06 V    |     Medido    |   299 Ω   |   
  
Tabla 5.2. Comprobación del Teorema de Thévenin.
  
|**PARÁMETRO ELÉCTRICO**| **CIRCUITO ELÉCTRICO** | | **CIRCUITO EQUIVALENTE DE THÉVENIN** ||
|     :---:    |   :---:   |     :---:     |   :---:       |    :---:    |  
|              | Calculado |     Medido    |   Calculado   |   Medido    |   
|  Voltaje (V) |  3.84 V   |     3.89 V    |    3.88 V     |   3.89 v    |  
|Corriente (mA)|  3.84 mA  |    3.89 mA    |    3.88 mA    |   3.89 mA   |

</div>

**4.5.5. Verifique el cumplimiento del Teorema de Superposición y compare los
resultados obtenidos prácticamente con los obtenidos analíticamente. Realice sus
conclusiones.**

**Procedimiento Analítico**

<div align="center">
  
![1](https://user-images.githubusercontent.com/84587172/127082076-45173429-3304-4750-8963-866234beab39.png)

![2](https://user-images.githubusercontent.com/84587172/127082110-26835ef5-7d4b-4c49-9113-946a75008190.png)

![3](https://user-images.githubusercontent.com/84587172/127082133-eef24638-7c0d-4a56-8d82-0fe8c0dc4322.png)
  
![4](https://user-images.githubusercontent.com/84587172/127082166-36e2a516-fca3-45d0-921b-9fc033e8b5c0.png)

![5](https://user-images.githubusercontent.com/84587172/127082190-1acacf2b-26f8-4f97-9a6d-29adc303c273.png)

![6](https://user-images.githubusercontent.com/84587172/127082211-15ca9af1-4591-4a2b-bd94-a661a7e0ebad.png)

  ![7](https://user-images.githubusercontent.com/84587172/127082231-5d99f79f-915d-4fe9-b5fc-178d5a570bed.png)

![8](https://user-images.githubusercontent.com/84587172/127082255-d1f194e5-b939-44a9-a365-a5eacd6eedd7.png)
  
![1](https://user-images.githubusercontent.com/84587172/127094806-111c26d6-166a-4523-b69b-d840c85d2f76.png)

![2](https://user-images.githubusercontent.com/84587172/127094811-2a83ebcd-6230-4120-8437-221c67fd10a7.png)

![3](https://user-images.githubusercontent.com/84587172/127094820-51132bd8-a2fd-486d-bf4b-d99e75f1fd56.png)

![4](https://user-images.githubusercontent.com/84587172/127094827-1e548aae-9c18-464e-82db-e0101342be3b.png)

![5](https://user-images.githubusercontent.com/84587172/127094832-1b59dab3-c91b-46be-8130-c17a347d5453.png)

![6](https://user-images.githubusercontent.com/84587172/127094835-d9ce4db7-b315-4d48-9727-b851b29f6b41.png)

![7](https://user-images.githubusercontent.com/84587172/127094843-2cd1c44a-bc62-45f4-ade5-4e76517533cb.png)

![8](https://user-images.githubusercontent.com/84587172/127094857-290ae6fd-bbba-4dc5-bb03-197a2dfdfeb3.png)

![9](https://user-images.githubusercontent.com/84587172/127094861-1965bf68-09f8-4091-ab1c-28576fd2b22d.png)
  
  
</div>

**Cálculo del Error**

<div align="center">

![1](https://user-images.githubusercontent.com/84587172/127096148-70a15118-33c5-4a33-bd90-8f66d940f61a.png)

![2](https://user-images.githubusercontent.com/84587172/127095999-bdb02682-cc40-4daa-b92d-2363ee73f885.png)

</div>
  
# 5 VIDEO 

https://youtu.be/qPvZ6IOeJFA

# 6 CONCLUSIONES 

- El circuito obtenido luego de aplicar el teorema de thévenin es mucho mas simple y rapido para calcular voltajes y corrientes o la potencia capaz de entregar un circuito al conectar una carga.

- Este teorema se puede aplicar a cualquier elemento del circuito, siempre y cuando la red tenga al menos una fuente independiente.

- Permiten encontrar un circuito equivalente de manera simple y rápida aun en circuitos de naturaleza complicados.

# 7 BIBLIOGRAFÍAS

ANÁLISIS DE CIRCUITOS Y SISTEMAS LINEALES. (s.f.). Obtenido de https://innovacionumh.es/Proyectos/P_19/Tema_1/UMH_07.htm

ECURED. (22 de 11 de 2013). Obtenido de Teorema de Thévenin: https://www.ecured.cu/Teorema_de_Th%C3%A9venin

Veloso, C. (25 de 05 de 2017). Obtenido de TEOREMA DE THÉVENIN – CIRCUITO EQUIVALENTE: https://www.electrontools.com/Home/WP/teorema-de-thevenin-circuito-equivalente/


