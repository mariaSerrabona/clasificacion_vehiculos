# clasificacion_vehiculos

En esta práctica se quiere entrenar una red neuronal convolucional para que sea capaz de identificar diferentesvehículos de transporte.

Como datos, tenemos un conjunto de fotos de entrenamiento con sus correspondientes clasificaciones, así como las fotos para hacer la validación de los datos. Para poder hacer una lectura de las imágenes se necesita el uso de librerías de pytohn como Beautiful soup, que puede leer páginas HTML para poder leer fotos subidas a la nube. 

Al no poder leer las fotos de forma legible ni entrenar la red de forma eficciente, se ha optado por implementar el código utilizado en la práctica anterior y adaptarlo a los requerimientos de esta prueba. Al tratarse de uan gran dimensión de imágenes, se ha tenido múltiples errores durante la lectura de las mismas. Es por ello que el código aparece sin ejecutar, pues se necesitaría un odenador con mayor capacidad de procesamiento.

Lo que se entrega es una implmentación y adaptación del código a los datos que se tiene, generando una red neuronal que en lugar de clasificar entre dos objetos distintos (perros y gatos), clasifica entre distintos vehículos.

