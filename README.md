# Neural Networks

This repo is a collection of simple image classifiers using neural networks.

----
## <ins>Table of Contents:</ins>

<ul>
 
 - [Technologies](#technologies)
 - [Libraries](#installation-of-libraries)
 - [CIFAR10](#cifar10-dataset)

</ul>

## <ins>Technologies</ins>

<ul>
 <li>Python v3.x</li>
 <li>Tensorflow v2.x or Tensorflow-GPU v2.x</li>
 <li>PyTorch v1.5.x</li>
 <li>OpenCV v4.3.x</li>
 <li>Numpy</li>
 <li>Matplotlib</li>
</ul>

----

## <ins>Installation of libraries:</ins>

***Tensorflow:***

``` pip install tensorflow```

---
>***NOTE:*** If your system has a CUDA compatible GPU (Nvidia cards):</p>


>``` pip install tensorflow-gpu```

---

## <ins>CIFAR10 Dataset</ins>

<p>The CIFAR dataset is an enormous collection of images belonging to ten diferent classes.</p>
<br/>

<img src="https://miro.medium.com/max/875/1*syyml8q8s1Yt-iEea5m1Ag.png" alt="cifar-img" width="50%">

<h3><u>Results:</u></h3>


This project uses Convolutional Neural Networks to classify images into Rock, Paper or Scissors.

## Network Architecture<br>
I have used **Tensorflow** and **Keras** here to create the neural networks. There are three sections to the project:
<ol>
 <li> A simple Neural Network that produces the least accurate results. This serves as teh benchmark for the rest of the project.</li>
 <li> A simple Convolutional Neural Network.</li>
 <li> Hyperparameter tuned CNN which produces the best accuracy.</li>
</ol>

## Dataset<br>
<ul>
 <li>The dataset <em><strong>rock_paper_scissors</strong></em> is loaded from the <strong>tensorflow_datasets</strong> library</li>
</ul>
 
