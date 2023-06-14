# ProyectoIA_UNALFaces

## Modelos

En el archivo Modelo_FaceNet.ipynb se pueden evidenciar cada una de las capas del modelo Face Net y como se realizo la carga de los pesos del modelo preentranado que se obtuvo del [github](https://github.com/R4j4n/Face-recognition-Using-Facenet-On-Tensorflow-2.X). 

En el archivo Face_Net.ipynb se encuentra el código para realizar el reconocimiento facial a través del calculo de los embeddings utilizando este modelo y su comparación. Además, incluye el procesamiento adecudo de las imágenes previo, y el calculo del porcentaje de clasificación correcta y de falsos positivos posterior.

El archivo VGGFace.ipynb contiene todo lo mencionado para Face Net anteriormente pero realiza el reconocimiento facial a través del calculo de los embeddings utilizando VGGFace, que se obtuvo del [github](https://github.com/prlz77/vgg-face.pytorch).
El archivo Api_Rec_Facial_Vivo.ipynb contine el código para realizar el reconocimiento facial en vivo con los rostros de los autores del presente trabajo o para realizar el reconocimiento a traves de imagenes previamente guardadas. Incluye la detección de rostros en video, el calculo y comparación de los embeddings.

Cabe resaltar que para ejecutar nuevamente el código es necesario establecer correctamente los directorios con las imagenes que se desean utilizar.

La base de datos utilizada fue obtenida de la plataforma [kaggle](https://www.kaggle.com/competitions/11-785-s23-hw2p2-classification/overview).

