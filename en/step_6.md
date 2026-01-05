<h2 class="c-project-heading--task">Asking for data</h2>
--- task ---
Python can ask for data, store it, and then use it.
--- /task ---

<h2 class="c-project-heading--explainer"><code>input()</code></h2>

The program can ask you what year you were born using the `input()` function.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 9-10
---
print('Hi, I can code in Python!')

print('''
here's a picture of a dog:
o____ 
 ||||
 ''')

born = input('What year were you born?')
print(born)
--- /code ---
</div>

Click *Run*, and type in your year of birth.  
The program will then show what you typed.
