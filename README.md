# Pandas
# Pandas-Data-Analysis

Steps:

1) Download Anaconda and install it
2) Open Anaconda prompt and see if you see (base) before the location address in the prompt, it means everything is installed properly
3) Check the available environments by running the following command:
    conda info --envs
4) Update your conda by running:
    conda update conda
5) Create a conda environment:
    conda create --name NameOfYourEnvironment
    This command creates an environment in the default location
    
    If you want to create an environment in some other location use the below command:
    conda create --prefix=/users/.../yourEnvName python=x.x

    Command I used: conda create --prefix=/Users/saily/Anaconda3/pandas_data_analysis python=3.8.3
6) Activate Env:
    conda activate C:\Users\saily\Anaconda3\pandas_data_analysis
7) conda install pandas jupyter bottleneck numexpr matplotlib
8) To activate deactivate: conda deactivate




Totally Unrelated to setup:
turning on intellisense or tab autocomplete in Jupyter Notebook:

%config Completer.use_jedi = False
