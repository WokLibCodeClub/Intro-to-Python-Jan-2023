# Code Club sessions teaching Python for beginners

We started our post-pandemic Code Club sessions in the new Wokingham library in January 2023, and our Python sessions began with some basic teaching on coding for people who had never used Python before.

This page includes some links to code and documents used during these beginner sessions.

## 7 January 2023

You can find the code which we built during this first session at

[https://trinket.io/python/2bf41e12e2](https://trinket.io/python/2bf41e12e2)

This session roughly followed the sequence in this document, which has more explanation:

[Sep 2020: Python from the Beginning Session 2.pdf](https://github.com/WokLibCodeClub/OnlineCodeclub/blob/master/20200915%20Python%20from%20the%20Beginning%20Session%202.pdf)

If you go to the link above you can click on the Download button in the top right to download a copy to your own computer.

---

## 28 January 2023

### Rules for naming your Python variables:
- A variable name can only contain alpha-numeric characters and underscores (A-Z, a-z, 0-9, and _ ). No SPACES allowed.
- A variable name must start with a letter or the underscore character - never a number
- Variable names are case-sensitive (age, Age and AGE are three different variables)
- We can’t use reserved keywords as a variable name (see below)
- We should avoid using names of Python functions, eg int, input, str

To find the list of reserved keywords go to the trinket Python console [trinket.io/console](https://trinket.io/console)

and type (you don't have to type the >>>):

```python
>>> import keyword
>>> keyword.kwlist
```

#### Here is a link to a project for learning about the turtle graphics window:

[https://trinket.io/python/edf3efe7aa](https://trinket.io/python/edf3efe7aa)

#### You can find the code which we built during the session on 28 January 2023 at

[https://trinket.io/python/ad24f53fea](https://trinket.io/python/ad24f53fea)

The code is the same as we wrote during the session but we've added a few Python *comments* (lines that begin with a ```#```) to show how useful comments can be! In trinket the comments always appear in green text.

#### Here is a website where you can find the list of all named the colours you can use in your Python code:

[www.w3schools.com/colors/colors_names.asp](https://www.w3schools.com/colors/colors_names.asp)

You can set a turtle to have any of these colours by putting the colour name in quotes inside the brackets after the word color. Example:

```Python
t.color('PeachPuff')
```

if your turtle is in a variable called ```t```. Python recognises the colour with or without the capital letters, so in this example you could type peachpuff instead of PeachPuff and it would still work.

Later on, you will find out how you can create your own colours.

---

## 4 February 2023

#### Link to shape-drawing **turtles** project with extra turtle properties added, as after the session on 4 February 2023:

I've added a few more comments to explain what each line of code does.

[https://trinket.io/python/9bc368b985](https://trinket.io/python/9bc368b985)

#### Link to starter project for *"Catch the ball"* game:

[https://trinket.io/python/0e429f731b](https://trinket.io/python/0e429f731b)

#### Link to  *"Catch the ball"* game as it was at the end of the 4 February 2023 session:

[https://trinket.io/python/d7a8fffb87](https://trinket.io/python/d7a8fffb87)

---

## 25 February 2023

In this session we finished the ***"Catch the ball"*** game. You can find the code for the final game at

[https://trinket.io/python/9a6df6ef39](https://trinket.io/python/9a6df6ef39)

In developing this code we learned how to make our own *functions*, and talked about the (complicated) difference between *local* variables and *global* variables. We also wrote code to allow us to *click* on Python turtles and control what happens when we do. You can find the little project which shows how the ```onclick``` turtle function works at

[https://trinket.io/python/7981c58fe5](https://trinket.io/python/7981c58fe5)

---

## 4 March 2023

Unfortunately this session had to be cancelled because of unavailability of volunteers.

---

## 25 March 2023

In this session we covered the very important idea of Python *lists*. Then we introduced another type of Python loop: the *for* loop, which we can use as an alternative to the *while* loop. We also covered the useful Python ```range()``` function.

#### We began with this starter trinket project for lists and the link is

[trinket.io/python/33bf438adb](https://trinket.io/python/33bf438adb)

#### You can see the code as it was at the end of the session at

[trinket.io/python/2e4d5a7866](https://trinket.io/python/2e4d5a7866)

We used the **Python console** [Your Interactive Python Console (trinket.io)](https://trinket.io/console) to explore the ```range()``` function with one, two or three parameters. (Parameters are the numbers you put inside the brackets.) Here is the text from the console session on 25 March 2023, showing different results from using ```range()```:

```
Interactive Python Console
>>> range(7)
[0, 1, 2, 3, 4, 5, 6]
>>> range(2,11)
[2, 3, 4, 5, 6, 7, 8, 9, 10]
>>> range(1,11)
[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
>>> range(1, 11, 3)
[1, 4, 7, 10]
>>> [10, 9, 8, 7, 6, 5, 4, 3, 2, 1, 0]
[10, 9, 8, 7, 6, 5, 4, 3, 2, 1, 0]
>>> range(10, 0, -1)
[10, 9, 8, 7, 6, 5, 4, 3, 2, 1]
>>> range(10, -1, -1)
[10, 9, 8, 7, 6, 5, 4, 3, 2, 1, 0]
>>> 
```

---

## Final session - 1 April 2023

We finished the formal teaching of Introduction to Python with a short demonstration about how you can move some of your code, for example, variables or functions, from the trinket tab called ```main.py``` into a new tab which you can create by clicking the plus sign to the left of the word Result in the trinket editing page. If you give your new file a name which ends in ```.py``` you can ```import``` the contents of this file and use them in your ```main.py``` code. You can see a trinket project where this has been set up at

[https://trinket.io/python/e10cf365be](https://trinket.io/python/e10cf365be)

We then moved on to the Python projects on the Raspberry Pi website. You can have a look at some of the Level 1 Python projects at

[Project path | Intro to Python for kids | Raspberry Pi](https://projects.raspberrypi.org/en/pathways/python-intro)

The first project, called *Hello*, builds on the ideas we have already introduced.

---



