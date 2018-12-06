# Setup
- Install (Anaconda)[https://www.anaconda.com/download/] python 3.7 with Visual Studio Code
- Install Git

# Create Env
Open the Anaconda Prompt (Windows) and execute:
```
$conda create –name modelling python=3.7
$conda activate modelling
```
You should have and active enviroment prompt like this:
```
(modelling) $
```
Then install the required dependencies with

```
(modelling) $conda install numpy pandas scikit-learn scipy seaborn matplotlib jupyterlab
```

and clone this repository to your computer.
`cd` to this repository and execute
```
$jupyter lab
```

