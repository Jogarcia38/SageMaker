# Laboratorio 3.1 - Amazon SageMaker
## Acceso a la Consola de administración de AWS

![Acceso AWS](Imagenes/Tarea%200.png)

 Inicié el entorno seleccionando Start Lab y esperé hasta que apareciera el estado “Lab status: ready”, con el fin de asegurar que todos los recursos estuvieran disponibles correctamente; después, accedí a la consola de administración de AWS mediante la opción AWS, permitiendo las ventanas emergentes del navegador en caso de ser necesario. Finalmente, organicé la consola y las instrucciones en pestañas visibles simultáneamente para facilitar el seguimiento de los pasos y realizar el laboratorio de forma ordenada y correcta.

## Tarea 1: Creación de un cuaderno de Jupyter con Amazon SageMaker

![Acceso AWS](Imagenes/Tarea%201.1.png)

![Acceso AWS](Imagenes/Tarea%201.2.png)

En esta tarea accedí a Amazon SageMaker AI desde la consola de AWS y creé una instancia de cuaderno llamada MyNotebook, seleccionando el tipo de instancia ml.m5.xlarge y la plataforma notebook-al2-v3 para trabajar con Amazon Linux 2; También configuré el ciclo de vida con la opción que contiene ml-pipeline, con el propósito de cargar automáticamente los recursos necesarios para el laboratorio, dejando las demás opciones con sus valores predeterminados. Finalmente, creé la instancia, esperé hasta que su estado cambiara a InService y abrí JupyterLab, con el objetivo de disponer de un entorno preparado para desarrollar, ejecutar y gestionar los cuadernos de las siguientes actividades.

## Tarea 2: Introducción a JupyterLab

![Acceso AWS](Imagenes/Tarea%202.png)

En esta tarea exploré la interfaz de JupyterLab en Amazon SageMaker abriendo el cuaderno de ejemplo PythonCheatSheeet.ipynb, con el propósito de familiarizarme con las principales herramientas del entorno; asimismo, revisé la barra de menús, el explorador de archivos, los kernels, las pestañas y la barra de herramientas, además de aprender a diferenciar entre celdas de código, Markdown y Raw, también practiqué la ejecución de celdas mediante Mayús + Intro y comprendí cómo el kernel procesa el código y muestra los resultados. Esta actividad fue importante para conocer el funcionamiento básico de JupyterLab y adquirir las habilidades necesarias para trabajar con código, documentación y análisis de datos en las siguientes tareas del laboratorio.

## Tarea 3: Apertura de un cuaderno de muestra

![Acceso AWS](Imagenes/Tarea%203.1.png)

![Acceso AWS](Imagenes/Tarea%203.2.png)

![Acceso AWS](Imagenes/Tarea%203.3.png)

![Acceso AWS](Imagenes/Tarea%203.4.png)

En este punto regresé a la carpeta de JupyterLab donde había abierto el cuaderno PythonCheatsheet y localicé el archivo linear_learner_mnist.ipynb para explorar un ejemplo práctico de un cuaderno de Jupyter; después, abrí el cuaderno y utilicé la opción Create a Copy para crear una copia en mi entorno de trabajo, con el objetivo de poder revisarlo sin modificar el archivo de muestra original. Por último, recorrí sus diferentes celdas para familiarizarme con la estructura, el código y el flujo de trabajo de un cuaderno de Jupyter; no ejecuté los pasos porque el ejemplo requiere un bucket de Amazon S3, recurso necesario para almacenar o acceder a los datos utilizados por el cuaderno.

## Tarea 4: Importación de datos

![Acceso AWS](Imagenes/Tarea%204.1.png)

![Acceso AWS](Imagenes/Tarea%204.2.png)

![Acceso AWS](Imagenes/Tarea%204.3.png)

![Acceso AWS](Imagenes/Tarea%204.4.png)

Aquí creé un nuevo cuaderno de Jupyter en JupyterLab utilizando el kernel conda_python310, añadí el título Importing the data mediante una celda Markdown y agregué las librerías necesarias para descargar, descomprimir y procesar los datos; después, utilicé Python para descargar el conjunto de datos médicos de la columna vertebral desde el repositorio de Machine Learning de UC Irvine, extraer los archivos comprimidos y comprobar que aparecieran los cuatro archivos esperados en el entorno de trabajo. Revisé los archivos para familiarizarme con su estructura y, para terminar, cargué el archivo column_2C_weka.arff mediante arff.loadarff() y lo convertí en un DataFrame de Pandas, utilizando df.head() para visualizar las primeras filas; todo este proceso se realizó con el objetivo de preparar y organizar los datos que se utilizarán en los siguientes laboratorios de análisis y machine learning.

## Tarea 5: Descargar el cuaderno y guardar el trabajo (opcional)

![Acceso AWS](Imagenes/Tarea%205.1.png)

Para finalizar realicé el procedimiento para guardar una copia local del cuaderno de Jupyter antes de finalizar el entorno de laboratorio de SageMaker, con el objetivo de evitar la pérdida del trabajo realizado; para ello, desde el navegador de archivos de JupyterLab hice clic con el botón derecho sobre el cuaderno que quería conservar, seleccioné la opción Download (Descargar) y elegí una ubicación segura en el equipo para almacenarlo. De esta forma, el archivo puede conservarse como respaldo y, si es necesario continuar trabajando posteriormente, puede cargarse nuevamente en un nuevo entorno de laboratorio para retomar las actividades realizadas.

## Conclusiones

El laboratorio permitió comprender de manera práctica el uso de Amazon SageMaker y JupyterLab para trabajar con datos y desarrollar procesos básicos de aprendizaje automático.

Se aprendió a crear y configurar una instancia de cuaderno, conocer las principales herramientas de JupyterLab, utilizar celdas de código y Markdown, explorar cuadernos de ejemplo e importar un conjunto de datos mediante Python para convertirlo en un DataFrame de Pandas.

Por último, se destaca la importancia de guardar o descargar los cuadernos antes de finalizar el laboratorio para conservar el trabajo realizado. En general, la actividad proporcionó una base práctica para la preparación, exploración y análisis de datos en un entorno de machine learning en la nube.
