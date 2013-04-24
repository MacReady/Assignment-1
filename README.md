Assignment-1
============

Code for GUI was provided by instructors, I completed the functions.

A1 Problem Domain: Coordinated Universal Time

The problem domain for this assignment involves time zones, and in particular Coordinated Universal Time (UTC), which is "the primary time standard by which the world regulates clocks and time" [Wikipedia]. As you know, there are many different time zones in the world. Wikipedia has a nice map of the time zones.

As of this writing, there are 40 time zones. One of them, UTC+00:00, is considered to be in the "middle" of the other time zones. All time zones have names, such as UTC+02:00, that indicate the number of hours and minutes they are away from UTC+00:00. For example, the Philippines are in time zone UTC+08:00 because clocks there are set 8 hours later than in time zone UTC+00:00. If it's noon in time zone UTC+00:00, it's 20:00 in time zone UTC+08:00.

Hours and minutes: representation

In this assignment, we are often going to represent hours and minutes and seconds together as a float. 1 hour will be represented as 1.0, 1 hour and 30 minutes as 1.5, and so on. Henceforth, when we specify a time zone, we will use this float representation, so the time zone for Nepal, which is in time zone UTC+05:45, will be represented here as UTC+5.75.

Preconditions

Some of the functions you will write assume that parameter values are in a certain range. The technical term for these restrictions is precondition: in order for the function to work, the precondition must be met. A precondition is a warning to whoever calls the function that the function was designed to work only under those conditions. When you see a precondition, that means we are guaranteeing that we will only call that function with values that meet the precondition. You can assume that the parameter values meet the preconditions, you do not need to check them. The preconditions are there to make your lives easier!

Print statements: don't use them

Nothing in the assignment requires print statements; your code will be marked as incorrect if you use them.
