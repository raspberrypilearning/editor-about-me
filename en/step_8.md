<h2 class="c-project-heading--task">Printing your future age</h2>

You can add your future age into a sentence.

<h2 class="c-project-heading--explainer">Storing and printing your age</h2>

Instead of printing your future age straight away, you can store it and then use it in a sentence.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 9
line_highlights: 11-12
---
born = input('What year were you born?')
born = int(born)
age = 2050 - born
print('In the year 2050 you will be', age, 'years old!')
--- /code ---
</div>

Click *Run*, and type in your year of birth.

### Debugging

<div class="c-project-callout c-project-callout--debug">

Make suropening quote `'` has a matching closing quote `'`
- Every bracket `(` has a `)`
- You have commas between the text and the number

</div>

## Now run your code

Click *Run*, type your birth year, and check that the program prints a sentence telling you how old you will be in 2050.
