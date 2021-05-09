# Stock Analysis Refactoring

## Overview Of the Project
	The project was intially set up with a program written in Visual Basic to be used by Steve to analyze data surrounding green energy stocks. The challenge was to then refactor the program so that it ran more efficiently. If the original program was to be used for larger datasets then it may take more time to run, so the goal is to optimize the code so, the program can run faster.
	
## Results

	After refactoring the code, the program does gather and organize the data quicker then the original program that was written. 
	
	With the original code the program would start with the first ticker, and sort through the entire dataset collecting what information it needed, storing it in variables that are reset at the beginning of every loop, and then printing the data to the worksheet. The next loop would start moving on to the next ticker, and repeating the process. 
	
	However in the refactored code, because the data is sorted by tickers alphabetically, the program only has to sort through the dataset once collecting the sata on the indivdual tickers as they come up and saving it into arrays and only after looping through the entire dataset does it print all of the data collected.
	
## Summary
	
	Refactoring code comes with the advantage of getting the chance to improve your code, be it actually optimizing it or just cleaning it or adding better documentation. However refactoring may not always be the best course of action, because adding more time to the development process and trying to fix what isn't broken can lead to a higher chance of getting something wrong and potentially adding bugs into code that was otherwise working.
	
	