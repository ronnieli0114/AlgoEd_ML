# Introduction to Machine Learning in Genomics (AlgoEd)

## Getting Started
Welcome to the course! In this tutorial, I'll show you how to install Anaconda and the required packages we'll be using for this course.

### Download Anaconda
First, we'll need to install Anaconda, an all-in-one data science tool. The installer takes up about 1 GB of space on your computer. You can download Anaconda [here](https://www.anaconda.com/download). You can click the small "Skip registration" link right below the large green "Submit" button if you don't want to provide them your email address.

Once it finishes downloading, run the installer. You can choose all the default options unless you are a more advanced user.

### Set up Anaconda
Once you have Anaconda downloaded, launch the Anaconda Prompt, Anaconda's command-line interface. From there, execute the following commands **one at a time**:
1. Create a new environment. This will allow you to isolate certain packages from the base environment, minimizing any package conflicts
2. Activate the new `algoed` environment
3. Add `conda-forge` to the list of channels so you can install packages
4. Install all the necessary packages we'll use for this course

```
conda create -n algoed --yes
conda activate algoed
conda config --env --add channels conda-forge
conda install python numpy pandas matplotlib scikit-learn jupyter --yes
```

## Run Jupyter Notebook
We will be using Jupyter Notebook for the course. It is an interactive notebook-like format that allows us to run code and add text/images. Once you have everything installed, open up another instance of Anaconda Prompt, and run the following commands one by one:
1. Activate our `algoed` environment
2. Run Jupyter Notebook
```
conda activate algoed
jupyter notebook
```
You should see some command-line text, and then a browser window should open up with the Jupyter logo and listing your current directory. **Do not close Anaconda Prompt!!!** This will cause Jupyter Notebook to stop running.
