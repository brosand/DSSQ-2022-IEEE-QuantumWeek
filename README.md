# Design and Simulation of Superconducting Qubits
@ IEEE Quantum Week 2022

Registration available at https://qce.quantum.ieee.org/registration/.

10:00-16:45 Mountain Time (MDT), Thursday, Sept 22, 2022


## Abstract

Superconducting qubits are a leading modality in quantum computing. Innovation in superconducting device architecture is rapidly expanding, leading to an explosion of new designs. However, being a novel field, there is a lack of standardization in design flow processes, which limits the speed of design iteration. Industry professionals and academic researchers alike can easily spend many months on the iterative process of designing and testing their circuits. This process involves laying down a prospective architecture, simulating at both the circuit and quantum Hamiltonian level, and ends with the lengthy process of device fabrication and testing. To accelerate this process, a tighter coupling between design and Hamiltonian simulation methods is needed. More efficient and rigorous testing of prospective designs in simulation has the potential to vastly improve the “virtual prototyping’’ process, in which designs are more thoroughly tested in simulation before moving to the fabrication phase, allowing for faster iteration of designs.

The goal of this workshop is to bring together experts in both superconducting qubit design and quantum system simulation to share their expertise. In the first session, leaders in both fields are invited to present the state of the art. The second session will follow this up with more pedagogically focused presentations on the foundational topics in superconducting qubit design, and quantum system simulation and optimization, providing a theoretical foundation for those new to either field. Finally, the third session will consist of a practical demonstration of these principles, using the open source software tools Qiskit Metal and Qiskit Dynamics to walk through an example of the design and optimization process from start to finish. More integrated tools for system design and simulation processes have the potential to streamline the iterative prototyping process, leading to more rapid innovation.




## Agenda

### 10:00 - 11:30 First Speaker Session

we need to time lunch? assume 45 min?
### 11:30 - 12:15 Lunch? But this is before lunch. Annoying!

### 12:15 - 1:00 this is when lunch should be!

### 1:00 - 2:30 Second Speaker session

### 3:15 - 4:45 Tool demonstration

### 10:45 - 12:15 Academic Session
| Time<br/> &nbsp; | Speaker<br/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Topic<br/> &nbsp; |
|------|---------|-------|
|5MIN | **Someone** | Introduction |
|TIME | **Jens Koch** <br/> > Associate Professor *@* Northwestern University <br/> Co-Director, Applied Physics Graduate Program Department of Physics and Astronomy<br/> | "Computer-aided quantization and numerical analysis of custom circuits with scqubits" |
|      | <img src="https://github.com/brosand/DSSQ-2022-IEEE-QuantumWeek/blob/main/Resources/koch.png" alt="Koch" width="200"> |The development of new superconducting circuits and the improvement of existing ones rely on the accurate modeling of spectral properties key to achieving needed advances in qubit performance. Systematic circuit analysis at the lumped-element level, starting from a circuit network and culminating in a Hamiltonian appropriately describing the quantum properties of the circuit, is a well-established procedure, yet cumbersome to carry out manually for larger circuits. We discuss the circuit module extension to the open-source scqubits package which now utilizes symbolic computer algebra and numerical diagonalization routines versatile enough to tackle a variety of circuits. |
|11:35 | **Katarina Cicak** <br/> Researcher *@* National Institute of Standards and Technology<br/> | "Evolving devices for superconducting qubit technology" |
|      | <img src="https://github.com/brosand/DSSQ-2022-IEEE-QuantumWeek/blob/main/Resources/cicak.jpg" alt="Cicak" width="200">|Our early work to understand sources of decoherence in superconducting (SC) qubits two decades ago improved basic SC microwave circuit components and circuit connectivity, informed modern transmon qubit design, and ultimately advanced SC technology for quantum information. The push to integrate and hybridize devices in order to access, connect, and exploit the quantum across different physical realms led to high performance devices like vacuum-gap capacitor drums in optomechanics, electro-optical quantum transducers for connecting disparate quantum systems from the microwave to the optical, and quantum efficient Josephson amplifiers on a versatile fabrication platform. Here we reveal key features that enable the innovation in these devices.  The overview of the technology presented serves as a good introduction to concepts informing design and simulation of SC devices in context of processes detrimental to quantum information, like loss, noise, and decoherence. |

