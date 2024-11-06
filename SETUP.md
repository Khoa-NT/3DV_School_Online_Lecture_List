## 1. Install Code editor
Install one of the following:
- [VSCode](https://code.visualstudio.com/docs/setup/setup-overview) (I prefer this one)
- [PyCharm Community Edition](https://www.jetbrains.com/pycharm/download)


## 2. Install Virtual environment
<!-- TODO: Change to use `uv` instead of `conda` -->
Follow this [instruction](https://docs.anaconda.com/miniconda/#quick-command-line-install) to install Miniconda (this is a lightweight version of Anaconda).


- For MacOS and Linux, to activate the environment automatically, run the following lines in your terminal: 
    <details>
    <summary>Click here to expand</summary>


    ```
    echo "source ~/miniconda3/bin/activate" >> ~/.bashrc
    ```

    Then refresh your terminal with this command:
    ```
    source ~/.bashrc
    ```

    </details>


## 3. Create Python environment
- Run the following command in your terminal to create a new environment named `3DV`:
```
conda create -n 3DV python=3.11
```

- Activate the environment:
```
conda activate 3DV
```

- Install those packages:
```
pip install numpy scikit-image matplotlib imageio plotly opencv-python jupyter
```

## 4. Open Jupyter Notebook

Follow this [video](https://www.youtube.com/watch?v=suAkMeWJ1yE) to setup Jupyter on VSCode.

**Note**: 
- Select the `3DV` environment at [1:56](https://youtu.be/suAkMeWJ1yE?t=116).


More information about VSCode + Jupyter Notebook can be found [here](https://code.visualstudio.com/docs/datascience/jupyter-notebooks).


## 5. Congratulations!
You have finished the setup.

With Jupyter Notebook, you can run Python code and see the results immediately. It is a good way to learn Python, practice coding, and take notes (in [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)).
