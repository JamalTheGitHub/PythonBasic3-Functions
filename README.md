# PythonBasic3 Function

Prerequisite => From this tutorial onwards, it is expected that you have the following extensions in your Visual Studio Code;

1)Code Runner 2)Python

If you want to know more on how to get Python on Visual Studio Code, google it.

First thing first, create a file called called whatever you want it to be called and save it as ".py". For example like this, "PythonTutorial.py". Navigate to that file and do your coding there.

================================================================================================

<h3>Functions</h3>

<strong>Functions</strong> are a collection of instructions for the program to properly run as it intended to. Look at the example below;

        def function1():
            print("I am inside the function")

Alright, let's look at closely what the code means. <strong>def</strong> means <strong>to define</strong>. <strong>function1()</strong> is the name of the function. The name of the function can be anything as long as it makes sense to YOU. A good practice is using a <strong>Camel Case</strong> when naming functions. Also notice the <strong>"()"</strong> which we called <strong>parentheses</strong>. <strong>Functions</strong> NEED to have parentheses in order for it to work. In the <strong>function</strong>, we have a <strong>print function</strong>. However, running the code will not do anything because in order to execute the <strong>function</strong>, we need to call it. In order to call the <strong>function</strong>, simply type out the name of the function PROVIDED that you have already defined it. Therefore, with the above example, we just add a new line;

        def function1():
            print("I am inside the function")
        function1()

Now, if we run the code, we will get the message from the <strong>print function</strong>. Since the code is working fine and dandy, let's talk about <strong>parantheses</strong>. <strong>Parantheses</strong> can be empty OR can include <strong>arguments</strong>. Here is what an <strong>argument</strong> looks like in a <strong>function</strong>;

        def function2(x):

The "<strong>x</strong>" inside the <strong>parantheses</strong> is what we call an <strong>argument</strong>. You can have more than one <strong>arguments</strong> depending on what you want the <strong>function</strong> to do. In this case, if we were run the code, we will get an <strong>IndentationError</strong>. Not to worry, let us just extend the <strong>function</strong> for a better understanding.

        def function2(x):
          return x + 3

        print(function2(3))

Alright, let's walk through on what happened. Inside <strong>function2(x)</strong>, we added a line that says <strong>return x + 3</strong>. What this means is that it just returns the value to the <strong>function</strong>. Without the <strong>return</strong>, nothing will be returned back to the <strong>function</strong> and it would render the <strong>function</strong> "pointless". So now, to test whether the <strong>function</strong> is working as it should, we want to call it. So how do we call it? With the <strong>print function</strong> of course! This is because, in <strong>function1()</strong>, we had assigned a <strong>print function</strong> within it, thus by calling the <strong>function</strong> just by writing the name of the <strong>function</strong> will give the output of the <strong>print function</strong> because it is a <strong>print function</strong>!

It is possible to multiple arguments in a single function. The concept is the same, like an example below;

        def function3(x,y):
            return x + y
        
        print(function3(5,6))

If you were to run the code, you will get 11. In this case, since there are two <strong>argurments</strong>, <strong>"x"</strong> and <strong>"y"</strong>, whatever values you put will correspond to how the <strong>function</strong> was written.

Basically that is it for <strong>functions</strong>! The point is to understand the concept and how it works. You can also make any <strong>functions</strong> provided that you know the proper and correct <strong>synstaxes</strong>.

================================================================================================

Alright it's time to test YOUR understanding!

Remember previously you had to create a simple bmi-calculator? Now, create it again but with <strong>functions</strong>! You should be able to create at least 3 Results from 3 different persons given their <strong>names</strong>,<strong>heights</strong> and <strong>weights</strong>.

Best of Luck and be creative!