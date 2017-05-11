# diff-between-python-javascript
Record the difference between python and javascript, during my learning.

## Basic
|                   | python                                       | javascript                                     |
|:----------------- |:-------------------------------------------- |:---------------------------------------------- |
| declare variable  | no need                                      | need let or const                              |
| comment           | # for single line, """ for multi lines       |                                                |
| boolean           | True                                         | true                                           |
| function          | def, :                                       | function, {}                                   |
| decimals          | "%.2f" % total                               |                                                |
| string            | str.lower()                                  | str.toLowerCase()                              |
| string            | str(num)                                     | num.toString()                                 |
| str joint('+')    | str can't joint num                          | can                                            |
| if only letters   | str.isalpha() => True                        |                                                |
|                   | dir(math) => list                            |                                                |
| type              | type(5) == int                               | typeof [1,2,3] == 'object'                     |
| print             | print 'a', 'b'                               |                                                |
| import            | from random import randint                   |                                                |

## Loop
|                   | python                                       | javascript                                     |
|:----------------- |:-------------------------------------------- |:---------------------------------------------- |
| if                | elif                                         | elseif                                         |
| while             | while: break else:                           | while                                          |
|                   | for item in list: break else:                |                                                |
|                   |                                              |                                                |

## List/ Array
|                   | python                                       | javascript                                   |
|:----------------- |:-------------------------------------------- |:-------------------------------------------- |
| length            | len(list)                                    | arr.length                                   |
| add item          | list.append(item)                            | arr.push(item)                               |
| index item        | list.index(item)                             | arr.indexOf(item)                            |
| insert item       | list.insert(index, item)                     | arr.splice(index, item)                      |
| del item          | list.remove(item)/del(list[i])/list.pop(i)   | arr.filter(function(a){return a != item}     |
| traversing        | for item in list:/for i in range(len(list)): | for(var i = 0; i < arr.length; i++)          |
|                   | for index, item in enumerate(list):          |                                              |
|                   | for a, b in zip(list_a, list_b):             |                                              |
| get num arr       | range(3,5)                                   | const arr = [3,4];                           |
| concat            | [1,2] + [3,4] => [1,2,3,4]                   | arr1.concat(arr2)                            |
|                   | ["O"] * 3 => ["O","O","O"]                   |                                              |
| join              | "---".join(list)                             | arr.join("---")                              |
| include           | 1 in [1,2] / 1 not in [1,2]                  | indexOf                                      |
| sum               | sum(list)                                    | arr.reduce(function(){}                      |
| sort              | list.sort() / sorted([11,2,55])              | arr.sort()                                   |
| reverse           | list(reversed[11,2,55])                      | arr.reverse()                                |
| filter            | filter(lambda x: x % 3 == 0, list)           | arr.filter(function() {})                    |
|                   |                                              |                                              |

## Dictionary/ Object
|                   | python                                       | javascript                                     |
|:----------------- |:-------------------------------------------- |:---------------------------------------------- |
| length            | len(dic)                                     |                                                |
| del item          | del dic[key]                                 |                                                |
| traversing        | for key in dic: *disordered                  | for key in obj: *disordered                    |
|                   | dic.items() => arr(k, v) *disordered         |                                                |
|                   | obj.keys() => arr *disordered                |                                                |
|                   | obj.values() => arr *disordered              |                                                |
| include           | a in {'a':1,'b':2} / a not in {'a':1,'b':2}  |                                                |

## List comprehension
`list = [i for i in range(51) if i % 2 == 0]`

## Functional programming(Lambda)
`filter(lambda x: x % 3 == 0, list)`

## Bitwise Operators
`0b100 => 4` `bin(4) => 0b100` `int("100",2) => 4`
```
# Left Bit Shift (<<)  
0b000001 << 2 == 0b000100 (1 << 2 = 4)
0b000101 << 3 == 0b101000 (5 << 3 = 40)       

# Right Bit Shift (>>)
0b0010100 >> 3 == 0b000010 (20 >> 3 = 2)
0b0000010 >> 2 == 0b000000 (2 >> 2 = 0) 

    a:  00101010  42
    b:  00001111  15       
================
a & b:  00001010  10
 
    a:  00101010  42
    b:  00001111  15       
================
a | b:  00101111  47

    a:  00101010  42
    b:  00001111  15       
================
a ^ b:  00100101  37

~42 = -43
```

## Class
```
class Animal(object):
    pass
```
