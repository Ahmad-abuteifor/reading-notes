# Error handling and debugging 

some time you need To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run

EXECUTION CONTEXTS
The JavaScript interpreter uses the concept of execution contexts. 


EXECUTION CONTEXT has three type :
1.  GLOBAL CONTEXT 
2. FUNCTION CONTEXT  
3. EVAL CONTEXT (NOT SHOWN)  


VARIABLE SCOPE : 
1. GLOBAL SCOPE  
2. FUNCTION-LEVEL SCOPE  


Each time a script enters a new execution context, there are two phases
of activity: 
1. PREPARE   
. The new scope is created  
. Variables, functions, and arguments are created  
. The value of the this keyword is determined    
2. EXECUTE    
. Now it can assign values to variables  
. Reference functions and run their code  
. Execute statements   



Error objects can help you find where your mistakes are
and browsers have tools to help you read them  


**ERROR type  :** 
1. Syntax Error  
2. Ref erenceError  
3. EvalError  
4. URI Error  
5. Type Error  
6. RangeError  
![error](https://www.tutsmake.com/wp-content/uploads/2020/05/Types-of-Errors-In-JavaScript.jpeg)



**A DEBUGGING
WORKFLOW** 
Debugging is about deduction: eliminating potential causes of an error.  


and there is a very helpfull tool too find the error 
BROWSER DEV TOOLS &
JAVASCRIPT CONSOLE  

![console](https://www.danielpuiatti.com/wp-content/uploads/2020/03/javascript-console-4.jpg)


tips that you
can try to use when debugging your scripts.  
- ANOTHER BROWSER  
- SEARCH  
- VALIDATION TOOLS  
- ADD NUMBERS  
- STRIP IT BACK  
- CODE PLAYGROUNDS  
- EXPLAINING THE CODE  
 