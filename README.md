# Modulo2CNN
Momento de Retroalimentación: Módulo 2 Implementación de un modelo de deep learning. (Portafolio Implementación)
# Introducción Básica al Data Set
  ¿Qué es un tumor cerebral? 
    Un tumor cerebral es una agrupación o masa de células anormales en el cerebro. El cráneo, que rodea el cerebro, es muy rígido. Cualquier crecimiento dentro de un espacio       tan limitado puede ocasionar problemas. Los tumores cerebrales pueden ser cancerosos (malignos) o no cancerosos (benignos). Cuando los tumores benignos o malignos crecen,       pueden aumentar la presión dentro del cráneo. Esto puede provocar daño cerebral y ser potencialmente mortal.

  ¿Por qué es importante esta área?
    La detección temprana y clasificación de tumores cerebrales es un ámbito de investigación crucial en el campo de la imágenes médicas. Esto contribuye significativamente a      la selección del método de tratamiento más adecuado para preservar la vida de los pacientes.
    
  Este conjunto de datos es una combinación de los siguientes tres conjuntos de datos:
      figshare
      Conjunto de datos SARTAJ
      Br35H

  Este conjunto de datos contiene 7023 imágenes de resonancias magnéticas del cerebro humano, las cuales están clasificadas en 4 clases: glioma, meningioma, sin tumor y          pituitaria.
# Modelo CNN
  Un modelo CNN (Convolutional Neural Network o Red Neuronal Convolucional) es un tipo de red neuronal profunda especialmente diseñada para procesar datos bidimensionales, como imágenes. Estas redes están compuestas por capas de convolución que aplican filtros a regiones locales de la entrada, seguidas por capas de agrupación (pooling) que reducen la dimensionalidad de la información. Esto permite que la red aprenda características locales y jerárquicas de la imagen, capturando patrones cada vez más complejos a medida que profundiza en las capas. A partir de esto, se ha decidido utilizar este modelo para la identificación de tumores cerebrales. 
