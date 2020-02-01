---
layout: page
title: Koopman Eigenfunctions
description: Discovering linear evolution of dynamical systems
img: /assets/img/bintel_square.jpg
---

This paper presents a novel episodic method to learn a robot's nonlinear dynamics model and an increasingly optimal control sequence for a set of tasks.  The method is based on the {\em Koopman operator} approach to nonlinear dynamical systems analysis, which models the flow of {\em observables} in a function space, rather than a flow in a state space.  Practically, this method estimates a nonlinear diffeomorphism that lifts the dynamics to a higher dimensional space where they are linear.  Efficient Model Predictive Control methods can then be applied to the lifted model.  This approach allows for real time implementation in on-board hardware, with rigorous incorporation of both input and state constraints during learning. We demonstrate the method in a real-time implementation of fast quadrotor landing, where the nonlinear ground effect is learned and used to improve landing speed and quality.     

#### References
{% reference ACC2020   %} 

[Code](https://github.com/Cafolkes/keedmd)

{% reference eKEEDMDicra20   %} 


![d](/assets/img/landing_1.png){:width=30%} ![d](/assets/img/landing_3.png){:width=30%} ![d](/assets/img/landing_3.png){:width=30%}

![d](/assets/img/eKEEDMD.png){:height="150px"}

#### Video

$$ \int x $$

{% youtube "https://youtu.be/hwSHLgly_bc" %}