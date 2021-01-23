# Projet d'identification d'une langue
*Cours “Réseaux de neurones pour la reconnaissance de l’oral et application linguistiques”*

<<<<<<< HEAD
Ici vous pouvez trouver le modèle qui prédit une langue (français, russe, arabe ou hindi) à partir d'un audio (mp3 ou wav).
Il y a également un dataset de [Mozilla CommonVoice](https://commonvoice.mozilla.org/fr) convérti en spectrogrammes.
Dans le fichier ipynb vous pouvez trouver un script du prétraitement, de l'apprentissage et des résultats ainsi qu'une code qui permet d'essayer le modèle par vous-mêmes (Section Post Scriptum).

Le modèle utilisé est un CNN qui a l'architecture ci-dessous.

![Model](https://github.com/project178/trash/blob/master/model.png)

Voici du statistique qui permet d'estimer le modèle.

![Accuracy](https://github.com/project178/trash/blob/master/accuracy.png)

![Loss](https://github.com/project178/trash/blob/master/loss.png)

![Confusion matrix](https://github.com/project178/trash/blob/master/confusion matrix.png)

Liens vers un notebook et un github avec des experiences differentes:
- [la version principale](https://colab.research.google.com/drive/178HUsBaFMissbx3KJbCZml220lqwh28j?usp=sharing)
=======
Lien vers un notebook et un github avec des expériences diverses :
- [google colab d'un CNN simple avec Adam (+ utilisation de train-split et shuffling de toutes les données)](https://colab.research.google.com/drive/1C_P1-1gFKuCZCytDUOmkmxrg_y3iw7Ln?usp=sharing)
- [ Lien github vers  un notebook avec les tests d'autres architectures](https://github.com/ShNineb/CNN/blob/master/resumary.ipynb)
- [lien vers le github avec les scripts](https://github.com/ShNineb/CNN/tree/master)
