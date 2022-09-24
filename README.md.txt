Pasos:

1) Descargar el repositorio.

2) Utilizar "Anaconda Promp" y copiar los siguientes comandos.

$ conda create -n FaceEmotion
$ conda activate FaceEmotion
$ conda install python=3.7
$ pip install tensorflow==2.4.1
$ pip install keras==2.4.3
$ pip install imutils opencv-python h5py
$ pip install matplotlib == 3.2.2

3) Para activar la WebCam, mediante la consola, buscar el repositorio descargado, luego escribe este comando.

$ python FaceEmotionVideo.py

Si quieres activar la grafica con el porcentaje de emociones activa este comando.

$ python FaceEmotionVideoBar.py