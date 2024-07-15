---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}


> ### NeuroVision Navigator: Predictive Modeling for Robotic Perception
> <hr style="border: none; height: 2px; background-color: #333; margin: 20px 0;">
> <p align="center">
>   <img src="https://raw.githubusercontent.com/yuceelege/yuceelege.github.io/master/images/project1.png" alt="Robot Image" width="400" />
> </p>
In the project, high-dimensional perception data was compressed using a variational autoencoder (VAE) pipeline, optimizing the efficiency of motion planning. The project’s ”Forward Model,” designed for task and motion planning applications, was constructed to predict the mobile robot’s future observations based on current sensory inputs and control actions. This predictive capability was achieved by integrating the VAE with a Long Short-Term Memory (LSTM) network.
> <p align="center">
>   <img width="600" alt="Scheme 1" src="https://raw.githubusercontent.com/yuceelege/yuceelege.github.io/master/images/project1-image2.png">
>   <br>
>   <em>Figure 1: Proposed Method for Predictive Modeling</em>
> </p>
> <p align="center" style="margin-top: 20px;">
>   <img width="600" alt="Scheme 2" src="https://raw.githubusercontent.com/yuceelege/yuceelege.github.io/master/images/project1-image1.png">
>   <br>
>   <em>Figure 2: Evolution of Observations and Predictions</em>
> </p>

> ### Autonomous Structure Building with Graph Neural Networks
> <hr style="border: none; height: 2px; background-color: #333; margin: 20px 0;">
> <p align="center">
>   <img src="https://github.com/yuceelege/yuceelege.github.io/blob/master/images/project2-pyramid.png?raw=true" alt="Robot Image" width="400" />
> </p>
This project introduces a novel approach using graph networks for task and motion planning in robotic structure
building. The system transforms an initial object configuration to a desired one by inferring spatial relations and
representing them as a graph. A graph neural network (GNN) identifies movable objects and determines the
necessary action sequence. Integrated with a Graph Search-based algorithm within the RAI framework, the system
effectively classifies movable objects and operates a robot arm with a motion planner and solves challenges like
tower and wall building fast.
> <div style="display: flex; justify-content: center; align-items: center; gap: 20px;">
>   <div style="text-align: center;">
>     <img height="300" alt="Scheme 1" src="https://github.com/yuceelege/yuceelege.github.io/blob/master/images/project2-algo.png?raw=true">
>     <br>
>     <em>Figure 1: Proposed Method for Predictive Modeling</em>
>   </div>
>   <div style="text-align: center;">
>     <img height="300" alt="Scheme 2" src="https://github.com/yuceelege/yuceelege.github.io/blob/master/images/project2-flow.png?raw=true">
>     <br>
>     <em>Figure 2: Evolution of Observations and Predictions</em>
>   </div>
> </div>