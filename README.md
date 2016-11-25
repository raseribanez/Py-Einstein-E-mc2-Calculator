# Py-Einstein-E-mc2-Calculator
What it says on the tin. Theres 2 versions of this, a, text version, and a Tk version

Nothing amazing, I just wanted to Prove the Power of Python

The ultimate equation in just 4 lines of code!
----------------------------------------------
The text version solves one of Physics most famous equations from the great Albert Einstein (E=mc2) with like 4 lines of code. It allows the user to enter ANY mass in kg and returns the energy conversion for that mass.

I then wrote a Tk app for it. Now I have the Tk apps sussed (on a basic level at least) i have a pretty sound template whicj you may notice looks similar across a few of my calculator/converters. It works...and when I learn how to improve them I will. The main thing I improved upon with this one and the all in one wavelength calculator I wrote, was how to put my GUI's into classes.

I had always just done it the way I was shown...just dump everything into one script (no classes or anything). It has taken me a few attempts to figure it out but I have a decent template to work with now across any type of Tk app. The original class example I used, I found on Stack.O...it worked, but I don't know if I really need all of those things included in the class object, maybe some day I will take it apart and see what is essential and what can be cut out of smaller programs like this. 

The values used in the calculations:

* mass: entered by user (Kg)
* speed of light:  299752458 (m/s)^2 - (I am sure that is what I used...will check that now) 
* energy conversion = mass x speedOfLight squared

I made the mistake of doing it like this first: E = (m x c)^2
I found my results matched with it like this instead: E = m x (c^2)

I ran this against 2 of the main online calculators and I got very accurate results.

It will accept a whole number (integer)
But loves it when you feed it a 7 decimal float (eg: 6.6666666)

Feedback welcome.

raserppsprograms@gmail.com

Ben
