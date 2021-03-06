# Beautifully-Concise-Benchmarks

The Beautifully Consice Bencharks (BCB) rankings attempt to objectively compare various programming languages on beauty &amp; conciseness.


# Motivation
It is often said by programmers that some bit of code is cleaner or prettier than some other piece of code, but there hasn't been much study into objective comparisons of implementations of the same solution to a given problem in many programming languages. 

# The Solutions
Each folder within the solutions folder represents a solution to one particular problem written in manny different programming languages. For example, the "Print-Hello-World" folder contains examples of the best ranking solution for each language that prints "Hello World".

# Auto-Ranker
The Auto-Ranker is a command line tool that can scan any project directory or glob of files and output a BCB ranking.

_Note: The Auto-Ranker is currently just an idea and doesn't exist yet..._

# How BCB Rankings Are Calculated And Displayed
For the sake of overall objectiveness and in spirit of leaving it up the people to look at the data and make their own conslusions, there is no "overall score" since there are actually _three_ different measures of consisenes which all together give an idea of how succintly a program has been written. The three measurements are:


#### 1. Total Number of Characters
#### 2. Average Number of Characters Per Function
#### 3. Total Number of Functions


## BCB Ignores "Names" In Character Counts
Having good variable and functions names is arguably one of the most important things in writing good programs. Because good naming applies equally to every programming langues and because we didn't want all the examples to have single-digit names for everything just for the sake of optimization for this benchmark, the names of variables, functions, constants, interfaces, constants, etc. are not included in the character count. They are not included when they are defined, and they are lot included when they are referred to later. Thus, we are left with the character count that reflects what characters are just a result of the syntax of the lanugage. This does make calculating the BCB character counts more difficult, but with this policy we can have well-named constructs in our examples yet still fairly compare solutions in one language versus another.


# Shortcomings of BCB

## 1. BCB Favors Briefness At The Expense of Clarity.
One valid criticism of the BCB ranking system is that it assumes doing something with fewer characters is always better. This means that demerits are often given in terms of BCB rankings for creating local variables for organization, adding type annotations, and importing many smaller files. BCB does stand for Beautifully ___Consise___ Benchmarks, although many fans of TypeScript would argue that the loss of brevity is more than made up for by the adittional information in and overall increase in clarity of the overall computer program provided by these "extra characters" when compared to JavaScript.


## 2. BCB Ignores Runtime Efficiency
The BCB rankings are purely about concineness and ease of human readability. The most beautiful-looking language could run very slowly when compiled and deployed, and so giving up a few extra lines could be worth it here. It is often said and proven in benchmarks) that statically-typed languages perform better than dynamic ones, although the difference in practice is often minimal. It really depends on the specific use-case of the given program, and sometimes those few milliseconds really do make all the difference. In that case going with something "bare metal" can be worth the sacrifice in character count.


## 3. BCB Ignore Personal Preferences
For some, an extremely terse and functional style of programming just doesn't gel with their way of thinking. Perhaps you have been put into a situation where your team and fellow comrades prefer _X_ and despise that so-called "more beautiful" _Y_ language. Whichever language you choose to code in is totally up to you, and honestly we recommend that everyone try to code in _every_ language, not just those at the top of the rankings because that will _really_ expand your mind and make you incredibly versatile and wise.


As always, we are open and eager to hear suggestions for and criticisms of the BCB Ranking System!


# Contributors Welcome!
We'd love to hear what the community thinks about this idea and encourage opening Github issues and tweeting us about this project!
