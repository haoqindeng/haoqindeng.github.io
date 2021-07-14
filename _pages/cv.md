---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

[CV pdf](https://haoqindeng.github.io/images/cv.pdf)

Education
======
* B.S. ECE, University of Southern California; GPA: 3.68/4.0
* M.S. EE, University of Southern California; GPA: 4.0/4.0
  
Skills
======
*	Courses: Data Structure, Algorithms, Machine Learning, Software Engineering, Digital Circuits, FPGA programming, Internetworking, Cellular Biology, Quantum Mechanics, Open Quantum System, Semiconductor Devices, Non-linear Circuits, Electromagnetism, VLSI, Neuromorphic computing
*	Programming languages: C/C++, Python, Java, Verilog
*	Tools & Softwares: Pytorch, Qiskit, pyqpanda, Cadence, ModelSim

Researches:
======

* **BioRC Group**<br/>
  *Research Assistant; Supervised by* ***Prof. Alice Parker****; Jun 2021 – present*
  * Developed VLSI circuits of excitatory/inhibitory synapse, Axon Hillock, STDP-dopamine-noise synapse,  dendritic spiking, edge detector, voltage adder
  * Constructed hardware & software multi-layer neural networks incorporating local STDP update and global dopamine modulation, using Cadence & Python
  * Currently developing a pytorch library that 
    * allows for convenient construction of software neural network for training & verification purpose
    * synthesizes VLSI circuits corresponding to software neural network model for deployment purpose

* **Khajavikhan Optics and Photonics Group**<br/>
  *Research Assistant; Supervised by* ***Prof. Mercedeh Khajavikhan****; Jun 2021 – present*
  * Researched on various architectures of Optical Neural Network(ONN), with an emphasis on chip-integrable setups
  * Proposed and developed PT-ONN architecture with cascading PT-symmetric couplers, based on modulations of gain/loss contrast; implemented simulations of on-chip training of PT-ONN using finite difference method with python; achieved 67% training accuracy on MNIST
  * Worked on ewbm simulations of directional couplers in COMSOL; calculated system transfer matrix of PT couplers with Mathematica
  * Reproduced on-chip training of MZI-based ONN with python; achieved 71% training accuracy on MNIST

* **USC Laboratory for Photons, Electrons and Materials**<br/>
  *Research Assistant; Supervised by* ***Prof. Rehan Kapadia*** *; Jun 2020 – Jan 2021*
  *	Researched on various architectures of mapping ANN/SNN onto hardware using semiconductor devices that mimic functions of synapses, neurons
  *	Simulated a rate-encoded convolutional SNN on MNIST digit recognition task with Pytorch and GPU acceleration, incorporating InP-synapse STDP parameters, with 71% accuracy
  *	Simulated a temporal-encoded SNN on MNIST digit recognition task with Python and GPU acceleration, incorporating InP-synapse STDP parameters; achieved 89% accuracy
  *	Collaborated on designing Arduino/breadboard implementation of neural networks, utilizing a crossbar array of InP transistors.
  *	Grew InP on GaAs using Low-Temperature Templated Liquid-Phase(LT-TLP)  technique.

* **USC ALCHEM Lab**<br/>
  *Research Assistant; Supervised by* ***Prof. Xuehai Qian*** *; May 2019 – Sept 2020*
  * Developed Accelerating Quantum Optimal Control (accQOC), a comprehensive compilation methodology that accelerates pulse generation by 9X 
    * partitioned DAG of quantum circuit into sub-components under size constraint
    * generated optimized pulse for each component using QOC
    * balance partitionioned MST computing nodes for efficient parallel computation, using METIS
  * Worked on optimization of VQE(Variational Quantum Eigen-solver) algorithm
    * self-implemented VQE circuits with pyqpanda
    * optimized VQE measurement overhead through joint measurement of commuting Hamiltonians, projecting LI basis terms onto qubit computational basis using stabilizer formalism
    * attempted pulse-level optimization of VQE circuits using Qiskit open-pulse and QOC

* **USC IMEDE Lab**<br/>	
  *Research Assistant; Supervised by* ***Prof. Manual Monge*** *; Mar 2019 – Mar 2020*
  * Corroborated on designing a neural-signal sampling device
  * Realized data transfer between FPGA and PC using Opal-Kelly’s API; implemented SPI protocol to transfer data between FPGAs; visualized data on PC end with matplotlib library


Publications
======
* AccQOC: Accelerating Quantum Optimal Control Based Pulse Generation
  *	Accepted. [Preprint](https://arxiv.org/abs/2003.00376)
  *	Jinglei Cheng, Haoqin Deng, Xuehai Qian
  *	2020 Annual International Symposium on Computer Architecture, ISCA

* Parity-time symmetric optical neural networks 
  *	Under review.
  *	Haoqin Deng, Mercedeh Khajavikhan
  *	Submitted to Optica, OSA

Internships
======

* Summer Internship, Shanghai AIKE Measurement Co. (July 2018 – August 2018)
  *	Automated printers to print labels on a pipeline using Labview
  *	Corroborated on designing the structure of a dispenser for lab usage
  *	kept track of daily tasks and progress for the team

Hackthones
======

* Mobile App: Go Eat
  *	Developed a cross-platform app that recommends restaurants based on users’ preferences
  *	Developed KNN and genetic models to recommend restaurants given users’ and restaurants’ features
  *	Implemented data fetching as storage using Firebase
* Desktop Game: Mind Palace
  *	Developed a game that trains players’”Mine Palace”  mnemonic technique
  *	Designed game stages and implemented them with SDL library 
  *	Extract key information from sentences with Google Cloud API for grading purpose


Class Projects
======
* CMOS VLSI 
  *	Implemented a 32 bit MAC unit with Brent-kung Adder and Array Multiplier; 
  *	Created schematics and drew layouts using Cadence
* Parallel Programming	
  *	Developed grayscale-to-color image conversion using CNN
  *	Converted python model into C++ model using keras2cpp library
  *	Parallelized convolution-layer computation using OpenMP and Pthread library
* Video Game Programming	
  *	Implemented 2D classical Arcade games such as Zelda, Super Mario, PAC-MAN
  *	Implemented 3D games such as Mario Cars, FPS, Parkor game
  *	Programmed game engines using C++ and SDL libraries
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