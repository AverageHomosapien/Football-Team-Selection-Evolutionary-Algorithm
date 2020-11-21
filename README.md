# Football Team Selection Evolutionary Algorithm
This was a 4th year coursework done as part of the Emergent Computing for Optimisation module.

## Overview
The task was to select the best football team from a file of 523 football players.
Each player was given a cost and a score associated with their skill level.

The output representation required was a 523 length binary string, with a 1 at the position of each player
selected to be taken and a 0 at the position of each player not coming.

## Approach
I fully detail my approach in the PDF file attached. I will summarise my approach taken below:

I used Python and the Deap library as this has a lot of pre-built EA functions inbuilt.
Python is an extremely flexible and easy-to-write language.

I used Jupyter Notebooks as this allows rapid prototyping, quick evaluation and code to be run line by line
 - extremely useful in a Scientific setting.

I used Matplotlib to visualise and compare my operators in the report as it allows for quick and flexible graphing.

## An example of some results:

![comparison-of-mutation-operators](https://github.com/AverageHomosapien/Football-Team-Selection-Evolutionary-Algorithm/blob/main/saved_plots/mutUniformInt.png)