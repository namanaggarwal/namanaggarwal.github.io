---
layout: archive
title: "Relevant Projects"
permalink: /projects/
author_profile: true
---
These are some of my projects during the final year of my undergraduate degree.

1. **Model-based Deep RL controller for Super Mario Bros** (Aug 2019 - Nov 2019) <br>
*Project conducted as a part of the course: Foundations of Intelligent and Learning Agents* <br>
Performed extensive literature survey on Model-based RL methods and learning without extrinsic rewards. Our controller is composed of two sub-parts: a curiosity-driven reward generator network and a policy network with some weight sharing between the two networks. Trained the agent using Advantage Actor-Critic (A2C) algorithm on the environment Super Mario Bros. [[Report]](https://namanaggarwal.github.io/files/CS747.pdf)

2. **Zap Q-Learning** (Jan 2020 - June 2020) <br>
*Research survey conducted as a part of the graduate level course: Introduction to Stochastic Optimization* <br>
*Advisor: [Prof. Vivek Borkar](https://scholar.google.co.in/citations?user=Km1V8WwAAAAJ&hl=en), EE IITB* <br>
Surveyed Zap Q-learning, a matrix gain algorithm with improved asymptotic covariance and speed of convergence than Watkin’s Q-learning algorithm. Studied dependance of the asymptotic covariance on the matrix-gain sequence and the two time-scale update equation. [[Report]](https://namanaggarwal.github.io/files/ZapQ.pdf)

3. **Regret Minimization for Correlated Multi-armed Bandits** (Jan 2020 - June 2020) <br>
*Research project conducted as a part of the graduate level course: Online Learning* <br>
*Advisor: [Prof. Jayakrishnan Nair](https://www.ee.iitb.ac.in/~jayakrishnan.nair/), EE IITB* <br>
Correlated bandit setting is one in which rewards produced by each arm are deterministic functions of a common latent source of randomness. Proposed new algorithms for the purpose of regret minimization in this setting based on latent distribution learning of the hidden source through the generated reward sequence. Compared performance to standard algorithms like the UCB algorithm and obtained better empirical results. [[Report]](https://namanaggarwal.github.io/files/EE737.pdf)

# Miscellaneous Projects
These are some of my (non-research) projects during the earlier years of my undergraduate degree.

4. **Parallel Computing for N-Body Simulation** (Jan 2018 - May 2018) <br>
*Project conducted as a part of the course: High Performance Scientiﬁc Computing* <br>
Developed a program in C++ to simulate the trajectory of n-bodies under their mutual gravitational force. Parallelized the code with OpenMP and MPI and analyzed performance for varying number of bodies, threads and processes.

5. **Controller Design** (Aug 2018 - Nov 2018) <br>
*Project conducted as a part of the course: Introduction to Control Theory* <br> 
Designed a PD controller in frequency domain using tools like the Bode plot, Nichols chart and the Nyquist plot to achieve required speciﬁcations of phase margin and bandwidth for a fourth order system. Simulated the design on MATLAB and validated the results with theoretical predictions.


6. **Dimensionality Reduction using Autoencoders** (Jan 2019 - May 2019) <br>
*Project conducted as a part of the course: Machine Learning for Remote Sensing* <br>
Compared PCA (linear) to a single hidden-layer autoencoder (non-linear) as latent space learning tools. Implemented and compared various autoencoders (Contractive, Variational etc.) on the MNIST dataset. Visualized and studied the eﬀect of the KL divergence term on the latent space learnt by the VAE model.










