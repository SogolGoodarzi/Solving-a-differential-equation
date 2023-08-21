# Solving-a-differential-equation

Consider the following equation:

![image](https://github.com/SogolGoodarzi/Solving-a-differential-equation/assets/125180530/ee03cedb-90a2-41bb-9ec7-55f7336cb492)

Find the answer of this equation to the following input with "residuez", "conv", and "filtic" functions.

![image](https://github.com/SogolGoodarzi/Solving-a-differential-equation/assets/125180530/2a77b548-ce75-483e-85cd-b923b678467a)

<p align="justify"> To solve this equation, we must take the one-way Z transformation from both sides of the equation and solve this equation with appropriate functions. First, we obtain the Z transformation of the input signal as follows. </p>

![image](https://github.com/SogolGoodarzi/Solving-a-differential-equation/assets/125180530/8faeef56-e8d6-4eed-ae5f-fad632941712)

<p align="justify"> To use the above functions, we must first form $H(z)$, and then to get the full answer of the equation, we need to include the initial conditions. So, the general form of $Y(z)$ is obtained as follows by transforming Z and simplifying We get the right one. </p>

![image](https://github.com/SogolGoodarzi/Solving-a-differential-equation/assets/125180530/c74049af-ba46-4d97-9cbc-e1c2fc84d18a)

![image](https://github.com/SogolGoodarzi/Solving-a-differential-equation/assets/125180530/9fce4345-ff52-46c3-abff-1b1fc1bee779)

<p align="justify"> After forming the expression $Y(z)$ as above, by obtaining r, p, k and residuez, we have formed the descriptive expression $Y[n]$ as follows in the commands: </p>

![image](https://github.com/SogolGoodarzi/Solving-a-differential-equation/assets/125180530/9355a253-b573-48fb-92b8-381a3bde2484)

The graph of the response obtained in this method is drawn as follows:

![image](https://github.com/SogolGoodarzi/Solving-a-differential-equation/assets/125180530/fca98341-4d34-49a9-a10a-cae73ec06c0e)

<p align="justify"> Another method of reaching the answer is to use "filtic" and "filter" functions. In this method, similar to the previous method, we must first obtain the term resulting from the initial conditions with the filtic command by giving the arguments b and a, which are the coefficients of the numerator and denominator of the transformation function $H(z)$, which are the same as b and a, plus the input signal to the filter function. The output of this function gives us the complete answer of the equation whose graph is drawn in the figure below, and it can be seen that its graph is similar to the graph of the previous method. </p>

![image](https://github.com/SogolGoodarzi/Solving-a-differential-equation/assets/125180530/6307f221-a5ee-4095-9a6f-f53dfce27e2c)

<p align="justify"> As it is clear from the diagram of the solution of the first and second method, we can see that the form of the general answers obtained from both methods has become the same. </p>
  
<p align="justify"> Now, to get the general and particular answers of the equation, we proceed similarly to solving the first method, with the difference that we find the answers separately. According to the equation we obtained for Y(z), the terms corresponding to the input and initial conditions are specified as shown. </p>

![image](https://github.com/SogolGoodarzi/Solving-a-differential-equation/assets/125180530/0a8519fc-1f6c-41f1-ab24-db4a4edef6c9)

* Plot of particular answer:

![image](https://github.com/SogolGoodarzi/Solving-a-differential-equation/assets/125180530/1242a48c-bda4-48ed-81d7-3e51877dbe1d)

* Plot of general answer:

![image](https://github.com/SogolGoodarzi/Solving-a-differential-equation/assets/125180530/e6084caf-c404-4275-b7bf-68de90ceed3f)

In the following figures you can see the results all together:

![image](https://github.com/SogolGoodarzi/Solving-a-differential-equation/assets/125180530/d34e091b-791f-427d-820e-d9e0ff5d2e77)

As it is obvious, from the sum of the particular and general answer of the equation, the complete answer can be reached. 

<p align="justify"> Now we have to find a transient and steady state answer. From the information of the first solution method, we have the r and p values ​​as follows. Using them, we form the complete answer. The constant term of this response is the steady state response and its exponential terms are the transient response. </p>

![image](https://github.com/SogolGoodarzi/Solving-a-differential-equation/assets/125180530/4274c0cf-084e-4035-b9eb-cb4c0a7485e5)

![image](https://github.com/SogolGoodarzi/Solving-a-differential-equation/assets/125180530/c86f22a7-f7e4-4ff2-a657-9586d811b768)

The results attained from this part is as follows:

![image](https://github.com/SogolGoodarzi/Solving-a-differential-equation/assets/125180530/78764c9a-4720-40f3-a991-c9356dd5f35c)
