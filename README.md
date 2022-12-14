# Design and Simulation of Superconducting Qubits

@ IEEE Quantum Week 2022

Registration available at <https://qce.quantum.ieee.org/registration/>.

10:00-16:45 Mountain Time (MDT), Thursday, Sept 22, 2022

## Abstract

Superconducting qubits are a leading modality in quantum computing. Innovation in superconducting device architecture is rapidly expanding, leading to an explosion of new designs. However, being a novel field, there is a lack of standardization in design flow processes, which limits the speed of design iteration. Industry professionals and academic researchers alike can easily spend many months on the iterative process of designing and testing their circuits. This process involves laying down a prospective architecture, simulating at both the circuit and quantum Hamiltonian level, and ends with the lengthy process of device fabrication and testing. To accelerate this process, a tighter coupling between design and Hamiltonian simulation methods is needed. More efficient and rigorous testing of prospective designs in simulation has the potential to vastly improve the “virtual prototyping’’ process, in which designs are more thoroughly tested in simulation before moving to the fabrication phase, allowing for faster iteration of designs.

The goal of this workshop is to bring together experts in both superconducting qubit design and quantum system simulation to share their expertise. In the first session, leaders in both fields are invited to present the state of the art. The second session will follow this up with more pedagogically focused presentations on the foundational topics in superconducting qubit design, and quantum system simulation and optimization, providing a theoretical foundation for those new to either field. Finally, the third session will consist of a practical demonstration of these principles, using the open source software tools Qiskit Metal and Qiskit Dynamics to walk through an example of the design and optimization process from start to finish. More integrated tools for system design and simulation processes have the potential to streamline the iterative prototyping process, leading to more rapid innovation.

## Agenda

<a href='https://qce.quantum.ieee.org/2022/home/program/program-schedule/'>Full IEEE Quantum Week Agenda<a/>

