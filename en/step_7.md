<h2 class="c-project-heading--task">Calculating with input</h2>
--- task ---
All input is text, so it needs converting to numbers before it can be used.
--- /task ---

<h2 class="c-project-heading--explainer">Converting text to numbers</h2>

If you try to do maths with data from `input()`, you will get an error.

You need to turn the text into a number first.  
You can use the `int()` function to do this.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 10-11
---
print('Hi, I can code in Python!')

print('''
here's a picture of a dog:
o____ 
 ||||
 ''')

born = input('What year were you born?')
born = int(born)
print(2050 - born)
--- /code ---
</div>

Click *Run*, and type in your year of birth.

<div class="c-project-callout c-project-callout--tip">

### Tip

Try removing this line:

`born = int(born)`

If you see an error message, it means Python tried to do maths with text.

</div>
