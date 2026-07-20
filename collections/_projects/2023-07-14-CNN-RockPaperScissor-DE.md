---
date: 2023-07-14
title: CNN Stein Papier Schere
subtitle: Stein-Papier-Schere spielen mit einem Convolutional Neural Network
language: de
lang: de
permalink: /de/project/cnn-rockpaperscissor/
image:
    path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_04.png
gallery:
    - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_02.png
    - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_03.png
    - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_04.png
    - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_05.png

layout: projects
---

Im Kurs "Smart Media Technology" meines Medientechnologie-Studiums war ich wesentlich an der Entwicklung eines interaktiven "Stein, Papier, Schere"-Spiels beteiligt. Das Ziel unserer Gruppe war es, ein Convolutional Neural Network (CNN) zu verwenden, um Webcam-Bilder der Benutzer zu analysieren und ihre Handgesten (Stein, Papier oder Schere) zu erkennen, um gegen den Computer zu spielen.

Die gesamte Implementierung erfolgte in Python auf der Google Colab-Plattform. Wir erstellten unseren eigenen Datensatz mit etwa 200 Bildern für jede Handgeste, um das CNN zu trainieren. Dabei verfeinerten wir ein vortrainiertes ResNet50-Modell, um es an unsere Anforderungen anzupassen. Wir verwendeten PyTorch als Framework, während Ray Tune und Tensorboard zum Trainieren und Visualisieren der Ergebnisse verwendet wurden.

Unser Spiel kann in einem speziell entwickelten Jupyter-Notebook auf Google Colab gespielt werden. Das Notebook lädt das neueste Modell aus einem Git-Repository und führt die Bilderkennung durch. Um die Gestenerkennung zu verbessern, wird das Webcam-Bild mit Mediapipe auf die erkannte Hand zugeschnitten, bevor die eigentliche Vorhersage durch unser CNN erfolgt. Die Benutzeroberfläche wurde mit IPython-Widgets entworfen.

Das Projekt gab mir praktische Erfahrung in Machine Learning und Künstlicher Intelligenz für interaktive Anwendungen. Es bot interessante Einblicke in die Herausforderungen und Möglichkeiten der Bilderkennung.

[Link zum Spiel-Notebook zum Spielen](https://colab.research.google.com/drive/1YFxfhp5Srf8tqa0avC0Oa3wqk1ovVd8V?usp=sharing)
