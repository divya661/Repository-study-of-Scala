# Repository-study-of-Scala

# Introduction
Scala programming language is an Open-Source project which have more than 30,000 commits till now. In this github repository commits are studied to know who are the most active contributors in this repository. The dataset has been gathered from github.

1. Imported the neccesary libraries & datasets
2. Prepared & Cleaned the data by working with the dates of the commits converting them to UTC. As well as converting the datatype of date in the dataset from strings to DateTime so that they can be easily compared.
3. Datasets were merged as they are available in 2 different files
4. Checked is the project is active among contributers & well-maintained. Pull requests submitted each month/year during the project lifetime's are calculated & a bar graph is ploted.
5. To answer does the project had contributions made by small group of people or a large community a histogram is ploted which shows the no of pull requests submitted by each user.
6. To know which are the active parts of the project to make a contribution, files that are changed in the last ten pull requests are collected.
7. To know who are the experts in the projects having most understanding of it, we will find who are the top 3 contributor of one the recently changed files.
8. We also find out who had made the last 10 pull requests on 1 of the file actively changed.
9. After finding out people who made the most contribution from task 7 & 8, now we will find out who is most active among them in recent times. A bar graph is plotted to make comparison easily.
10. In this task, comparison is made among the 2 contributors on basis of who made the most pull requests & how recent are those

## Steps to run the application

1. Make a virtual environment

```
python3 -m venv env
```

2. Activate the virtual environment

```
source env/bin/activate # This command is for linux 
```

3. clone the repository :
```
   git clone https://github.com/divya661/Repository-study-of-Scala.git
```   
   Or

   Download the zip folder & unzip the folder downloaded

4. Install all the necessary packages

```
pip install -r requirements.txt
```

5. Open the jupyter notebook and run the file 'notebook-checkpoint.ipynb'
