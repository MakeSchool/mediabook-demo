---
title: 'Descriptive Names'
slug: 'variables-activity'
contentType: 'Assessment'
---

# Variable Tables

Let's practice an easy way of keeping track of variables and their values when we read more complicated code: variable tables.

A variable table includes the variable name and value at each line of code.

For this section of code:

```python
# Here are two variables that store data representing scores for a video game
my_score = 30
high_score = 60

#let's use variable reassignment to update the scores!
my_score = 31
high_score = 99
high_score = my_score
```

The variable table would look like this:

| Line # | Variable   | Value |
| ------ | ---------- | ----- |
| 2      | my_score   | 30    |
| 3      | high_score | 60    |
| 6      | my_score   | 31    |
| 7      | my_score   | 99    |
| 8      | high_score | 99    |

Let's look at the table entry for line 8: can you explain in your own words why the value in the table is 99?

[action]
Candy break! Draw your own variable table by walking through each line of the following code.

```python
# Let's count some candy bars
number_of_kit_kats = 20
number_of_skittles = 70
number_of_hi_chews = 15

number_of_kit_kats = 88
number_of_skittles = number_of_kit_kats
number_of_kit_kats = number_of_hi_chews
number_of_hi_chews = number_of_skittles
```

# Check Your Understanding

<MultipleChoice prompt="What is the value of `number_of_kitkats` when the program finishes?" choices={[ "20", "70", "15", "88" ]} correctIndex={2} />

<MultipleChoice prompt={"What is the value of `number_of_kitkats` when the program finishes?"} choices={[ "20", "70", "15", "88" ]} correctIndex={2} explanation={"The value of `number_of_kitkats` is 15. Let's trace back through the code to find that answer. The value of `number_of_kitkats` is assigned to the value of `number_of_hi_chews` in line 7. `number_of_hi_chews` at that line is 15, because it was assigned that value in line 4."} />

