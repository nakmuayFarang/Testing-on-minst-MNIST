# Variational Autoencoder



## About Variational Autoencoder

This model is similar to an autoencoder, and is made of an encoder <img src="https://render.githubusercontent.com/render/math?math=\mathcal{Q}: \mathcal{D} \mapsto \mathcal{Z}"> and a decoder <img src="https://render.githubusercontent.com/render/math?math=\mathcal{R}: \mathcal{Z} \mapsto \mathcal{D}"> and  <img src="https://render.githubusercontent.com/render/math?math=\forall x \in \mathcal{D},  x \sim \mathcal{R} \circ \mathcal{Q} (x)"> <br>

<img src="https://render.githubusercontent.com/render/math?math=\forall x \in \mathcal{D},  x \sim \mathcal{R} \circ \mathcal{Q} (x) = \mathcal{P}"> 

and an encoder 
<img src="https://render.githubusercontent.com/render/math?math=\mathcal{Q}">  where  <img src="https://render.githubusercontent.com/render/math?math=\forall x \in \mathcal{D}, \exists z \in \mathcal{z} / \mathcal{Q} (x) = z">

<img src="https://render.githubusercontent.com/render/math?math=\mathcal{P}_\theta (x) = \int_{\mathcal{Z}} \mathcal{P}_{\theta}(x,z) "> using Bayes theorem <img src="https://render.githubusercontent.com/render/math?math=\mathcal{P}_\theta (x) = \int_{\mathcal{Z}} \mathcal{P}_{\theta}(x | z)\mathcal{P}(z)">



## Multilayer Perceptron Variational Autoencoder

![alt text](https://github.com/nakmuayFarang/start-with-MNIST/blob/master/img/vae-mlp.jpg)


### Convolutional Variational Autoencoder
![alt text](https://github.com/nakmuayFarang/start-with-MNIST/blob/master/img/vae_cnn.jpg)


### Conditional Variational Autoencoder
