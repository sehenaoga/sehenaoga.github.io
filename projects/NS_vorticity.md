---
layout: post
title: Solving the Navier-Stokes equations through vorticity-stream function formulation
date: 2020-04-24
author: Sebastian Henao
---

 The characteristics of the fluid flow within the region enclosed by the top and bottom walls shown in the figure below need to be computed. How? Well, 

 [Click here](https://drive.google.com/file/d/1I7gCmSa_8qfnW2QWEyRHudK5kmpFJgJL/view?usp=sharing){:target="_blank"} to see the full project report.

<img src="NS_vorticity/domain.png" alt="domain.png" width="60%" class="center"/>

$$
\begin{equation}
    \nabla\cdot\vec{u} = \frac{\partial u}{\partial x} + \frac{\partial v}{\partial y} = 0 \ \ \ \ \text{(Continuity equation)}
    \label{Continuity} 
\end{equation}
$$

$$
\begin{equation}
    \frac{D\vec{u}}{D t} = \frac{\partial \vec{u}}{\partial t} + (\vec{u}\cdot\nabla)\vec{u} = -\frac{1}{\rho}\nabla P + \nu \nabla^2\vec{u} \ \ \ \ \text{(Momentum equation)}
    \label{Momentum} 
\end{equation}
$$

$$
\begin{equation}
    \frac{D\omega}{D t} = \frac{\partial \omega}{\partial t} + \frac{\partial \psi}{\partial y}\frac{\partial \omega}{\partial x} - \frac{\partial \psi}{\partial x}\frac{\partial \omega}{\partial y} =  \nu \nabla^2\omega \ \ \ \ \text{(Vorticity-stream function formulation)}
    \label{Vorticity_momentum} 
\end{equation}
$$

<img src="NS_vorticity/results.png" alt="results.png" width="60%" class="center"/>



[home](/index.html)