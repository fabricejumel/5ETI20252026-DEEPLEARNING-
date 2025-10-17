### LLM et Fine-tuning

---

TODO // regarder le dataset de finetuning
// tester le modle avant finetuning vs dataset
// apres finetuning retester le modele

// choisir un autre dataset si mieux


## Question 1
> [!CAUTION]
> Vous avez besoin de vous créer à un moment un compte sur hugginface et surtout de générer (profile/access_token/) un token, ce token doit être un
**TOKEN TYPE : WRITE*, et penser idéallement à le sauvegarder

[Colab LLM Fine-tuning](https://colab.research.google.com/github/fabricejumel/5ETI20252026-DEEPLEARNING-/blob/main/Fine_Tune_Your_Own_Llama_2_1B_LORA64_CPE.ipynb)

[Tester son modele enregistré sous Hugging Face](https://colab.research.google.com/drive/1kVxUn5rvvetJzftgSiSUNtaNZTxnxkYq?usp=sharing)

**1.a** À quoi correspond le site Hugging Face Hub cité dans le document ? Créez-vous un compte.

**1.b** Concernant les tutoriels disponibles, ils sont très nombreux. Si le sujet vous intéresse, vous pourrez les regarder, mais cela n’est pas demandé :
- [Cours de NLP](https://huggingface.co/learn/nlp-course/)
- [Classification de séquence](https://huggingface.co/docs/transformers/tasks/sequence_classification)
- [Classification de token](https://huggingface.co/docs/transformers/tasks/token_classification)
- [Question answering](https://huggingface.co/docs/transformers/tasks/question_answering)
- [Modélisation de langage](https://huggingface.co/docs/transformers/tasks/language_modeling)
- [Modélisation de langage masqué](https://huggingface.co/docs/transformers/tasks/masked_language_modeling)
- [Traduction](https://huggingface.co/docs/transformers/tasks/translation)
- [Résumé automatique](https://huggingface.co/docs/transformers/tasks/summarization)
- [Tutoriel LLM](https://huggingface.co/docs/transformers/llm_tutorial)

**1.c** Quel est le nom du modèle de réseau sous-jacent ? Quelle est sa taille et son architecture ?

**1.d** Le modèle est-il déjà entraîné ou est-ce simplement une structure de réseau ?

**1.e** Si le modèle est déjà entraîné, sur quels datasets a-t-il été formé ?

**1.f** Qu’est-ce qu’un LoRA ? Expliquez ses 3 paramètres.

**1.g** Qu’est-ce qu’un Transformer ? Expliquez son usage dans le cadre d’un LLM.

**1.h** Si ce n’est pas déjà fait, lancez l’exécution de l’ensemble du code (cela prend environ 30 minutes).

---

## Question 2

En quoi consiste la notion de *token* ? Donnez des exemples de tokens dans notre cas.

---

## Question 3

Le but de ce code est de procéder à un *fine-tuning* du modèle.

**3.a** De quoi parle-t-on ici ?

**3.b** Quel est le dataset utilisé ? Montrez des exemples et indiquez sa taille. Quelle puissance de calcul en TFlops a été nécessaire pour le *fine-tuning* ? A-t-on modifié la taille du modèle après apprentissage ?

---

## Question 4

**4.a** Testez différents prompts. Que pensez-vous de ses performances ? Comparez les résultats avec ChatGPT.

---

## Question 5

**5.a** Refaites les tests en partant du même modèle sans le *fine-tuning*. Comment procéder ? Que pensez-vous de la différence ?

**5.b** Tester sur des exemples issus du dataset d'apprentissage

**5.b** En vous inspirant du dataset utilisé , trouvé des cas pertinent où l'apprentissage a servi à quelque chose 

---

## Question 6

Proposer une liste de différents LLM utilisables pour faire du finetuning,  quelles sont les caractéristqiues des machines nécessaires (minimum et idéal) pour les utiliser en inference et pour les fine tuner .

## Question 7 (Exploratoire)

Quelles sont les différentes outils proposés classiquement pour faire du finetuning de LLM ?

## Question 8 (Exploratoire)

Proposez un *fine-tuning* particulier en trouvant un dataset original. Quelle est la taille conseillé pour ce dataset. Montrez en quoi les résultats sont mauvais avant le *fine-tuning*, puis montrez le résultat après. Êtes-vous satisfait ?




