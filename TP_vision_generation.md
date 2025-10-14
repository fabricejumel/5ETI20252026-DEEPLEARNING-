
###  « Deep » Génération

---

## Question 1

On s’intéresse au réseau suivant :  
[GAN Fashion-MNIST sur Google Colab](https://colab.research.google.com/github/fabricejumel/5ETI20252026-DEEPLEARNING-/blob/main/2_0_GAN_fashion_mnist_CPE.ipynb) 

> [!CAUTION]
> En cas de problème  d'excecution sur la fin,  utilisez une version ulterieure de tensorflow
>!pip install tensorflow==2.12.0 (à faire section code notebook)
> et vous aurez sans doute  à relancer la machine d'execution pour la prise en compte

> [!NOTE]  
>Il arrive souvent de devoir rétrograder la version de NumPy, de TensorFlow ou d'autres bibliothèques pour pouvoir exécuter des exemples datant de quelques années. Les exemples les plus récents peuvent parfois ne fonctionner qu'avec les dernières cartes graphiques, ce qui peut rendre l'utilisation d'anciens exemples plus pertinente.

**1.a** Mettre en œuvre le réseau.

**1.b** Quel est son objectif ?

**1.c** Que pensez-vous des résultats ?

**1.d** Quel est le nom d’une telle approche ? Explicitez le sens de l’architecture.

**1.e** À quel moment est utilisé le dataset ?

**1.f** Comment pourrait-on mettre en œuvre un équivalent pour des visages ou des pizzas en utilisant la même architecture ? Quelle particularité pour le dataset ?

**1.g** Essayer d'appliquer sur le CIFAR10

---

Même type de questions pour le code suivant :  
[CVAE sur Google Colab](https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/generative/cvae.ipynb)

**1.a** Mettre en œuvre le réseau.

**1.b** Quel est son objectif ?

**1.c** Que pensez-vous des résultats ?

**1.d** Quel est le nom d’une telle approche ? Explicitez le sens de l’architecture.

**1.e** Changer le dataset MNIST digits par le MNIST Fashion.

**1.f** À quel moment est utilisé le dataset ?

**1.g** Comment pourrait-on mettre en œuvre un équivalent pour des visages ou des pizzas en utilisant la même architecture ? Quelle particularité pour le dataset ?

**1.h** Y a-t-il une différence entre les deux approches ?

**1.i** Essayer d'appliquer sur le CIFAR10

(BONUS) **1.j** Essayer d’utiliser le dataset Pokémon disponible sur Kaggle pour générer des Pokémon à la fois sur l'appriche VAE et l'approche GAN
