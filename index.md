***🦈 Hey you! Welcome to my Focus Projects Page!🦈***
=======================================================

This is a place for me to flex all my projects I do for my TKS Focus, which, by the way, is about Quantum Computing.
You can also read about the stuff I write on [Medium](https://max-c.medium.com)! 
And while you're here, why not apply to [TKS](https://tks.life)?
Anyways, enjoy the content and feel free to do a little exploring on your own! 

## About Me
Hello everybody, and welcome! I'm Max, a teenager and future unicorn 🦄 person, also known as an innovator at [The Knowledge Society aka TKS](https://tks.world).
I'm interested in a lot of different emerging technologies, but my main interests right now are Quantum Computing ⚛️, Blockchain 💵, Artificial Intelligence 🤖, and last but not least, Space Tech/Exploration 🚀.
So yeah, that's basically who I am. You can check out my social media profiles below.  
<p>
  <a href="https://www.linkedin.com/in/max-cui-9889641b7/" rel="nofollow noreferrer">
    <img src = "https://i.stack.imgur.com/gVE0j.png" alt="linkedin">
    LinkedIn
  </a> &nbsp;
  <a href = "https://github.com/TKSMax" rel="nofollow noreferrer">
    <img src = "https://i.stack.imgur.com/tskMh.png" alt="github">
    GitHub
  </a> &nbsp;
  <a href="https://max-c.medium.com" rel="nofollow noreferrer">
    Medium
  </a> &nbsp;
  <a href = "https://maxmcui.substack.com" rel="nofollow noreferrer">
    Sub to my Newsletter
  </a>
</p>

Introduction to Quantum Computing
---------------------------------

Ever wondered what quantum computing is? 
Or maybe you've never even heard of it before! 
Well, quantum computing is using quantum phenomena, such as *entanglement*, *superposition* and *teleportation* to perform computations.
The devices that perform quantum computations are no doubt called quantum computers. 
It's not too late to start learning!  
Here are some courses you might want to check out!  
*Some courses may cost money*  
- [The Introduction to Quantum Computing](https://coursera.org/learn/quantum-computing-algorithms)
- [Quantum Conputing. Less Formulas More - Understanding](https://coursera.org/learn/quantum-computing-lfmu)
- [Physical Basics of Quantum Computing](https://coursera.org/learn/physical-basis-quantum-computing)
- [EdX courses!](https://edx.org/learn/quantum-computing)

Project #1: Quantum Operations
------------------------------
### About the Project
In this project, I learned about the basic quantum operations that a quantum computer uses to perform quantum computations.
The quantum operations I will be introducing you to are for the IBM Quantum Experience, which is a cloud-based Quantum Computing service.
You can sign up for it [here](https://quantum-computing.ibm.com).  
*This was made in 2020 and is not up to date due to a recent IBM update.*

### What are Quantum Operations?
Quantum Operations are operations used to manipulate quantum bits (or [qubits](https://en.wikipedia.org/wiki/Qubit), for short) in quantum circuits.
They include quantum gates (think of the classical **AND, OR, NOT** gates), as well as some operations that are not quantum gates, but still manipulate qubits.
A quantum gate, by the way, is just a basic circuit (i.e electrical pulses)operating on a small number of qubits.
They are the building blocks of quantum circuits, and can be put together like LEGOs.
There are different types of quantum gates, such as Clifford gates, and diagonal gates.
You can read more about Quantum Operations in [my article](https://www.medium.com/swlh/introduction-to-quantum-operations-e797fae3fab).

### Applying Quantum Operations
#### Creating a Superposition
We'll start off with the most basic thing possible, which is to create a simple superposition of two qubits.
We do this using the Hadamard gate.
It rotates the states |0⟩ and |1⟩ to the states |+⟩ and |-⟩, respectively.
Lets see how it works!  

##### IBM Quantum Experience
We'll head on over to [IBM Quantum Experience](https://quantum-computing.ibm.com), and open up the Quantum Composer.
First, we'll remove the extraneous qubits \(if there are any\), ad we'll be left with two qubits, q0 and q1.
We start by dragging-and-dropping the
<html>
  <p style="color: orange;">orange</p>
</html>
Hadamard gate icon and putting it onto the q0 line.
