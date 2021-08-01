# Project Title:  Deep-Learning---Thermal and Flow Boundary Layers
This repositrory contains all the required files to solve nonlinear coupled partial differential equations attributed to the flow and thermal boundary layer problems occuring in fluid mechanic science. We have explored the capability of Physics-Informed-Neural Network (PINN) developed by Professor Maziar Raissi and his colleagues in Brown university. The original code along with the relevant papers can be found through (https://github.com/maziarraissi/PINNs.).  

Three Benchmark problems named **1-Blasius flow** , **2- Flakner-Skan wedge flow** and **3- Natural convection on a vertical flat plate** were considered and solved by PINN. The controlling parameters, such as **a) _Learning rate_**, **b) _Width and Deoth of the network_** , **c) _Prandtl number_** , **d) _the unlimited boundary value_** and **e) _Overfitting test_** were investigated in detail aimed to obtain the reasonable outcomes.

We used **Python 3.6** and **TensorFlow 1.14** for coding and employing the tensorflow package. Also **ADAM optimization** was used to optimize the Loss function in terms of weights and biases. 
