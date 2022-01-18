# Lab Assignment 02, Due on [Canvas](https://psu.instructure.com/) at Jan. 26 at 11:59pm
## Exploratory Data Analysis Using Classic Novels

**Background / Getting Started**:  The main objective of today's lab is to repeat the activities in Section 1.3 of the textbook and then duplicate them on a novel of your choosing.  You should maintain the existing analyses from Section 1.3 on the novels Huck Finn and Little Women, while adding your own anaylsis of the novel you have chosen.  To do this, you will need to combine code from three different Jupyter Notebooks.

I recommend starting with the Jupyter Notebook from [Section 1.3](https://inferentialthinking.com/chapters/01/3/Plotting_the_Classics.html), then copy-and-pasting code from Sections 1.3.1 and 1.3.2 as needed.  To do this, follow steps 1 through 6 from Lab #1, but in step 6 scroll to, then select, the notebook corresponding to [Section 1.3](https://inferentialthinking.com/chapters/01/3/Plotting_the_Classics.html), entitled "Plotting_the_Classics". 

I recommend that you also open the Jupyter notebooks from Section 1.3.1 ("Literary_Characters") and Section 1.3.2 ("Another_Kind_of_Character") in separate browser windows or tabs so that you can copy-and-paste code from those sections as needed.

Remember that you can execute the code inside any python-code window by typing "shift-Return" inside that window or clicking on the arrow on the left side of the window.   Additionally, you can add a box for code or a box for text using the "+ Code" and "+ Text" buttons near the top left.  

**Objective**:  You should repeat the analyses performed in [Section 1.3](https://inferentialthinking.com/chapters/01/3/Plotting_the_Classics.html) on the novels Huck Finn and Little Women, and duplicate these analyses on a third novel of your own choosing.  You should do this in a single Jupyter notebook, which you'll create using code found in three separate notebooks.  

**Your assignment** is as follows (Step 3 is optional; the rest are required):

1.	Visit the Project Gutenberg website and browse for third book to add to Huck Finn and Little Women.  You can choose any book you wish, as long as it has chapters and you can find a link to its text version.  As examples of the types of links (URLs) you should find, try browsing for Adventures of Huckleberry Finn and Little Women and find the links to the Plain Text UTF-8 files.  The URLs for these links are, respectively, https://www.gutenberg.org/files/76/76-0.txt and http://www.gutenberg.org/cache/epub/514/pg514.txt. 

2.	I recommend changing the code that creates the huck_finn_url and little_women_url objects so that it uses the above links instead of the links at www.inferentialthinking.com. Create a third object for your chosen book using the same ideas found in the Section 1.3 code.  Print a table showing the chapters in your chosen book, as in [Section 1.3](https://inferentialthinking.com/chapters/01/3/Plotting_the_Classics.html).  Keep in mind that you may have to change the capitalization of the word "CHAPTER," depending on how your chosen book begins new chapters.  Also, using the example of Huck Finn, be sure to modify your code if your book includes a Table of Contents that python interprets as multiple "CHAPTER"s. 

_Some of the books at Project Gutenberg don’t work very well with this assignment.  You might find that you need to switch books if, for example, the book you first choose doesn’t use a consistent text string (like “CHAPTER”) to separate the book into chapters. I also recommend using the “find” command on your browser to check whether the text string that separates the book into chapters is used inside any chapters, or before/after the main text of the novel.  This can help you figure out whether to drop any spurious chapters at the beginning or end, or even whether to choose a new novel altogether.

3.	_Step 3 is optional, for one extra point:_  Figure out how to eliminate all of the extra Project Gutenberg text that appears at the end of the final chapter.  Do this for not only your book but for Huck Finn and Little Women as well.  Make sure to add a text box that explains how you did this and provide some output that provides evidence that it worked.  

4.	Find 2 to 10 characters in your novel (or possibly just often-used words, if you think that will be more interesting), then produce a plot of the cumulative number of times each name/word appears per chapter.  Adapt the code from Section 1.3.1—that is, copy-paste relevant sections of that code into a code box you create in your own Jupyter notebook, then edit appropriately—to do this.  Write a summary, in a text box, that explains a little bit about what your plot appears to reveal about your book.  

5.	Create a table for your chosen book with two columns, the length (in characters) and number of periods for each chapter.  Adapt the code from Section 1.3.2 to do this.  Finally, create a scatterplot that graphs all three books' periods vs. characters, using a different color for each book, just like Section 1.3.2 does for the two books.  Add comments in a text box if you notice anything interesting!

When you've completed this assignment, you should select "Print" from the File menu, then somehow save to pdf using this option.  The pdf file that you create in this way is the file that you should upload to Canvas for grading.  
