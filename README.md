# Informe de trabajo extra - Amplificador no inversor
Amplificador operacional no inversor 

1. OBJETIVOS

- Objetivo general:

  Construir y simular un amplificador no inversor

- Objetivos específicos:

  - Explicar el funcionamiento de un amplificador operacional no inversor
  
  - Fabricar un circuito que duplique su voltaje de entrada 

2. MATERIALES

- Batería de 3.5 V
- Dos resistencias de 1000 ohmios
- Cable amarillo y negro 
- Amplificador operacional 741
- Potenciómetro
 
3. MARCO TEÓRICO
 
 ![Untitled](https://user-images.githubusercontent.com/93950169/156994241-fb8f3bee-2726-4ae8-bda9-154a5e5d4f6e.jpg)

4. PROCEDIMIENTO

Se sabe que I=V/R

![lagrida_latex_editor (30)](https://user-images.githubusercontent.com/93950169/156994644-cd98ba09-81a8-4cf4-949b-9459d4f59381.png)

![lagrida_latex_editor (31)](https://user-images.githubusercontent.com/93950169/156994817-f6bb6268-2e41-4537-9a72-54e48a2e2f33.png)

Como Vx=Vi

![lagrida_latex_editor (32)](https://user-images.githubusercontent.com/93950169/156995038-b6b34aad-1cae-4d92-ad4a-2bff4b59fa1b.png)

![lagrida_latex_editor (33)](https://user-images.githubusercontent.com/93950169/156995171-76a54aea-b974-471c-b1a4-6ed1d66c9968.png)

Se sustituye I1 = I2

![lagrida_latex_editor (34)](https://user-images.githubusercontent.com/93950169/156995445-dce13297-e8b1-4548-9dc5-745ac20b5109.png)

Se despeja V0 (Voltaje de salida)

![lagrida_latex_editor (35)](https://user-images.githubusercontent.com/93950169/156995759-371af431-61d3-4e71-8011-969b21f5466e.png)

Se pretende obtener un voltaje de salida ![lagrida_latex_editor (36)](https://user-images.githubusercontent.com/93950169/156996076-e6a702ce-5973-4441-8f09-7efa81addbb8.png)

Para esto se puede decir que:

![lagrida_latex_editor (37)](https://user-images.githubusercontent.com/93950169/156996360-dc7d789e-4205-4cb5-a2e0-87a45c521952.png)

![lagrida_latex_editor (38)](https://user-images.githubusercontent.com/93950169/156996413-29abe9c2-4ace-4bb0-95c2-792c092841b1.png)

Con estos valores se obtine un oltaje de salida: 

![lagrida_latex_editor (39)](https://user-images.githubusercontent.com/93950169/156996703-49fe8bd4-b727-4b8d-9b14-7c77fab6ea87.png)

Sin embargo con la configuración adoptada, no se puede obtener un voltaje de salida superior al voltaje de la fuente.

Se procede a la simulación del circuito

![image](https://user-images.githubusercontent.com/93950169/156997152-2502565c-133f-4404-bf1a-ea559da86470.png)

Se ejecuta la simulación del circuito en el sitio Tinkercat

![image](https://user-images.githubusercontent.com/93950169/156997520-21f5720e-062f-429a-babc-9bcc03954d38.png)

Se procede a al ensamblaje del circuito

![WhatsApp Image 2022-03-06 at 16 27 57](https://user-images.githubusercontent.com/93950169/156997914-d2d7add0-174a-4756-b7e3-1f0f4f6529be.jpeg)

Como siguiente punto procedemos a medir el voltaje mientras otorgamos un cierto voltaje al ircuito el mismo que es regulado por un potenciometro

![WhatsApp Image 2022-03-05 at 11 50 36](https://user-images.githubusercontent.com/93950169/156998140-de03eb90-62fc-4cd6-b570-03f6395ff9d0.jpeg)

5. VIDEO 

https://www.youtube.com/watch?v=YZuJ4vNUbpw

6. CONCLUSIONES 

- Este amplificador operacional no inversor la salida de la señal no tiene desfase y la ganacia varía de acuerdo al valor de Rf
- La configuración aplicada al amplificador operacional no permite obtener un voltaje mayor al de la fuente de poder, sin embargo duplica el voltaje con una menor cantidad de energia suministrada por la funete de poder regulada por un potenciometro.
- La manera de realizar el cálculo permite anticipar el valor con el que se amplificará el voltaje de entrada.

7. BIBLIOGRAFÍA
  - Youtube.com. 2022. Amplificador Operacional 6 - No Inversor. [online] Available at: <https://www.youtube.com/watch?v=XSnFv-Bn9OE> [Accessed 7 March 2022].
  - Youtube.com. 2022. ✅AMPLIFICADOR NO INVERSOR Teoría | FÁCIL y RÁPIDO| Curso AMPLIFICADORES OPERAcIOnALES. [online] Available at: <https://www.youtube.com/watch?v=tT3LTOkve54&t=63s> [Accessed 7 March 2022].
  - Tinkercad. 2022. Tinkercad | From mind to design in minutes. [online] Available at: <https://www.tinkercad.com/things/17TcM9LPnJZ-amazing-turing/editel> [Accessed 7 March 2022].
