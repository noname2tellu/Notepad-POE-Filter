# Notepad-POE-Filter
A syntax highlight for Path of Exile loot filter.

Just download the file, make sure it is an .xml file, and then import it into Notepad++.

To import the file to Notepad++ : Open Notepad++ > Language > Define your language... > Import

----------------------------

Comments are green text.

BaseType items are blue with a light blue background.

Class items are dark yellow with a light yellow background.

Color related stuff (text / border / background) are orange.

Conditions are blue text.

----------------------------

Some typos and incorrect capitalization of words have a red background. This does not work with words found after BaseType or Class (due to how the highlight is handled now).

If a word receives green coloring (like a comment) then the word was not recognized.

-NOTE!-
If a word is colored incorrectly in a 'comment' block in the filter just place parenthesis around it!
Quality -> (Quality)

Enjoy!

Only small problems:

The way the highlight is handled is a little 'hackish' in a way.

BaseType and Class are considered 'comments' according to the rules of the syntax highlighting (that is why they highlight their entire line no matter what is in them) which means the syntax highlight stuff doesn't mess with stuff after them (old filter could highlight some incorrect spelled basetypes and classes).

So regardless of what is after BaseType it gets the BaseType highlight and the same goes for Class.

To make it appear that comments in the filter (lines that start with #) are 'comments' the default style is just green text.
