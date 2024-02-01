---
date: 2023-07-14
title: CNN Rock Paper Scissor
subtitle: Rock Paper Scissor mit einem Convolutional Neural Network spielen
image:
    path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_04.png
gallery:
    - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_02.png
    - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_03.png
    - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_04.png
    - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_05.png

layout: projects
---

Im Kurs Smart Media Technology meines Medientechnik Studiums war ich maßgeblich an der Entwicklung eines interaktiven "Schnick, Schnack, Schnuck"-Spiels beteiligt. Unsere Gruppenzielsetzung war es, durch ein Convolutional Neural Network (CNN) das Webcam-Bild der Nutzer:innen zu analysieren und ihre Handgesten (Schere, Stein oder Papier) zu erkennen, um gegen den Computer anzutreten.

Die gesamte Implementierung erfolgte in Python auf der Plattform Google Colab. Wir erstellten einen eigenen Datensatz mit etwa 200 Bildern für jede Handgeste, um das CNN zu trainieren. Dabei verfeinerten wir ein vortrainiertes ResNet50-Modell, passend für unsere Anforderungen. Als Framework nutzten wir PyTorch, während Ray Tune und Tensorboard für das Training und die Visualisierung der Ergebnisse zum Einsatz kamen.

Unser Spiel kann in einem eigens entwickelten Jupyter-Notebook auf Google Colab gespielt werden. Dabei lädt das Notebook das aktuellste Modell aus einem Git-Repository und führt die Bilderkennung durch. Zur Verbesserung der Gestenerkennung wird vor der eigentlichen Prädiktion durch unser CNN das Webcam-Bild mit Hilfe von Mediapipe auf die erkannte Hand zugeschnitten. Die Benutzeroberfläche wurde mithilfe von IPython-Widgets gestaltet.

Das Projekt bot mir eine praktische Erfahrung im Bereich maschinelles Lernen und Künstliche Intelligenz für interaktive Anwendungen. Es eröffnete interessante Einblicke in die Herausforderungen und Möglichkeiten der Bilderkennung.

[Link zum Game Notebook zum Spielen](
https://colab.research.google.com/drive/1YFxfhp5Srf8tqa0avC0Oa3wqk1ovVd8V?usp=sharing)
