![Heading image](img/Shane_O'Gorman's_n_Programming_for_Data_Analysis_n_Project_1.png)

## Overview ##
This repository contains my work for Project 1 of the Programming for Data Analysis module. I have outlined below a brief description of the problem, how the program works and the references I used. 


### Problem Statement ###
---
**Description** - Create a data set by simulating a real-world phenomenon. 
- Choose a real-world phenomenon that can be measured and for which you could collect at least one-hundred data points across at least four different variables.
- Investigate the types of variables involved, their likely distributions, and their relationships with each other.
- Synthesise/simulate a data set as closely matching their properties as possible
- Detail your research and implement the simulation in a Jupyter notebook – the data set itself can simply be displayed in an output cell within the notebook.



**How the program works** - 
jyjtyj
1. The program begins by asking the user to input the weight (kg) and then height (cm). 
2. Both inputs are stored as int variables, ***w_kg*** and ***h_cm*** respectively. 
3. The formala for BMI<sup>1</sup> is: **weight (kg) / (height (m))<sup>2</sup>**. This was calculated and stored as ***bmi***. 
4. Given the inputed height was in cm, ***h_cm*** was divided by 100 in the calculation of ***bmi*** to convert to meters.
5. The round function<sup>2</sup> was used to round ***bmi*** to 2 decimal places. 
6. Next, I decided to add a bit more to the program and give the user an indication<sup>3</sup> whether the BMI they got was underweight, normal, overweight, obese or extremly obese.
7. This was acheived using if/else statements<sup>4</sup> and Comparison Operators<sup>5</sup>.
8. Finally, The BMI was printed<sup>6</sup> out along with the result indicator (i.e. underweight, normal, etc.)

**How the program works** - 
1. Firstly, the program gets the x-points to plot - using np.arrange we can get the points between 0-4 incremented by 0.1 for accuracy<sup>1</sup>. This is inputed into a numpy array. 
2. We can then calculate or y-points based off our x-points for each of the three functions f(x), g(x) and h(x). 
3. We can then plot the fuctions using ***plt.plot()*** giving each function a different colour and labeling them.
4. ***plt.legend()*** shows the fuction labels and colour to distinguish between them<sup>4</sup>.
5. I added "Functions" as the title of the plot along with labeling the x and y axis. 
6. plt.xticks and plt.yticks were used to get the correct x and y axis label increments i.e on the x axis I wanted 0, 1, 2, 3, 4 to be shown and on the y axis 0 - 70 with increments of 10.<sup>3</sup>
7. ***plt.grid()*** puts grid lines on the plot. 
8. Finally, 4. ***plt.show()*** shows the plot we created. 

**References** - 
jytjy
1. <a href="https://pynative.com/python-range-for-float-numbers/" target="_blank">Used to get more x-points</a>

### README References ###
jytjt
1. <a href="https://www.youtube.com/watch?v=ECuqb5Tv9qI&t=158s&ab_channel=codeSTACKr" target="_blank">Ideas for README 1</a>
2. <a href="https://www.youtube.com/watch?v=a8CwpGARAsQ&ab_channel=Mr.RandomGenerator" target="_blank">Ideas for README 2</a>
3. <a href="https://banner.godori.dev/" target="_blank">Banner Maker</a>
3. <a href="https://www.markdownguide.org/basic-syntax/#blockquotes-1" target="_blank">Markdown Cheat Sheet</a>