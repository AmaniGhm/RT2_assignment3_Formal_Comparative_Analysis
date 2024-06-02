# RT2_assignment3_Formal_Comparative_Analysis
------------------------------------------------
This comprehensive analysis examines the performance of two different robotic systems, each created by a different student: Amani (myself) and Lydia. The aim of this study is to simulate and control a mobile robot in an environment containing several golden boxes, with the task of gathering all the boxes together in one place. This report compares the performance of my code with that of Lydia's code, which is designed to accomplish the same task. The performance of two implementations assessed by running experiments that varied the number of tokens in the environment. Their execution time for each task and tracked their success/failure rates is measured.

The evaluation of performance is based on the hypotheses outlined in the subsequent section. The primary metric for determining the superior algorithm is the time required for the robot to gather all the golden boxes in a centralized location. Furthermore, the analysis considers the number of successes and failures of each algorithm in detecting and collecting the golden boxes, particularly as the number of boxes in the environment varies. 

For further explanation you can check the Jupyter Notebook attached to this repo under the name "Formal_Comparative_Analysis.ipynb"

## How to RUN the code
-----------------------------

After cloning the repositoriy on your machine, you need to navigate to the folder "robot-sim". then you are able to run the code.
To run the script in the simulator, use `run.py`, passing it the file names. 

you can run the programs with:

```bash
$ python run.py Amani_assignment1.py 
$ python run.py Lydia_assignment1.py 
```

If you want to check the codes you can use `gedit` to see the code structure.

Use the following line :

```bash
$ gedit Amani_assignment1.py
$ gedit Lydia_assignment1.py
`
