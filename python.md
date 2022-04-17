## Variables:

- can change as you code
- cant use special letters
- can't start with a number

```python
a = 1
print(a)  # 1
a = 2
print(a)  # 2
```

### Constants

- good habit to have variables in CAPITALS to distinguish them from variables
    - ie `LIKETHIS`
- to print, we must add “constant” in front
    - ie. print(constant.`LIKETHIS`)

## Lists
* Use [ ] to make enclose list ie a = [1,2,3,4,5]
* Can also use [ ] to select for certain data. Always stars from 0. So a[2] would print out 3 
* Remember variables can be replaced at any point: 
    * If a[2]=10; print(a) — output → [1,2,10,4,5] 

## Tuple 

* Doesn't change 
    * immutable
* Could be lists in pairs, 3s, etc

## Operations: 

* +, -, /, *, // (float, division without the remainder), % (module, only gives remainder), **(root) 
* Order: ( ), exp/roots, x or /, + or - 

## Boolean
* True or False 

* Use == to see if something is equal to something else 
    * Useful in _if_ statements 
* != is the fxn for not equal 

## If statements: 

* Must have the block of code indented (4 spaces in) 
* You can put if statements like below: 

```python
var = 5
if var: 
    <Code>
```
*This will run the code if the variable exists (can be a pos or neg number, just cant be zero) 

* zero falsey
* [List of falsey values](https://stackoverflow.com/a/39984051)


* Try/except 
* This will try to run the code and if it doesnt, it will spit out the except code without stopping the program. Must always have an “except” block with a “try” block  
    * You can put pass under “except” and it will do nothing/dont worry about it and ignore the error 

## Strings

* Can do math with strings: 
    * Add: will add the 2 strings together without any spaces 
    * Multiply: will add that string the amount of times you multiplied 
        * Ie this*5 = thisthisthisthisthis
* 