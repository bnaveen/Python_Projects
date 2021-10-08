 Chapter 2 :- Variables,Expressions, and Statements
Constants
* Fixed Values such as numbers,letters, and strings, are called "Constants" because their value does not change
* Numeric Constants are as you expect
* String Constants use single quote(') or double quote (")
eg:>>> print (123)
output is 123
>>> print(98.6)
output is 98.6

Variables
* A Variable is a named place in the memory where a programmer can store data and later retrieve the data using the Variable "name"
* Programmers get to choose the names of the variables
* You can change the contents of a variable in a later statement
x=12.2    o/p: x 12.2
y=14      o/p: y 14
the assignment statement as having an arrow to it so this is not saying X for all time is the same as 12.2 wt it's saying is take 12 point to find a place find some memory in your computer there master python give it a label X we get to choose the X that's the variable part we choose it right and then stick 12 in it and then the same is true for 14 we will find in there another spot name it y and then put a 14 in there so think of this as an arrow every time you see that equality the assignment in an assignment statement now these variables hold one value so now if we have these three statements these two and then the third one executes it says put 100 into x bt that wipes out the old value of twelve point two and it rewrite it with a hunt with a hundred and so we can change the variables that's another reason that we call them variable     
x=12.2     o/p: x 100 
y=14       o/p: y 14
x=100

Python Variable Name Rules
* Must start with a letter or underscore _
* Must consist of letters,numbers, and underscores
* Case Sensitive
 Good:  spam   eggs  spam23    _speed
 Bad:   23spam   #sign  var.12
 Different: spam   spam   SPAM
There are some names now some rules for making variable names you can start with a letter or an underscore we tend not to as normal programmers use underscore we tend to reserve those four variables that we use to communicae with python itself so we're making up a variable we tend not to use underscore as a pre first character you can have letters and numbers and underscores after the first character and their case sensitive it is really a bad idea to use causes the only differentiator so in this case spam eggs spam23 and underscore meter alt or legit we would probably not use this one unless we were actually doing it because python told us to use that variable23 spam starts with the number pound sign starts and dot is not a legitimate variable character and spam capital spam and all cat spam are different but this is not something that you want to sort of  depend on too much so that's just the rule names we tend to start them with a letter and then use letters numbers and underscores               
underscores other than the first character are generally pretty common and you'll see those used a lot

Mnemonic Variable Names
Since we programmers are given a choice in how we choose our variable names, there is a bit of "best practice"
We name variables to help us remember what we intend to store in them("mnemonic"="memory aid")
This can confuse beginning students because well-named variables often "sound" so good that they must be keywords
We're choosing variable names one of the things about variables we get to choose the name we get to choose the name X choose the name Y and so sometimes we like them short but sometimes we want them descriptive and the notion that of making variables descriptive is often confusing to beginning students sometimes it's really helpful to if you're gonna have a line of text and you main the variable line that's great because the next person reading your program says that must be the line of text where is it also can't become misleading that line the name of a variable somehow has meaning so sometimes we'll having seen variables & plural variables like friend and friends like his is plural does python know about singular and plural & the answer is no so sometimes we pick variables that make no sense sometimes we pick variables that make a lot of sense this is just something that you as a beginning programmer are going to have to understand that we can pick anything we want & you'll see i'll try to call attention this in the first few lectures as we go through so 
here's a bit of code with an assignment statement - assignment statements of multiplication & a print statement & you can say what is this doing now python is perfectly happy with this code because it assigns it in there you have said please go give this as a label & then we assign two variables &  then we're carefully pulling these two variables back out multiplying them together & sticking them into yet another variable & then printing that variable out that seems like you know we can figure out what it is you just have to look really careful & a single character mistake & python is going to be you know pretty unhappy okay so that's one way to write this program.                           
	x1q3z9ocd = 35.0
	x1q3z9afd = 12.50
	x1q3p9afd = x1q3z9ocd + x1q3z9afd
	print(x1q3p9afd)
it's hard though because you could any of those characters or long variables & they're random stuff it's not very friendly to anyone who might read your program now below looks a little friendly it's the same program because python just wants a correspondence you picked a you picked B & you pick C & it's really much easier for us to see what's going on & so this is in a way going from here to here is much friendlier but we can be even friendlier if we pick mnemonic variable names so this is below is not mnemonic this is short and convenient the above is long & inconvenient python is happy with any of these 
	a = 35.0
	b = 12.50
	c = a * b
	print(c)
here on the other hand is another version of the exact same program & now you think to yourself
	hours = 35.0
	rate  = 12.50
	pay   = hours * rate
	print(pay)
Whoever wrote this program is much is helping us greatly understand what's going on & that's good choosing variable names a python again all three of these are the same two python using variable names in a way that help your reader understand what's going on is a great thing the problem is the danger is if you read this & you think that somehow python understands payroll that if you name a variable hours that python knows what hours means the answer is python really doesn't care what you name the variable as long as what you name it you use it right & so you got to be careful & so you'll see.

Sentences or Lines
	X = 2      Assignment statement
	X = X + 2  Assignment with expression
	print(X)   Print statement
  Variable      Operator     Constant     Reserved Word
  
	Assignment Statements
We assign a value to a variable using the assignment statement (=)
An assignment statement consists of an expression on the right-hand side and a variable to store the result
x = 3.9 * x * ( 1 - x)	
An assignment statement you have to really get it your head around the notion that it has this arrow nature and that it valuates this entire right hand side before we change the left-hand side & so you can think of this sort of as at time step 1 it does this and then a time step 2 it does the copy and that's how you can have something like X on both sides of assignment statement
so if for example we have X and X has 0.6 in it X has 0.6 in it what happens is that at first it sort of ignores this part right here and evaluates the expression so it pulls 0.6 everywhere X appears it pulls 0.6 out starts running these calculations and then it has the new value after all the calculations are done then and only then is it going to put that back into X and so it sort of takes that and puts it back into X and then wipes out the old value at this point this has all been taken care of and it's been reduced down to the zero point nine three and so that is what's put in as the new value                       
		X  0.6
 x = 3.9 * x * ( 1 - x )
A variable is a memory location used to store a value(0.6)
The right side is an expression.Once the expression is evaluated, the result is placed in (assigned to)x.
A variable is a memory location used to store a value. The value stored in a variable can be updated by replacing the old value (0.6) with a new value (0.93).
The right side is an expression.Once the expression is evaluated, the result is placed in (assigned to) the variable on the left side (i.e., X). 
 
