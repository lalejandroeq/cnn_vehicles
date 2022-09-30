Contexto

Este proyecto esta basado en un pipeline creado hace algun tiempo para extraer informacion de anuncios de vehiculos usados en las paginas de crautos.com y purdyusados.com utilizando un framework conocido como Scrappy, el cual facilita la estructura de un proyecto de extraccion a mayor escala.

Objetivos de negocio

La información disponible en los sitios web anteriormente descritos, no está necesariamente en condiciones óptimas, muchas veces, esta información puede presentar datos faltantes que impiden el registro correcto de todos los valores que describen un anuncio.

Para poder utilizar esta información para análisis y post procesamiento después de su captura, es necesario completar la información lo mejor posible, y el negocio ha notado que muchos de los anuncios les hace falta la marca del carro, por lo que el objetivo principal del negocio es de alguna manera, completar la información de las marcas de los vehículos.

Criterios de éxito

El éxito está definido como la capacidad de completar los datos faltantes de la manera más integra posible, de manera que las técnicas que se utilicen para determinar las marcas de carros faltantes en el conjunto de datos deben tener un grado de precisión mejor que el simplemente sustituir la marca con un valor como la moda del conjunto de datos. Adicionalmente, el segundo criterio de éxito es poder utilizar la información que está actualmente almacenada como imágenes de los autos, de manera que las técnicas que se implementen para el proyecto deberán de utilizar las imágenes como parte de los criterios de imputación de las marcas faltantes.

Objetivos de minería de datos

• Implementar un modelo de aprendizaje profundo que pueda procesar las imágenes que se almacenan para cada anuncio de carro

Criterios de éxito (minería de datos)

• Un modelo de clasificación con mejor precisión que el etiquetado de un modelo ingenuo (digamos etiquetar todos los faltantes con la moda del conjunto de datos)
• Capacidad de crear una red neuronal de aprendizaje profundo que pueda predecir las marcas de carros mediante las matrices de pixeles de las imágenes de estos.
