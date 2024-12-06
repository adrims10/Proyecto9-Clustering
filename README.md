# Proyecto9-Clustering
![OIP (3)](https://github.com/user-attachments/assets/14183db5-eff2-4f77-9d41-962bbec3bcf0)

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


# MEDIDAS DE PREDICCION DEL CLUSTER 1










**Proximos pasos**

-Clusterizar con el metodo aglomerativo: Hemos intentado pero despues de 433 minutos de computacion no hemos conseguido sacar parametros.
Además despues de mas de una hora tampoco nos has sacado los cluster.

-Clusterizar mediante DBUSCAN, se ha clusterizado con este metodo pero salen unos 47 cluster por lo que tendriamos que averiguar nuevos parametros.

-Mejorar metricas de los modelos predictivos.

-Preprocesar con diferentes tratamientos de datos.



![OIP](https://github.com/user-attachments/assets/a3261f22-9193-45df-bf33-14a396dfd988)