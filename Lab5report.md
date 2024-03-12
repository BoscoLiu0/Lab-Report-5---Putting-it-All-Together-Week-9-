# Lab Report 5 - Putting it All Together (Week 9)
## Part 1 - Debugging Scenario
> [!WARNING]
> ### （Because I lost the screenshot of my classmate gave me, I need to recreate the question.）
Hello, recently I was working on an autograder bash script called `grade.sh` and I dont know why is didnt get "score 0". but my tested `https://github.com/ucsd-cse15l-f22/list-methods-corrected, which has the methods corrected (I would expect this to get full or near-to-full credit)` got 100%

Here is a screenshot of his output: 

![image](./1.png)

![image](./3.png)

Here's a screenshot of his bash script: 

![image](./code1.png)

### TA's Response

You don't need to change any code, but you can consider the missing `ListExamples.java` file.

### Student Response

I think the classmate's code is correct because he was able to change the score for the second link. I would consider this from ListExamples. Then when I modify lines 38-40 in grade.sh and add echo "Score 0", I can get the answer.

![image](./2.png)

I tried running the bash script with the new classpath, and here's the output:

![image](./3.png)

As shown, the command statement is missing.

### All setup information 

The working directory should have a WEEK9-lab folder with the necessary JUnit jar files, the tester file, the Java program, and the bash script. It should look similar to this: 

![image](./4.png)

Before fixing the bugs. To trigger the bug, we used the command `bash test.sh`, in order to test our Java program. , and if it still doesn't work, then we need to look at the other files to see if they are correct, and it is clear that this is a simple "small bug".

## Part 2 - Reflection

During the second half of the quarter, I delved deeper into Bash scripting and discovered the power of using loops and conditional statements to automate repetitive tasks. Learning how to write efficient Bash scripts not only improved my productivity but also gave me a better understanding of the underlying Unix-like operating system. Additionally, I learned how to leverage command-line tools and utilities effectively, enhancing my proficiency in managing and manipulating files and directories within the terminal environment.
