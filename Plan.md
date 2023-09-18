
## Are Minkowski functionals useful for feature extraction in the classification of radio galaxy images?

*Minkowski functionals (MF) are mathematical descriptors of the topology of continuous fields, quantifying the area, perimeter, and mean curvature 
of an excursion set. They can be used to compress the information in a 2d image into a much sparser 1-dimensional representation. In this project 
students will investigate whether the MFs of radio galaxy images can be used to categorise those galaxies into different types, either directly 
using (e.g.) neural networks or indirectly using additional dimensionality reduction techniques. The students will compare these approaches to more 
standard image classification techniques such as those using convolutional neural networks.*

---

Work Plan:

* Build and train baseline deep-learning model from [E2CNN paper code](https://github.com/as595/E2CNNRadGal);
* Write code to extract MFs from input images of radio galaxies;
* Replace trainable convolutional layers in baseline model with MF extraction and retrain model;
* Compare and evaluate performance of MF approach vs baseline deep-learning approach;
* (if time allows) implement scattering transform / haralick features to benchmark different feature extraction techniques.

