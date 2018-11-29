# pull_text
I am not a coder and am wondering if anyone knows a solution to this or could create one. 
any and all help is appreciated.<br>

I need a program that can scan text and find a section of text between two divs, then take the selected text and write it into a seperate file, name the file, and save it in a designated folder.

There are 14,300 pages of html code that need editing, similar to the code below.:point_down:<br><br> example below image.
<h2>Figure 1</h2>

![code example](https://github.com/luvlylavnder/pull_text/blob/master/code%20_example.png)

<h2>I need a program or a bot that can do the following.....</h2><br>

<b>Look in folder =</b> (<i>/path/to/example folder</i>)<br> 
<b>Recognize files in folder =</b> (<i>example files - html.1, html.2, html.3</i>)<br>
<b>Perform task on all files in folder.</b>

<b>Task - Find Text Between =</b> (<i>```<div id="topheading"></i></b> and <b><i><div class="vheading2">```</i>)<br>
<b>Write new found text in new file, rename new file, save new file in new folder</b><br> 
<b><i>Program should rename file according to the title tag</i></b><br>
<b><i>Program should reconize either the word (<b>Hebew</b>) or (<b>Greek</b>) and the (<b>number</b>) in the title</i></b>:point_down:<br><br>
<h2>Figure 2</h2>

![title hebrew](https://github.com/luvlylavnder/pull_text/blob/master/title_hebrew_example.png)
 
<h2>Figure 3</h2>

![title greek](https://github.com/luvlylavnder/pull_text/blob/master/title_greek_example.png)
 
<i>If the title contains the word <i>Hebrew</i> and a <i>number</i> the program should rename the new file (<b>H</b>) and the (<b>number</b>)</i><br><br>
<i>If the title contains the word <i>Greek</i> and a <i>number</i> the program should rename the new file (<b>G</b>) and the (<b>number</b>)</i><br>
 <br>
<i>The number in the title tag should always be formated as a four digit number.<i>  The number 1 should become 0001, the number 10 should become 0010, the number 100 should become 0100, the number 1000 should stay as it is.</i>
 
<h2>Example 1</h2>
<b><i>From Figure 2</i></b><br>

<i>if the program recognizes Hebrew 350 in the title tag it should create a new file named <b>H0350.html</b>, Then write the text selected from inbetween the two divs,(shown in <b>Figure 1</b> ), and then save the newly created file in the specified folder.</i>

<h2>Example 2</h2>
<b><i>From Figure 3</i></b><br>

<i>if the program recognizes Greek 1 in the title tag it should create a new file named <b>G0001.html</b>, Then write the text selected from inbetween the two divs,(shown in <b>Figure 1</b> ), and then save the newly created file in the specified folder.</i>

