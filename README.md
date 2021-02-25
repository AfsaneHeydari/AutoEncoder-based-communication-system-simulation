# AutoEncoder-based-communication-system-simulation
These codes aim to model a communication system  by AutoEncoders and simulate its authentication based on Hanzo papers.
The main paper is 
'Learning-Aided Physical Layer Authentication as an Intelligent Process' 
by He Fang, Xianbin Wang, Lajos Hanzo.

In this simulation the whole communication system is modeled by an AutoEncoder :
The transmiter is modeled by encoding layers,
The Receiver is modeled by decoding layers,
The channel is modeled by GaussianNoise layer.

Data is generated randomly, and spoofing data is simulated by adding guassian noise, to the data which is recieved from transmiter 
(the output of encoding layers).

At the end intelligent Auth Algorithm is implemented by computing RSS(Recieved Signal Strength).

The other code is just the simulation of communication system by AutoEncoders.
The third code is a simulation based on paper 
'A Learning Approach for Physical Layer Authentication Using Adaptive Neural Network paper '
by XIAOYING, JIANMEI DAI, AND MONSON HAYES 


