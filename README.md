# zigzag justify

Among  the  four  basic  typographic  alignments–flush  left  (ragged  right),  flush  right(ragged left), justified, and centered[1]–the justified alignment delivers the highest com-prehension.  Justified alignment, however, has a shortcoming.  When reading a justifiedparagraph  with  many  lines,  sometimes  we  cannot  locate  the  next  line  correctly  andeither reread the same line or skip the subsequent line.  To address this shortcoming,this work introduces a new zigzag-style typographic alignment.  In this zigzag alignmentstyle we propose to maintain the justification but arrange the lines in a zigzag style (asin this paragraph).  We observed that our zigzag style of text alignment addresses the is-sue of locating the next line by subconsciously training a reader to look for a protrudingline on the left when returning the gaze from a protruding end of the previous line onthe right.  Similarly, the reader is also automatically trained to look for an indented linewhen returning the gaze from an indented end of the previous line on the right.  As such,the zigzag alignment style alleviates the issue of locating the next line.  This style couldbe immediately helpful to those who write longer journal articles and to the proposalwriters who submit many pages of plain text content 

## How to use it
* Include the `zigzag.sty` file in your project
* Import the package using `\usepackage(zigzag)`
* Apply the command using `\zigzagpar{paragraph.....}`
* The usage of this package can be seen in the test file `test.tex` for reference
