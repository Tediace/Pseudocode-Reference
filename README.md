# Pseudocode-Reference
<br>Pseudocode does not have a strict syntax but there are common ways of explaining different coding 
concepts like input, variables, conditional statements, loops and functions.</br>
## Input
<br>Input could be from a keyboard, database, mouse, and so on. You want to indicate that data is 
coming into the program from some external source.</br>
<pre><code>get name from user
get user_record from employee_database</pre></code>
## Variables
### Simple variable
Create a variable named points and give it the value of two:
<pre><code>set points to 2</pre></code>
Collection of values like an array or list
<pre><code>set names to 'Dave', 'Reggie', 'Hope', 'Colleen'</pre></code>

## Conditional Statements
### Single condition
If the points variable is more than 100, print "High Score!"
<pre><code>if points is greater than 100 
    print “High Score”
endif</pre></code>
Indent code inside of conditional statements to make clear the steps the program follows if the condition is true.

## Multiple conditions
<pre><code>if points is less than 0 
     print “You lose!”
elseif points is greater than 100
    print "High Score"
else
    print "You won, but didn't get the high score"
endif</pre></code>
### Loops
Looping though a collection of items like an array or list
<pre><code>for each name in names 
     print name
endfor</pre></code>
Looping a set number of times:
<pre><code>for every number from 1 to 100
    print number
endfor</pre></code>
Loop while a condition is true:

<pre><code>while user_input is not 'Exit'
   ...do something here
endwhile</pre></code>
## Functions
### Create a function
Create a function that prints out a message to the console.
<pre><code>function print_message 
    pass in message
    print message
endfunction</pre></code>
### Call a function
<br>call print_message with "Howdy!"
A function that returns a value:</br>

<pre><code>function calculate_tax
    pass in amount and tax_rate
    return amount * tax_rate
endfunction

set tax to call calculate_tax with 100 and .08
print 'Your tax is'
print tax</pre></code>
