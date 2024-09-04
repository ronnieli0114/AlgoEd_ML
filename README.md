# AlgoEd_ML
Machine learning course for AlgoEd

## Getting Started
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
conda install python numpy pandas scikit-learn spyder --yes
```
