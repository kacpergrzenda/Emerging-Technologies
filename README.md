# Emerging Technologies

## Table of contents
* [About The Project](#about-the-project)
* [Main Project Topics](#main-project-topics)
* [Technologies Used](#technologies-used)
* [Getting Started](#getting-started)
* [Features](#features)
* [Acknowledgements](#acknowledgements)


## About The Project

The Software industry is rapidly changing and moving forward, with new software and technology coming out constantly that can be used to improve research and workflow. The purpose of this repository is to showcase how to utilise new technologies (Docker, Python, Qiskit & Jupyter Notebook) to visualize and analyse data on any machine by using containers, this helps get rid of the problem of software incompatibility. While utilising the new software also learning about Scikit-Learn Algorithms and Quantum Computing / Deutsch Algorithm, which are the two main topics in this repository, more detail about these topics down below.

## Main Project Topics
The two files ```scikit-learn.ipynb``` and ```quantum-deutsch.ipynb``` are two separate Jupyter-Lab notebooks that help easily visualise the learning process of the two topics Scikit-learn and Quantum Computing.

### Scikit-Learn.ipynb
The ```scikit-learn.ipynb``` notebook demonstrates a clear concise overview of the Scikit-learn Python library. The notebook showcases two categories of machine learning algorithms Supervised and Unsupervised learning. It has demonstration of three tasks (Clustering, Regression, Classification) using three scikit-learn algorithms (K-Means Algorithm, Nearest Neighbours Algorithm, SVR Algorithm) while using three different Datasets (Wholesale Customer DS, Forest Fire DS, Wine Quality DS). The notebook also represents plots and other visualisation tools to enhance better understand the algorithms.

### Quantum-Deutsch.ipynb
The ```quantum-deutsch.ipynb``` notebook demonstrates a clear concise comparison of quantum computing and classical computing. This notebook talks about Quantum Qubits, Advantages of Quantum Computing, Quantum Entanglement, and other interesting information about Quantum computers. Also, an explanation of Deutsch Algorithm and code simulating it using Qiskit and diagrams and graphs giving a visual representation of Deutsch’s algorithm.

## Technologies Used

* Python (Algorithms used, scikit-learn)
* Jupyter Lab (Jupyter notebooks)
* Docker (containers, images, docker commands)
* Qiskit (Quantum Computing)


## Getting Started

1. Open a directory on your machine and in the command line of this directory Git Clone this GitHub repository.

    ```bash
    $ git clone https://github.com/kacpergrzenda/emerging-technologies 
    ```
2. Build the Docker container.
    ```bash
    $ docker-compose up
    ```
3. Access the server in a browser using this URL (If this URL does now work please view the URLs Docker has provided in the command line, should look somthing like the one below).
    ``` 
    http://127.0.0.1:8888/lab?token=7a9fae4f51d98b7e380f9eb3b4355c204eef7e8831ff2613 
    ```
4. Once accessed the server open the two main project notebooks (```quantum-deutsch.ipynb``` & ```scikit-learn.ipynb```) from the panel on the left handside.

5. When notebooks are open and no graphs or diagrams are shown, Restart the kernel by clicking the two *fast forward arrows* at the top of the page or clicking the buttons as shown below.
    ```
    ESC + 0 0
    ```

6. Once everything is shown you are free to read through the notebooks and change any values in the algorithms.

7. Once finished viewing/changing the files, Stop the Docker container.
    ```bash
    $ docker-compose down
    ```

## Features

### Docker
Docker is used in this project to provide a service. Docker allows easier visualization of the software & libraries being used by building everything on a server without needing to download all software on personal machine. Follow the [Getting Started](#getting-started) to start up the Docker OS on a cloud server and view the contents of the project. Find out more about Docker [here](https://www.docker.com/).

### Jupyter Lab
Jupyter Lab provides an interactive IDE that helps visualize the two main topics of this project repository Scikit-Learn Algorithms and Quantum Computing / Deutsch Algorithm. Find out more about Jupyter Lab [here](https://jupyter.org/).

### Qiskit
Qiskit is a software kit that is used for working with Quantum computing, it provides tools for creating and manipulating quantum programs. In this project as demonstrated in ```quantum-deutsch.ipynb``` it is used to help showcase Deutsch Algorithm by simulating code using Qiskit and showcase the difference between classical and quantum computing. Find out more about Qiskit [here](https://qiskit.org/).

### Scikit-Learn
Scikit-learn is a software machine learning library for Python. It features many algorithms that build machine learning models as demonstrated in ```scikit-learn.ipynb```. Also, to help reading, summarising, and manipulating the data, other libraires are used like Panadas, Matplotlib & NumPy. Find out more about Scikit-Learn [here](https://scikit-learn.org/stable/).

## Acknowledgements

* Dr.Ian McLoughlin Module Lecturer https://learnonline.gmit.ie/course/view.php?id=3762
* Docker https://www.docker.com/
* Jupyter-Lab https://jupyter.org/
* Scikit-Learn https://scikit-learn.org/stable/
* Qiskit https://qiskit.org/