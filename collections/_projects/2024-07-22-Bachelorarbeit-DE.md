---
date: 2024-07-22
title: Bachelorarbeit
subtitle: Nutzung von Stable Diffusion zur Datensatzgenerierung für die Bilderkennung von Verschmutzungen in Sanitärbereichen
language: de
lang: de
permalink: /de/project/bachelorthesis/
image:
    path: /assets/images/projects/bachelorarbeit/bachelorarbeit_header.jpeg

layout: projects
---

In meiner Bachelorarbeit untersuche ich die Anwendung von Stable Diffusion zur Generierung von Datensätzen für die Bilderkennung, insbesondere im Sanitärsektor. Die Methodik beinhaltet die Anpassung von Stable Diffusion für diese spezifische Anwendung mittels Low Rank Adaptation (LoRA) und nutzt das Modell Realistic Vision 5.1, um fotorealistische Bilder zu erstellen. Die Arbeit demonstriert die Machbarkeit der automatisierten Datensatzerstellung mit Stable Diffusion und erreicht vielversprechende Ergebnisse mit einer Validierungsgenauigkeit von über 90% für die generierten Datensätze, bewertet durch ein trainiertes InceptionV3-Bilderkennungsmodell. Mögliche Verbesserungsbereiche wurden identifiziert, einschließlich der Notwendigkeit, die realistische Darstellung von Verschmutzungen durch einen größeren und realistischeren Trainingsdatensatz zu verbessern und das Modell weiter mittels LoRA anzupassen. Zukünftige Arbeiten sollten auch die Erstellung eines größeren, ausgewogeneren Evaluationsdatensatzes in Betracht ziehen, um aussagekräftigere Ergebnisse zu erhalten.

Das entwickelte Framework für die automatisierte Datensatzerstellung ist auf [Github](https://github.com/marttasch/StableDiffusion_generateDataset) verfügbar.
Die vollständige Thesis ist im [HAW Hamburg Repository](https://reposit.haw-hamburg.de/handle/20.500.12738/16340) verfügbar.
