---
title: Realtime Deformation of Constrained Meshes using GPU
authors: Alexandre Kaspar, Bailin Deng
event: Symposium on GPU Computing and Application 2013
date: 2013
---

![](highlight.png)

# Realtime Deformation of Constrained Meshes using GPU
Alexandre Kaspar and Bailin Deng

Symposium on GPU Computing and Application, Singapore, 2013

## Abstract

Constrained meshes play an important role in freeform architectural design,
as they can represent panel layouts on freeform surfaces.
It is challenging to perform realtime manipulation on such meshes,
because all constraints need to be respected during the deformation
while the shape quality needs to be maintained.
This usually leads to nonlinear constrained optimization problems,
which are challenging to solve in real time.
In this paper, we present a GPU-based shape manipulation tool for constrained
meshes, using the parallelizable algorithm proposed in [Deng et al. 2013].
We discuss the main challenges and solutions for the GPU implementation,
and provide timing comparison against a CPU implementation of the algorithm.
Our GPU implementation significantly outperforms the CPU version, allowing
realtime handle-based deformation for large constrained meshes.

## Links
* [Paper](paper.pdf)
* [Presentation](slides.pdf)
* [Video](video.mov)
* [Youtube](http://www.youtube.com/watch?v=k0ACkSBQ_aM)
