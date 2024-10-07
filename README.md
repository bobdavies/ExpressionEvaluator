# ExpressionEvaluator
This is a Python program that reads mathematical expressions as an input from a text file. It then evaluates each expression using a stack-based approach, and writes the results/output to another text file.

## How to Run the Program

1. Ensure you have Python 3.x installed on your system, by running the command in your terminal below to check if installed:
    -  `python3 --version`

2. Save the Python script as data.py.
3. Create an input.txt file where you can input your mathematical expressions 
    - Ensure you write each expression on a new line

4. Run the program using the command below in your terminal:
    -  `python data.py`
   
5. Check the results in the output.txt file.
6. If you didn't get an output kindly ensure that you are in the right directory and run program again

## Input File Structure (input.txt)

- Each mathematical expression should be on a new line.
- Expressions are separated by lines containing only a separator ("-------------").
- For Example:
  
  3 + 5 * 2
  -------------
  (8 / 4) + 7 * 2
  -------------
  10 - (2 + 3) * 4
  

## Output File Structure (output.txt)

- The output file will contain the results/output of each expression in the input.txt file.
- Each result will be on a new line, separated by the same separator used in the input file.
- Note that the output values are in their nearest whole number
- Example (corresponding to the above input):
  
  13
  -------------
  17
  -------------
  -10
