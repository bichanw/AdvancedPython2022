# Advanced Python 2022

## Set up environment
Google colab works, but it relies on remote machines of which you have less control. To install proper environment to run python code on your own machine:
1. Install [miniconda](https://docs.conda.io/en/latest/miniconda.html#)
2. Create `conda create --name advp`
3. Going into the environment `conda activate advp`
4. Install necessary packages in your environment. 
	```
	conda install numpy git jupyterlab matplotlib seaborn pandas scipy scikit-learn conda-forge::gh
	```