|4:15  |Moderator<br/>**Yaniv Rosen** <br/> Quantum Physicist *@* Lawrence<br/> Livermore National Lab | **Panel Discussion** |
|      | <img src="https://github.com/ThomasGM4/QHDA-2021-IEEE-QuantumWeek/blob/main/Resources/rosen.jpg" alt="Rosen" width="200">| |


### 1:00 - 2:30 Commercial Software Session
| Time<br/> &nbsp; | Speaker<br/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Topic<br/> &nbsp; |
|------|---------|-------|
|1:00  |**Brian Rautio** <br/> VP Operations *@* Sonnet Software |  "EM Simulation—when does it break?"  |
|      | <img src="https://github.com/ThomasGM4/QHDA-2021-IEEE-QuantumWeek/blob/main/Resources/rautio.jpg" alt="Rautio" width="200">| As a large, multi-decade industry full of strong and reliable products, it’s easy to trust the results of your EM simulator. However, at Sonnet, we can understand that simulation is inherently going to be wrong to some degree. The question we always need to ask is, “How wrong is my answer?” It’s a spectrum and the error margins may be insignificant to alarming, and the types of things we do and the way we drive our simulators can have a significant impact on that. Pushing the limit of physics means that we may be pushing the limits of our EM simulation as well, and this talk will help navigate that concept with awareness.|
|1:15  |**Kostas Nikellis** <br/> Director of R&D *@* Ansys Inc. |  "Large scale modeling of electromagnetic effects in superconductive silicon designs" |
|      | <img src="https://github.com/ThomasGM4/QHDA-2021-IEEE-QuantumWeek/blob/main/Resources/nikellis.jpg" alt="Nikellis" width="200">|The increasing size and complexity of superconductive silicon designs has resulted in additional needs in terms of electromagnetic modeling. Super-accurate modeling of inductance in various small parts of the layout and a robust crosstalk model between the physical qubits are critical for a successful design. In this session, we will present RaptorQ, an extremely high-capacity engine that boosts the limits of electromagnetic simulation to include problems that, until recently, seemed impossible to solve. |
|1:30  |**Chris Mueth** <br/> Business Development, Marketing, and Technical Specialist *@* Keysight Technologies |  "Quantum Hardware Design and Analysis: Challenges, Technology, Workflows"  |
|      | <img src="https://github.com/ThomasGM4/QHDA-2021-IEEE-QuantumWeek/blob/main/Resources/mueth.jpg" alt="Mueth" width="200">|Engineers designing Quantum qubits today face a lot of challenges.  Linking the Hamiltonian world to the EDA design world must be done.  From there, the engineer needs to select the right EDA technologies and understand how to apply these.  Lastly, they must design the qubit in an efficient and effective manner.   This paper explores the various challenges the Quantum hardware designer faces, the technology available to them, and requirements for an efficient workflow. |
|1:45  |**Davi Correia** <br/> Sr. Principal Application Engineer *@* Cadence Design Systems|  "Clarity 3D Solver: The New Standard in 3D Electromagnetics" |
|      | <img src="https://github.com/ThomasGM4/QHDA-2021-IEEE-QuantumWeek/blob/main/Resources/correia.jpg" alt="Correia" width="200">|Clarity, a breakthrough in electromagnetic simulation, is going to be presented. We will explore Clarity from two perspectives. First, we will see the performance side of Clarity, and we will understand why it is much more efficient than the legacy solutions currently available in the market. We will show how Clarity uses the computational resources available to create the mesh and to solve the matrices in a completely new approach to the problem, and show examples of the performance gain. Second, we will see the integration side of Clarity, and show an example on how it can be part of your entire flow so you can focus on your design, not on exporting the geometry, setting up your EM simulation, extracting S-parameters, stitching it back into your circuit, etc.  At the end we will show that if your bottleneck is performance (simulation time/capacity) or engineering time (set up time, multiple tools) Clarity can help.|
|2:00  |Moderator<br/>**John P. DeVale** <br/> Group Supervisor *@* The Johns Hopkins University Applied Physics Laboratory| **Panel Discussion** |
|      | <img src="https://github.com/ThomasGM4/QHDA-2021-IEEE-QuantumWeek/blob/main/Resources/devale.jpg" alt="DeVale" width="200">| |

