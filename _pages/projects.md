---
layout: archive
title: "Research Projects"
permalink: /projects/
author_profile: true
---

## Research Interests ##

* **Data-driven modeling**:
  Reduced order modeling of dynamical systems, rational approximation
* **Reduced order modeling of transport-dominated problems**: 
  Conservation laws, nonlinear reduced order modeling
* **Numerical linear algebra**:
  Efficient, problem specific linear algebra solvers, conditioning analysis
* **Scientific computing**:
  Robust numerical software, open source software
  
---
## Reduced order modeling of transport-dominated problems ##
Computational models are essential in modern engineering practice.  Standard finite-element discretizations of governing partial differential equations can result in very large systems of coupled ordinary differential equations which may be computationally expensive to evaluate, especially in many-query applications.  When the underlying physics are dispersive, standard linear model reduction and reduced order modeling techniques have been highly successful at lessening this computational burden.  When the physics are dominated by transport phenomena such as moving shock waves, linear methods lose their effectiveness.  Thus, specialized nonlinear reduced order modeling methods are required to handle transport-dominated problems.  In particular, special care must be taken with the numerical implementation of these methods as the nonlinearities in the reduced modeling process often add significant computational burden to the online phase of the ROM.  In this project, we develop a novel reduced modeling framework for transport-dominated problems which is both exceptionally accurate at predicting shock locations and results in a significant speed up over the full order model.

## Data-driven modeling of structured dynamical systems ##
When a computational model is either completely unavailable or accessible only as a black-box, the only option to form a lower cost surrogate model is to learn a model from data.  When some information about the underlying physics is available, this information should be exploited to enable reinterpretation of the model and ensure the data-driven surrogate is as faithful as possible.  This leads to the structured data-driven reduced order modeling problem, where one optimizes parameters of a model form that enforces the appropriate structure.  In this project, we develop an adaptive structured rational approximation algorithm for modeling second-order structured dynamical systems from measurements of its frequency response.

## Optimal frequency-based reduced models from time-domain data ##
Reduced models of dynamical systems constructed from frequency (Laplace)-domain data come with powerful theoretical guarantees for their performance. However, at times frequency domain data is unavailable and must be inferred from time-domain data.  While there exist methods to infer a system's frequency response from time-domain simulations, using standard techniques to learn the system's response to an exponentially growing input can be impractical due to restrictions on the power of the input.  When constructing optimal reduced models from data, one requires samples of the system's transfer function at points corresponding to exponentially growing inputs.  In this project, we develop a computationally robust method to learn values and derivatives of a system's transfer function at any point in the complex plane from only a single input-output trajectory in the time-domain.  Further analysis enables an effective algorithm for learning optimal reduced models from a single input-output trajectory.

## Adaptive rational approximation ##
Rational approximations enjoy exponential convergence rates to many classes of functions, including non-analytic functions and functions with branch cuts.  While a very accurate rational approximation of a given degree may exist, computing this rational approximation is a different problem.  In this project, we develop a novel method for rational approximation based on interpolation and nonlinear least-squares fitting of a provided data set.  The method is adaptive in the sense that the degree of the rational approximation grows until the data are fit to a prescribed tolerance.  Due to an adaptive initialization strategy for the nonlinear least-squares problems we solve at each step, the method is guaranteed to monotonically decrease the approximation error.



<!--
## Context-Aware Learning of Low-Dimensional Controllers ##
  
<p class="text-block">
<img class="projectpiccalearn" src="/images/context_aware_learning.png"
alt="Context-aware Learning Flow Chart">
The general idea of context-aware learning is to directly learn the task of
interest rather than some generic descriptions of the occurring dynamics, which
usually demands for lots of data and computational resources to learn an
accurate representation of the underlying physics.
Thereby, it is possible to restrict to the task-relevant dynamics,
which are often simpler than the full underlying physics, such that the data
requirements for the training only scale with the task.
In this project, we consider the task of learning controllers for dynamical
systems from given data.
</p>

---

## Data-Driven Reduced-Order Modeling of Mechanical Systems ##
  
<p class="text-block">
<img class="projectpicddrom" src="/images/dd_rom.png"
alt="Structured Data-Driven Reduced-Order Modeling">
Data-driven reduced-order modeling is essential in the construction of compact,
high-fidelity models from frequency domain data.
While there exist already unstructured approaches for data-driven modeling from
data, it is of particular interest to retain the physical structure as in the
case of structure-preserving model reduction. The main problems arising here
are, first of all, to enforce the classical mechanical system structure,
which is typically lost in data obtained from the system’s transfer function
and second, to receive physically interpretable properties in the resulting
matrices such as positive definiteness of mass, damping and stiffness.
In this project, we develop extensions of the barycentric form to the
case of mechanical systems leading to the extension of known techniques to the
learning of structured models from frequency domain data such as the
AAA algorithm, the Loewner framework or vector fitting.
</p>
  
---

## Structure-Preserving Model Reduction for Mechanical Systems ##

<p class="text-block">
<img class="projectpicsomor" src="/images/mor_system_so.png"
alt="Second-Order System MOR">
For the construction of complex mechanical structures such as bridges, 
buildings, or vehicles, the use of computer models is nowadays indispensable. 
Such computer models are typically used to simulate and, if necessary, to 
optimize the oscillation behavior. For instance, such an optimization is useful 
to suppress and damp undesired oscillations. Taking into account the 
input-output structure of the system, modeling of such mechanical structures 
typically leads to dynamical systems described by second-order ordinary 
differential equations.
Often the system dimension (i. e., the number of masses) is very large. The aim 
of model reduction is now to approximate the original system by a much smaller 
one to save a huge amount of computational resources during evaluation of the 
model.
In this project we want to develop new model reduction techniques for 
second-order mechanical systems that also preserve certain system properties 
like dissipativity.
</p>

---

## Robust Flow Control via HINFBT ##

<p class="text-block">
<img class="projectpicstabflow" src="/images/hinfbt.png"
alt="Flow Stabilization">
For the efficient stabilization of flows, controllers of small orders are 
needed, which also bridge the gap between approximation and model, or
model and reality.
While there are established construction formulas for robust stabilizing 
controllers, those usually lead to controllers described by systems of 
differential equations of the same size as the original system, which makes
real time control of the system impossible.
In this project, we aim for the construction of such low-order robust 
stabilizing controllers by employing LQG- and H-Infinity-based model reduction 
methods and controller theory.
</p>

---

## MORLAB &ndash; Model Order Reduction LABoratory ##

<p class="text-block">
<img class="projectpicmorlab" src="/images/morlab_logo.png" alt="MORLAB Logo">
<b>MORLAB</b>, the <b>M</b>odel <b>O</b>rder <b>R</b>eduction <b>LAB</b>oratory
toolbox, is a collection of MATLAB and Octave routines for model order reduction 
of dense linear time-invariant continuous-time systems. The toolbox contains 
model reduction methods for standard, descriptor and second-order systems based 
on the solution of matrix equations. Therefore, also spectral projection based 
methods for the solution of the corresponding matrix equations are included.
See the <a target="_blank" 
href="https://www.mpi-magdeburg.mpg.de/projects/morlab">project website</a>
for more information.
</p> -->
