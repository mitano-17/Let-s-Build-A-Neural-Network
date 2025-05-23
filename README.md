# Let-s-Build-A-Neural-Network
A walkthrough on the basics of neural networks and how to code them from scratch using Python and Jupyter Notebooks.

## Outline
● Quick Jupyter Notebook/Python review;</br>
&emsp;&emsp;⚬ Print;</br>
&emsp;&emsp;⚬ For loops; and</br>
&emsp;&emsp;⚬ Arrays.</br>
● Creating functions and initialising the network;</br>
● Initialise weights;</br>
● Query the network; </br>
&emsp;&emsp;⚬ Matrix computation; and</br>
&emsp;&emsp;⚬Activation function.</br>
● Build the training function;</br>
&emsp;&emsp;⚬ Compute signals between layers;</br>
&emsp;&emsp;⚬ Error computation; and</br>
&emsp;&emsp;⚬ Update weights.</br>
● Preparing the MNIST dataset; </br>
&emsp;&emsp;⚬ Training data; and</br>
&emsp;&emsp;⚬ Testing data.</br>
● Testing the network; and</br>
● Tweaking the network. </br>
&emsp;&emsp;⚬ Adjusting the learning rate;</br>
&emsp;&emsp;⚬ Multiple runs;</br>
&emsp;&emsp;⚬ Changing network shapes; and</br>
&emsp;&emsp;⚬ Simple data augmentation using rotations.</br>

## Instructions
> [!WARNING]
> The following applies only to Windows OS. For Mac OS and Linux users, please refer to online resources.

### Creating a Python Environment
1.) Download and install <a href="https://www.anaconda.com/download/">Anaconda Navigator</a>. </br>
> [!NOTE]
> The **Anaconda Navigator** provides a hassle-free installation of the components needed to run Jupyter Notebook.

2.) Open the **Anaconda Prompt** and create an environment. Replace `envname` with your preferred environment name:</br>
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

### Navigating Jupyter Notebook
5.) Open Jupyter Notebook. The application will be launched via a web browser with a new tab named **Home**.
```
jupyter notebook
```
![image](https://github.com/user-attachments/assets/5b631bfb-1727-4ba0-be5c-183af114c1a5)
6.) Navigate to the folder where the MNIST dataset is located. Create a notebook by clicking the **New** button, then select **Python 3 (ipykernel)**. The new notebook should look similar to the image presented below. 
![image](https://github.com/user-attachments/assets/e47f13e9-2612-4b70-a106-c40536d94b30) 

![image](https://github.com/user-attachments/assets/5f1348f7-4251-44a8-ac7b-c52ad10e4f93)

<h2>💌 Credits ✉️</h2>
This project is done by <b>ERMITANO, Kate Justine</b> as a supplementary material for the workshop entitled <i>Building Your Neural Network</i> under the instructions of <b>Sir Arren Matthew Antioquia</b>. The work is based on <b>Tariq Rashid's</b> book named <i>Make Your Own Neural Network (2018)</i>. 
