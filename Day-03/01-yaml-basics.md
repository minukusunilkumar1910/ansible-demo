# Understanding YAML

YAML (YAML Ain't Markup Language) is a human-readable data serialization format that is commonly used for configuration files and data exchange between languages with different data structures.

## YAML Syntax

### Strings, Numbers and Booleans:

```
string: Hello, World!
number: 42
boolean: true
```

### List 

```
fruits:
  - Apple
  - Orange
  - Banana
```

### Dictionary 

```
person:
  name: John Doe
  age: 30
  city: New York
```

### List of dictionaries 

YAML allows nesting of lists and dictionaries to represent more complex data.

```
family:
  parents:
    - name: Jane
      age: 50
    - name: John
      age: 52
  children:
    - name: Jimmy
      age: 22
    - name: Jenny
      age: 20
```
### Practise All
```
---
name:'sunil'
age:21
working:false
---
Tasks:
 - coding
 - reading
 - watching

adress:
  street: '1234'
  city: 'newyork'
  state: 'california'
  country: 'USA' 

working:
  company:
    morning:
     - 'eat breakfast'
     - 'go to work' 
    evening:
     - 'go to gym'
     - 'eat dinner'
     - 'watch movie'
    night:
     - 'sleep'
     - 'read book'   
  home:
    morning:
     - 'wake up'
     - 'eat breakfast' 
    evening:
     - 'go to gym'
     - 'eat dinner'
    night:
     - 'sleep'
     - 'read book'
  weekend:
    morning:
     - 'wake up at 10am'  
