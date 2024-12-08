<<<<<<< HEAD

<div style="text-align: center;">
  <img src="https://github.com/Hack-io-Data/Imagenes/blob/main/01-LogosHackio/logo_celeste@4x.png?raw=true" alt="esquema" />
</div>


# Proyecto Clustering y Modelos de Regresión

En este proyecto, asumirás el rol de **cientifico de datos en una empresa de comercio global**. La compañía busca comprender mejor su base de clientes, productos y operaciones para tomar decisiones informadas que maximicen el beneficio y optimicen sus procesos. 

Trabajarás con un conjunto de datos del comercio global que incluye información sobre ventas, envíos, costos y beneficios a nivel de cliente y producto. Tu tarea será segmentar los datos mediante **clustering** y luego diseñar modelos de **regresión** específicos para cada segmento, lo que permitirá obtener insights personalizados sobre los factores que influyen en el éxito de la compañía.


## Objetivo del Proyecto

La empresa tiene las siguientes preguntas clave:

1. **¿Cómo podemos agrupar a los clientes o productos de manera significativa?**

   - Por ejemplo, identificar clientes según su comportamiento de compra o productos según su rentabilidad.

2. **¿Qué factores son más relevantes para predecir el beneficio o las ventas dentro de cada grupo?**

   - Esto ayudará a diseñar estrategias específicas de marketing, optimizar precios o ajustar políticas de descuento.

3. **¿Cómo podemos utilizar estos *insights* para tomar decisiones estratégicas?**

   - Por ejemplo, enfocarse en los segmentos más rentables o intervenir en los menos rentables.

Para contestar estas preguntas, el objetivo en este proyecto es realizar: 

1. **Clustering**: Realizar un análisis de segmentación para agrupar clientes o productos según características clave, las cuales deberás elegir personalmente además de justificar el porque de su elección.

2. **Regresión por Segmentos**: Diseñar modelos de predicción para cada segmento, explicando las relaciones entre variables, intentando predecir el total de ventas en cada uno de los segmentos. 

## Estructura del Proyecto

1. **Preparación de los Datos**:

   - **Carga de datos**: Familiarízate con las variables incluidas en el conjunto de datos (por ejemplo, ventas, costo de envío, beneficio, categoría de productos).

   - **Limpieza de datos**: Maneja valores faltantes, elimina duplicados y identifica y trata *outliers*.

   - **Transformaciones**: Normaliza variables numéricas y codifica variables categóricas si es necesario.

2. **Clustering**:

   - **Elección de variables**: Selecciona atributos clave para agrupar a los tipos de ventas que hacemos como empresa (por ejemplo, `Sales`, `Profit`, `Discount`, `Shipping Cost`).

   - **Escalado**: Normaliza las variables para evitar que algunas dominen sobre otras.

   - **Método de clustering**: Aplica algoritmos como K-means, clustering jerárquico o DBSCAN.

   - **Evaluación**: Determina el número óptimo de clusters usando técnicas como el método del codo o el coeficiente de silueta.

   - **Interpretación**: Analiza los clusters resultantes e interpreta su significado en términos de comportamiento del negocio.


3. **Modelos de Regresión por Clusters**:

   - **Variable objetivo**: Define una métrica clave para predecir (por ejemplo, `Sales`).

   - **Segmentación**: Ajusta un modelo de regresión para cada cluster, utilizando las variables disponibles.

   - **Evaluación**: Evalúa el desempeño de los modelos usando métricas como R², MAE o RMSE.

   - **Comparación entre clusters**: Identifica diferencias en los factores clave que impactan el beneficio en cada grupo.

4. **Entrega de Insights**:

   - Responde preguntas del negocio basándote en los resultados del clustering y los modelos de regresión.

   - Propón recomendaciones accionables para la empresa.


## Como Entregar el Proyecto

La entrega del proyecto se realizará a través de una **issue en GitHub**, trabajando en un repositorio propio en tu cuenta personal. Los pasos que deberás seguir para hacer la entrega del proyecto son:


- **Crear un nuevo repositorio en tu cuenta de GitHub:**

   - Crea un nuevo repositorio llamado `Proyecto9-NombreProyecto`. Este nombre es obligatorio, no podremos llamarlo de otra forma. 

   - Configuralo como público. 


- **Desarrolla el proyecto:**

   - Implementa el código para la resolución del problema.

   - Recuerda hacer commits regulares mientras avanzas en el desarrollo:

     ```bash
     git add .
     git commit -m "Descripción del avance"
     git push
     ```


- **Crear una issue en el repositorio original del curso:**

   - Ve al repositorio original del curso y dirígete a la pestaña de **Issues**.

- **Abrir una nueva issue para tu entrega:**

   - Haz clic en **New Issue** y llena los siguientes campos:

     - **Título:** Usa el formato "Entrega Proyecto: ProyectoXXXX - [Tu Nombre]".

     - **Descripción:** En la descripción, incluye:

       - Una breve explicación de tu proyecto.

       - Instrucciones para ejecutar tu código (si aplica).

       - Un enlace a tu repositorio personal donde está alojado el proyecto.


## 🚀 Entrega del Proyecto 🚀

**Fecha y hora límite:**

🗓️ **Lunes a las 9:00 AM.**


**Nota importante:**

⚠️ **Todos los proyectos que sean entregados o modificados después de la hora límite (lunes a las 9:00 AM) se considerarán como no entregados.** Por favor, asegúrate de completar y enviar tu trabajo a tiempo para evitar problemas.


# 🎤 Presentación de Proyectos 🎤

El lunes tendremos las **presentaciones de los proyectos**. La dinámica será la siguiente:

- De forma **aleatoria**, seleccionaremos entre **3 y 5 alumnos** para presentar su proyecto.

- Cada alumno tendrá **5 minutos** para explicar su proyecto y hacer una demo en vivo. Durante este tiempo podrán mostrar cómo funciona su juego y resaltar las características principales.

**Detalles importantes:**

- Es importante que lleguéis puntuales, ya que comenzaremos las presentaciones de inmediato.

- Asegúrate de que tu código esté listo y funcional para la demo.

- Todos debemos estar preparados para presentar, ya que la selección será completamente aleatoria.

=======
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
