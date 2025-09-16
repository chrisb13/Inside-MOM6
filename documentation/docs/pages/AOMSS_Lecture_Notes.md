---
author:
- Andy Hogg
date: |
  Australian Ocean Modelling "Summer" School\
  April 2019
title: Some Notes on Ocean Modelling
---

------------------------------------------------------------------------

::: multicols
2
:::

------------------------------------------------------------------------

# Introductory Lecture

- Note differing backgrounds and approaches. Steve comes from physics to
  global ocean models. Andy has a fluid mechanics to idealised models
  background. We hope these differences will complement, not impede
  understanding ...

- There is much to learn about ocean models -- between us we know a lot,
  but in many topics there may be people who are more expert than us --
  please feel free to contribute, or ask questions to clarify.

- Our approach is to outline fundamental topics, which will allow you to
  apply what you have learnt to your particular configuration.

- Notation. We will mostly use vector notation, and will try to be
  consistent. But, on occasion, we need to use tensors. Going from
  vector to tensor notation for position, $\mathbf{x}$ and velocity,
  $\mathbf{u}$, we write
  $$\mathbf{x} = (x, y, z) \to x_i = (x_1, x_2, x_3)$$
  $$\mathbf{u} = (u, v, w) \to u_i = (u_1, u_2, u_3)$$
  $$\textrm{We may sometimes use the 2D velocity: } \mathbf{v} = (u,v)$$
  $$\frac{\partial u}{\partial x} \to u_{1,1}$$
  $$\nabla \cdot \mathbf{u} \to u_{i,i}$$ $$\nabla p \to p_{,i}$$
  $$\mathbf{u}  \cdot  \nabla \mathbf{u} \to u_j u_{i,j}$$
  $$\mathbf{a} \times \mathbf{b}  \to  \epsilon_{ijk} a_j b_k$$
  $$\nabla \times \mathbf{u}  \to  \epsilon_{ijk} u_{k,j}$$ We adopt the
  summation convention -- where repeated indices imply sum across all
  dimensions.

