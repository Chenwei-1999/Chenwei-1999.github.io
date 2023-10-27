---
title: "Beyond PID Controllers: PPO with Neuralized PID Policy for Proton Beam Intensity Control in Mu2e"
collection: publications
permalink: /publication/ML4Phy
excerpt: 'This paper introduces a neuralized-PID Soft Actor-Critic (SAC) algorithm for real-time proton beam intensity control in the Mu2e experiment at Fermilab.'
date: 2023-10-27
venue: 'NeurIPS (ML4Phy Workshop)'
paperurl: 
citation: 
---


We introduce a novel Proximal Policy Optimization (PPO) algorithm aimed at
addressing the challenge of maintaining a uniform proton beam intensity delivery in
the Muon to Electron Conversion Experiment (Mu2e) at Fermi National Accelerator
Laboratory (Fermilab). Our primary objective is to regulate the spill process to
ensure a consistent intensity profile, with the ultimate goal of creating an automated
controller capable of providing real-time feedback and calibration of the Spill
Regulation System (SRS) parameters on a millisecond timescale. We treat the
Mu2e accelerator system as a Markov Decision Process suitable for Reinforcement
Learning (RL), utilizing PPO to reduce bias and enhance training stability. A key
innovation in our approach is the integration of neuralized PID controller into the
policy fucntion, resulting in a significant improvement in the Spill Duty Factor
(SDF) by 9.4%, surpassing the performance of the current PID controller baseline 
by an additional 2.2%. This paper presents the preliminary offline results based
on a differentiable simulator of the Mu2e accelerator. It paves the ground works
for real-time implementations and applications, representing a crucial step towards 
automated proton beam intensity control for the Mu2e experiment.

[Download paper here](http://chenwei-1999.github.io/files/Mu2e_ML4Phy_preprint.pdf)
