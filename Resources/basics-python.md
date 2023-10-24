# how to create a function algo vs python 
## Algorithmic Pseudocode:
1. Function AddNumbers(a, b)
2.   result = a + b
3.   Return result
4. End Function
# classic :
###### function:
FONCTION ident_fonction(<liste des paramètres>) : ident_type_retourné
       <déclarations paramètres>
       [<déclarations locales>]
  DEBUT>
       <instruction>
    ...
  RETOURNE <résultat>
  FIN
  ###### procedure :
  PROCEDURE ident_procedure(<liste des paramètres>)
       [<déclarations paramètres>]
       [<déclarations locales>]
  DEBUT
       <instructions>
  FIN
## python function dec : 
def function_name(parameters):
    """
    Brief description of the function's purpose.

    Parameters:
    - parameter1 (type): Description of parameter 1.
    - parameter2 (type): Description of parameter 2 (if applicable).

    Returns:
    - return_value (type): Description of the return value (if applicable).
    """
    # Function code here
    # You can include conditional statements, loops, and other operations

    # Optionally, return a value
    return return_value
 exemple :
 def my_function(): <br>
  print("Hello from a function") <br>

my_function() <br>
##  Enumerate in python : 
Here, we are using the enumerate() function with both a list and a string. Creating enumerate objects for each and displaying their return types. It also shows how to change the starting index for enumeration when applied to a string, resulting in index-element pairs for the list and string.
exmp: 
l1 = ["eat", "sleep", "repeat"] <br>
s1 = "geek" <br>

**creating enumerate objects <br>
obj1 = enumerate(l1) <br>
obj2 = enumerate(s1) <br>

print ("Return type:", type(obj1)) <br>
print (list(enumerate(l1))) <br>

**changing start index to 2 from 0 <br>
print (list(enumerate(s1, 2))) <br>
