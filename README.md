# ST0256 Tópicos Especiales en Telemática

## Estudiante:
- Nombre: Julian Andres Romero hinestroza
- Correo: jaromeroh@eafit.edu.co

## Profesor:
- Nombre: Álvaro Ospina
- Correo: aeospinas@eafit.edu.co

# Reto 5 -  HDFS y S3

## Cluster e instancias
Cluster definido para el desarollo de los laboratorios 

![image](https://github.com/Pokloskaya/TelematicaLab01/assets/83888452/0b92bebf-a1e9-4bf7-980e-8516857762f3)

![image](https://github.com/Pokloskaya/TelematicaLab01/assets/83888452/eb3cb7d8-00d6-4ab6-abee-c0d52dc65df1)



## Bucket S3

![image](https://github.com/Pokloskaya/TelematicaLab01/assets/83888452/0af53e86-3ea0-4c9b-957e-b7eb199df72c)

## Archivos en HDFS

Se copia el repositorio con el dataset en el nodo maestro del cluster

git clone git@github.com:st0263eafit/st0263-241.git

Se envian los archivos al HDFS con el comando:

hdfs dfs -copyFromLocal
