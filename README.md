I will be letting you go through how that notebook could be run successfully

There are mainly two three requirements which needed to be followed if you want to run this notebook inside the kaggle.

1. You need to install Efficient Net Model
2. After that there are some cells which have some configurations to made prior to running the main model code. We need to run those cells and only after them we can run the further code.
3. After that the cell of making the CLASSES also need to be run to make the specific classes.
4. After that we can run the further cells which are making the each model and seeing its results.

Now aif you want to run this notebook in your local computer then do the following.

```
1. Create a folder
```

2. After that create the anaconda environment using the below command inside this main folder
```
conda create -p <name_of_environment> python==3.7 -y
```

3.After this just create a requirements.txt file using below code 

```
touch requirements.txt
```

4. Now copy paste the libraries which I have written inside this file and then run the below code to install all these libraries

```
pip install -r requirements.txt
```

5. NNow follow the starting instructions just simply to run that notebook file 