# Modelos AR(p)

Analisis de una serie de tiempo con datos históricos para ajustarla de forma óptima a un modelo auto-regresivo adecuado de orden p (denominado AR(p)).

Cargamos librerías e importamos datos a utilizar de precios para la empresa Walt Disney Company para el periodo que va del 1 de Enero del 2023 al 31 de Marzo del 2023
<br>![image](https://github.com/user-attachments/assets/698eb2c8-ea6b-4af1-88fb-9f85a89946a7)

Creamos los grupos de entrenamiento y prueba
<br>![image](https://github.com/user-attachments/assets/ce97fda0-cf02-4381-9b3c-dde8b6f0a873)

Realizamos las pruebas de autocorrelación y autocorrelación parcial
<br>![image](https://github.com/user-attachments/assets/54758cb2-b1ca-494e-92c6-1dd32df742f6)
<br>![image](https://github.com/user-attachments/assets/3b27f897-5452-48d4-9d5b-ade54623f198)

Mediante la prueba de autocorrelación parcial, podemos ver el cambio súbito despues del valor 1, por lo que el modelo AR(1) parece ser el más adecuado
<br>![image](https://github.com/user-attachments/assets/beed631c-155a-4f41-8257-68708f24c726) ![image](https://github.com/user-attachments/assets/039f6cbd-a7cd-463d-8d34-6148c8321528)

Los criterios Akaike y Bayesiano muestran que el modelo es mejor en un valor de 1

Pronosticamos los precios diarios por acción para el mes de Abril del 2023, tanto de manera puntual como mediante un intervalo de confianza del 90%, a partir del resultado obtenido en el punto anterior, p.
<br>![image](https://github.com/user-attachments/assets/a199e061-e53d-4877-8261-f5b5b82c8f58)

Realizamos las transformaciones necesarias para la graficación
<br>![image](https://github.com/user-attachments/assets/3655e94f-3023-4729-8756-d7cabdb7416a)
<br>![image](https://github.com/user-attachments/assets/960c6e74-757e-41ad-9fa6-415e53bea7d5)
<br>![image](https://github.com/user-attachments/assets/3dfd4831-6ab3-4d10-a4c6-82a3a8f5a280)
<br>![image](https://github.com/user-attachments/assets/d3df87b8-cea9-40dc-a789-521293a2381e)

![image](https://github.com/user-attachments/assets/a5978e98-ffea-4179-99d7-d67f33fb5cf8)
<br>![image](https://github.com/user-attachments/assets/cf6445bc-b5e0-4804-8cc7-60dfc1b33be3)

Con estos valores podemos concluir que nuestro pronóstico puede esta 6.17% equivocado y que en promedio, nuestros valores están alejados por 6.29 dólares del valor real
