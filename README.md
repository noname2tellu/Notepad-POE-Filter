# Notepad-POE-Filter
A syntax highlight for Path of Exile loot filter.

Just download the file, make sure it is an .xml file, and then import it into Notepad++.

To import the file to Notepad++ : Open Notepad++ > Language > Define your language... > Import

----------------------------

Comments are green text.

BaseType items are blue with a light blue background.

Class items are dark yellow with a light yellow background.

Color related stuff (text / border / background) are orange.

Conditions are light blue.

Numbers are dark blue.

----------------------------

Some typos and incorrect capitalization of words have a red background. This does not work with words found after BaseType or Class (due to how the highlight is handled now).

-NOTE!-

If a word is colored incorrectly in a 'comment' block in the filter just place parenthesis around it! Hopefully this doesn't happen anymore on the latest version...

Quality -> (Quality)

Enjoy!

Only small problems:

BaseType and Class are delimiters now (instead of 'comments' in the old version). It seems to work the same way as before, but now comment lines are real comment lines (instead of colored normal text)! Having actual comment lines should prevent odd coloring in of text when you are trying to type a comment line out.

Regardless of what is after BaseType it gets the BaseType highlight and the same goes for Class (the coloring goes until the end of the line).
