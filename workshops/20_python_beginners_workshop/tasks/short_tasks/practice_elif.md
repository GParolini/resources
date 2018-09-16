# Exercise 3: Conditions

Imagine that you are a teacher in school and you would like to automatize the calculation of grades.

### Instructions:

1. Create a new variable `student_points` and give it a number between `100` and `0`.
2. Write first `if` condition that will say `student_points > 90`. If the condition is `True`, this will print `A`.
3. The second condition will start with the new word `elif` (= else if). This condition will say `student_points >= 80 and student_points <= 90`. If the condition is `True`, this will print `B`. Ask coaches for a help.
4. And write `else` condition at the end that will print `C`.

**Note**: do not forget the 4 spaces after semicolon `:`, otherwise you will get `IndentationError`.

### Output:

**Example:** The student Nicole got 82 point in the school test.

You can expect this result:

~~~Python
B
~~~

### Optional:

You can build your program with all grades according to this table:

- 90 or higher should get an "A"
- 80 - 89 should get a "B"
- 70 - 79 should get a "C"
- 65 - 69 should get a "D"
- Anything below a 65 should receive an "F"