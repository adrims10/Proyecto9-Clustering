
# Proyecto9-Clustering
![empresa](https://github.com/user-attachments/assets/e8aa01b4-c7a2-461b-8f4d-945474200af8)


Bienvenidos!

# *Es un placer recibirlos*

## Introducción

En este proyecto, asumiremos el rol de cientifico de datos en una empresa de comercio global. La compañía busca comprender mejor su base de clientes, productos y operaciones para tomar decisiones informadas que maximicen el beneficio y optimicen sus procesos.

Trabajaremos con un conjunto de datos del comercio global que incluye información sobre ventas, envíos, costos y beneficios a nivel de cliente y producto. Tu tarea será segmentar los datos mediante clustering y luego diseñar modelos de regresión específicos para cada segmento, lo que permitirá obtener insights personalizados sobre los factores que influyen en el éxito de la compañía.

## 🗂️ Estructura del Proyecto

    ├── notebooks/           # Notebooks de Jupyter donde se encontraran la exploracion y clusterizacion y los modelos predictivos de los cluster
    ├── src/                 # Soportes de funciones.
    ├─  Datos                # Datos para el estudio del modelo
    ├── README.md            # Descripción del proyecto.

## 🛠️ Instalación y Requisitos  
Este proyecto utiliza Python 3.12.6.

### **Librerías utilizadas**  
- **pandas**  
  Utilizado para la manipulación y análisis de datos.  
  - [Documentación de Pandas](https://pandas.pydata.org/pandas-docs/stable/)  

- **numpy**  
  Ayuda en cálculos numéricos eficientes y matrices multidimensionales.  
  - [Documentación de NumPy](https://numpy.org/doc/)  

- **os**  
  Gestiona las operaciones del sistema operativo, como la navegación de directorios.  
  - [Documentación de os](https://docs.python.org/3/library/os.html)  

- **sys**  
  Permite acceder a variables y funciones específicas del intérprete de Python.  
  - [Documentación de sys](https://docs.python.org/3/library/sys.html)  

- **seaborn**  
  Facilita la creación de gráficos estadísticos atractivos y fáciles de interpretar.  
  - [Documentación de Seaborn](https://seaborn.pydata.org/)  

- **matplotlib.pyplot**  
  Herramienta para crear visualizaciones básicas y avanzadas en Python.  
  - [Documentación de Matplotlib](https://matplotlib.org/stable/contents.html)



**Resultados , Conclusiones**

# CLUSTERIZACION MEDIANTE EL METODO KMEANS.

![image](https://github.com/user-attachments/assets/436c7d65-15c7-4e52-8ec6-f207838b1729)


Los clústeres parecen tener sentido desde una perspectiva de segmentación de mercado:

* Clúster 0 se enfoca en costos bajos y eficiencia, probablemente adecuado para consumidores sensibles al precio.

* Clúster 1 tiene un enfoque equilibrado, ideal para una variedad de clientes, balanceando costo y beneficio.

* Clúster 2 se centra en alta demanda y rapidez, adecuado para clientes corporativos que valoran el tiempo sobre el costo.

# METODOLOGIA DE LAS PREDICCIONES O MODELOS PREDICCTIVOS.

Se han entrenado varios modelo sobre cada cluster, variando hiperparametros sobre el mismo notebook(para no repetir el mismo modelo pero con diferentes hiperparametros). Posteriormete hemos usado otro modelo mas basico sin hiperparametros que ha dado algun resultado para el cluster dos, pero sin resultado favorable para el cluster 3. 


# MEDIDAS DE PREDICCION DEL CLUSTER 1

* Nos quedamos con el modelo predictivo ramdom forest:

![image](https://github.com/user-attachments/assets/11bce9e7-fa3a-485a-8d0b-eba48d4ce10a)

El valor del R2 indica que aproximadamente el 63% de la variabilidad en el conjunto de entrenamiento y el 60% en el conjunto de prueba pueden ser explicados por el modelo. Aunque estos valores no son extremadamente altos, sugieren que el modelo tiene una capacidad moderada para explicar la variabilidad en los datos.

Un RMSE de alrededor de 40 sugiere que el error promedio de las predicciones del modelo es de unas 40 unidades. La pequeña diferencia entre train y test nuevamente indica que el modelo es relativamente consistente entre los conjuntos de datos.

# MEDIDAS DE PREDICCION DEL CLUSTER 2

![image](https://github.com/user-attachments/assets/fc400777-0140-4d6c-996c-5cc386e7d687)


El modelo tiene un rendimiento aceptable, con un R² que sugiere que está capturando bien las variables predictoras. 

El RMSE podría indicar que hay margen para reducir el error absoluto. Aunque viendo los margenes en los que se mueve este cluster y viendo la incapacidad del resto de modelos usados que podemos ver en los notebooks de predecir nos quedamos con esta predicción contando que tenemos que mejorar un poco mas ese r2.

# MEDIDAS DE PREDICCION DEL CLUSTER 3

No se ha conseguido un modelo solido para la prediccion del profit para el cluster 3 por lo que no vamos a sacar conclusiones de los varios modelos que se han entrenado para este cluster. Podemos observar en los nootebooks las diferentes formar de entrenamiento.



# **Proximos pasos**

-Clusterizar con el metodo aglomerativo: Hemos intentado pero despues de 466 minutos de computacion no hemos conseguido sacar parametros.

![Captura](https://github.com/user-attachments/assets/18d6b16a-3625-4cf8-ae45-bdb592f42169)  

*Caracteristicas del equipo*: 8 nucleos de intel icore 7 de 8 generacion y 8 GB de RAM

Además despues de mas de una hora tampoco nos has sacado los cluster utilizando medidas ward y 3 clusters por defecto.

-Clusterizar mediante DBUSCAN, se ha clusterizado con este metodo pero salen unos 47 cluster por lo que tendriamos que averiguar nuevos parametros.

-Mejorar metricas de los modelos predictivos.

-Preprocesar con diferentes tratamientos de datos.



![OIP](https://github.com/user-attachments/assets/a3261f22-9193-45df-bf33-14a396dfd988)
>>>>>>> 8f412e9a392de6b649e22e88e24aebf7052c8375
