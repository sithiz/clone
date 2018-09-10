![GA logo](https://camo.githubusercontent.com/6ce15b81c1f06d716d753a61f5db22375fa684da/68747470733a2f2f67612d646173682e73332e616d617a6f6e6177732e636f6d2f70726f64756374696f6e2f6173736574732f6c6f676f2d39663838616536633963333837313639306533333238306663663535376633332e706e67)

# WDI

---

Title: Afternoon Lab<br>
Duration: 1 hr 15 mins approx<br>
Creator: Alex White <br>
Topics: Terminal, Errors, While loops, For Loops<br>

---

# Afternoon Lab

## Topics

Today we had a look at

* Errors
* Variables with `let` and `const`
* DRY
* Boolean expressions
* While loops
* For loops


Let's go over them for a refresher. We will be returning to them throughout the course.

Work through the following prompts in turn:

<br>
<hr>

# Terminal

* Open Terminal

* Navigate to your Class folder 

* Make a **directory** inside your class folder and day called `w1d1_lab`

* Go into the `w1d1_lab` directory

* Inside `w1d1_lab`create the simple file structure that we did yesterday with a `js` folder `css` folder and a `index.html

* Create your `app.js` file in the `js` folder

* Run your javascript file by opening your `index.html` file in the browser and then go look at the console.

<br>
<hr>

# Errors

Cut and paste the following code into your text editor (the "Cheers" song lyrics). The code is broken -- there are **three errors**. You might already see the errors, but --

Run the code and read the error message in the terminal. Using information from the error message (line numbers, etc.), debug the code and make it work.

At the same time, write a comment below the code that specifies what _type_ of error it was. Example, if you get this:

![](https://i.imgur.com/KRHtmPM.png)

Write

```
// SyntaxError: missing ) after argument list
```

Cut and paste:

```javascript
console.log("Making your way in the world today takes everything you've got.");
console.log("Taking a break from all your worries, sure would help a lot.");
console.log("Wouldn't you like to get away?");
console.log("Sometimes you want to go");
console.log("Where everybody knows your name,");
console.lo("and they're always glad you came.");
console.log("You wanna be where you can see,";
console.log("our troubles are all the same");
console.log("You wanna be where" "everybody knows");
console.log("Your name.");
```

Make it so you do not get any more errors!

<br>
<hr>

# Boolean Expressions
**... and arithmetic**

By just looking at the following expressions, determine in your mind whether or not each will evaluate to **true** or **false**

1. `999 > 999`
2. `999 == 999`
3. `999 != 999`
4. `-5 >= -4`
5. `100 <= -100`
6. `20 + 5 < 5`
7. `81 / 9 == 9`
8. `9 != 8 + 1`

<br>
<hr>

# Assignment operator vs Equality operator vs Strict Equality operator

What is the difference between:

the **assignment operator** `=`

and the **equality comparison operator** `==`

and the **strict equality comparison operator** `===`

?

<br>
<hr>

# While Loops: reps and reps

## 1

Write a *while* loop that will log the following phrase in the console 1000 times.

```
'Ginger chocolate honey patties'
```

You can test it out with a smaller number first, such as 10, and when that works, use 1000.

Make sure you do not run an infinite loop! If you do, you may have to force-quit your browser (`⌘ + option + escape`). Oops!


## 2

Write another *while* loop that counts from 0 to 1000 and will log in the console the current loop number.

> => 0
>
> => 1
>
> => 2
>
> => 3

etc.

## 3

Write another *while* loop that prints a message to the console _and_ interpolates the current loop number. Make it count from 0 to 1000.

> => "Current loop number is: 0"
>
> => "Current loop number is: 1"
>
> => "Current loop number is: 2"
>
> => "Current loop number is: 3"

<br>

**NOTE:** You should not need to see the 'correct answers' in this markdown for these loops. Either they work, or they don't. **Test** them thoroughly to make sure they are giving you the desired output.

<br>
<hr>

# For loops

# 1
* Write a **for loop** that counts from 0 to 100 and console.logs each number.

# 2
* Write another **for loop** that counts from 7 to 635 (no more, no less!), and console.logs each number.

# 3
* Declare a variable `let start = 0`
* Declare a variable `const limit = 100`
* Write a for loop that counts from the value of `start` to the value of `limit`, using those variables in the **control panel** odf the loop.

Test the loop thoroughly.

# 4
* Think of something in real life, or nature, or wherever / whenever that displays **looping** behavior (a repeated action).

Use a **for loop** to model the looping behavior of that thing.

Where does the loop begin? Where should it end? Does it simply count from one number to another? Or does it change or mutate data?

<br>
<hr>

# Conclusion

Congrats! There is no need to submit this lab. 

If you want more to do, later today we will be getting into git and Github. Use your **research skills** (Google-fu) to find out more about:

* The difference between git and github
* What is a Github repo
* forking a repo on Github
* cloning a repo from Github
* What does `git push origin master` do? What does it mean?
* What would `git pull upstream master` do?

<br>
<hr>
