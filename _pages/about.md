---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.md
---


I am currently an undergraduate student at the Department of Electrical and Computer Engineering, University of Southern California. I am expected to receive B.S./M.S. degrees in Electrical and Computer Engineering in 2022. 

My current research interests include:

* Optical/Photonic Computing
* Quantum Computing
* Neuromorphic ICs
* Machine Learning Acceleration with Emerging Technologies
* Software/Hardware Co-design

My personal interests include reading sci-fi/fan-fi/detective novels, playing Hearthstone, cooking dark cuisines.

The complete CV can be found here: [CV.pdf](https://haoqindeng.github.io/images/cv.pdf)

Publications
======
* **AccQOC: Accelerating Quantum Optimal Control Based Pulse Generation**
  *	Accepted. [Preprint](https://arxiv.org/abs/2003.00376)
  *	Jinglei Cheng, **Haoqin Deng**, Xuehai Qian
  *	2020 Annual International Symposium on Computer Architecture, ISCA

* **Parity-time symmetric optical neural networks**
  *	Accepted.
  *	**Haoqin Deng**, Mercedeh Khajavikhan
  *	Optica, OSA



Researches:
======
* **Spiking Neural Networks**<br/>
  *Research Assistant; Supervised by* ***Prof. Peter Beerel****; September 2021 – present*
  * Currently developing an RNN-SNN framework that
    * converts analog LSTM to spiking LSTM through weight transfer and spike-domain finetuning
    * allows pipelined inference on SNN hardware.

* **Optical computing**<br/>
  *Research Assistant; Supervised by* ***Prof. Mercedeh Khajavikhan****; Jun 2021 – present*
  * Researched on various architectures of Optical Neural Network(ONN), Quantum Optical Neural Network(QONN), Coherent Variable(CV) Quantum Computation
  * Proposed and developed PT-ONN architecture with cascading PT-symmetric couplers, based on modulations of gain/loss contrast; implemented simulations of on-chip training of PT-ONN using finite difference method with python; achieved 67% training accuracy on MNIST
  * Worked on simulations of directional couplers in COMSOL; calculated system transfer matrix of PT couplers with Mathematica
  * Reproduced on-chip training of MZI-based ONN with python; achieved 71% training accuracy on MNIST

* **CMOS neuromorpic circuits**<br/>
  *Research Assistant; Supervised by* ***Prof. Alice Parker****; Jun 2021 – August 2021*
  * Developed VLSI circuits of excitatory/inhibitory synapse, Axon Hillock, STDP-dopamine-noise synapse,  dendritic spiking, edge detector, voltage adder
  * Constructed hardware & software multi-layer neural networks incorporating local STDP update and global dopamine modulation, using Cadence & Python
  * Currently developing a program that synthesizes VLSI circuits corresponding to software neural network model for deployment purpose

* **In-memory computing with InP memristor**<br/>
  *Research Assistant; Supervised by* ***Prof. Rehan Kapadia****; Jun 2020 – Jan 2021*
  *	Researched on various architectures of mapping ANN/SNN onto hardware using semiconductor devices that mimic functions of synapses, neurons
  *	Simulated a temporal-encoded convolutional SNN on MNIST digit recognition task with PyTorch and GPU acceleration, incorporating InP-synapse STDP parameters; achieved 89% accuracy
  *	Simulated a rate-encoded SNN on MNIST digit recognition task with PyTorch and GPU acceleration, incorporating InP-synapse STDP parameters, with 71% accuracy
  *	Collaborated on designing Arduino/breadboard implementation of neural networks, utilizing a crossbar array of InP transistors.
  *	Grew InP on GaAs using Low-Temperature Templated Liquid-Phase(LT-TLP) technique.

* **Quantum computing**<br/>
  *Research Assistant; Supervised by* ***Prof. Xuehai Qian****; May 2019 – Sept 2020*
  * Developed Accelerating Quantum Optimal Control (accQOC), a comprehensive compilation methodology that accelerates pulse generation by 9X 
    * partitioned DAG of quantum circuit into sub-components under size constraint
    * generated optimized pulse for each component using QOC
    * balance partitionioned MST computing nodes for efficient parallel computation, using METIS
  * Worked on optimization of VQE(Variational Quantum Eigen-solver) algorithm
    * worked on circuit-level implementation of VQE with pyqpanda
    * optimized VQE measurement overhead through joint measurement of commuting Hamiltonians; projecting LI basis terms onto qubit computational basis using stabilizer formalism
    * attempted pulse-level optimization of VQE circuits using Qiskit open-pulse and QOC

* **Signal sampling**<br/>	
  *Research Assistant; Supervised by* ***Prof. Manual Monge****; Mar 2019 – Mar 2020*
  * Corroborated on designing a neural-signal sampling device
  * Realized data transfer between FPGA and PC using Opal-Kelly’s API; implemented SPI protocol to transfer data between FPGAs; visualized data on PC end with matplotlib library


Internships
======

* Summer Internship, Shanghai AIKE Measurement Co. (July 2018 – August 2018)
  *	Automated printers to print labels on a pipeline using Labview
  *	Corroborated on designing the structure of a dispenser for lab usage
  *	Kept track of daily tasks and progress for the team

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
* RL in games
  * Developed customized gym-compatible, overhead-shooting game environment with pygame
  * Trained AI agents to achieve close to full score with Deep Q learning (DQN), written with PyTorch
  * Currently extending the current framework to allow multi-player collaboration
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

Skills:
======
Programing/Software:
* Python 
* C/C++
* Java
* PyTorch
* Qiskit
* pyqpanda
* Verilog
* Cadence

Related Course
======
* EE514: Quantum Error Correction
* EE301: Linear Systems 
* EE370: Electromagnetism 
* EE354: Introduction to Digital Circuits
* EE348: Electronic Circuits
* EE451: Parallel and Distributed Computation
* EE457: Computer System Organization
* EE477: MOS VLSI Circuit Design
* EE459: Embedded System Design Laboratory
* EE520: Introduction to Quantum Computing
* EE582: Neuromorphic Computing
* EE540: Quantum Electronics 
* CSCI201: Pinciple of Software Engineering
* CSCI270: Introduction to Algorithms and Theory of Computing
* CSCI104: Objected Oriented Programming
* CSCI353: Internetworking
* Math 407: Propability Theory
* Math 445: Mathematics of Physics and Engineering
* Phys438: Introduction to Quantum Mechanics
* Phys304: Mechanics
* ITP445: Professional C++
* ITP380: Video Game Programming
