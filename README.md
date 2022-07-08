# INFORME-laboratorio-5
laboratorio 5
UNIVERSIDAD DE LAS FUERZAS ARMADAS

DEPARTAMENTO DE ELECTRICA Y ELECTRÓNICA

FUNDAMENTOS DE CIRCUITOS ELECTRICOS

Nombres : Martin Coronel, Jefferson Chicaiza, Tito Obando

NRC: 10133

1.OBJETIVOS

Objetivo General

Analizar el voltaje y la corriente solicitados en los diferentes componentes de un circuito cerrado, mediante una práctica de laboratorio para comprender cómo funciona el teorema de Thevenin y un circuito Equivalente.

Objetivo Especificos

Conocer los conceptos del teorema de Thevenin para mantener una idea calra de lo que tarta.

Realizar un circuito cerrado en un protoboard siguiendo la estructura dada por el docente, para analizar la corriente y voltaje de un circuito Equivalente a Thevenin.

Medir con el multimetro valores de las corrientes y volatje tanto en el circuito original como en el equivalente.

Comparar los valores calculados con los valores medidos para determinar mayor validez a nuestro analisis.

2.MARCO TEORICO

![image](https://user-images.githubusercontent.com/84789271/178023377-9d6ef39b-5379-435e-b404-2b7f1eda6a25.png)

3.MATERIAL Y EQUIPO REQUERIDO

![image](https://user-images.githubusercontent.com/84789271/178023497-b7d50026-afe0-4b75-931a-93c7760482fb.png)

4.EXPLICACIÓN DEL PROCEDIMIENTO

1.Arme el circuito que se muestra en la figura 5.1.

![image](https://user-images.githubusercontent.com/84789271/178023559-ebb6cdb3-7e35-4ff0-9804-927044f201af.png)

![image](https://user-images.githubusercontent.com/84789271/178023612-a4630e76-35b8-4769-b621-55881d91f793.png)

Primeramente se observa el funcionamiento del circuito eléctrico en base al diagrama propuesto por el docente.

2.Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.2.

![image](https://user-images.githubusercontent.com/84789271/178023671-1fe42a9a-8c4d-4882-9880-355b14994563.png)

Aquí se observa la medición del voltaje en R5.

![image](https://user-images.githubusercontent.com/84789271/178023736-b7c09c4d-81df-46d1-8392-83284dd07ce2.png)

De la misma manera, se observa la corriente que actúa en la resistencia R5.

3.Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor medido en la tabla 5.1.

![image](https://user-images.githubusercontent.com/84789271/178023786-fe2cd5e0-1ce9-4a71-9ec6-5d628af6ee9b.png)

Aquí se muestra el voltaje obtenido al remover la resistencia R5 y medirlo a partir de un circuito abierto y evidentemente ese valor representa el voltaje de Thevenin.

4.Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 5.1.

![image](https://user-images.githubusercontent.com/84789271/178023824-d4e38723-cae9-4020-ac41-651204c4c885.png)

Haciendo corto a cada una de las fuentes de alimentación del circuito es decir reemplazandolas a partir de sus resistencias internas que equivalen a cero.

5.Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2

![image](https://user-images.githubusercontent.com/84789271/178023874-4d743221-38b0-4709-b317-2cb36b092b27.png)

![image](https://user-images.githubusercontent.com/84789271/178023896-c2ec10a1-2027-4754-a6df-5b9e5a3b0eb4.png)

Aquí se muestra el circuito equivalente de Thevenin con el circuito original, evidentemente la corriente y el voltaje son valores muy aproximados a los valores del circuito original en R5.

CIRCUITO DE THEVENIN ARMADO ANALITICAMENTE

Primeramente, se remueve la resistencia R5 del circuito

![image](https://user-images.githubusercontent.com/84789271/178023991-716dc0f5-cd79-4756-b76f-57e35a25e5bc.png)

Se calcula el voltaje en R3 mediante el método de tensiones en los nodos es importante mencionar que R4 ya no pertenece al circuito cerrado dado que una de sus ramas ya no conecta al circuito.

![image](https://user-images.githubusercontent.com/84789271/178024031-f5feee49-3c5f-40f3-a804-5b1be1b97e72.png)

![image](https://user-images.githubusercontent.com/84789271/178024059-5791bd46-5c3b-42ca-a353-7abfc1b22a02.png)

Mediante Symbolab se pudo obtener el valor de V1 al que equivale a “X” para luego reemplazar y obtener una de las corrientes que pasa por R3, finalmente obtener su voltaje.

![image](https://user-images.githubusercontent.com/84789271/178024115-d18a5280-0903-4f11-b1d0-f9cc77076c77.png)

Después hacemos corto a cada una de las fuentes de voltaje para obtener la resistencia equivalente de todo el circuito.

![image](https://user-images.githubusercontent.com/84789271/178024151-4f58133d-16f4-4663-b758-d11e16a42239.png)

![image](https://user-images.githubusercontent.com/84789271/178024187-67469215-5403-4bdf-b132-aacf3002977b.png)

Finalmente se realiza el circuito equivalente de Thevenin

![image](https://user-images.githubusercontent.com/84789271/178024234-0dc04cba-06a8-4196-9b65-253b33e580b6.png)

Aquí se calcula el voltaje y la corriente del circuito equivalente al original en la resistencia de carga o R5

![image](https://user-images.githubusercontent.com/84789271/178024288-919f0ccf-31da-4952-a418-4acf8b26858b.png)

Finalmente se muestra los datos puestos en las respectivas tablas

![image](https://user-images.githubusercontent.com/84789271/178024403-cf177882-5073-47c9-925b-efa7225aa78e.png)

![image](https://user-images.githubusercontent.com/84789271/178024419-ead824e2-7bf6-496c-aeb1-0e8345a516b6.png)

5. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

Evidentemente se muestra que tanto el circuito Equivalente de Thevenin y el circuito original lanzan valores muy similares en los voltajes y corrientes respecto a la resistencia de carga R5. Por lo que el margen de error tiende a ser cero.

![image](https://user-images.githubusercontent.com/84789271/178024473-fa00c65e-70a0-471d-87e3-5f53a8de8557.png)

6. VIDEO:



7. CONCLUSIONES

En conclusion, debemos tener los conceptos claros en lo que se refiere a corriente y a la definición del teorema de thevenin nos ayudó a medir de forma precisa la corriente, voltaje y la resistencia equivalente del circuito original.

Se pudo observar que el teorema de thevenin es un metodo muy eficiente para realizar circuitos equivalentes.

Los valores analiticos, experimentales y simulados muestran una gran semejanza entre ellos, lo que signfica que la corriente y voltaje obtenidos del circuito cerrado y equivalente son en cierta manera precisos.

8. BIBLIOGRAFÍA

Floyd, T. (2007). Principios de circuitos electricos (Ed. 8va). Pearson EDUCATION

