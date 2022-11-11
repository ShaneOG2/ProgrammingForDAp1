![Heading image](img/Shane_O'Gorman's_pfda.png

## Overview ##
This repository contains my work for the Pand-Problems given for Programming and Scripting course. I have outlined below each problem with a brief description, how the program works and the references I used to when writing the program. 


### Problem 1 - Body Mass Index (BMI) ###
---
**Description** - Calculate the Body Mass Index (BMI) of a person given their weight (kg) and height (cm). 

**How the program works** - 
1. The program begins by asking the user to input the weight (kg) and then height (cm). 
2. Both inputs are stored as int variables, ***w_kg*** and ***h_cm*** respectively. 
3. The formala for BMI<sup>1</sup> is: **weight (kg) / (height (m))<sup>2</sup>**. This was calculated and stored as ***bmi***. 
4. Given the inputed height was in cm, ***h_cm*** was divided by 100 in the calculation of ***bmi*** to convert to meters.
5. The round function<sup>2</sup> was used to round ***bmi*** to 2 decimal places. 
6. Next, I decided to add a bit more to the program and give the user an indication<sup>3</sup> whether the BMI they got was underweight, normal, overweight, obese or extremly obese.
7. This was acheived using if/else statements<sup>4</sup> and Comparison Operators<sup>5</sup>.
8. Finally, The BMI was printed<sup>6</sup> out along with the result indicator (i.e. underweight, normal, etc.)

**References** - 
1. <a href="https://www.cdc.gov/nccdphp/dnpao/growthcharts/training/bmiage/page5_1.html#:~:text=With%20the%20metric%20system%2C%20the,by%2010%2C000%2C%20can%20be%20used" target="_blank">BMI Formula</a>
2. <a href="https://www.w3schools.com/python/ref_func_round.asp" target="_blank">Round Function</a>
3. <a href="https://www.everydayhealth.com/diet-nutrition/bmi/bmi-adults-yours-healthy-not-how-can-you-lose-weight/" target="_blank">BMI Indicator</a>
4. <a href="https://www.w3schools.com/python/python_conditions.asp" target="_blank">If/else statements</a>
5. <a href="https://www.w3schools.com/python/python_operators.asp" target="_blank">Comparison operators</a>
6. <a href="https://www.w3schools.com/python/ref_string_format.asp" target="_blank">Format</a>

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
1. <a href="https://pynative.com/python-range-for-float-numbers/" target="_blank">Used to get more x-points</a>
2. <a href="https://www.w3schools.com/python/matplotlib_labels.asp" target="_blank">Design of plot</a>
3. <a href="https://stackabuse.com/how-to-set-axis-range-xlim-ylim-in-matplotlib/" target="_blank">Design of plot (Axis labels)</a>
4. <a href="https://stackoverflow.com/questions/21226868/superscript-in-python-plots" target="_blank">Power of formating</a>

### README References ###
1. <a href="https://www.youtube.com/watch?v=ECuqb5Tv9qI&t=158s&ab_channel=codeSTACKr" target="_blank">Ideas for README 1</a>
2. <a href="https://www.youtube.com/watch?v=a8CwpGARAsQ&ab_channel=Mr.RandomGenerator" target="_blank">Ideas for README 2</a>
3. <a href="https://banner.godori.dev/" target="_blank">Banner Maker</a>
3. <a href="https://www.markdownguide.org/basic-syntax/#blockquotes-1" target="_blank">Markdown Cheat Sheet</a>