# genExam Source Code
## The basic idea
### Generation of Random test

Let us say that we have 120 students in the classroom. At a distance learning mode, we aim to give 120 students different take-home exam papers so that any two exams are not the same. This is where the genExam can help. If you have a set of questions, let us say 10 questions, and you need to make exam papers consisting of 3 questions from this set of 10. The total number of sets that can be created is 120 (10C3). Now, if you have 120 students, no two students will have the same paper. This can be easily done by genExam by just one line of command. If we put a little more effort and make 15 questions, the total number of 3 questions sets generated will be 455. That's it, now, even the probability of any two students getting even two same questions is less. Another example is creating 20 questions, and creating papers of 5 questions will result in 15504 papers.

However, there is another question: what if we want to have questions from different chapters, and only one question from each chapter should be there. No problem, we can set any defined rules initially by modifying certain sections of the source code and the code will make sure that exam papers are generated according to the rules you have set.


### How does it work!

Initially, we need to feed separate word file for questions, cover paper, end page. To generate all possible combinations, one needs to specify how many questions each paper should have. In case, additional rules are to be applied; the source code can be changed easily. A few examples for exam papers with the user-defined rules are given.

## Running the code

First intsall, docxxompose from pip
The code can be run on python by typing the command:
> python genExam.py

## Authors

### In case of any further information on the code or the use of it, please contact us at
- Swarit Dwivedi (dwivediswarit@gmail.com)
- Akshat Tanksale (Akshat.Tanksale@monash.edu)
