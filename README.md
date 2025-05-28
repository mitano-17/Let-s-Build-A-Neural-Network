# Let-s-Build-A-Neural-Network
A walkthrough on the basics of neural networks and how to code them from scratch using Python and Jupyter Notebooks.

## Outline
● 🐍 Quick Python review; </br>
&emsp;&emsp;⚬ Print;</br>
&emsp;&emsp;⚬ Arrays; </br>
&emsp;&emsp;⚬ For loops; and</br>
&emsp;&emsp;⚬ Functions.</br>
● 🛠 Creating functions and initialising the network;</br>
&emsp;&emsp;⚬ Initialising the network; and</br>
&emsp;&emsp;⚬ Initialise weights.</br>
&emsp;&emsp;&emsp;&emsp;- Import numpy library; and</br>
&emsp;&emsp;&emsp;&emsp;- Adding weights to class.</br>
● 🗃 Query the network; </br>
&emsp;&emsp;⚬ Activation function;</br>
&emsp;&emsp;⚬ Matrix computation using dot product;</br>
&emsp;&emsp;⚬ Compute signals between layers; and</br>
&emsp;&emsp;⚬ Testing the network.</br>
● 🛴 Build the training function;</br>
&emsp;&emsp;⚬ Compute signals between layers;</br>
&emsp;&emsp;⚬ Error computation; and</br>
&emsp;&emsp;⚬ Update weights.</br>
● 📚 Preparing the MNIST dataset; </br>
&emsp;&emsp;⚬ Reading training data;</br>
&emsp;&emsp;⚬ Plotting training data;</br>
&emsp;&emsp;⚬ Preparing training data;</br>
&emsp;&emsp;⚬ Setting up the training function; and</br>
&emsp;&emsp;⚬ Reading test data.</br>
● 🔌 Testing the network;</br>
&emsp;&emsp;⚬ Setting up scoring; and</br>
&emsp;&emsp;⚬ Computing performance.</br>
● 🧮 Tweaking the network; and</br>
&emsp;&emsp;⚬ Multiple runs;</br>
&emsp;&emsp;&emsp;&emsp;- Finding the most optimal no. of epochs; and</br>
&emsp;&emsp;&emsp;&emsp;- Plotting the performance.</br>
&emsp;&emsp;⚬ Adjusting the learning rate; and</br>
&emsp;&emsp;&emsp;&emsp;- Finding the most optimal learning rate; and</br>
&emsp;&emsp;&emsp;&emsp;- Plotting the performance.</br>
&emsp;&emsp;⚬ Changing network shape.</br>
&emsp;&emsp;&emsp;&emsp;- Finding the most optimal no. of hidden layers; and</br>
&emsp;&emsp;&emsp;&emsp;- Plotting the performance.</br>
● Visualizations.</br>
&emsp;&emsp;⚬ Confusion matrix; and</br>
&emsp;&emsp;⚬ Predicted vs actual.</br>

## Instructions
### Downloading the MNIST Dataset
1.) Download `mnist_train_100` and `mnist_test_10` from the <a href="https://github.com/mitano-17/Let-s-Build-A-Neural-Network/tree/main/mnist_dataset">dataset folder</a>. </br>
2.) Download the full <a href="https://www.kaggle.com/datasets/oddrationale/mnist-in-csv?resource=download">MNIST in CSV</a> dataset from Kaggle. </br>
3.) Place the files in a subfolder named **mnist_dataset** under the parent folder.
![image](https://github.com/user-attachments/assets/c60dbad7-d655-4721-92f4-ccb7a191b22e)

### Creating a Python Environment
> [!WARNING]
> The following applies only to Windows OS. For Mac OS and Linux users, please refer to online resources.

4.) Download and install <a href="https://www.anaconda.com/download/">Anaconda Navigator</a>. </br>
> [!NOTE]
> The **Anaconda Navigator** provides a hassle-free installation of the components needed to run Jupyter Notebook.

5.) Open the **Anaconda Prompt** and create an environment. Replace `envname` with your preferred environment name:</br>
```
conda create -n envname python anaconda -y
```
> [!TIP]
> A good rule of thumb is to create a Python virtual environment so we can start fresh. This prevents conflict with other applications that need certain dependencies and versions.

6.) Activate the virtual environment:
```
conda activate envname
```
7.) Install IPython:
```
pip install ipython
```
> [!NOTE]
> We use **IPython** as it allows our notebooks to be interactive. Additionally, it contains extensions needed for data and numerical plotting.

### Navigating Jupyter Notebook
8.) Open Jupyter Notebook. The application will be launched via a web browser with a new tab named **Home**.
```
jupyter notebook
```
![image](https://github.com/user-attachments/assets/5b631bfb-1727-4ba0-be5c-183af114c1a5)</br>
</br>
9.) Navigate to the folder where the MNIST dataset is located. Create a notebook by clicking the **New** button, then select **Python 3 (ipykernel)**. The new notebook should look similar to the image presented below. </br></br>
![image](https://github.com/user-attachments/assets/d8b3d105-d5b6-4ecb-ad73-395289ed2f02)</br>
</br>Feel free to rename the notebook. I am renaming mine to **my_neural_network.ipynb** for simplicity.</br>
![image](https://github.com/user-attachments/assets/30215dd2-1334-40e7-a8b7-e9647d062500)

> [!NOTE]
> The expected folder structure should be like the image below for convenience and ease of following further instructions inside the notebook.</br>
> ![image](https://github.com/user-attachments/assets/a9db673b-5334-4659-9394-7c864f947165)

### Closing Notebook and Shutting Down
10.) Shutdown the notebook by going to <b>File</b> then select **Close and Shut Down Notebook**.</br>
![image](https://github.com/user-attachments/assets/ceb0d21f-3bd5-4df7-a4db-ac457093a27c)</br>

12.) Go back to the Anaconda Prompt, then press `Ctrl+C` in the terminal to stop the application.</br>
13.) Deactivate the virtual environment:</br>
```
conda deactivate
```
![image](https://github.com/user-attachments/assets/fd5f2ff7-61d6-4389-a4eb-d379448bf32c)


<h2>💌 Credits ✉️</h2>
This project is done by <b>ERMITANO, Kate Justine</b> as a supplementary material for the workshop entitled <i>Building Your Neural Network</i> under the instructions of <b>Sir Arren Matthew Antioquia</b>. The work is based on <b>Tariq Rashid's</b> book named <i>Make Your Own Neural Network (2018)</i>. 
