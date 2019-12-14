# Helena Civic Data Jupyter notebook tutorial

## Getting started

1. Download the Anaconda Python 3.7 distribution for your operating system from https://www.anaconda.com/distribution/
2. Download this tutorial repository (folder) and move it to a convenient place on your computer (e.g. a `Coding/` folder)
    - With git (if you know what that is): `git clone https://github.com/eidietrich/hln-data-jupyter-tutorial`
    - Or: click the green `Clone or download` button at the upper right on this page, then `Download ZIP`, then unzip
3. *If you're not familiar with using the command line on your operating system* **(Is this necessary w/ Anaconda?)**:
    - Look at TK link for basic tutorial
    - OR: Basic commands (mac/linux bash shell)
        - `cd`: Change Directory, e.g. `cd Documents` or `cd Documents/code-tutorial`
        - `cd ~`: Change back to default location
        - `pwd`: Print Working Directory
        - `ls`: LiSt what's in your working directory
        - `mkdir`: MaKe DIRectory, e.g. `mkdir Coding`
        - `rm <file name>`: ReMove file
        - `rm -r <directory name>`, ReMove directory (be careful with this!)
4. Open your command line app and navigate to the place you put this folder
5. Start JupyterLab in your browser with `jupyter lab`
    - Note some web references will suggest you use `jupyter notebook`, but that gives you an older environment where some of the data viz elements in the demo notebooks won't work properly
6. Open the notebook that looks most interesting from the list below and start fiddling

## What's here 

- `python-intro.ipynb` - Start here if you're brand new to coding
- `jupyter-intro.ipynb` - Start here if you're new to Jupyter Notebooks
- `pandas-intro.ipynb` - **TK** Introduction to the Pandas data analysis library, which equips Python with data wrangling tools
- `demo-pandas-data-cleaning` - **TK** Demo notebook showing some methods for cleaning data with Pandas
- `demo-pandas-data-exploration` - **TK** Demo notebook showing some methods for exploring data with Pandas
- `demo-data-scraping` - **TK** Demo showing how to use TK Scraping library to fetch data from TK Source
- `demo-altair-data-visualiztion` - **TK** Demo showing how to use the Altair library to visualize data
- `data/` - Folder with tutorial data files
- `README.md` - The text you're reading right now
- `.gitignore` - A Git/GitHub housekeeping file; feel free to ignore