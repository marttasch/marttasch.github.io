---
date: 2024-07-22
title: Bachelor Thesis
subtitle: Using Stable Diffusion to generate datasets for image recognition of contamination in sanitary areas
language: en
image:
    path: /assets/images/projects/bachelorarbeit/bachelorarbeit_header.jpeg
# gallery:
#     - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_02.png
#     - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_03.png
#     - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_04.png
#     - path: /assets/images/projects/cnnRockPaperScissor/cnnRockPaperScissor_05.png

layout: projects
---

In my bachelor thesis, I investigate the application of Stable Diffusion for generating datasets for image recognition, specifically in the sanitary sector. The methodology involves adapting Stable Diffusion for this specific application using Low Rank Adaptation (LoRA) and utilizes the Realistic Vision 5.1 model to create photorealistic images. The thesis demonstrates the feasibility of automated dataset creation with Stable Diffusion and achieves promising results with a validation accuracy of over 90% for the generated datasets, evaluated by a trained InceptionV3 image recognition model. Potential areas for improvement have been identified, including the need to improve the realistic representation of pollution through a larger and more realistic training dataset and to further adapt the model using LoRA. Future work should also consider creating a larger, more balanced evaluation dataset to achieve more meaningful results.

The developed framework for automated data set generation is available on [Github](https://github.com/marttasch/StableDiffusion_generateDataset).
The complete paper is available on the [HAW Hamburg repository](https://reposit.haw-hamburg.de/handle/20.500.12738/16340).
