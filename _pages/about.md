---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is Haoqin Deng's homepage

About
======
I am currently an undergraduate student at the Department of Electrical and Computer Engineering, University of Southern California. I am expected to receive the B.E./M.E. degree in Electrical and Computer Engineering in 2022.

My current research intersts include:

* Optical/Photonic Computing
* Quantum Computing
* Neuromorphic Computing
* Machine Learning Acceleration with Emerging Technologies
* Software/Hardware Co-design

Skills
======
* Programming/Software
  * Python
  * C/C++
  * Java
  * Pytorch
  * Qiskit
  * pyqpanda
  * Verilog
  * Cadence

Related Course
======
* EE301: Linear System
* EE370: Electromagnetism
* EE477: VLSI 
* EE520: Introduction to Quantum Computing
* EE582: Neuromorphic Computing
* CSCI201: Pinciple of Software Engineering
* CSCI270: Introduction to Algorithms
* CSCI104: Objected Oriented Programming
* CSCI310: Internetworking
* ITP445: Professional C++
* ITP380: Video Game Programming

* Parker’s BioRC project	
  *	Implemented VLSI circuit implementation of excitatory/inhibitory synapses, Axon Hillock, STDP/dopamine/noise synapse, edge detectors, voltage adder.
  *	Used above components to construct multi-layer neural networks; incorporated edge detectors and one-hot encoding outputs
  *	Used STDP rule for local update of synaptic weights; used dopamine feedback (supervised training) signal to globally modulate synaptic weights;
  *	Currently writing pytorch-based library that allows for convenient construction of software neural network for verification purpose, and that can synthesize a functioning VLSI circuit bases on the software construction
* Khajavikhan Optics and Photonics Group
  *	Explored various architectures of Optical Neural Network(ONN), with an emphasis on integrable setups
  *	Develop PT-ONN architecture, which utilized cascading PT-symmetric couplers to build an ONN; 
  *	Modulated gain/loss contrast as the on-chip parameters; simulated onchip-training of PT-ONN on MINIST dataset; computed gradients using finite difference method and updated parameters using SGD; achieve 67% training accuracy.
  *	Simulated onchip-training of a conventional ONN made of cascading Mach-Zehnder interferometers with tunable phases; achieved 71% training accuracy on MINIST dataset 
  *	Co-author of the paper “Parity-time symmetric optical neural networks” currently under review
* Research Assistant, USC Laboratory for Photons, Electrons and Materials	Jun 2020 – present
  *	Studied principles of materials growth technique, including evaporation, TLP, LP-TLP, MOCVD; learned to operate machines to grow materials using these techniques.
  *	Studied the computational model of neurons and its hardware emulation with semiconductor devices such as memristors and MOSFETS
  *	Explored various architectures of mapping Artificial Neural Networks and Spiking Neural Networks onto available hardware synapse/neuron devices; 
  *	Simulated DCSNN(Deep Convolutional Spiking Neural Network); used STDP local updating rule that incorporates realistic hardware parameters; used Reward/Punishing signals to globally adjust STDP polarity; implemented with Pytorch libraries; achieved 91% best training accuracy.
  *	Designed hardware implementation of a neural network using crossbars of floating-gate MOSFET devices.
* Research Assistant, USC ALCHEM Lab	May 2019 – Aug 2020
  *	Studied mechanism of quantum computing and various quantum algorithms; learned to use quantum libraries such as qiskit and pyqpanda
  *	Developed accQOC, a comprehensive compilation methodology that accelerates pulse generation by 9x
  *	Partition DAG of quantum circuit into sub-components under size constraint; generated optimized pulse for each component using QOC, and concatenated them in the end.
  *	Implemented Variational Eigen-Solver algorithm from scratch using pyqpanda library; 
  *	implemented simultaneous-measurement methodology for mutually commuting Hamiltonians to reduce measurement overhead in Variational Eigen-Solver algorithm; 
  *	Coauthor of the paper “Accelerating Quantum Optimal Control Based Pulse Generation”, ISCA2020
* Research Assistant, USC IMEDE Lab	Mar 2019 – Mar 2020
  *	Assisted in designing a neural-signal sampling device
  *	Used Opal-Kelly’s API to realize data transfer between FPGA and PC; implemented SPI protocol to transfer data between FPGAs; visualized data on PC end
* Summer Internship, Shanghai AIKE Measurement Co.      	July 2018 – August 2018
  *	Learned to use LabView to sample data and control hardware
  *	Assisted in designing the structure of a dispenser for lab usage
  *	kept track of daily tasks and progress for the team

