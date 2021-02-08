# js-insider
JavaScript explanation based on my understanding...

# What is JavaScript ??
  In simple words JS is programming language with the following functionality: 
  
  * **High-Level**: JS is a high level programming language. Unlike other languages, JS don't have to manage the memory
    or explicitly command the CPU. SO, JS do not have to manage resources.
    
  * **Prototype-based Object-Oriented**: Everything in Js is object except primitive datatypes like string and numbers. 
    And when we are using array.push method  
  
  * **Multy-paradigm**: JS supports all the type of programming approch so it is Multy paradigm language.
    i.e. 1) Functional programming 2) Object oriented programming 3) Procedural programming
  
  * **Interpreted (just-in-time compiled)**: Computer understand only machine code (0s and 1s). So we have to first compile 
    the code and after that convert code into machine code. In JS there is JS Engine which do this both task for us. 
    In other languages compilation and execution both process are done one by one but in JS, JS engine first compiles 
    program and then imideatly executes the code so we called JS as interpreted or Just-in-time compiled language. 
    
  * **Dynamic**: Unlike to other languages in Js we do not need to define type when we are declaring variables. JS finds
    type of variable dynamically at run time.
    
  * **Single-threaded with Non blocking Event loop**: JS is single threaded means there is only one single thread which 
    executes JS code in CPU, so JS can do only one thing at a time. But what is we have some task which is taking time
    longer time??, In Js there is special functionality called Event loop which takes this time taking code and runs in
    the background. And once they are finished it put it back in the main stack. 
    
  * **Garbage-collected**: When we write a code it's possible that some variables are taking space in the memory while we don't 
    require them at all. So, with this functionallity JS automaticly clear the spaces in the memory which is not currently in use.
 
  
  
# How JS works behind the scene ??
  ![JS Execution Context](https://www.google.com/url?sa=i&url=http%3A%2F%2Fdannyzhang.run%2F2017%2F04%2F03%2FHow-JavaScript-works-Behind-the-   Scenes%2F&psig=AOvVaw0AUjS809IrwCaxqf3ONXOJ&ust=1612872318086000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCMCR4uif2u4CFQAAAAAdAAAAABAD)
  
  ## Execution stack:
  This mechanizm is normal stack in which last pushed item poped first i.e(LIFO). All the executable task are pushed into execution 
  stack and when time comes they are poped after the execution.
  ## Global Execution Context:
  Js engine puts all top level code into global execution context and the code in global execution context runs very first.
  ## Function Execution Context
  Js engine puts the code of each function in saperate execution context assigned to that function.
  
  Execution context generally stores the variables and other stuff to execute perticular code.
  
  Very first Js engine reads the javascript program and takes the top level code to global execution context, and other function code to
  their seprate execution context.
  After that execution stack first runs the code which inside the global execution context and then function code when function call arrives. 
  
  
# JS variables
  Variables are one kind of box with the name and we can use them to store whatever we won't. Suppose we have to store our age then first we 
  give a name "age" to one box and then stores our age i.e. 20 in that box.
  
  While we declare a variable we have to follow some rules for naming them like other programming language.
  Most recommended approch is to use camelCase notation in variable nameing.
  like my_age is written as myAge and
  your_name is written as yourName etc.
  
# JS datatypes
  * Number 
  * String
  * Boolean
  * Objects
  * null: It is special type of value and the value itself is "null". 
  * undefined: Meaning of undefined is "the value is no assigned or defined".
  
  
# JS type conversion
# JS operator
# Loops: for and while
# function: function declaration, function expression and arrow function
 
  
