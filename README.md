# **Acute Ischemic Stroke Segmentation**
![figura 1](https://github.com/gysselis40/Acute_Ischemic_Stroke_Segmentation/blob/main/Banner.png)
## Integrantes 
**Gysselis Vásquez Garcés, Óscar Andrés Ramírez Serna, Laura Rodríguez Cala**
## Objetivo
Crear un método automatizado para segmentar las lesiones en estudios de imagenología de pacientes con ACV isquémico agudo (AIS).

## Descripción del dataset
Este proyecto se basa en un conjunto de datos privado del grupo BIVL2ab, que contiene imágenes capturadas a pacientes con ACV isquémico en las primeras 24 horas tras los síntomas. Las imágenes son de las modalidades DWI, ADC y NCCT, y están pareadas con las marcaciones de las lesiones hechas por expertos. El conjunto de datos se divide en:
- Train: 60 pacientes
- Test: 38 pacientes

## Descripción del proyecto
El diagnóstico y tratamiento oportuno de las lesiones de ACV isquémico requiere una segmentación manual precisa, pero esta tarea es ineficiente y subjetiva. Por eso, el objetivo de este proyecto es crear un método automatizado para segmentar las lesiones de ACV isquémico agudo (AIS) en las imágenes de ADC y NCCT. El problema que se soluciona es la detección temprana y exacta de estas lesiones, que pueden provocar daños neurológicos y discapacidad. Para ello, se usan técnicas de Deep learning y procesamiento de imágenes, con las marcaciones de expertos como ground truth. Se busca obtener un algoritmo que identifique y delimite las áreas afectadas por el AIS, con alta sensibilidad y especificidad, y que funcione con diferentes tipos de imágenes.

## Modelo
Con el fin de lograr el objetivo, se implmentó un modelo U-Net. Esta arquitectura cuenta con 4 bloques para el encoder y 4 bloques para el decoder, además de las skip connections.
