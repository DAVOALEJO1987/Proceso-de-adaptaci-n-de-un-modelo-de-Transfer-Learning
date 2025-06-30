# Proceso de adaptacion de un modelo de Transfer Learning
Este cuaderno implementa un flujo completo de Transfer Learning supervisado con MobileNetV2, aprovechando su capacidad de generalización para una tarea binaria, con un enfoque eficiente en tiempo y recursos, ideal para aplicaciones reales con pocos datos etiquetados.

## Autor: Narváez Mejía David Alejandro
Estudiante de Maestría de Inteligencia Artificial en UEES 
Materia: APRENDIZAJE PROFUNDO – MIAR0530

## Claves del programa
En este taller exploraremos el uso de Transfer Learning con el modelo preentrenado MobileNetV2 para clasificar imágenes de gatos y perros. Utilizaremos Google Colab para entrenar, evaluar y probar el modelo con imágenes nuevas. Finalmente, elaboraremos un informe detallando los resultados obtenidos y respondiendo a preguntas clave sobre la actividad práctica
## Breves Recomendadciones 
![image](https://github.com/user-attachments/assets/3d8ebce6-fee7-480d-b041-3ea074a2aa1b)
1.	Imágenes de alta calidad y buena iluminación.
2.	Los elementos centrados y en primer plano, lo que facilita que las características relevantes sean detectadas por la red convolucional.
3.	No hay elementos visuales distractores ni fondos complejos que interfieran con la predicción.
Esto demuestra que, bajo condiciones controladas, el modelo puede generalizar con gran efectividad.
4.	Se presentan oclusiones, sombras o desenfoques.
5.	Se usan ángulos inusuales o partes del animal no visibles completamente.
Además, al estar limitado a solo dos clases (gato o perro), cualquier otro animal sería mal clasificado, mostrando la necesidad de ampliar la base de datos y aplicar técnicas de regularización y robustez para una mayor generalización.
6.	Calidad y balance del dataset La precisión mejora cuando el conjunto de datos es diverso, balanceado y representativo de las clases. Imágenes claras, sin ruido y bien etiquetadas permiten que el modelo aprenda patrones relevantes y evite sesgos.
7.	Arquitectura del modelo y pesos preentrenados Utilizar una red como MobileNetV2 con pesos preentrenados en un gran conjunto como ImageNet acelera el aprendizaje y mejora la generalización. El Transfer Learning permite conservar características útiles ya aprendidas.
8.	Técnicas de preprocesamiento y data augmentation Aplicar transformaciones como rotación, escalado o recorte durante el entrenamiento incrementa la robustez del modelo, ayudándole a generalizar mejor ante variaciones reales en las imágenes.
9.	Parámetros de entrenamiento (batch size, learning rate, épocas) Un learning rate inadecuado puede hacer que el modelo no aprenda (si es muy bajo) o que no converja correctamente (si es muy alto). El número de épocas también influye: pocas pueden causar underfitting, mientras que muchas podrían inducir overfitting si no se controlan.
10.	Regularización y validación cruzada Usar técnicas como dropout, early stopping, y validación cruzada asegura que el modelo no se sobreajuste al conjunto de entrenamiento y tenga un rendimiento consistente en datos no vistos.
## Resultados 
100% :-) 
![image](https://github.com/user-attachments/assets/8a798dd8-305f-4abd-90b6-941f96fee411)

    
