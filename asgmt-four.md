# Assignment 4

> Programming Design 2023

## 01. Define a function `square_args()` which takes flexible integers and returns their squared values in a `list`.

```python
def square_args(*args) -> list:
    """
    >>> square_args(0)
    [0]
    >>> square_args(0, 1)
    [0, 1]
    >>> square_args(0, 1, 2)
    [0, 1, 4]
    >>> square_args(0, 1, 2, 3)
    [0, 1, 4, 9]
    >>> square_args(0, 1, 2, 3, 4)
    [0, 1, 4, 9, 16]
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 02. Define a function `abs_args()` which takes flexible integers and returns their absolute values in a `list`.

```python
def abs_args(*args) -> list:
    """
    >>> abs_args(0)
    [0]
    >>> abs_args(0, -1)
    [0, 1]
    >>> abs_args(0, -1, -2)
    [0, 1, 2]
    >>> abs_args(0, -1, -2, -3)
    [0, 1, 2, 3]
    >>> abs_args(0, -1, -2, -3, -4)
    [0, 1, 2, 3, 4]
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 03. Define a function `uppercase_keys_from_kwargs()` which takes flexible key-value pairs and returns keys in uppercased form with a `list`.

```python
def uppercase_keys_from_kwargs(**kwargs) -> list:
    """
    >>> uppercase_keys_from_kwargs(twn='Taiwan')
    ['TWN']
    >>> uppercase_keys_from_kwargs(twn='Taiwan', jpn='Japan')
    ['TWN', 'JPN']
    >>> uppercase_keys_from_kwargs(twn='Taiwan', jpn='Japan', ltu="Lithuania")
    ['TWN', 'JPN', 'LTU']
    >>> uppercase_keys_from_kwargs(twn='Taiwan', jpn='Japan', ltu="Lithuania", svn='Slovenia')
    ['TWN', 'JPN', 'LTU', 'SVN']
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 04. Define a function `square_negatives_from_args()` which takes flexible integers and returns the square of negatives in a `list`.

```python
def square_negatives_from_args(*args) -> list:
    """
    >>> square_negatives_from_args(-3, -2, -1, 0, 1, 2, 3)
    [9, 4, 1]
    >>> square_negatives_from_args(-3, -2, -1, 0, 1, 2, 3, '4', '5')
    [9, 4, 1]
    >>> square_negatives_from_args(-3, -2, -1, False, True, 2, 3, '4', '5')
    [9, 4, 1]
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 05. Define a function `reverse_key_value_from_kwargs()` which takes flexible key-value pairs and returns a `dict` with reversed key-value pairs.

```python
def reverse_keys_values_from_kwargs(**kwargs) -> dict:
    """
    >>> reverse_keys_values_from_kwargs(twn='Taiwan')
    {'Taiwan': 'twn'}
    >>> reverse_keys_values_from_kwargs(twn='Taiwan', jpn='Japan')
    {'Taiwan': 'twn', 'Japan': 'jpn'}
    >>> reverse_keys_values_from_kwargs(twn='Taiwan', jpn='Japan', ltu="Lithuania")
    {'Taiwan': 'twn', 'Japan': 'jpn', 'Lithuania': 'ltu'}
    >>> reverse_keys_values_from_kwargs(twn='Taiwan', jpn='Japan', ltu="Lithuania", svn='Slovenia')
    {'Taiwan': 'twn', 'Japan': 'jpn', 'Lithuania': 'ltu', 'Slovenia': 'svn'}
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 06. Define a class `Pet` which instantiates objects with 1 attribute `species` and 1 method `make_sound()`.

```python
class Pet:
    """
    >>> dog = Pet('Dog', 'Bark')
    >>> type(dog)
    '__main__.Pet'
    >>> dog.species
    'Dog'
    >>> dog.make_sound()
    'Bark'
    >>> kitty = Pet('Cat', 'Meow')
    >>> type(kitty)
    '__main__.Pet'
    >>> kitty.species
    'Cat'
    >>> kitty.make_sound()
    'Meow'
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 07. Define a class `Hogwarts` which instantiates objects with 3 attributes `location`, `founders`, and `houses`.

```python
class Hogwarts:
    """
    >>> hogwarts = Hogwarts()
    >>> type(hogwarts)
    '__main__.Hogwarts'
    >>> hogwarts.location
    'Scotland'
    >>> hogwarts.founders
    ['Godric Gryffindor', 'Salazar Slytherin', 'Rowena Ravenclaw', 'Helga Hufflepuff']
    >>> hogwarts.houses
    ['Gryffindor', 'Slytherin', 'Ravenclaw', 'Hufflepuff']
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 08. Define a class `StrCase` which instantiates objects with 3 methods `upper_case()`, `lower_case()`, and `swap_case()`.

```python
class StrCase:
    """
    >>> luke = StrCase('Luke Skywalker')
    >>> type(luke)
    '__main__.StrCase'
    >>> luke.upper_case()
    'LUKE SKYWALKER'
    >>> luke.lower_case()
    'luke skywalker'
    >>> luke.swap_case()
    'lUKE sKYWALKER'
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 09. Define a class `MethodCalculator` which instantiates objects with 4 methods `add()`, `substract()`, `multiply()`, and `divide()`.

```python
class MethodCalculator:
    """
    >>> method_calculator = MethodCalculator(5, 6)
    >>> type(method_calculator)
    '__main__.MethodCalculator'
    >>> method_calculator.add()
    11
    >>> method_calculator.subtract()
    -1
    >>> method_calculator.multiply()
    30
    >>> method_calculator.divide()
    0.8333333333333334
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 10. Define a class `SymbolicCalculator` which instantiates objects with 1 method `calculate()`.

```python
class SymbolicCalculator:
    """
    >>> symbolic_calculator = SymbolicCalculator(5, 6)
    >>> type(symbolic_calculator)
    '__main__.SymbolicCalculator'
    >>> symbolic_calculator.calculate('+')
    11
    >>> symbolic_calculator.calculate('-')
    -1
    >>> symbolic_calculator.calculate('*')
    30
    >>> symbolic_calculator.calculate('/')
    0.8333333333333334
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```