### 3:15 - 4:45 Open-source Software Session
| Time<br/> &nbsp; | Speaker<br/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Topic<br/> &nbsp; |
|------|---------|-------|
|3:15  |**Jens Koch** <br/> Associate Professor *@* Northwestern<br/> University | "scqubits: a Python package for superconducting qubits" |
|      | <img src="https://github.com/ThomasGM4/QHDA-2021-IEEE-QuantumWeek/blob/main/Resources/koch.jpg" alt="Koch" width="200">|Superconducting qubits have emerged as a top technology in the pursuit of quantum computation. The quantitative modeling of such circuits is a critical cornerstone in research and development of this hardware platform. The open-source package “scqubits” streamlines the modeling of superconducting qubits and coupled circuit QED systems. This presentation will highlight package capabilities including the prediction of spectra and coherence properties, the construction of composite systems of multiple qubits and harmonic modes, and the ease of performing multi-dimensional parameter sweeps of circuit QED systems. *We gratefully acknowledge support by the AFOSR under grant FA9550-20-1-0271.* |
|3:30  |**Marco Facchini** <br/> Senior Development Engineer *@* IBM | "Qiskit Metal - Superconducting Qubit Chip Design and Analysis" |
|      | <img src="https://github.com/ThomasGM4/QHDA-2021-IEEE-QuantumWeek/blob/main/Resources/facchini.png" alt="Facchini" width="200">|If you start designing semiconducting quantum chips today, you are bound to face a fragmented design flow landscape. Available tools may or may not be ready to support some of the key features, and most of the quantum-specific algebra lives in ink publications. Additionally, this design flow is by nature iterative, setting the stage for time inefficiency and human-errors. We started Qiskit Metal to unify the semiconducting qubit chip design flow, and to help unify the quantum community on a framework that allows to freely share your innovation and discoveries.|
|3:45  |**Johannes Heinsoo** <br/> Senior Quantum Engnieer *@* IQM |  KQCircuits, an open-source package for drawing automation of<br/> superconducting quantum processors |
|      | <img src="https://github.com/ThomasGM4/QHDA-2021-IEEE-QuantumWeek/blob/main/Resources/heinsoo.jpg" alt="Heinsoo" width="200">|<p>The research field of quantum computing with superconducting qubits is maturing. There is still a lack of established open-source tools for design of quantum processing unit (QPU) elements, chips, and lithography masks. In some research groups, this task is still done by manually drawing the polygons or using locally developed software components prone to human errors and limited scalability. </p><p>We present KQCircuits, a GPLv3-licensed tool developed at IQM Finland, that enables designing QPU out of parameterized elements with geometric relations. The basic elements, chips and mask can be drawn programmatically and using a graphical user interface. Masks and simulation scripts can be exported to establish a complete and robust workflow. Most standard QPU elements, and some single and multi-layer chips are provided as examples.</p><p>With KQCircuits, quantum engineers are empowered to quickly develop new quantum experiments and processors while also having the opportunity to contribute to the codebase and libraries to help their peers and push the field forward.</p>|
|4:00  |**Boxi Li** <br/> PhD Candidate *@* Forschungszentrum<br/> Jülich | QuTiP | "Quantum Hardware Simulation with QuTiP" |
|      | <img src="https://github.com/ThomasGM4/QHDA-2021-IEEE-QuantumWeek/blob/main/Resources/boxi.jpg" alt="Li" width="200">|Simulating quantum dynamics is of essential importance in the design and engineering of various components in quantum hardware. The Quantum Toolbox in Python (QuTiP), one of the earliest open-source software packages in simulating quantum dynamics, has been widely used in developing qubits, quantum gates and measurement protocols. The package is now being developed under a worldwide collaboration and has grown rapidly in the last few years. In this talk, I will briefly present the basic functionality of the package and introduce a few new features that offer more flexibility in hardware simulation. In particular, in the next major version of QuTiP, qutip-v5, one will be able to define custom data types and ODE solvers as a plug-in package. Moreover, in the new sub-package, qutip-qip, we provide tools for circuit simulation at the level of time evolution, allowing studying various kinds of noise in the numerical simulation. |
|4:15  |Moderator<br/>**Yaniv Rosen** <br/> Quantum Physicist *@* Lawrence<br/> Livermore National Lab | **Panel Discussion** |
|      | <img src="https://github.com/ThomasGM4/QHDA-2021-IEEE-QuantumWeek/blob/main/Resources/rosen.jpg" alt="Rosen" width="200">| |


### Organizers

Thomas G. McConkey: IBM Quantum, USA

Zlatko Minev: IBM Quantum, USA

Nicholas Bronn: IBM Quantum, USA