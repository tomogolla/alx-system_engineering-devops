## Shell variables expansions

Bash scripting involving variable declaration, shell expansions and more.

---

0. (\<o>) Create a script that creates an alias.
   _file_: `./0-alias`

> - Name `ls`
> - Value: `rm *`

---

1. (Hello you) Create a script that prints `hello user`, where user is the current Linux user.
   _file_: `1-hello_you`

---

2. (The path to success is to take massive, determined action) Add `/action` to the PATH. `/action` should be the last directory the shell looks into when looking for a program.
   _file_: `./2-path`

---

3. (If the path be beautiful, let us not ask where it leads) Create a script that counts the number of directories in the `PATH`.
   _file_: `./3-paths`

---

4. (Global variables) Create a script that lists environment variables.
   _file_: `./4-global_variables`

---

5. (Local variables) Create a script that lists all local variables and environment variables, and functions.
   _file_: `./5-local_variables`

---

6. (Local variable) Create a script that creates a new local variable.
   _file_: `./6-create_local_variable`

> - Name: `BEST`
> - Value: `School`

---

7. (Global variable) Create a script that creates a new global variable.
   _file_: `./7-create_global_variable`

> - Name: `BEST`
> - Value: `School`

---

8. (Every addition to true knowledge is an addition to human power) Write a script that prints the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEDGE`, followed by a new line.
   _file_: `./8-true_knowledge`

---

9. (Divide and rule) Write a script that prints the result of `POWER` divided by `DIVIDE`, followed by a new line.
   _file_: `./9-divide_and_rule`

> - `POWER` and `DIVIDE` are environment variables

---

10. (Love is anterior to life, posterior to death, initial of creation, and the exponent of breath) Write a script that displays the result of `BREATH` to the power `LOVE`
    _file_: `./10-love_exponenent_breath`

> - `BREATH` and `LOVE` are environment variables
> - The script should display the result, followed by a new line

---

11. (There are 10 types of people in the world -- Those who understand binary, and those who don't) Write a script that converts a number from base 2 to base 10.
    _file_: `./11-binary_to_decimal`

> - The number in base 2 is stored in the environment variable `BINARY`
> - The script should display the number in base 10, followed by a new line

---

12. (Combination) Create a script that prints all possible combinations of two letters, except `oo`.
    _file_: `./12-combinations`

> - Letters are lower cases, from `a` to `z`
> - One combination per line
> - The output should be alpha ordered, starting with `aa`
> - Do not print `oo`
> - Your script file should contain maximum 64 characters

---

13. (Floats) Write a script that prints a number with two decimal places, followed by a new line. The number will be stored in the environment variable `NUM`.
    _file_: `./13-print_float`

---

14. (Decimal to Hexadecimal) Write a script that converts a number from base 10 to base 16.
    _file_: `./100-decimal_to_hexadecimal`

> - The number in base 10 is stored in the environment variable `DECIMAL`
> - The script should display the number in base 16, followed by a new line

---

15. (Everyone is a proponent of strong encryption) Write a script that encodes and decodes text using the rot13 encryption. Assume ASCII.
    _file_: `./101-rot13`

---

16. (The eggs of the brood need to be an odd number) Write a script that prints every odd line from the input, starting with the first line.
    _file_: `./102-odd`

---

17. ( I'm an instant star. Just add water and stir.) Write a shell script that adds the two numbers stored in the environment variables `WATER` and `STIR` and prints the result.
    _file_: `./102-odd`

> - `WATER` is in base `water`
> - `STIR` is in base `stir.`
> - The result should be in base `bestchol`

---
