# Learning pandas

Using DataCamp free course: [pandas Foundations](https://www.datacamp.com/courses/pandas-foundations)

1. Create virtual environment with your preferred solution. This project will use Miniconda.
You can find it from here [Miniconda](https://conda.io/en/latest/miniconda.html)

    ```
    conda create -n learning-pandas python=3.6
    ```

2. Activate the virtual environment
    ```
    conda activate learning-pandas
    ```
    
3. Install pandas
    ```
    pip install pandas 
    ```

4. In this case pandas will be used in Jupyter notebook. To install it 
follow the guide [Install instructions](https://jupyter.org/install.html) or use these commands 
    
    ```
    pip install --upgrade pip
    pip install jupyter
    ```
5. Activate Jupyter notebook
    ```
    jupyter notebook
    ```
    
6. From browser you will see the jupyter started a server with interface. Go ahead and create a new notebook

7. Import pandas to the notebook. The letter combination **pd** is used as an alias
    ```
    import pandas as pd
    ```
8. 