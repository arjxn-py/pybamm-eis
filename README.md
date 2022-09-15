# Efficient Linear Algebra Methods to Determine Li-ion Battery Behaviour

Code developed as part of the Oxford Mathematics Summer Project "Efficient Linear Algebra Methods to Determine Li-ion Battery Behaviour". 

Student: Rishit Dhoot

Supervisors: Prof Colin Please and Dr. Robert Timms

## 💻 About PyBaMM
The example simulations use the package [PyBaMM](www.pybamm.org) (Python Battery Mathematical Modelling). PyBaMM solves physics-based electrochemical DAE models by using state-of-the-art automatic differentiation and numerical solvers. The Doyle-Fuller-Newman model can be solved in under 0.1 seconds, while the reduced-order Single Particle Model and Single Particle Model with electrolyte can be solved in just a few milliseconds. Additional physics can easily be included such as thermal effects, fast particle diffusion, 3D effects, and more. All models are implemented in a flexible manner, and a wide range of models and parameter sets (NCA, NMC, LiCoO2, ...) are available. There is also functionality to simulate any set of experimental instructions, such as CCCV or GITT, or specify drive cycles.

## 🚀 Installation
In order to run the notebooks in this repository you will need to instal a number of packages. We recommend installing within a [virtual environment](https://docs.python.org/3/tutorial/venv.html) in order to not alter any python distribution files on your machine.

PyBaMM is available on GNU/Linux, MacOS and Windows. For more detailed instructions on how to install PyBaMM, see [the PyBaMM documentation](https://pybamm.readthedocs.io/en/latest/install/GNU-linux.html#user-install).

### Linux/Mac OS
To install the requirements on Linux/Mac OS use the following terminal commands:

1. Clone the repository
```bash
https://github.com/rish31415/Summer-Project
```
2. Change into the `Summer-Project` directory 
```bash
cd Summer-Project
```
3. Create a virtual environment
```bash
virtualenv env
```
4. Activate the virtual environment 
```bash
source env/bin/activate
```
5. Install the required packages
```bash 
pip install -r requirements.txt
```

### Linux/Mac OS
To install the requirements on Linux/Mac OS use the following terminal commands:

1. Clone the repository
```bash
https://github.com/rish31415/Summer-Project
```
2. Change into the `Summer-Project` directory 
```bash
cd Summer-Project
```
3. Activate the virtual environment 
```bash
\path\to\env\Scripts\activate
```
where `\path\to\env` is the path to the environment created in step 2 (e.g. `C:\Users\'Username'\env\Scripts\activate.bat`).

4. Install the required packages
```bash 
pip install -r requirements.txt
```

As an alternative, you can set up [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/about). This allows you to run a full Linux distribution within Windows.

## 📫 Get in touch
If you have any questions, or would like to know more about the project, please get in touch via email <timms@maths.ox.ac.uk>.
