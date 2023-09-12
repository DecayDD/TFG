## David del Cerro Domínguez
 En este archivo se detalla el contenido de la parte de desarrollo del TFG. Todos los modelos preentranados se encuentran en la carpeta modelos correctamente ordenados, disponibles también en Google Drive /enlace/. De la misma forma se encuentran los datasets utilizados, disponibles tanto en la carpeta /datasets como en drive. Todos los archivos se encuentran correctamente comentados y explicados en sus respectivos archivos, así como sus pruebas y experimentos realizados. </p>

___
El archivo Gui contiene la GUI con una representación sencilla para pruebas de transformaciones

---
El archivo ageClassifier contiene los distintos clasificadores de edad como sus distintos resultados.

---

El archivo gender contiene el clasificador por género y la presentación de los resultados.

---

El archivo fake-real-Classifier contiene la red neuronal que elige las imágenes de mejor calidad de StyleGAN3 y sus resultados.

---

El archivo gen_dataset contiene el script que genera el dataset clasificado partiendo de las imágenes generadas por StyleGAN3.

---

El archivo fid contiene el cálculo del FID entre dos grupos de imágenes.

---

El archivo glasses contiene la detección de gafas y un apartado para pruebas, en la carpeta pruebaGafas se encuentra algunos ejemplos de prueba.

---

### Licencias

El archivo age_classifier deriva del uso de las redes MobileNet [MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications](https://arxiv.org/abs/1704.04861) por Andrew G. Howard, Menglong Zhu, Bo Chen, Dmitry Kalenichenko, Weijun Wang, Tobias Weyand, Marco Andreetto y Hartwig Adam, que se encuentra bajo licencia [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) y red VGG16 [Very Deep Convolutional Networks for Large-Scale Visual Recognition](https://www.robots.ox.ac.uk/~vgg/research/very_deep/) por Karen Simonyan y Andrew Zisserman, con licencia [Creative Commons BY 4.0](https://creativecommons.org/licenses/by/4.0/)

El archivo glasses deriva del uso del detector [MTCNN](https://arxiv.org/abs/1604.02878) por Kaipeng Zhang, Zhanpeng Zhang, Zhifeng Li, Yu Qiao disponible bajo licencia [MIT](https://opensource.org/license/mit/) como [libreria](https://github.com/ipazc/mtcnn).

El archivo cyclegan deriva del uso del modelo CycleGAN [Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks](https://arxiv.org/abs/1703.10593) por Jun-Yan Zhu, Taesung Park, Phillip Isola y Alexei A. Efros. Se utiliza la implementación realiza por Tensorflow en sus [tutoriales](https://www.tensorflow.org/tutorials/generative/cyclegan?hl=es-419) como base.
