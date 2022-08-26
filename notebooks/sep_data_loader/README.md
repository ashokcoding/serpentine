# Installation 
1. Make sure you have a recent version of [Anaconda](https://www.anaconda.com/products/distribution) installed.
2. [Download this file](https://github.com/serpentine-h2020/serpentine/archive/refs/heads/main.zip) and extract to a folder of your choice.
3. Open your terminal/command line/Anaconda prompt, navigate to the downloaded (extracted) folder `notebooks/sep_data_loader` that contains the file `requirements.txt`, and run the following:

``` bash
$ conda create --name serpentine python=3.9
$ conda activate serpentine
$ pip install -r requirements.txt
```


# Run 
1. Open your terminal/command line/Anaconda prompt.
2. In the terminal, navigate to the downloaded (extracted) folder `notebooks/data_loader` that contains the file `data_loader.ipynb`
3. Run `jupyter notebook data_loader.ipynb`
4. Your standard web-browser should now open the Jupyter Notebook.