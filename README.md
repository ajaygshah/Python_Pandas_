# Python_Pandas_
How do we collapse columns?

Lot of times, there is a need to collapse columns. Especially for examinations,
we need ot figure out the MCQ choices and figure out which one has been marked.

Assumptions:
1) For each question, there are going to be four options.
2) The column names are in a range. For example, if there are 10 questions
with 4 options each. There are 40 columns.

df.columns = list(range(0,40))


There are three possibilities:
1) Student has marked only one of the choices (this is straight-forward)
2) Student has marked none of the choices
3) Student has marked more than one of the choices.

The objective is to come up with different solutions and find out which one
would be the most effective. While we find different solutions, there are 
scenarios that may come up and we need to account for them.
