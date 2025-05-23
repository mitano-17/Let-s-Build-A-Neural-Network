# Let-s-Build-A-Neural-Network
A walkthrough on the basics of neural networks and how to code them from scratch using Python and Jupyter Notebooks.

## Outline
● Quick Jupyter Notebook/Python review;</br>
&emsp;⚬ Print;</br>
&emsp;⚬ For loops; and</br>
&emsp;⚬ Arrays.</br>
● Creating functions and initialising the network;</br>
● Initialise weights;</br>
● Query the network; </br>
&emsp;⚬ Matrix computation; and</br>
&emsp;⚬Activation function.</br>
● Build the training function;</br>
&emsp;⚬ Compute signals between layers;</br>
&emsp;⚬ Error computation; and</br>
&emsp;⚬ Update weights.</br>
● Preparing the MNIST dataset; </br>
&emsp;⚬ Training data; and</br>
&emsp;⚬ Testing data.</br>
● Testing the network; and</br>
● Tweaking the network. </br>
&emsp;⚬ Adjusting the learning rate;</br>
&emsp;⚬ Multiple runs;</br>
&emsp;⚬ Changing network shapes; and</br>
&emsp;⚬ Simple data augmentation using rotations.</br>

## Instructions
### Creating a Python Environment
1.) Download and install <a href="https://www.anaconda.com/download/">Anaconda Navigator</a>.</br>
2.) Open the Anaconda Prompt and create an environment. Replace `envname` with your preferred environment name.</br>
```
conda create -n envname python anaconda -y
```
> [!TIP]
> A good rule of thumb is to create a Python virtual environment so we can start fresh. This prevents conflict with other applications that need certain dependencies and versions.

3.) Activate the virtual environment:
```
conda activate envname
```
4.) Install IPython:
```
pip install ipython
```
> [!NOTE]
> We use **IPython** as it allows our notebooks to be interactive. Additionally, it contains extensions needed for data and numerical plotting.


<h2>💌 Credits ✉️</h2>
This project is done by <b>ERMITANO, Kate Justine</b> as a supplementary material for the workshop entitled <i>Building Your Neural Network</i> under the instructions of <b>Sir Arren Matthew Antioquia</b>. The work is based on <b>Tariq Rashid's</b> book named <i>Make Your Own Neural Network (2018)</i>. 
