# Majorana1

Majorana1 was released by microsoft on 19th February 2025. Everyone has been talking about it but what makes it so special ? How can it change out lives ? Will it be really applicable to us or is it for different domains ? To undestand this, we must know what is Quantum Computing and qubits, so let us explore Quantum Computing first.

## What is Quantum Computing ?

Quantum Computing aims to solve problems which cannot be solved by today's computers or even supercomputers in countable days. By taking advantage of quantum physics, fully realized quantum computers would be able to process massively complicated problems at orders of magnitude faster than modern machines. For a quantum computer, challenges that might take a classical computer thousands of years to complete might be reduced to a matter of minutes.<br/>
The study of subatomic particles, also known as quantum mechanics, reveals unique and fundamental natural principles. Quantum computers harness these fundamental phenomena to compute probabilistically and quantum mechanically. <br/>

## Principles of Quantum Mechanics

1. **Superposition:** Superposition is the state in which a quantum particle or system can represent not just one possibility, but a combination of multiple possibilities.<br/>
2. **Entanglement:** Entanglement is the process in which multiple quantum particles become correlated more strongly than regular probability allows.<br/>
3. **Decoherence:** Decoherence is the process in which quantum particles and systems can decay, collapse or change, converting into single states measurable by classical physics.<br/>
4. **Interference:** Interference is the phenomenon in which entangled quantum states can interact and produce more and less likely probabilities.<br/>

## Qubits

Our classical computers rely on bits. These bits are basically switch in hardware form which can store information in form of 1 or 0. But quantum computer uses qubits, which can store potentially much more data than bits. A qubit, can be either 0 or 1 at the same time, but can be niether of them. To understand this let us go with some basic mathematics:<br/>

Qubits are generally represented in the form of vectors:

<img width="72" alt="Screenshot 2025-03-24 at 8 39 42 PM" src="https://github.com/user-attachments/assets/b0209e82-9144-454a-9c89-1156c1cf61e6" /> &ensp;....(1) <br/>
where **α, β**
are amplitudes of states 0 and 1 respectively or we can say the probability to be in state 0 and 1 respectively.<br/>
This is pronounced as ket. <br/>

But what does this vector actually means ?
<br/>
It means that, α is actually probability of measuring ket 0 state and β is actually the probability of measuring the ket 1 state. So it can be safely said that,<br/>
In coloumn vectors, |1> = [0, 1] actually means that α probability = 0 and β probability = 1. <br/>
Same way, |0⟩ = [1, 0] actually means that α probability = 1 and β probability = 0. <br/>

Just for an example consider: <br/><br/>
α probability = √3/2    and β probability = 1/2 <br/>
|ψ> = [√3/2, 1/2] <br/>
Probability of measuring |ψ> as 0 = 75%  <br/>
Probability of measuring |ψ> as 1 = 25%  <br/>

Now taking normal form of equation (1) we get <br/>
|ψ> = α|0> + β|1>   &ensp; ......(2) <br/>
This form is also known as dirac form.<br/>

This concludes enough about quantum eqautions and mathematics. Now let us come to how to synthesize the qubit state.<br/>

## Qubit State
I presume many of the readers may not have a full knowledge and grasp of qubits so I will break it down in very simple language for everyone to understand. <br/>
Till now we know, out computers work on binary system which allows it to store the information in the form of 1 or 0 only. As discussed above, the qubits give way for a third state where it is existing in both 1 and 0. This third state is called as _superposition_. Now, applying the rules according to quantum mechanics, the qubit probability is a wave function. This allows us to encode more than 1 bit of data and in turn help us to carry extremely difficult calculations. <br/>
Now the problem is, maintaing this qubit state has been extremely difficult till now. These are really sensetive to minute temperature fluctuations, electron movements, or even atomic level vibtrations. Such environmental disturbances lead to collapse and decay of qubits, which we call as _decoherence_. Now this decoherence can give us errors in calculations, whihc in turn can pour water on our dreams of calculating complex equations.<br/>

## Microsoft Mijorana1 Team
Now Microsoft basically achieved a great feat, they created a whole new state just to give us a quantum chip with 8 qubits. Yea, you heard it right, they created a whole new state of matter !!!<br/>



## References
1. https://www.ibm.com/think/topics/quantum-computing
2. https://www.linkedin.com/pulse/qubit-representation-hafiz-muhammad-attaullah/
3. https://www.geeksforgeeks.org/qubit-representation/
4. https://azure.microsoft.com/en-us/blog/quantum/2025/02/19/microsoft-unveils-majorana-1-the-worlds-first-quantum-processor-powered-by-topological-qubits/
5. https://news.microsoft.com/source/features/innovation/microsofts-majorana-1-chip-carves-new-path-for-quantum-computing/
6. https://www.ibm.com/think/topics/qubit
7. 



