JavaScript Chapter10 - "Error handling and debugging"
    -If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.
    -Debugging is the provess of finding errors. It involves a provess of deduction. 
    -The console helps narrow down the area in which the error is located, so you can try to find the exact error. 
    -JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
    -If you know that you may get an error, you can handle it gracefully using the try, catch finally statement. Use them to give your users helpful feedback.
    -Order of execution, to find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.
    -Execution contents, the JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new execution context. They correspond to variable scope.
    -The stack, The JavaScript interpreter processes one line of code at a time. When a statement needs data from another function, it stacks (or piles) the new function on top of the current task.
    -Execution context and hoisting, Each time a script enters a new execution context, there are two phases of activity: Prepare, the new scope is created; Variables functions, and arguments are created. Execute, now it can assign values to variables, reference functions and run their code, execute statements.
    -Understanding scope, in the interpreter, each execution context has its own variables object. It holds the vairables, functions, and parameters available within it. Each execution context can also access its parent's variables object.
    -Understanding errors, If a JavaScript statment generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code. 
    -Error objects can helop you find where your mistakes are and browsers have tools to help you read them.
    -How to deal with errors: Debug the script to fix errors, if you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it. Handle errors gracefully, you can handle errors gracefully using try, catch, throw and finally statements.
    Debugging workflow, debugging is about deduction: eliminating potential causes of an error. 