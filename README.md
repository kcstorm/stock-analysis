# VBA Module 2 - Green Stocks Refactoring
***
## Overview of Project
Steve, a financial market analyst, had tasked me with writing a VBA script that would display total daily volumes and returns for a handful of his favorite stocks. After further discussion, he would like to eventually add many more stocks to his analysis portfolio. However, doing so would certainly affect report execution performance, so I offered to refactor the VBA script to lessen the memory and performace load on his PC.
***
## Results
The refactored script (for both 2017 and 2018) ran 87% faster than the original script and produced the same financial results in a reliably consistent fashion. 

2017 Run
- Before refactoring: 0.4843785 seconds [Ref Image: https://github.com/kcstorm/stock-analysis/blob/main/Resources/VBA_Challenge_2017_Old.PNG]
- After refactoring: 0.0625 seconds [Ref Image: https://github.com/kcstorm/stock-analysis/blob/main/Resources/VBA_Challenge_2017.PNG]

2018 Run
- Before refactoring: 0.484375 seconds [Ref Image: https://github.com/kcstorm/stock-analysis/blob/main/Resources/VBA_Challenge_2018_Old.PNG]
- After refactoring: 0.0625 seconds [Ref Image: https://github.com/kcstorm/stock-analysis/blob/main/Resources/VBA_Challenge_2018.PNG]
***
## General Advantages/Disadvantages of Refactoring Code
- Advantages
1. Readability: refactored code can end up being easier to read and follow.
2. Performance: could significantly decrease performance time for reporting, and provide a better user experience.
- Disadvantages
1. Quality assurance: potential risk to create bugs in the code.
2. Readability: could be jeopardized if a programmer didn't satisfactorily comment and used lesser known or complicated shortcuts.

## Other refactoring opportunities for larger projects, code change and processes
1. Analyzing the frequency of database calls for large amounts of data.
2. Creating loops to initially store values of heavy, complex calculations that will be used further in the code.
3. Moving processes off of legacy systems.

## Advantages/Disadvantages of Refactoring VBA scripts
- Advantages
1. Readability: the refactored code was easier to read and follow.
2. Performance: decreased performance time and less CPU use.
- Disadvantages
1. Risk: potential risk to create bugs in the script.
2. Readability: could be jeopardized if a programmer didn't satisfactorily comment and used lesser known or complicated shortcuts.
3. Computer program/processing conflict: a machine may have unidentified background programs and/or proceses that significantly affect performance time.  As such, the benefit of refactoring may or may not be fully realized, nor necessary.
