# diff-between-python-javascript
Record the difference between python and javascript, during my learning.

|                   | python                                       | javascript                                     |
|:----------------- |:-------------------------------------------- |:---------------------------------------------- |
| declare variable  | no need                                      | need let or const                              |
| comment           | # for single line, """ for multi line        |                                                |
| boolean           | True                                         | true                                           |

|                   | python                                       | javascript                                     |
|:----------------- |:-------------------------------------------- |:---------------------------------------------- |
| if                | elif                                         | elseif                                         |
| while             | while: else:                                 | while                                          |
|                   | for item in arr: else:                       |                                                |
|                   |                                              |                                                |

|                   | python                                       | javascript                                     |
|:----------------- |:-------------------------------------------- |:---------------------------------------------- |
| LIST/ARRAY        |                                              |                                                |
| length            | len(arr)                                     | arr.length                                     |
| add item          | arr.append(item)                             | arr.push(item)                                 |
|                   | for index, item in enumerate(arr):           |                                                |
|                   | for a, b in zip(list_a, list_b):             |                                                |
| del item          | arr.remove(item) / del(arr[i])               | arr.filter(function(a){return a != item}       |
| traversing        | for item in arr: / for i in range(len(arr)): | for(var i = 0; i < arr.length; i++)            |
| get num arr       | range(3,5)                                   | const arr = [3,4];                             |
| concat            | arr1 + arr2                                  | arr1.concat(arr2)                              |
|                   | ["O"] * 5                                    |                                                |
|                   | "---".join(arr)                              | arr.join("---")                                |
| include           | 1 in [1,2] / 1 not in [1,2]                  | indexOf                                        |
| sum               | sum(arr)                                     | arr.reduce(function(){}                        |
| sort              | sorted([11,2,55])                            | arr.sort()                                     |
| reverse           | list(reversed[11,2,55])                      | arr.reverse()                                  |
| filter            |filter(lambda x: x % 3 == 0, my_list)         | arr.filter(function() {})                      |
|                   |                                              |                                                |

|                   | python                                       | javascript                                     |
|:----------------- |:-------------------------------------------- |:---------------------------------------------- |
| DICTIONARY/OBJECT |                                              |                                                |
| traversing        | for key in obj: *disordered                  | for key in obj: *disordered                    |
|                   | obj.items() => arr * disordered              |                                                |
|                   | obj.keys() => arr * disordered               |                                                |
|                   | obj.values() => arr * disordered             |                                                |
| include           | a in {'a':1,'b':2} / a not in {'a':1,'b':2}  |                                                |
| del item          | del obj[key]                                 |                                                |
| print             | print 'a', 'b'                               |                                                |

## range
`range(6) # => [0,1,2,3,4,5]`
`range(1,6) # => [1,2,3,4,5]`
`range(1,6,3) # => [1,4]`

## list comprehension
`[i for i in range(51) if i % 2 == 0]`

## bitwise operator
`0b` `bin(5)`

## Class
`class Animal(object):`
`    pass`
