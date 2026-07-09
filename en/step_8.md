## Printing your future age

You can add your future age into a sentence.

Instead of printing your future age straight away, you can store it and then use it in a sentence.

```python filename="main.py" line_numbers="true" line_number_start="9" line_highlights="11-12"
born = input('What year were you born?')
born = int(born)
age = 2050 - born
print('In the year 2050 you will be', age, 'years old!')
```

Click **Run**, and type in your year of birth.

> [!DEBUG]
>
> Make sure the opening quote `'` has a matching closing quote `'` and that:
> - Every bracket `(` has a `)`
> - You have commas between the text and the number

## Now run your code

Click **Run**, type your birth year, and check that the program prints a sentence telling you how old you will be in 2050.
