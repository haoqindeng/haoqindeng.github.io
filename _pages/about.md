---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.md
---


I am currently an undergraduate student at the Department of Electrical and Computer Engineering, University of Southern California. I am expected to receive B.S degrees in Electrical and Computer Engineering in 2022. 

My current research interests include:

* Optical/Photonic Computing
* Quantum Computing
* CMOS Neuromorphic Circuits
* Spiking Neural Networks
* Machine Learning Acceleration with Emerging Technologies
* Software/Hardware Co-design

My personal interests include reading sci-fi/fan-fi/detective novels, playing Hearthstone, cooking dark cuisines.

The complete CV can be found here: [CV.pdf](https://haoqindeng.github.io/images/cv.pdf)

Publications
======

* **Parity-time symmetric optical neural networks**
  *	**Haoqin Deng**, Mercedeh Khajavikhan
  *	Optica, Oct., 2021.
  * [PDF](https://www.osapublishing.org/DirectPDFAccess/79A24C4A-376B-4DC7-A11FA9DBB1F4DD55_460568/optica-8-10-1328.pdf?da=1&id=460568&seq=0&mobile=no), [SLIDES](https://docs.google.com/presentation/d/1XzsGmUK8dy9Yh141qB497mno4hSBjfXrwpHvSLL8eCU/edit#slide=id.p)

* **AccQOC: Accelerating Quantum Optimal Control Based Pulse Generation**
  *	Jinglei Cheng, **Haoqin Deng**, Xuehai Qian
  *	International Symposium on Computer Architecture (ISCA), May, 2020.
  * [PDF](https://arxiv.org/pdf/2003.00376.pdf), [SLIDES](https://docs.google.com/presentation/d/1axy5mV14oSG08vWh7tF4VN6wQ9bVRVwXNK0sJfZjPgM/edit#slide=id.p)

Researches:
======

* **Optical computing**<br/>
  *Research Assistant; Supervised by* ***Prof. Mercedeh Khajavikhan****; Jun 2021 – present*
  * Researched various architectures of Optical Neural Network(ONN), Quantum Optical Neural Network(QONN), Continuous/Discrete Variable Quantum Computation
  * Developed PT-ONN architecture with cascading PT-symmetric couplers, based on modulations of gain/loss contrasts; implemented simulations of on-chip training of PT-ONN using finite difference method with Python; achieved 68% training accuracy on MNIST dataset; simulated directional couplers in COMSOL; verified system transfer matrix of PT couplers with Mathematica
  * Reproduced on-chip training of MZI-based ONN with Python; achieved 71% on-chip training accuracy on MNIST dataset
  * Investigated the detrimental effect of V-shaped, intensity-dependent optical nonlinearity on VGG network architecture
* **Spiking Neural Networks: Long Short-Term Memory (LSTM)**<br/>	
  *Research Assistant, supervised by* ***Prof. Peter Bereel****; Aug 2021 - present*
  * Developed custom Spiking LSTM that allows pipelined inferencing
  * Implemented custom Analog LSTM and Spiking LSTM module with PyTorch; 
  * Implemented RNN-to-SNN conversion through weight transfer and spike-timing-dependent plasticity (STDP) training; achieved 85%, 96% testing accuracy on IMDB, temporal-MNIST datasets

* **CMOS neuromorpic circuits**<br/>
  *Research Assistant; Supervised by* ***Prof. Alice Parker****; Jun 2021 – August 2021*
  * Developed VLSI circuits of excitatory/inhibitory synapse, Axon Hillock, STDP-dopamine-noise synapse, dendritic spiking, edge detector, voltage adder, using Cadence; designed transistors to operate at subthreshold regime; obtained ideal biological waveforms for each circuit component
  * Designed a multi-layer neural network with edge-detection, STDP-synapse, and dopamine-modulation layers; used PyTorch to simulate the network topology, spike propagation, and synaptic weight update, with hardware-realistic parameters; achieved unity accuracy on self-designed four-class, nine-pixel dataset
  * [Report](https://haoqindeng.github.io/images/report.pdf)<br/> 

* **Quantum computing**<br/>
  *Research Assistant; Supervised by* ***Prof. Xuehai Qian****; May 2019 – Sept 2020*
  * Developed Accelerating Quantum Optimal Control (accQOC), a comprehensive compilation methodology that accelerates pulse generation by 9x:
    * partitioned the DAG of quantum circuit into sub-components under size constraints, using Qiskit
    * concatenated QOC pulses of each components using dynamic programming
    * balance partitionioned the MST of computing nodes for efficient parallel computation, using METIS
  * Worked on the optimization of VQE(Variational Quantum Eigen-solver) algorithm:
    * worked on circuit-level implementation of VQE with pyQpanda
    * optimized VQE measurement overhead through joint measurement of commuting Hamiltonians; projecting linearly-independent basis terms onto qubit computational basis using stabilizer formalism
    * worked on pulse-level optimization of VQE circuits using Qiskit open-pulse and QOC

* **In-memory computing with InP memristor**<br/>
  *Research Assistant; Supervised by* ***Prof. Rehan Kapadia****; Jun 2020 – Jan 2021*
  *	Researched various architectures of mapping ANN/SNN onto hardware using semiconductor devices that mimic synapses, neurons
  * Simulated a temporal-encoded convolutional Spiking Neural Network(SNN) and a rate-encoded SNN with PyTorch, incorporating InP-synapse STDP parameters; achieved 89 & 91% training accuracies respectively, on MNIST dataset
  * Collaborated on designing Arduino/breadboard implementation of neural networks, utilizing a crossbar array of InP memristors
  * Grew InP using the Low-Temperature Templated Liquid-Phase(LT-TLP) technique



Internships
======

* Summer Internship, Shanghai AIKE Measurement Co. (July 2018 – August 2018)
  *	Learned to use Labview to sample data and control hardware
  * Used Labview to automate a printer to print labels on a streamline
  * Assisted in designing the structure of a dispenser

Activities
======

* **Mobile App: Go Eat**
  *	Developed a cross-platform app that recommends restaurants according to users’ preferences
  * Developed KNN and genetic models to recommend restaurants based on users’ and restaurants’ features
  * Implemented data fetching and storage using Firebase
* **Desktop Game: Mind Palace**
  *	Developed a game that trains players to master ”Mind Palace” mnemonic technique
  * Designed game stages and implemented them with SDL library
  * Extracted key information from sentences with Google Cloud API
* **Neural Signal Sampling**
  * Collaborated on designing a neural-signal sampling device
  * Realized data transfer between FPGA and PC using Opal-Kelly’s API; implemented SPI protocol to transfer data between FPGAs; visualized data on PC end with matplotlib library




Class Projects
======
* **Reinforcement Learning in Games**
  * Developed customized gym-compatible, overhead-shooting game environment with pygame
  * Trained AI agents to achieve close to full score with Deep Q learning (DQN), written with PyTorch
  * Currently extending the current framework to allow multi-player collaboration
* **CMOS VLSI** 
  *	Implemented a 32 bit MAC unit with Brent-kung Adder and Array Multiplier; 
  *	Created schematics and drew layouts using Cadence
* **Parallel Programming**
  *	Developed grayscale-to-color image conversion using CNN
  *	Converted python model into C++ model using keras2cpp library
  *	Parallelized convolution-layer computation using OpenMP and Pthread library
* **Video Game Programming**	
  *	Implemented 2D classical Arcade games such as Zelda, Super Mario, PAC-MAN
  *	Implemented 3D games such as Mario Cars, FPS, Parkor game
  *	Programmed game engines using C++ and SDL libraries
* **FPGA Arcade Game “SPLATOON”**
  *	Designed a 2D-board Splatoon game that runs on a Xilinx FPGA Spartan 6, implemented with Verilog
  *	Integrated joystick module for user control and VGA module for image display 
* **Web Game “Mission Universe”**
  *	Created a web-based, multiplayer jet-fighting game, using HTML, JavaScript, Java
  *	Utilized Phaser API to construct game elements and WebSocket to transmit data in multiplayer mode
* **Home Light System IoT Project**
  *	Developed a remote light control system running on Raspberry Pi
  *	Fetched data from light sensor and transmit it through OpenMote
  *	Utilized MQTT library to transmit data and control illumination
* **Code Compiler**
  *	Implemented a compiler that parses a realistic program into tree structure, with Bison and C++
  *	Generated assembly language and computed values of variables and memories
* **Accelerometer**
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
* CSCI527: Applied Machine Learning in Games
* CSCI201: Pinciple of Software Engineering
* CSCI270: Introduction to Algorithms and Theory of Computing
* CSCI104: Objected Oriented Programming
* CSCI353: Internetworking
* Math407: Propability Theory
* Math445: Mathematics of Physics and Engineering
* Phys438: Introduction to Quantum Mechanics
* Phys304: Mechanics
* ITP445: Professional C++
* ITP380: Video Game Programming
