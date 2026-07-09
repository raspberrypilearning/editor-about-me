## Calculating with input

All input is text, so it needs converting to numbers before it can be used.

### Converting text to numbers

If you try to do maths with data from `input()`, you will get an error.

You need to turn the text into a number first.  
You can use the `int()` function to do this.

```python filename="main.py" line_numbers="true" line_number_start="1" line_highlights="10-11"
print('Hi, I can code in Python!')

print('''
Here's a picture of a dog:
o____ 
 ||||
 ''')

born = input('What year were you born?')
born = int(born)
print(2050 - born)
```

Click **Run**, and type in your year of birth.

> [!TIP]
>
> Try commenting out this line so Python ignores it:
>
> `#born = int(born)`
>
> You'll see an error message. This means Python tried to do maths with text.
>
> Don't forget to uncomment it after you've seen the message.

## Now run your code

Click **Run**, type your birth year, and check that the program shows how old you will be in 2050.
