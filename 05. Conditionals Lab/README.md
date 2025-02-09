# Conditionals Lab

## Objective: 
In this lab, you will learn how to start writing **conditions** using **conditionals** and make programs that can make decisions!



<img src="https://thumbs.gfycat.com/QualifiedAdolescentHind-size_restricted.gif">




> Before we start, navigate to the Repl.it assignment associated with this lab in the Teams tab! 

## Instructions:

### 1) Homer Diet
<img src="https://s3.amazonaws.com/after-school-assets/homer.gif" width="300px" align="right" hspace="10"> Homer Simpson has decided to go on a diet and he needs your help to stay on track. You are going to make the tests pass and help him control his donut intake.   

1. *Define* a new variable called `num_donuts` that takes in the number of donuts as an **input**. 

```python
num_donuts = input('Enter number of donuts here: ')
```

2. Now write a few conditional statements that meet the following criteria:
    - If the **number of donuts** is *greater* than **zero**, then your code should **print** `"Get back on your diet!"` 
    - Otherwise it should **print** `"Good job, Homer!"`   

    - **Hint**: If your code is not working, think about this. What datatype is `num_donuts`? What datatype do you need it to be?

- Homer's diet has been going well and we're going to cut him some slack. 

3. Write a new set of conditionals that reward him for this, using `num_donuts`.
    - Your code should print `"good job"` when Homer eats **less than *3 donuts***
    - And to `"slow down"` if he's eaten **exactly 3 donuts** 
    - And "`get back on your diet"` if he eats **more than 3 donuts**.

- We've decided to give Homer a little more control over his diet. *Define* a new variable, `max_donut_intake`, that takes in the maximum number of donuts Homer can eat, as an **input**.

4. Write a new set of conditional statements, using `num_donuts` and `max_donut_intake`.
    - Your code should tell Homer `"good job"` if he eats **less than half his maximum intake**
    - And `"get back on your diet"` when he **exceeds his maximum intake**.


### 2) GO HOME!, Unless...  

We will now use conditionals to see who get's to go home!

1. *Define* a new variable, `name`, that takes a person's name as an **input**.

2. Write conditional statements so your code prints `"[name], Go home!"`, unless the `name` is `"homer"`, as he is allowed to stay!

3. [BONUS] Does it work if you put in these strings as the `name` argument?
    - `"homer"`
    - `"Homer"`
    - `"hoMEr"`
    - If it doesn't take the previous strings, update and fix your code so it accepts the name `"homer"` in any way written! 
        - **Hint:** Look up `string.lower()`, `string.upper()`, etc...


### 3) Daily Routine

Homer's daily routine is:
- 8-9 Wake up
- 9-10 Brush teeth, then eat 10 donuts.
- 10-12 Run to the store and make sure you have enough donuts for lunch.
- 12-13 Donuts Lunch
- 13-15 Go to the park
- 15-19 TV Time!
- 19-20 Donuts Dinner!
- 20-24 Fall asleep while watching TV and eating donuts.

1. *Define* a new variable, `time`, which takes the time of the day as an **input**.

2. Plan your set of conditionals so that your code print's Homer's task according to the daily routine plan of his!
    - For example: if `time=12:30`, your code would print `Donuts Lunch`
    
3. Does it work properly? Test it out!
 
4. Now, ask a neighbor to write down his/her daily routine, and write a new set of conditionals that does the same, but for the new routine!
    - Let your neighbor try it out!



[![](https://media.tenor.com/images/a1a7f2e6a0a7e99a019a8937af3935e7/tenor.gif)]()




##### Great job!
##### Call an Instructor/TA to check your completed tasks
 

If you have extra time, continue to the **Bonus Problems** *below*.  
If not, make sure your code is saved in **Repl.it**!







## Bonus Problems:

#### Leap Years*
<img src="https://s3.amazonaws.com/after-school-assets/leap.gif" align="right" hspace="10">

1. Write a new set of conditionals that uses in **two inputs** for a `starting year` and an `ending year`, and then `print` all of the **leap years** *between them* (including the starting and ending years, if they are also leap years). 

    - Hint: Leap years are years **divisible by four** (like 1984 and 2004). However, years divisible by 100 are _not_ leap years (such as 1800 and 1900) unless they are ALSO divisible by 400 (like 1600 and 2000). 

Yes, it's all pretty confusing, but not as confusing as having July in the middle of the winter, which is what would eventually happen if we didn't have leap years!



##### Great job on completing the bonus problems section!  
###### Make sure your code is saved in Repl.it

