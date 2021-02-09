# Getting Setup to Learn Python and SAS/Python
For *MSDS5023 Information Structures* and *SAS/Python Bootcamp*

## Introduction



## Python Setup
There are several ways to install Python on your PC.  If you have a Python environment installed that you are happy with, you can use that in this course.  However we will be teaching the Python portions of this coures with JupyterLab installed with Anaconda. This is the easiest way to get a very robust Python environment up and running quickly on your PC.

1. [Download Anaconda](https://www.anaconda.com/products/individual#Downloads) for your prefered OS.
1. Run the installer and complete the installation of Anaconda. At the time of this writing, Anaconda installs Python 3.8.
1. Launch Anaconda and click the JupyterLab tile to launch JupyterLab in your browser.
     


## SAS Setup

1. You should have already received instructions to register for a **SAS OnDemand for Analytics (ODA)** cloud account. As a reminder, the instructions can be found [at this link]( https://support.sas.com/ondemand/steps.html). Verify that you can log into **ODA** and launch **SAS® Studio**.

1. Install the SAS Python library, [SASPy](https://pypi.org/project/saspy/).

    From the JupyterLab "Launcher" tab, select the "Terminal" tile to launch a shell.  Execute the following commands from the command line. (If you don't see a "Launcher" tab then select File->New Launcher.)
    
    ```conda install saspy```
    
        or if you did not install Anaconda you can execute
    
    ```pip install saspy```
        
1. Configure your Python environment to access ODA.

   Once you have authenticated to **ODA**, follow the instructions under [SASPy access to SAS® hosted servers](https://support.sas.com/ondemand/saspy.html) to configure your Python environment to access the ODA SAS server.
   
1. Test access to **ODA** from JupyterLab or your Python environment.
    1. Go to the  [this Jupyter Notebook](https://drive.google.com/drive/folders/1kZPvVYnJtC4RoNSK-M6plUyPViFLxGiN?usp=sharing)