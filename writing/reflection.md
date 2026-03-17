# CS101 Spring 2026 — Practice Midterm Reflection

Name: Mark Sutara
Date: 3/17/2026

After completing the practice test, please reflect on your experience by
answering the questions below. Replace each  with a thoughtful response
(a few sentences each). Your responses help you consolidate what you learned
and identify areas to review before the real midterm.

---

## 1. Self-Assessment

**Question:** How did you feel about your performance on the practice test?
Which topics felt most comfortable, and which ones felt most difficult?

**Your Answer:**

I felt pretty comfortable with everything.

---

## 2. Tricky Questions

**Question:** Identify one question you got wrong (or were unsure about).
Explain the concept being tested and describe why the correct answer is right.

**Your Answer:**

I was unsure of question 5 because I don't remember it ever being mentioned in class. I looked it up and got the right answer.

---

## 3. Loops and Iteration

**Question:** In your own words, explain the difference between `range(a, b, step)`
with a positive step versus a negative step. Give one original example of each.

**Your Answer:**

Positive counts forward, reverse counts backwards. range(1, 5 ,1) is 1-5, range (1, 5, -1) is 5-1.

---

## 4. Data Structures

**Question:** Python has lists, tuples, dictionaries, and sets. Describe one key
difference between a list and a tuple, and one key difference between a
dictionary and a set. When would you choose each?

**Your Answer:**

A list holds a set of data, a tuple holds only a pair. A dictonary has a key and a value, while sets only have values. I would use them depending if I had data that needed to be changed or not.

---

## 5. Functions

**Question:** What is a default parameter in a Python function? Write a short
example function that uses a default parameter, and explain what happens when
the caller omits that argument.

**Your Answer:**

def add(x=1, y=1):
    return x + y

Equals 2 by default unless the user specifies otherwise.

---

## 6. List Comprehensions

**Question:** List comprehensions can include an optional filter condition.
Rewrite the following traditional loop as a list comprehension:

```python
result = []
for n in range(1, 11):
    if n % 3 == 0:
        result.append(n * 2)
```

**Your Answer:**

values = n for n in range(1, 11) if n % 3 == 0
results.append(values * 2)

---

## 7. Operator Precedence

**Question:** Python evaluates `**` (exponentiation) right-to-left.
What is the value of `2 ** 2 ** 3`? Show your step-by-step reasoning.

**Your Answer:**

PEMDAS states 2 ** 2 must be first. So it would equal 64.

---

## 8. Classes 

**Question:** What are classes in Python programming? Explain why they are necessary in programming.

**Your Answer:**

Classes are ways to organize specific functions in order for the program to look cleaner and be more organized.

---

(Did you remember to add your name and date at the top of this document?)
