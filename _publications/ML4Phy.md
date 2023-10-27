---
title: "Beyond PID Controllers: PPO with Neuralized PID Policy for Proton Beam Intensity Control in Mu2e"
collection: publications
permalink: /publication/ML4Phy
excerpt: 'We developed a neuralized-PID Soft Actor-Critic (SAC) algorithm for real-time proton beam intensity control in the Mu2e experiment at Fermilab.'
date: 2023-09-22
venue: 'NeurIPS ML4Phy'
paperurl: 
citation: 
---

We introduce a novel Soft Actor Critic (SAC) algorithm equipped with neuralized-PID policy function to address the uniform proton beam intensity delivery problem for the upcoming Mu2e experiment at Fermi National Accelerator Laboratory (Fermilab). 
The challenge lies in controlling the spill regulation process to sustain a consistent intensity profile. 
Our primary goal is to establish an automated controller capable of real-time calibration of the Spill Regulation System (SRS) parameters, offering feedback on a millisecond timescale. 
By treating the physical Mu2e accelerator system as a Markov Decision Process suitable for Reinforcement Learning (RL) with continuous action, we tackle it utilizing a Soft-Actor-Critic (SAC) equipped with neuralized-PID policy for bias reduction and stabilized training process.
A key feature of our approach is the use of the inductive biases from a PID controller in the neuralized-PID policy, which guards against typical overfitting of the policy during training, while maintaining robustness to environmental changes. 
Our method delivers a significant improvement in the Spill Duty Factor (SDF), outperforming the currently employed PID controller baseline by an additional XX+\%.
The paper presents initial offline results obtained from a differentiable Mu2e accelerator simulator, laying the groundwork for real-time implementation and application, and signifying an important step towards automatic proton beam intensity control for the Mu2e experiment.

# [Download paper here](http://chenwei-1999.github.io/files/2309.12673.pdf)
