# Predicción de la Estructura Secundaria de Proteinas usando CNN
Este proyecto se centra en el uso de Redes Neuronales Convolucionales (CNNs) en la predicción de la estructura secundaria de las proteínas a partir de su estructura primaria.

## Dataset
- Consiste en 6133 proteinas, cada una tiene 39900 características. Estas se describen por una matriz de 700 por 57 características. 

- Las 57 características están divididas de la siguiente manera: las primeras 22 representan la estructura primaria (20 aminoácidos, 1 aminoácido desconocido o cualquier aminoácido, 1 ‘No Seq’ -relleno-), 22 los Perfiles de Proteínas (igual que la estructura primaria) y 9 son la estructura secundaria (8 posibles estados, 1 ‘No Seq’ -relleno-)

- También se presenta una versión reducida del dataset original donde solo se incluyen 1500 proteínas
  
## Redes neuronales
- Se entrenaron dos redes neuronales una para clasificar entre 3 de las estructuras secundarias y otra para clasificar entre 8 de las estructuras secundarias.
- prediccion_Q3 y prediccion_Q8 respectivamente
