# freshsonnets
A mashup between Will Smith's raps and Will Shakespeare's sonnets

Code is in the Python notebook.

Steps: 
Grab the rap lyrics. Grab the sonnets from Gutenberg.

The source files were cleaned by removing any headers, empty lines, and regex replacement. Of note to remove the following:
<pre>
In sonnetall2021.txt:
\u2019
\u2013
empty newlines

In willsmith.txt :
\d?EmbedShare URLCopyEmbedCopy 
Chorus\s\d\d?:\n
</pre>

Then select a few lines from each source and put them into sonnet form. It's readable but not perfect.

Other than that, it was interesting learning to use the lyrics api, and also FPDF to format a pdf.

I wish that I could have done something like replacing interesting words from one to the other-- maybe next year!

Python Notebook: 
https://github.com/anjchang/freshsonnets/blob/main/FreshPrinceShakespeare2021.ipynb

Example Finished Output:
https://github.com/anjchang/freshsonnets/blob/main/freshsonnets.pdf

---
Nanogenmo Submission:
https://github.com/NaNoGenMo/2021/issues/86
