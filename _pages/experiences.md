---
layout: archive
title: "Experiences"
permalink: /experiences/
author_profile: true
---

Researches:
------

* Research Assistant, Parker’s BioRC project	(Jun 2021 – present)
  * Implemented VLSI circuits of excitatory/inhibitory synapses, Axon Hillock, STDP/dopamine/noise synapse, edge detectors, voltage adder; constructed hardware/software multi-layer neural networks with edge detectors and one-hot encoding outputs, with Cadence/Python
  * Used STDP rule for local update of synaptic weights; used dopamine feedback (supervised training) signal to globally modulate synaptic weights;
  * Currently writing pytorch-based library that allows for convenient construction of software neural network for verification purpose, and that can synthesize a functioning VLSI circuit bases on the software construction
* Khajavikhan Optics and Photonics Group (Jun 2021 – present)
  * Researched on various architectures of Optical Neural Network(ONN), with an emphasis on chip-integrable setups
  * Proposed and Developed PT-ONN architecture with cascading PT-symmetric couplers, based on modulations of gain/loss contrast; implemented simulations of onchip-training of PT-ONN using finite difference method with python; achieved 67% training accuracy.
  * Worked on ebwm simulations of directional couplers in COMSOL; calculated system transfer matrix with Mathematica.
  * Reproduced onchip-training of MZI-based ONN with python; achieved 71% training accuracy 
* Research Assistant, USC Laboratory for Photons, Electrons and Materials	(Jun 2020 – Jan 2021)
  * Grew InP on GaAs using Low-Temperature Templated Liquid-Phase(LT-TLP)  
  * Researched on various architectures of mapping Artificial Neural Networks and Spiking Neural Networks onto semiconductor synapse/neuron devices
  * Worked on simulation of temporal-encoded DCSNN(Deep Convolutional Spiking Neural Network) based on realistic hardware STDP parameters and reward modulation, implemented with Pytorch libraries; achieved 91% best training accuracy.
  * Collaborated on designing hardware implementation of a neural network using Arduino and crossbars of floating-gate MOSFET devices.
* Research Assistant, USC ALCHEM Lab	(May 2019 – Aug 2020)
  * Developed accQOC, a comprehensive compilation methodology that accelerates pulse generation by 9X; partitioned DAG of quantum circuit into sub-components under size constraint; generated optimized pulse for each component using QOC 
  * Implemented VQE(Variational Eigen-Solver) algorithm with pyqpanda; implemented simultaneous measurement methodology for mutually commuting Hamiltonians to reduce measurement overhead in VQE with qiskit.
* Research Assistant, USC IMEDE Lab	(Mar 2019 – Mar 2020)
  * Corroborated on designing a neural-signal sampling device
  * Realized data transfer between FPGA and PC using Opal-Kelly’s API; implemented SPI protocol to transfer data between FPGAs; visualized data on PC end with matplotlib library


Publications
------
* AccQOC: Accelerating Quantum Optimal Control Based Pulse Generation
  *	Accepted. [Preprint](https://arxiv.org/abs/2003.00376)
  *	Jinglei Cheng, Haoqin Deng, Xuehai Qian
  *	2020 Annual International Symposium on Computer Architecture, ISCA

* Parity-time symmetric optical neural networks 
  *	Under review.
  *	Haoqin Deng, Mercedeh Khajavikhan
  *	submitted to Optica, OSA

Internships
------

* Summer Internship, Shanghai AIKE Measurement Co. (July 2018 – August 2018)
  *	Automated printers to print labels on a pipeline using Labview
  *	Corroborated on designing the structure of a dispenser for lab usage
  *	kept track of daily tasks and progress for the team

Activities/Projects
------

* Video Game Programming	
  *	Implemented 2D classical Arcade games such as Zelda, Super Mario, PAC-MAN
  *	Implemented 3D games such as Mario Cars, FPS, Parkor game
  *	programmed game engines using C++ and SDL libraries
* Mobile App: Go Eat
  *	Developed a cross-platform app that recommends restaurants based on users’ preferences
  *	Created KNN and genetic models to recommend restaurants given users’ and restaurants’ features
  *	Stored and fetched data with Firebase
* Desktop Game: Mind Palace
  *	Developed a game that trains players’ mnemonic technique
  *	Designed game stages and implemented them with SDL library 
  *	Extract key information from sentences with Google Cloud API to
* FPGA Arcade Game “SPLATOON”
  *	Designed a 2D-board Splatoon game that runs on a Xilinx FPGA Spartan 6, implemented with Verilog
  *	Integrated joystick module for user control and VGA module for image display 
* Web Game “Mission Universe”
  *	Created a web-based, multiplayer jet-fighting game, using HTML, JavaScript, Java
  *	Utilized Phaser API to construct game elements and WebSocket to transmit data in multiplayer mode
* Home Light System IoT Project
  *	Developed a remote light control system running on Raspberry Pi
  *	Fetched data from light sensor and transmit it through OpenMote
  *	Utilized MQTT library to transmit data and control illumination
* Code Compiler
  *	Implemented a compiler that parses a realistic program into tree structure, with Bison and C++
  *	Generated assembly language and computed values of variables and memories
* Accelerometer
  *	Developed an accelerometer running on Arduino
  *	Integrated a rotary encoder to set threshold and a buzzer to present speed, controlled by interrupt

