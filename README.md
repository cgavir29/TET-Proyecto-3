# TET Proyecto 3

El Jupyter Notebook en donde se desarrolló lo que se muestra a continuación se puede encontrar en [covidcs.ipynb](covidcs.ipynb).

## 1. Integrantes

- Santiago Arredondo Quintero
- Camilo Gaviria Castrillón

## 2. Fuentes de Datos

Se descargaron los datasets que había en los enlaces proveídos. Estos se encuentran en el directorio [datasets](datasets).

## 3. Ingesta y Almacenamiento de Datos

La ingesta y almacenamiento de los datos a AWS S3 se hizo con los siguientes pasos:

1. Creamos un _bucket_ en AWS S3 como se observa en las imágenes. ![s3-1](images/s3/img-1.png) ![s3-2](images/s3/img-2.png) ![s3-3](images/s3/img-3.png)
2. Creamos una carpeta _datasets_ donde subiremos los directorios con los correspondientes datasets. ![s3-4](images/s3/img-4.png) ![s3-5](images/s3/img-5.png) ![s3-6](images/s3/img-6.png)
3. Subimos los datos a _datasets_ como se muestra a continuación. Damos click en datasets ![s3-6](images/s3/img-6.png) y después en el botón **Upload**. En la interfaz que se muestra arrojamos nuestras fuentes de datos, ![s3-7](images/s3/img-7.png) unda **Next** hasta que llegue a la siguiente pantalla y asegúrese de poner la configuración que se muestra, ![s3-8](images/s3/img-8.png) ahora presionamos **Upload** y todo quedará listo ![s3-9](images/s3/img-9.png) ![s3-10](images/s3/img-10.png)

## 4. Procesamiento: Análisis Exploratorio de Datos con PySpark

![jupyter-01](images/jupyter/img-01.png) ![jupyter-02](images/jupyter/img-02.png) ![jupyter-03](images/jupyter/img-03.png) ![jupyter-04](images/jupyter/img-04.png) ![jupyter-05](images/jupyter/img-05.png) ![jupyter-06](images/jupyter/img-06.png) ![jupyter-07](images/jupyter/img-07.png) ![jupyter-08](images/jupyter/img-08.png) ![jupyter-09](images/jupyter/img-09.png) ![jupyter-10](images/jupyter/img-10.png) ![jupyter-11](images/jupyter/img-11.png)

## 5. Visualización Básica de Datos

### 5.1. Situación a Nivel Mundial

#### 5.1.1. Confirmados por País Descendente

![jupyter-12](images/jupyter/img-12.png)

#### 5.1.2. Muertes por País Descendente

![jupyter-13](images/jupyter/img-13.png)

#### 5.1.3. Recuperados por País Descendente

![jupyter-14](images/jupyter/img-14.png)

#### 5.1.4. Casos Activos Descendente

![jupyter-15](images/jupyter/img-15.png)

### 5.2. Situación en Colombia

#### 5.2.1. Muertes por Género

![jupyter-16](images/jupyter/img-16.png) ![jupyter-17](images/jupyter/img-17.png)

#### 5.2.2. Casos por Departamento

![jupyter-18](images/jupyter/img-18.png) ![jupyter-19](images/jupyter/img-19.png)

#### 5.2.3. Muertes por Edad

![jupyter-20](images/jupyter/img-20.png)

### 5.3. Colombia vs Mundo

#### 5.3.1. Confirmados

![jupyter-21](images/jupyter/img-21.png) ![jupyter-22](images/jupyter/img-22.png)

#### 5.3.2. Muertes

![jupyter-23](images/jupyter/img-23.png) ![jupyter-24](images/jupyter/img-24.png)

#### 5.3.3. Recuperados

![jupyter-25](images/jupyter/img-25.png) ![jupyter-26](images/jupyter/img-26.png)