- 10:00 - 11:30 [First Speaker Session](#1045---1215-speaker-session-1)
- 11:30 - 1:00 Lunch (General IEEE Quantum event)
- 1:00 - 2:30 [Second Speaker session](#100---230-speaker-session-2)
- 2:30 - 3:15 Break and Posters (General IEEE Quantum event)
- 3:15 - 4:45 [Tool demonstration](#315---445-tool-demonstration)

### 10:45 - 12:15 Speaker Session 1

| Time<br/> &nbsp; | Speaker<br/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Topic<br/> &nbsp; |
|------|---------|-------|
|10:00 | <b><a href='https://www.linkedin.com/in/benjamin-rosand/'>Benjamin Rosand<a/><b/> <br/> Quantum Software *@* IBM Quantum | Introduction |
|10:03 | <b><a href='https://physics.northwestern.edu/people/faculty/core-faculty/jens-koch.html'>Jens Koch<a/><b/> <br/> Professor *@* Northwestern University <br/> Deputy Director SQMS <br/> Co-Director CAPST | "Computer-aided quantization and numerical analysis of custom circuits with scqubits" |
|      | <img src="Resources/Koch.png" alt="Koch" width="200"> |The development of new superconducting circuits and the improvement of existing ones rely on the accurate modeling of spectral properties key to achieving needed advances in qubit performance. Systematic circuit analysis at the lumped-element level, starting from a circuit network and culminating in a Hamiltonian appropriately describing the quantum properties of the circuit, is a well-established procedure, yet cumbersome to carry out manually for larger circuits. We discuss the circuit module extension to the open-source scqubits package which now utilizes symbolic computer algebra and numerical diagonalization routines versatile enough to tackle a variety of circuits. |
|10:23 | <b><a href='https://www.nist.gov/people/katarina-cicak'>Katarina Cicak<a/><b/> <br/> Researcher *@* National Institute of Standards and Technology<br/> | "Evolving devices for superconducting qubit technology" |
|      | <img src="Resources/Cicak.jpeg" alt="Cicak" width="200">|Our early work to understand sources of decoherence in superconducting (SC) qubits two decades ago improved basic SC microwave circuit components and circuit connectivity, informed modern transmon qubit design, and ultimately advanced SC technology for quantum information. The push to integrate and hybridize devices in order to access, connect, and exploit the quantum across different physical realms led to high performance devices like vacuum-gap capacitor drums in optomechanics, electro-optical quantum transducers for connecting disparate quantum systems from the microwave to the optical, and quantum efficient Josephson amplifiers on a versatile fabrication platform. Here we reveal key features that enable the innovation in these devices.  The overview of the technology presented serves as a good introduction to concepts informing design and simulation of SC devices in context of processes detrimental to quantum information, like loss, noise, and decoherence. |
|10:43 | <b><a href='https://physics.illinois.edu/people/directory/profile/akou'>Angela Kou<a/><b/> <br/> Assistant Professor *@* University of Illinois Urbana-Champaign<br/> | "Building a hybrid quantum device from an Andreev spin qubit and a superconducting transmon" |
|      | <img src="Resources/Kou.png" alt="Kou" width="200">|Hybrid superconducting circuits, which integrate non-superconducting elements into a circuit quantum electrodynamics (cQED) architecture expand the possible applications of cQED. For example, superconducting devices coupled to semiconducting spin qubits would enable long-distance coupling between long-lifetime spin qubits. Proper design of hybrid devices, however, require simulations of both the superconducting device and the non-superconducting elements. In this talk, I will discuss our experimental work coupling an Andreev spin qubit (ASQ) to a superconducting transmon and the associated theoretical work necessary to design our devices. We first use the transmon to perform spectroscopy on the ground states of a quantum dot with superconducting leads and map out the phase diagram of the superconductor-quantum dot-superconductor device. We then use the spin-split doublet ground state of S-QD-S device to form our ASQ and demonstrate direct coherent manipulation of the ASQ with Rabi rates of up to 200 MHz. Finally, we strongly coherently couple the ASQ to the transmon, which paves the way toward using superconducting devices to mediate interactions between distant ASQs. |
|11:03  |Moderator<br/><b><a href='https://www.nist.gov/people/john-teufel'>John Teufel<a/><b/> <br/> Quantum Physicist *@*  National Institute of Standards and Technology | **Panel Discussion** |
|      | <img src="Resources/Teufel.jpeg" alt="Teufel" width="200">| |
{: .tablelines}

### 1:00 - 2:30 Speaker Session 2

| Time<br/> &nbsp; | Speaker<br/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Topic<br/> &nbsp; |
|------|---------|-------|
|1:00 | <b><a href='https://www.uml.edu/sciences/physics/faculty/kamal-archana.aspx'>Archana Kamal<a/><b/> <br/> Associate Professor *@* UMass Lowell <br/> | "PIQUE: a new framework for quantum systems engineering" |
|      | <img src="Resources/Kamal.jpeg" alt="Kamal" width="200"> |High-fidelity quantum state preparation, manipulation and measurement are the three cornerstones of any quantum information processing platform. In this talk I will describe a new paradigm called PIQUE (for Parametrically-Induced QUantum Engineering), which promises new functionalities to tackle all three challenges in a unified framework employing parametric interactions between quantum systems. In the first part of my talk, I will focus on how parametrically-induced interactions can be leveraged for quantum reservoir engineering, specifically high-fidelity dissipative control and scalable entanglement generation. In the second part, I will focus on some recent results on the emerging platform of “parametric circuit-QED“ that provides new mechanisms for readout and control of quantum systems. |
|1:20 | <b><a href='https://profiles.stanford.edu/amir-safavi-naeini'>Amir Safavi-Naeini<a/><b/> <br/> Associate Professor *@* Stanford University<br/> | "SQCircuit and AutoQEC: Approaches for automated design and discovery of quantum circuits" |
|      | <img src="Resources/Safavi.jpeg" alt="Safavi" width="200">|In this talk I will outline two software packages developed by our group at Stanford with the goal of automating the design and discovery of superconducting quantum circuits. The first approach called AutoQEC, operates at the level of Hamiltonian and master equations, and is used to discover new error correcting schemes. The second package called SQcircuit, is a general circuit analysis tool that given a physical description of the circuit, can do a full quantum analysis and give us the Hamiltonian, as well as coupling and loss operators. Finally I will discuss some of our goals going forward in combining these different approaches to create powerful new tools for design and discovery.
 |
|1:40 | <b><a href='https://scholar.google.com/citations?user=Q0j-7W0AAAAJ&hl=en'>Holger Haas<a/><b/> <br/> Research Staff Member *@* IBM Quantum<br/> | "Quantum control strategies for enhancing fixed frequency transmon performance" |
|      | <img src="Resources/Haas.jpeg" alt="Holger" width="200">|Fixed frequency transmon qubit architectures come with always-on inter-qubit ZZ coupling, or quantum crosstalk, that can induce decoherence and gate errors. It is known that quantum control strategies, specifically, the application of phase and amplitude adjusted Stark shift tones on individual qubits (siZZle protocol), can negate the effect of such quantum crosstalk. We demonstrate the implementation of siZZle protocol for a 27-qubit device and present its implications for probabilistic error correction. Furthermore, we also discuss the simulation and use of amplitude-shaped Stark shift tones for implementing CZ gates. |
|2:00  |Moderator<br/><b><a href='https://scholar.google.com.au/citations?user=CxoASb4AAAAJ&hl=en'>Michael Hush<a/><b/> <br/> Chief Science Officer *@*  Q-Ctrl | **Panel Discussion** |
|      | <img src="Resources/Hush.jpeg" alt="Hush" width="200">| |
{: .tablelines}

### 3:15 - 4:45 Tool demonstration

<table class="tablelines">
  <thead>
  <tr>
    <th>Time</th>
    <th colspan="2">Speaker(s)</th>
    <th>Topic </th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td>3:15</td>
    <td colspan="2"><a href="https://scholar.google.com/citations?user=kih5-60AAAAJ"><b>Yehan Liu</b></a><br>IBM Quantum</td>
    <!-- <td><a href="PATRICKLINK"><b>Patrick O'Brien</b></a><br>IBM Quantum</td> -->
    <td>"Design of interacting superconducting quantum circuits with Qiskit Metal and Quantum Spice"</td>
  </tr>
  <tr>
    <td></td>
    <td colspan="2"><img src='Resources/Liu.png' alt="Liu" width="200"></td>
    <!-- <td><img src='Resources/OBrien.jpeg' alt="O'Brien" width="100"></td> -->
    <td>The remarkable growth in the field of quantum information processing increasingly requires precise, widely applicable, and modular methods that can model the quantum electrodynamics of the physical circuits, including their more-subtle renormalization effects. Here, we present a practical demonstration of a computationally efficient method satisfying these criteria. The method partitions a quantum device into compact lumped or quasi-distributed cells. Each is first simulated individually. The composite system is then reduced and mapped to a set of simple subsystem building blocks and their pairwise interactions. We demonstrate the versatility of this approach by several examples in a full stack workflow, from device layout to electromagnetic simulation, then to Hamiltonian analysis.<br>In this talk, we will showcase both the Qiskit Metal workflow and our latest Quantum Spice web app.</td>
  </tr>
  <tr>
    <td>3:50</td>
    <td colspan="2"><a href='https://scholar.google.com/citations?user=YW1hekQAAAAJ&hl=en'><b>Ziwen Huang</b></a><br>Research Associate @ Fermilab</td>
    <td>"Using Qiskit Metal to assist quantum device designing on 2D and 3D architectures"</td>
  </tr>
  <tr>
    <td></td>
    <td colspan="2"><img src='Resources/Huang.jpeg' alt="Huang" width="200"></td>
    <td>The optimization of the design of the superconducting circuits, including their structure, geometry, size, choice of material, etc., is key toward noise-resilient quantum computation. An efficient simulation tool that predicts the qubit parameters and performance under these specifications will not only save significant amount of experimental resource, but also enable more efficient exploration on novel experimental designs. In this talk, I first summarize the efforts on designing superconducting resonators at SQMS using Qiskit Metal and present the measurements on these devices. We explicitly show how Metal makes the designing more convenient. Second, I show some newly proposed designs, and present the simulation results by Metal. Finally, future efforts at SQMS on not only 2D but also 3D designs using this toolkit will be discussed.</td>
  </tr>
  <tr>
    <td>4:10</td>
    <td><a href="https://scholar.google.ca/citations?user=sRExdr0AAAAJ"><b>Daniel Puzzuoli</b></a><br>IBM Quantum</td>
    <td><a href="https://www.linkedin.com/in/benjamin-rosand"><b>Benjamin Rosand</b></a><br>IBM Quantum</td>
    <td>"Simulating quantum systems with Qiskit Dynamics"</td>
  </tr>
  <tr>
    <td></td>
    <td><img src='Resources/Puzzuoli.jpeg' alt="Puzzuoli" width="200"></td>
    <td><img src='Resources/Rosand.jpeg' alt="Rosand" width="200"></td>
    <td>Classical simulation is an important tool for understanding and controlling quantum devices, and can be a component of the design process itself. In this domain, performance is critical; the more simulations you can do per unit time, the more advanced workflows you can implement. As every simulation problem is different, and speed is impacted by many factors, optimizing performance of simulations requires finding the right configuration of numerical tools best suited to the problem. In this talk, we outline various numerical tools and how they can impact performance, from different algorithms to modern numerical linear algebra packages. We will then introduce the Qiskit Dynamics package, an open source Python package for simulating Hamiltonian and Lindblad dynamics, which has been designed to enable a variety of numerical tool configurations. We will end with a Qiskit Dynamics demo, with a focus on showing how to specify simulation problems, and configure them in the ways described throughout the talk.</td>
  </tr>
  </tbody>
</table>

### Organizers

<a href="https://www.linkedin.com/in/benjamin-rosand"><b>Benjamin Rosand: IBM Quantum, USA</b></a><br>
<a href="https://www.linkedin.com/in/patrick-obrien-phd"><b>Patrick O'Brien: IBM Quantum, USA</b></a><br>
<a href="https://scholar.google.com/citations?user=kih5-60AAAAJ&hl=en"><b>Yehan Liu: IBM Quantum, USA</b></a><br>
<a href="https://scholar.google.ca/citations?user=sRExdr0AAAAJ"><b>Daniel Puzzuoli: IBM Quantum, Canada</b></a><br>

<style>
.tablelines table, .tablelines td, .tablelines th {
        border: 1px solid black;
        overflow-x: auto;
        }

</style>
