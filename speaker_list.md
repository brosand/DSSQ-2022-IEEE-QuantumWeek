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
|10:03 | <b><a href='https://physics.northwestern.edu/people/faculty/core-faculty/jens-koch.html'>Jens Koch<a/><b/> <br/> Professor *@* Northwestern University <br/> Deputy Director of the DOE Center for Superconducting Quantum Materials and Systems <br/> Co-Director of the Northwestern-Fermilab Center for Applied Physics of Superconducting Technologies | "Computer-aided quantization and numerical analysis of custom circuits with scqubits" |
|10:23 | <b><a href='https://www.nist.gov/people/katarina-cicak'>Katarina Cicak<a/><b/> <br/> Researcher *@* National Institute of Standards and Technology<br/> | "Evolving devices for superconducting qubit technology" |
|10:43 | <b><a href='https://physics.illinois.edu/people/directory/profile/akou'>Angela Kou<a/><b/> <br/> Assistant Professor *@* University of Illinois Urbana-Champaign<br/> | "Building a hybrid quantum device from an Andreev spin qubit and a superconducting transmon" |
|11:03  |Moderator<br/><b><a href='https://www.nist.gov/people/john-teufel'>John Teufel<a/><b/> <br/> Quantum Physicist *@*  National Institute of Standards and Technology | **Panel Discussion** |
{: .tablelines}

### 1:00 - 2:30 Speaker Session 2

| Time<br/> &nbsp; | Speaker<br/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Topic<br/> &nbsp; |
|------|---------|-------|
|1:00 | <b><a href='https://www.uml.edu/sciences/physics/faculty/kamal-archana.aspx'>Archana Kamal<a/><b/> <br/> Associate Professor *@* UMass Lowell <br/> | "PIQUE: a new framework for quantum systems engineering" |
|1:20 | <b><a href='https://profiles.stanford.edu/amir-safavi-naeini'>Amir Safavi-Naeini<a/><b/> <br/> Associate Professor *@* Stanford University<br/> | "SQCircuit and AutoQEC: Approaches for automated design and discovery of quantum circuits" |
 |
|1:40 | <b><a href='https://scholar.google.com/citations?user=Q0j-7W0AAAAJ&hl=en'>Holger Haas<a/><b/> <br/> Research Staff Member *@* IBM Quantum<br/> | "Quantum control strategies for enhancing fixed frequency transmon performance" |
|2:00  |Moderator<br/><b><a href='https://scholar.google.com.au/citations?user=CxoASb4AAAAJ&hl=en'>Michael Hush<a/><b/> <br/> Chief Science Officer *@*  Q-Ctrl | **Panel Discussion** |
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
    <td>3:50</td>
    <td colspan="2"><a href='https://scholar.google.com/citations?user=YW1hekQAAAAJ&hl=en'><b>Ziwen Huang</b></a><br>Research Associate @ Fermilab</td>
    <td>"Using Qiskit Metal to assist quantum device designing on 2D and 3D architectures"</td>
  </tr>
  <tr>
    <td>4:10</td>
    <td><a href="https://scholar.google.ca/citations?user=sRExdr0AAAAJ"><b>Daniel Puzzuoli</b></a><br>IBM Quantum</td>
    <td><a href="https://www.linkedin.com/in/benjamin-rosand"><b>Benjamin Rosand</b></a><br>IBM Quantum</td>
    <td>"Simulating quantum systems with Qiskit Dynamics"</td>
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
