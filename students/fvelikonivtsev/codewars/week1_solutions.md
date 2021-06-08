# [1. Opposite Number](https://www.codewars.com/kata/56dec885c54a926dcd001095)

```python
def opposite(number):
    return - number
```

# [2. Even or Odd](https://www.codewars.com/kata/53da3dbb4a5168369a0000fe/train/python)

```python
def even_or_odd(number):
    return 'Even' if number % 2 == 0 else 'Odd'
```

# [3. Vowel count](https://www.codewars.com/kata/54ff3102c1bad923760001f3)

```python
def get_count(input_str):
    num_vowels = 0
    num_vowels += input_str.count('a')
    num_vowels += input_str.count('e')
    num_vowels += input_str.count('i')
    num_vowels += input_str.count('o')
    num_vowels += input_str.count('u')
    return num_vowels
```

# [4. Disemvowel Trolls](https://www.codewars.com/kata/52fba66badcd10859f00097e)

```python
def disemvowel(string_):
    vowels = ('aeiouAEIOU')
    for vowel in vowels:
        string_ = string_.replace(vowel, '')
    return string_

```

# [5. Get the Middle Character](https://www.codewars.com/kata/56747fd5cb988479af000028)

```python
def get_middle(s):
    middle = len(s) // 2
    if len(s) % 2 != 0:
        return s[middle]
    return s[middle - 1: middle + 1]
```

```Pyt
>>> s = 'mid' # => 3 // 2 = 1, middle = 1, length is even
>>> get_middle(s)
>>> 'i'
```

# [6. Get the Middle Character](https://www.codewars.com/kata/5863f97fb3a675d9a700003f/python)

```python
def sum_ppg(playerOne, playerTwo):
    ppg_1 = playerOne['ppg']
    ppg_2 = playerTwo['ppg']
    return ppg_1 + ppg_2
```



# Challenges

# [1. Who likes it?](https://www.codewars.com/kata/5266876b8f4bf2da9b000362)

```python
def likes(names):
    if len(names) < 2:
        return f'{names[0] if names else "no one"} likes this'
    if len(names) == 2:
        return f'{names[0]} and {names[1]} like this'
    if len(names) == 3:
        return f'{names[0]}, {names[1]} and {names[2]} like this'
    return f'{names[0]}, {names[1]} and {len(names) - 2} others like this'
```

# [2. Array.diff](https://www.codewars.com/kata/523f5d21c841566fde000009/python)

```pyth
def array_diff(a, b):
    different_values = set(a) - set(b)
    
    array = []
    for item in a:
        if item in different_values:
            array.append(item)
    return array
```

# [3. All Star Code Challenge #22](https://www.codewars.com/kata/5865cff66b5699883f0001aa)

```python
def to_time(seconds):
    hours = seconds // 3600
    return f'{hours} hour(s) and {(seconds - hours * 3600) // 60} minute(s)'
```

