# Week14_14
## Integrantes:
DIEGO ALEJANDRO RUIZ ALFONSO - diegoaruiz@ucundinamarca.edu.co PEDRO PASCUAL MURCIA VARGAS - ppmurcia@ucundinamarca.edu.co JHON EDUARD TINJACA CRUZ - jetinjaca@ucundinamarca.edu.co JULIAN DAVID SILVA GUZMAN - jdsilva@ucundinamarca.edu.co

# Proyecto GANs: Generación de Imágenes (MNIST & Fashion MNIST)

Este proyecto implementa y compara arquitecturas de Redes Neuronales Generativas Adversarias (GAN) para la creación de imágenes sintéticas.

## Contenido
1. **Modelos implementados**:
   - **GAN MLP**: Modelo base utilizando capas densas.
   - **DCGAN Estándar**: Uso de capas convolucionales inversas (Conv2DTranspose).
   - **DCGAN Mejorada**: Arquitectura optimizada con mayor número de filtros y BatchNormalization.

2. **Datasets**:
   - **MNIST**: Dígitos escritos a mano.
   - **Fashion MNIST**: Prendas de vestir y calzado.

3. **Resultados**:
   - Se logró un entrenamiento estable de 5,000 épocas para el dataset MNIST.
   - Se incluyeron mecanismos de seguridad (try-except) para evitar errores de memoria o reinicio de runtime.

## Cómo ejecutar
1. Ejecutar las celdas de configuración e importación.
2. Definir las arquitecturas de Generador y Discriminador.
3. Entrenar los modelos utilizando la función modular `train_model`.
4. Visualizar resultados con `plot_images`.

## Archivos Generados
- Resultado.png`: Muestra de la DCGAN mejorada.
- Resultado_final.png`: Resultados tras 5000 épocas de entrenamiento.

