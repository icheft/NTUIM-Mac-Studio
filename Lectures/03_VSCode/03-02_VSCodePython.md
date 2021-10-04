# VSCode in MGT 2001

I will use my *MGT 2002* (the second half of the class) directory to demonstrate. 

## Environment Settings

I assume that you already have Anaconda installed.

1. First, download the `pipenv` environment managing package
    ```sh
    pip3 install pipenv
    pipenv --python 3.8
    pipenv shell
    ```
2. Now, the environment won't automatically show up in Jupyter Notebook (as a kernel), we have to set it manually
    ```sh
    pip install ipykernel
    python -m ipykernel install --user --name=MGT_2001
    ```
3. `mgt2001` package has everything installed. If you find any packages are missing, please always feel free to submit an issue [here](https://github.com/icheft/mgt2001/issues/new/choose).
    ```sh
    pip install mgt2001
    ```

## mgt2001 docs.

Your. Exam. Assistant.

Here is how you can take this website as your own "tools" (please notice that "making changes of this note and publishing it as your own property is not allowed"):

1. Clone from the repo
    ```sh
    git clone https://github.com/icheft/mgt2001-docs
    ```
2. If you have installed `mgt2001`, this step is relatively simple (meaning that, in your environment, you should have `mgt2001` package installed). Once installed 

    ```sh
    mkdocs serve
    ```

    will do the trick
3. Feel free to modify the `.md` files to best suit your need. 