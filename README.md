# Advanced-Image-Processing-CV
Este proyecto explora las técnicas fundamentales y avanzadas del procesamiento digital de imágenes (Computer Vision). Se implementa un pipeline completo que abarca desde la manipulación geométrica y el filtrado de ruido hasta la segmentación avanzada de objetos mediante algoritmos de aprendizaje no supervisado y son utilizados en un motor de recomendación de imagenes. Los modelos de computer vision utilizados fueron Vit y Resnet de hugging faces.

# Advanced Image Processing & Segmentation Pipeline.

## Descripción
Este proyecto explora las técnicas fundamentales y avanzadas del procesamiento digital de imágenes (Computer Vision). Se implementa un pipeline completo que abarca desde la manipulación geométrica y el filtrado de ruido hasta la segmentación avanzada de objetos mediante algoritmos de aprendizaje no supervisado son utilizados en un motor de recomendación de imagenes. Los modelos de computer vision utilizados fueron Vit y Resnet de hugging faces.


## Stack Tecnológico
* **Librerías de Visión:** OpenCV (`cv2`), Scikit-Image (`skimage`).
* **Algoritmos:** K-Means Clustering para segmentación de color.
* **Procesamiento:** Filtros Gaussianos, Sobel (Edge Detection), Umbralización de Otsu.
* **Matemáticas:** NumPy para manipulación de arreglos multidimensionales de píxeles.

## Técnicas Implementadas
* **Transformaciones Geométricas:** Reescalado y rotación de imágenes manteniendo la integridad de los datos.
* **Detección de Características:** Aplicación de filtros de gradiente (Sobel) para identificar contornos y estructuras clave.
* **Segmentación por K-Means:** Agrupamiento de píxeles en el espacio de color para separar objetos del fondo de manera automática.
* **Binarización Adaptativa:** Uso de umbralización local y global (Otsu) para la extracción de máscaras binarias en diferentes condiciones de iluminación.

## Estructura de las diferentes partes. 
<img width="1445" height="584" alt="image" src="https://github.com/user-attachments/assets/ba928b15-ce05-4a25-8d47-56ff111ce9f9" />
<img width="1725" height="499" alt="image" src="https://github.com/user-attachments/assets/51922c85-123d-42a9-a5a7-6df80f6b1db6" />
<img width="916" height="321" alt="image" src="https://github.com/user-attachments/assets/18e7721e-8f06-4a8d-a083-97ff1cc0922e" />
<img width="968" height="496" alt="image" src="https://github.com/user-attachments/assets/4b226d09-4cf9-4ecd-b2d4-54228b810c99" />



## Cómo empezar
1.  Clonar el repositorio.
2.  Instalar dependencias: `pip install scikit-image opencv-python matplotlib numpy`
3.  Ejecutar el notebook `Practica_Final_CV.ipynb`.
