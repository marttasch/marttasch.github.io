---
date: 2024-07-22
title: Bachelorthesis
subtitle: Nutzung von Stable Diffusion zur Datensatzgenerierung für die Bilderkennung von Verschmutzungen in Sanitärbereichen
# image:
#     path: /assets/images/projects/cnnRockPaperScissor/.png
# gallery:
#     - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_02.png
#     - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_03.png
#     - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_04.png
#     - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_05.png

layout: projects
---

In meiner Bachelorarbeit untersuche ich die Anwendung von Stable Diffusion zur Generierung von Datensätzen für die Bilderkennung, speziell im Sanitärbereich. Die Methodik umfasst die Anpassung von Stable Diffusion für diese spezifische Anwendung mittels einer Low Rank Adaptation (LoRA) und nutzt das Realistic Vision 5.1 Modell zur Erstellung photorealistischer Bilder. Die Arbeit demonstriert die Machbarkeit der automatisierten Datensatzerstellung mit Stable Diffusion und erzielt vielversprechende Ergebnisse mit einer Validierungsgenauigkeit von über 90 % bei den generierten Datensätzen, bewertet durch ein trainiertes InceptionV3 Bilderkennungsmodell. Verbesserungspotentiale wurden identifiziert, darunter die Notwendigkeit, die realistische Darstellung der Verschmutzung durch einen größeren und realistischeren Trainingsdatensatz zu verbessern und das Modell mittels LoRA weiter anzupassen. Zukünftige Arbeiten sollten außerdem die Erstellung eines größeren, ausgewogeneren Evaluationsdatensatzes in Betracht ziehen, um aussagekräftigere Ergebnisse zu erzielen.

Das Entwickelte Framework zur automatisierten Datensatzgenerierung ist auf [Github verfügbar](https://github.com/marttasch/StableDiffusion_generateDataset). <br>
Die vollständige Arbeit ist auf auf dem [Reposit der HAW Hamburg](https://reposit.haw-hamburg.de/handle/20.500.12738/16340) verfügbar.
