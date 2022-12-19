# IRN_Entregable02_Corregido

#Entregable2Corregido.ipynb sirve para procesar la data, en la carpeta DATASET se coloca inicialmente 
#toda la data que se desea evaluar, para armas blancas, anteriormete se debió de nombrar todas 
#las fotos empezando con "AB" para armas blancas, de la misma manera, "CA" para armas de corto 
#alcance y "LA" para armas de largo alcance. Finalmente, se obtendrán carpetas de Training, Testing
#y Validation (diferenciados para AB, LA y CA) para su posterior utilización en el entrenamiento 
#de la red.

#EntrenamientoEntrega2TF2.ipynb sirve para entrenar la red neuronal, se crea una carpeta CustomTF2 
#en la cual se almacena toda la data que se va a utilizar para el entrenamiento (en la carpeta data)
#que proviene del preprocesamiento anterior. Se obtienen las siguientes carpetas: traindataset,
#testdataset y trainrecord y testrecord, con las cuales podremos ejecutar códigos de tensorflow que
#nos permite realizar el entrenamiento de la red. 

#En el linkDATAdrive se encontrarán todos los links de la data necesaria. 
