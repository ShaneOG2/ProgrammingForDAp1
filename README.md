![Heading image](img/sleeping.png)

# Programming for Data Analysis - Project 1 #

## Overview ##
This repository contains my work for Project 1 of the the Programming for Data Analysis Module module at ATU as part of the Higher Diploma in Computing (Data Analytics). This repository contains: 

- The Jupyter notebook 'Simulation Notebook.ipynb' which contains the main body of work. 
- A folder named 'img' which contains images used in 'Simulation Notebook.ipynb'. 
- This README file.

**Project Statement** - Create a data set by simulating a real-world phenomenon. 
- Choose a real-world phenomenon that can be measured and for which you could collect at least one-hundred data points across at least four different variables.
- Investigate the types of variables involved, their likely distributions, and their relationships with each other.
- Synthesise/simulate a data set as closely matching their properties as possible
- Detail your research and implement the simulation in a Jupyter notebook – the data set itself can simply be displayed in an output cell within the notebook.

**About this Respository** - The contents of this repository are:

1. **README** consists of the project statement and how to access .
2. **Simulation Jupyter Notebook**



**How the program works** - 
1. Firstly, the program gets the x-points to plot - using np.arrange we can get the points between 0-4 incremented by 0.1 for accuracy<sup>1</sup>. This is inputed into a numpy array. 
2. We can then calculate or y-points based off our x-points for each of the three functions f(x), g(x) and h(x). 
3. We can then plot the fuctions using ***plt.plot()*** giving each function a different colour and labeling them.
4. ***plt.legend()*** shows the fuction labels and colour to distinguish between them<sup>4</sup>.
5. I added "Functions" as the title of the plot along with labeling the x and y axis. 
6. plt.xticks and plt.yticks were used to get the correct x and y axis label increments i.e on the x axis I wanted 0, 1, 2, 3, 4 to be shown and on the y axis 0 - 70 with increments of 10.<sup>3</sup>
7. ***plt.grid()*** puts grid lines on the plot. 
8. Finally, 4. ***plt.show()*** shows the plot we created. 



