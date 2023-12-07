 Python Statements is an instruction that the python intepreter can execute.

- For example My favorite statement is the [[Match]] Statement, It somewhat works like `elif` statement, but much more readable and only for python 3.10+ Here's a sample I use alot

```python
def main():

	#SPLITS THE STRING WITH THE WHITESPACES TO 3
    x, y, z = str.split(input("INPUT: ")) 
    
    x = float(x) #//CONVERT X TO FLOAT
    z = float(z) #//CONVERT Y TO FLOAT

    match y:
        case "+" | "plus":
            result = x + z
            print(result)

        case "-" | "minus":
            result = x - z
            print(result)
            
        case "*" | "times" | "x":
            result = x + z
            print(result)

        case "+" | "divide" | "/":
            result = x / z
            print(result)
            
main()

```