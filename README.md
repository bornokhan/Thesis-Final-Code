# Thesis-Final-Code
My thesis work.
AD is the extremely ordinary kind of dementia, and its occurrence is growing around the
world. Disorder in brain cells develops in early years and manifest obvious indications.
Neuropsychological, imaging, and spinal fluid tests all provide a high degree of diagnostic
accuracy. The pace with which study and advances are being made in AD is unmatched in
neuroscience history, and the result bearing this research can change future in a better way
for the aged. Although no optimal diagnostic test exists for Alzheimer&#39;s disease,
neuropsychological testing, neuroimaging, and CSF analysis all have the potential to
dramatically increase diagnosis accuracy. AD generally has no remedy. However, in
modern days, machine learning algorithms and neural networks may play a critical role in
recognizing such disorders more quickly and affordably.
We used five separate strategies in this research to make an early and reliable diagnosis of
Alzheimer&#39;s disease. We applied these techniques to the 373 occurrences in the OASIS
dataset, each of which was significant in its own way. This raw dataset was converted to a
readable format and separated into 70% and 30% segments for training and testing
purposes.
In this research, we tried to find best Naïve Bayes variant between Gaussian and binomial.
Gaussian NB showed the promising result. We achieved an accuracy of about 93% with
this verified machine learning algorithm but faced underfitting with this model.
Secondly, we used fine parameter optimization to operate with SVM. The C parameter,
gamma parameter, and kernel function were tuned to locate the graph hyperplane that
would divide the examples into demented and non-demented classes. The higher the C
value and the lower the gamma value, the better the segregation. We reached 87% accuracy
with this confirmed machine learning classifier, although the model had an overfitting
issue.
For our third model, three-layer architecture was introduced, consists of three-layer
architecture where input was the first, second hidden and finally output layers was the third.
We took 9 input layers. Hidden layer, which is first containing 9 neurons, 18 neurons
contained by the second, and last layer of hidden containing 5 neurons and an output layer.
Finally, one output layer for binary classification. It resulted in an accuracy of about 93.33
% and introduced underfitting problem.
Our last model 1DCNN was implemented before the ensemble. This model has 2 Conv1D
layers, 2 BatchNormalization layers and 2 MaxPooling layers. Then extracted features were
used in the neural network layer as dense layer. Hidden layers where we had three layers
containing 64, 32 and 16 neurons individually. Finally, we achieved an accuracy of 91%
from our 1DCNN and resulted as underfit model.
Finally, after considering the issue of overfitting and underfitting, we developed a new
model. The ensemble vote classifier uses an ensemble of NB, SVM, ANN, and 1DCNN. It
was able to achieve a 93.33 % overall accuracy while also ensuring minimal variance and
bias, resulting in a more generic solution. This optimized accuracy outperforms NB, SVM,
ANN, and 1DCNN accuracy. Taking variance, bias, and accuracy into account, it can be
concluded that the ensemble of NB, SVM, ANN, and 1DCNN will provide advantages of
these classifiers and succeed in producing a superior overall prediction performance than
any single classifier.
In terms of performance, the presented methodologies have outperformed all previous
studies. However, further study might lead to some improvements. Overall, this study
achieves a satisfactory level of performance in the area of early prediction of AD.
