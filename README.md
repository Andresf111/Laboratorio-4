# Laboratorio-4

1.OBJETIVOS DE LA PRÁCTICA

Comprobar experimentalmente el Teorema de superposición, mediante la simulación de un circuito mixto utilizando laboratorios virtuales, para implementar los conocimientos adquiridos en clase y analizar de forma correcta el circuito planteado.

1.2. OBJETIVOS ESPECÍFICOS

Determinar el fundamento que aplica el Teorema de superposición para el análisis de circuitos eléctricos que cuentan con varias fuentes.
Establecer los pasos básicos que se necesitan para aplicar el Teorema de superposición.
Determinar la utilidad del Teorema de superposición en el análisis de circuitos eléctricos.

2.MARCO TEÓRICO

![image](https://user-images.githubusercontent.com/105291794/176591444-9856a40d-a767-4480-892f-61f231221510.png)

3.EXPLICACIÓN DEL PROCEDIMIENTO

MATERIAL Y EQUIPO REQUERIDO

![image](https://user-images.githubusercontent.com/105291794/176591616-d4cc2ade-0cc5-4d4e-ab3b-901470d443f1.png)

3.1 Arme el circuito que se muestra en la figura 4.1.

![image](https://user-images.githubusercontent.com/105291794/176591937-13ba5f56-1544-4526-abf3-949d6d6296b9.png)

3.2 Con las dos fuentes conectadas, mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

Medición de voltaje y corriente en Tinkercad:

![image](https://user-images.githubusercontent.com/105291794/176592815-30dfc8a9-80ba-4977-82da-37aa417461ad.png)

Simulación Multisim:

![image](https://user-images.githubusercontent.com/105291794/176592849-b6322658-6040-473c-9f7c-1ff1b3324236.png)

3.3 Haga “cero” la fuente de voltaje de 12 V (V2) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

Cuando V2: 12 V es cero

En primer lugar, redibujamos el circuito para analizarlo solo con la fuente de 20V.

![image](https://user-images.githubusercontent.com/105291794/176593197-0331387d-377f-417d-97a7-76480264ddad.png)

Mediante el método de mallas calculamos la corriente y voltaje solicitado.

![image](https://user-images.githubusercontent.com/105291794/176593257-55ab3a8a-f279-407b-a690-f8ab3ca33c5f.png)

El sistema de ecuaciones para encontrar la corriente es:

![image](https://user-images.githubusercontent.com/105291794/176593692-ea3bd087-a2c4-460d-889f-18c53bbdfa33.png)

![image](https://user-images.githubusercontent.com/105291794/176593713-add77348-d175-419f-a0ce-6cfb4fa2afb8.png)

Por tanto, los valores de las corrientes que pasa por cada una de las mallas son:

![image](https://user-images.githubusercontent.com/105291794/176593738-343f2330-ba6a-4871-9c4f-8a37354eddb3.png)

Por lo que, calculando la corriente que pasa por Ix:

![image](https://user-images.githubusercontent.com/105291794/176593766-04df111d-4b86-40b8-a4a3-e1899d80023d.png)

Para calcular el voltaje VA usamos la ley de ohm:

![image](https://user-images.githubusercontent.com/105291794/176593831-9be90921-6748-4ab7-96a5-b63bb00b424e.png)

A continuación, la captura de pantalla de corriente y voltaje medidos tanto en Tinkercad como en multisim:

4.5.3.	Haga “cero” la fuente de voltaje de 12 V (V2) y mida el voltaje VA y la corriente
IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.


![image](https://user-images.githubusercontent.com/105291794/176594893-e0d9e03b-84b9-44e5-9b08-80674878b183.png)

![image](https://user-images.githubusercontent.com/105291794/176594909-0c170287-0581-4a2f-8c6d-81b199d84c92.png)

Finalmente, el valor de la corriente y del voltaje del circuito es:

![image](https://user-images.githubusercontent.com/105291794/176594978-19e384da-e7b0-4d7e-83fb-14a5bc7aff2e.png)

A continuación, la captura de pantalla de corriente y voltaje medidos tanto en Tinkercad como en multisim:

4.5.4.	Haga “cero” la fuente de voltaje de 20 V (V1) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.


![image](https://user-images.githubusercontent.com/105291794/176595718-c7757b93-f4ad-4a5d-bd54-c49b83cf8e44.png)


![image](https://user-images.githubusercontent.com/105291794/176595736-964bab28-9656-4105-9a11-9da1cfa79e1f.png)

Primero redibujamos el circuito para analizar la corriente y voltaje solo con la fuente de 12V.

![image](https://user-images.githubusercontent.com/105291794/176595865-8e7faa1a-ef38-408d-adc0-701c5a7f6dbc.png)

Encontrando la resistencia equivalente para las resistencias de 1.1kΩ y 2.2 kΩ y redibujando el circuito para una mejor comprensión:

![image](https://user-images.githubusercontent.com/105291794/176596543-c00690bb-c2cb-49bb-9ead-4f6698f2ff98.png)

Realizando una suma de las resistencias que se encuentran en serie 0.6875kΩ y las de 0.82kΩ, y redibujando el circuito:

![image](https://user-images.githubusercontent.com/105291794/176596567-4bb6b80b-488b-4c36-a80b-a21c9761b828.png)

Encontrando la resistencia equivalente entre 1.51kΩ y 0.47kΩ que se encuentran en paralelo para obtener la resistencia total:

![image](https://user-images.githubusercontent.com/105291794/176596636-045edcdd-2439-406d-82e1-580de23cb4fc.png)

Calculando la intensidad total del circuito:

![image](https://user-images.githubusercontent.com/105291794/176596653-2a4a8139-c626-44fb-ad2d-f4f6ec03daa9.png)

Aplicando la fórmula del divisor de corriente para encontrar Ix:

![image](https://user-images.githubusercontent.com/105291794/176596681-315a7060-b6a4-4173-a562-753bed017320.png)

Calculando la corriente que circula por la resistencia de 820Ω para luego encontrar el valor del voltaje.

![image](https://user-images.githubusercontent.com/105291794/176596716-f6d760b4-e16d-4a20-9f46-5f717cf1a91b.png)

Para calcular el voltaje VA usamos la ley de ohm:

![image](https://user-images.githubusercontent.com/105291794/176596738-4938e90c-8544-48c3-b01c-658b370e99b8.png)

Pero, como estamos calculando el voltaje con la polaridad opuesta:

![image](https://user-images.githubusercontent.com/105291794/176596757-b41aba06-3672-4cc1-b0f5-b59b901c9e49.png)


Tablas de medición de voltaje y de corriente:

![image](https://user-images.githubusercontent.com/105291794/176597465-52a8e571-1d38-4760-b1aa-d37aa713e588.png)

![image](https://user-images.githubusercontent.com/105291794/176597477-eae466f5-4c33-4802-b721-19e790d20177.png)

4.RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

Para calcular el margen de error efectuado en cada una de las mediciones obtenidas de forma analítica y experimental se usa la siguiente formula del cálculo de error.

![image](https://user-images.githubusercontent.com/105291794/176597536-569a5676-b182-4aec-adcf-2ce117cf3356.png)

Por tanto, el margen de error del cálculo de los datos obtenidos son:

![image](https://user-images.githubusercontent.com/105291794/176597568-7cbc600d-8482-4330-bae2-94ea8df8cb77.png)

6.CONCLUSIONES

El fundamento que emplea el Teorema de superposición se basa en que el voltaje o la corriente que pasa por cualquier elemento de un circuito puede obtenerse sumando algebraicamente todos los voltajes o corrientes individuales generados, a su vez para realizar el análisis se establece que en cualquier rama de un circuito con múltiples fuentes, se puede calcular la corriente o voltaje reemplazando las fuentes por sus resistencias internas, recordando que para una fuente de voltaje su resistencia interna es cero y para una fuente de corriente su resistencia interna se considera infinita.

El Teorema de superposición es de mayor utilidad dentro de circuitos eléctricos que posean 2 o más fuentes de voltaje, dado que, nos permite reducir o redibujar nuestro circuito para analizar de forma individual la corriente o voltaje generado por las fuentes dentro del mismo, es decir que permite transformar un circuito complejo en uno más simple para analizar.

7.BIBLIOGRAFÍA

Floyd, T. (2007). Principios de circuitos eléctricos. México: Pearson.

Obando, L. (08 de Noviembre de 2019). Obtenido de https://dademuch.com/2019/11/08/principio-de-superposicion-analisis-de-circuitos-electricos/



















