# zigzag justify

Among  the  four  basic  typographic  alignments–flush  left  (ragged  right),  flush  right(ragged left), justified, and centered–the justified alignment delivers the highest comprehension.  Justified alignment, however, has a shortcoming.  When reading a justified paragraph  with  many  lines,  sometimes  we  cannot  locate  the  next  line  correctly  andeither reread the same line or skip the subsequent line.  To address this shortcoming, this work introduces a new zigzag-style typographic alignment.  In this zigzag alignment style we propose to maintain the justification but arrange the lines in a zigzag style (as in this paragraph).  We observed that our zigzag style of text alignment addresses the issue of locating the next line by subconsciously training a reader to look for a protruding line on the left when returning the gaze from a protruding end of the previous line on the right.  Similarly, the reader is also automatically trained to look for an indented line when returning the gaze from an indented end of the previous line on the right.  As such, the zigzag alignment style alleviates the issue of locating the next line.  This style could be immediately helpful to those who write longer journal articles and to the proposal writers who submit many pages of plain text content.

## How to use it
* Include the `zigzag.sty` file in your project
* Import the package using `\usepackage(zigzag)`
* Apply the command using `\zigzagpar{paragraph.....}`
* The usage of this package can be seen in the test file `test.tex` for reference

## Example Usage
The image shown here is the output of the `test.tex` file.

![ZigZag](https://github.com/ba-lab/zigzag-justify/blob/main/zigzag_paragraph.png)
