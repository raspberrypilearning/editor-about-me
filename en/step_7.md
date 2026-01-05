<h2 class="c-project-heading--task">Calculating with input</h2>
--- task ---
All input is text, so it needs converting to numbers before it can be used.
--- /task ---

<h2 class="c-project-heading--explainer">Converting numbers to text</h2>

If you try and do calculations with data from `input()` then you will get an error. You need to convert input into numbers first. You can use the `int()` function to do this.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 9
---
print('Hi, I can code in Python!')

print('''
here's a picture of a dog:
o____ 
 ||||
 ''')

born = input('What year were you born?')
print(born)
''')

born = input('What year were you born?')
born = int(born)
print(2050 - born)
--- /code ---
</div>

Click **Run**, and type in your year of birth. It should then print out how old you will be in 2050.

<div class="c-project-callout c-project-callout--tip">

### Tip

Try removing the line `born = int(born)`. The program will give you an error message. If you see this message in the future, you will know it is probably because you forgot to convert some input.

</div>