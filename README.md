# SimpleAnsweringQuestionSystem

##Input files:
Two files will be used by the algorithm: One which includes a text, and one containing questions.
While implementing the project, you can use the files provided. The (the_truman_show_script.txt) file is the text through which you will be searching for answers. 
The (questions.txt) file contains example questions

To which you must find answers from the text. Each question is on a newline with a question mark at the end.
During the evaluation of the submission, (the the_truman_show_script.txt) file will be used as the text, however, the given questions are exemplary questions and it will not be the file you are graded on. You can use them for test purposes since the actual questions which will be given to your algorithm will be very similar.

##Details:
A long text and a list of questions will be given as input to the program. 
For each question, an answer must be found in the text and printed to the screen. 
Most of the questions will have a single word answer. 
All questions asked will have an answer in the text, i.e. it is impossible that an output for a question is "No answer". 
An answer to a question will not span multiple sentences, all answers will be contained in a single sentence in the text. 
Since the program will be tested on questions which you will not know in advance, it may be helpful to parse the words into a general representation which we can easily use to perform a search. It may also be a good idea to eliminate stop words. You can use any text searching algorithm you would like. 
The pattern matching algorithm must be written by the programmer.

##Important Instructions:
When the program is executed, it will automatically generate an answer for each question in the questions.txt file using the the_truman_show_script.txt file as main text. It will NOT get any inputs.
The program should give an output to the console in the following format when executed:
1) {Question}
{Answer}
2) {Question}
{Answer}
