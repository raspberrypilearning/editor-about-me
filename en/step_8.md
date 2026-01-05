<h2 class="c-project-heading--task">Printing your future age</h2>
--- task ---
You can add your future age into a sentence.
--- /task ---

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

<div class="c-project-callout c-project-callout--debug">

### Debugging

Make sure that:
- Every quote `'` has a matching `'`
- Every bracket `(` has a `)`
- You have commas between the text and the number

</div>
