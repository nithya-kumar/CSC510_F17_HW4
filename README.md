# HW4
## CSC 510 (Software Engineering) F17 HW4

The HW is an extension of the [Complexity workshop](https://github.com/CSC-510/Complexity)

### Simple calculations

**Per Function:**

***ParameterCount:*** The number of parameters for function.  
***Returns:*** The number of return statements in function.  

**For File:**  

***AllConditions:*** The total number of conditions in file.  
***String Usage:*** How many string literals are used in file.  
***PackageComplexity:*** The number of imports used in file.  

**Using multiple visitors**

***SimpleCyclomaticComplexity:*** The number of if statements/loops + 1.  

***MaxMessageChains:*** The max length of a message chain in a function. A message chain can be formed from a method call (), a data access (.), or array access [n].  

The code for the above can be seen in [**analysis.js**](https://github.ncsu.edu/nkumar8/HW4/blob/master/analysis.js) in the function *complexity*
