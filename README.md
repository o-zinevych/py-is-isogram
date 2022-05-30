# Is isogram

- Read [the guideline](https://github.com/mate-academy/py-task-guideline/blob/main/README.md) before start

An isogram is a word that has no repeating letters, consecutive or non-consecutive.

Inside `app/test_main.py`, write tests for a function `is_isogram` that takes a string word, that contains only letters, 
and checks whether this word is an isogram.

Notes:

- for this task, the empty string is an isogram;
- function should be case-insensitive (M and m are considered the same letter).

Examples:
```python
is_isogram('playgrounds') == true
is_isogram('look') == false
is_isogram('Adam') == false
is_isogram('') == true
```

Run `pytest app/` to check if function pass your tests.
Run `pytest tests/` to check if your tests cover all boundary conditions
and pass task tests.