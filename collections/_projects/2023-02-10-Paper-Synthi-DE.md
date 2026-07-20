---
date: 2023-02-10
title: Paper Synthi
subtitle: Synthesizer mit Spielsteinen auf Papier spielen
language: de
lang: de
permalink: /de/project/papersynthi/
image:
  path: /assets/images/projects/paperSynthi/paperSynthi_2.png
gallery:
  - path: /assets/images/projects/paperSynthi/paperSynthi_1.png
  - path: /assets/images/projects/paperSynthi/paperSynthi_0.png
  - path: /assets/images/projects/paperSynthi/paperSynthi_2.png

layout: projects
---

Als Teil eines Universitätsprojekts entwickelten wir einen Synthesizer, der mit Spielsteinen auf einem Blatt Papier gesteuert werden kann.

Mit Hilfe von OpenCV und MediaPipe kann eine Webcam die Positionen der Spielsteine und Finger präzise erkennen. Die Spielsteine auf dem Papier fungieren als Steuerelemente für den Synthesizer. Benutzer können diese Steine verschieben, um verschiedene Einstellungen am Synthesizer anzupassen z.B. für Klangfarben oder Effekte. Gleichzeitig können sie auch die Noten auf der virtuellen Tastatur mit ihren Zeigefingern spielen. Die erkannten Noten und Einstellungen werden via MIDI an eine Webanwendung gesendet, die die "Web Audio API" für die Sounderzeugung verwendet, so dass der Browser als Audio-visuelles Ausgabegerät für den Synthesizer dient.

Dieses Projekt demonstriert eindrucksvoll das Potenzial von Computer Vision und einfacher Objekterkennung. Es zeigt, wie technologische Lösungen kreative Prozesse unterstützen können und die physische und digitale Welt auf faszinierende Weise verbinden, um innovative und interaktive Anwendungen zu schaffen.

Das Projekt ist auf [GitHub](https://github.com/marttasch/avprg_PaperSynthi) verfügbar.
