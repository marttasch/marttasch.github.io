---
date: 2023-02-10
title: Paper Synthi
subtitle: Playing synthesizers with game pieces on paper
language: en
lang: en
permalink: /en/project/papersynthi/
image:
  path: /assets/images/projects/paperSynthi/paperSynthi_2.png
gallery:
  - path: /assets/images/projects/paperSynthi/paperSynthi_1.png
  - path: /assets/images/projects/paperSynthi/paperSynthi_0.png
  - path: /assets/images/projects/paperSynthi/paperSynthi_2.png

layout: projects
---

As part of a university project, we developed a synthesizer that can be controlled using game pieces on a piece of paper.

With the help of openCV and mediaPipe, a webcam can be used to precisely detect the positions of the game pieces and fingers. The game pieces on the paper act as control elements for the synthesizer. Users can move these pieces to adjust various settings on the synthesizer, such as changing timbres or effects. At the same time, they can also play the notes on the virtual keyboard with their index fingers. The recognized notes and settings are sent via MIDI to a web application that uses the “Web Audio API” for sound generation, allowing the browser to serve as an audio-visual output platform for the synthesizer.

This project impressively illustrates the potential of computer vision and simple object recognition. It demonstrates how technological solutions can be used to support creative processes and connect the physical and digital worlds in fascinating ways, creating innovative and interactive applications.

The project can be found on [GitHub](https://github.com/marttasch/avprg_PaperSynthi).