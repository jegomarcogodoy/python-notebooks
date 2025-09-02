2ECE-A | GODOY, JEGO MARCO E. | EXPERIMENT 1

🐍 Python Mini Challenges: Fun with Strings & Lists

📌 Overview:

This experiment consists of a set of simple Python problems for beginners that have been answered in a Jupyter Notebook. It is intended to assist you in practicing basic programming ideas, including list unpacking, string manipulation, and basic algorithms.

🎯 Focus of this Experiment:

-Strengthening Python fundamentals.

-Practicing problem-solving with code.

-Writing solutions that are simple, readable, and reusable.

This experiment focuses on three(3) problems:

1. ALPHABET SOUP PROBLEM: Create a function that takes a string and returns a string with its letters
in alphabetical order.

2. EMOTICON PROBLEM: Create a function that changes specific words into emoticons. Given a sentence
as a string, replace the words smile, grin, sad, and mad with their corresponding emoticon

3. UNPACKING LIST PROBLEM: Unpack the list writeyourcodehere into three variables, being first,
middle, and last, with middle being everything in between the first and last element. Then print all three
variables.

SOLUTION FOR THE PROBLEM:

1.  CODE:
   def alphabet_soup(word):
    return ''.join(sorted(word))
print(alphabet_soup("hello"))
print(alphabet_soup("hacker"))

EXPLANATION:
The code takes a word and puts its letters in the correct order.
The word "hello" becomes "ehllo" after the letters are sorted, for instance.
The word "hacker" also becomes "acehkr" when the letters are switched around.

2. CODE:
s1 = "You make me smile and grin"
s1
'You make me smile and grin'
s2 = s1.replace("smile",":)")
s2.replace("grin",":D")
'You make me :) and :D'
s3 = "You make me sad and mad at the same time"
s3
'You make me sad and mad at the same time'
s4 = s3.replace("sad", ":((")
s4.replace("mad", ">:(")
'You make me :(( and >:( at the same time'

EXPLANATION:
The code illustrates how to use the replace function to swap out particular words in a statement with emoticons. The first example substitutes ":)" for "smile" and ":D" for "grin" in the statement "You make me smile and grin," producing "You make me :) and :D." "You make me :(( and >:( at the same time" is the ultimate result of changing the statement "You make me sad and mad at the same time" in the second example by replacing "sad" with ":(( " and "mad" with ">:(". This demonstrates how replace can be used to change the meaning or style of text by replacing words with emoticons or symbols.

3. CODE:
writeyourcodehere = [1, 2, 3, 4, 5, 6]
writeyourcodehere
[1, 2, 3, 4, 5, 6]
writeyourcodehere = [1, 2, 3, 4, 5, 6]   

first = writeyourcodehere[0]
middle = writeyourcodehere[1:-1]
last = writeyourcodehere[-1]

print("first: " + str(first))
print("middle: " + str(middle))
print("last: " + str(last))
first: 1
middle: [2, 3, 4, 5]
last: 6

EXPLANATION:
The code demonstrates how to extract a list's first, middle, and last members. The variable writeyourcodehere is allocated the list [1, 2, 3, 4, 5, 6]. With indexing, writeyourcodehere[0] is used to access the first element, writeyourcodehere[1:-1] is used to take the middle elements, and writeyourcodehere[-1] is used to access the last element. The output's "first: 1", "middle: [2, 3, 4, 5]", and "last: 6" when printed make it evident how slicing and indexing operate in Python lists.

THANK YOU!
