# PSE2
Hello Students, this read me file will guide you in setting up mini conda  and Pyomo in your PC.There are mainly 3 steps in this process:
  * Setting up the environment using miniconda
  * Installing the necessary packages
  * Running the IDE
------------------------------------------------------------------------------------------------------------------------------

## **Setting up the environment using miniconda** 

It is convenient to setup an environment using miniconda , to avoid dependency conflicts.
  * For this we first download miniconda from the website: https://www.anaconda.com/download/  .You can either create an 
    account and download or skip registration and download. Please select the recommended settings while installation.
  * After installing miniconda, press windows and search for 'anaconda prompt'. Click on it and the prompt window opens up.

for detailed tutorial check out the following youtube video: https://www.youtube.com/watch?v=oHHbsMfyNR4 .

------------------------------------------------------------------------------------------------------------------------------
## **Installing the necessary packages**

The second step is installing the packages. All the necessary packages required for the tutorial has already been included in the 'pse.yml' file in the repository.If you want to take a look at the packages open the .yml file in notepad. I have included Spyder IDE , but if you have individual preference you can install that IDE. To start with this step:

  * Download the pse.yml file from this repository
  * Move the pse.yml file from the download location to the base environment location (as shown in anaconda prompt) , in my 
    case it was:
> (base) C:\Users\Padua 
  * Alternately you can also change base directory to the location where the .yml file is present by typing the code below. 
    Enter your path between the "".
    
```
cd ".yml location"
```
  * The next step is to create the environment. Type the following code in the anaconda prompt

 ```
 conda env create -f pse.yml
``` 
* The environment will be created and you can activate it by typing
```
conda activate pse
```
* The environment will be activated and the name of the environment can be seen in the beginning of the command line.

 Any missing packages can be installed dynamically.

 ---------------------------------------------------------------------------------------------------------------------------

 ## Running the IDE

 Now that the environment is activated we can run the IDE by typing the IDE name as shown. Since i prefer spyder i typed the following and pressed enter

```
spyder
```

The spyder IDE will open up and we can enter the code there.

----------------------------------------------------------------------------------------------------------------------------
