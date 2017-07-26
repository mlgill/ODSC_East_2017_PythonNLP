# Learning from Text: Introduction to Natural Language Processing with Python
ODSC East  
May 3, 2017  

Michelle L. Gill, Ph.D.    
Senior Data Scientist  
Metis  

---

## Software Installation Instructions
Tested on Mac OS X 10.12 and Ubuntu 14.04

1. Download the Anaconda distribution for **Python 3.6** (Python 2.7 will not work) from this [link](https://www.continuum.io/downloads) and configure your environment as described at the end of the installation process. This will install the following necessary libraries: Jupyter notebook, Numpy, Scipy, Pandas, Scikit-Learn, Matplotlib, and Seaborn.

2. With the above Anaconda environment activated, install the following additional libraries using the commands listed:
    ```console
    conda install -y -c anaconda gensim nltk
    conda install -y -c conda-forge textblob
    pip install pyldavis
    ```  
    Packages can also installed with `pip` the conda installation does not work.

3. Download the corpora associated with nltk using the following command from a terminal: 
    ```console
    python -m nltk.downloader -d $HOME/nltk_data all
    ```  
    This will create a folder "nltk_data" in your home directory that is large (~ 4 GB) when expanded.

4. Download Google's pre-trained word2vec files from this [link](https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit). Note that this file is also somewhat large (~ 1.5 GB). This file can be downloaded to a preferred location and left there.

5. Clone this GitHub repo. Note that the materials associated with this workshop are being updated, so this step should be performed (or updated) the evening before the workshop.
