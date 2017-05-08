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

## Control Flow
|                   | python                                       | javascript                                     |
|:----------------- |:-------------------------------------------- |:---------------------------------------------- |
| if                | elif                                         | elseif                                         |
| while             | while: else:                                 | while                                          |
|                   | for item in arr: else:                       |                                                |
|                   |                                              |                                                |

## List/ Array
|                   | python                                       | javascript                                     |
|:----------------- |:-------------------------------------------- |:---------------------------------------------- |
| length            | len(list)                                    | arr.length                                     |
| add item          | list.append(item)                            | arr.push(item)                                 |
| index item        | list.index(item)                             | arr.indexOf(item)                              |
| insert item       | list.insert(index, item)                     | arr.splice(index, item)                        |
| del item          | list.remove(item) / del(arr[i])              | arr.filter(function(a){return a != item}       |
| traversing        | for item in list:/for i in range(len(list)): | for(var i = 0; i < arr.length; i++)            |
|                   | for index, item in enumerate(arr):           |                                                |
|                   | for a, b in zip(list_a, list_b):             |                                                |
| get num arr       | range(3,5)                                   | const arr = [3,4];                             |
| concat            | arr1 + arr2                                  | arr1.concat(arr2)                              |
|                   | ["O"] * 5                                    |                                                |
|                   | "---".join(arr)                              | arr.join("---")                                |
| include           | 1 in [1,2] / 1 not in [1,2]                  | indexOf                                        |
| sum               | sum(arr)                                     | arr.reduce(function(){}                        |
| sort              | list.sort() / sorted([11,2,55])              | arr.sort()                                     |
| reverse           | list(reversed[11,2,55])                      | arr.reverse()                                  |
| filter            |filter(lambda x: x % 3 == 0, my_list)         | arr.filter(function() {})                      |
|                   |                                              |                                                |

## Dictionary/ Object
|                   | python                                       | javascript                                     |
|:----------------- |:-------------------------------------------- |:---------------------------------------------- |
| length            | len(dic)                                     |                                                |
| del item          | del dic[key]                                 |                                                |
| traversing        | for key in obj: *disordered                  | for key in obj: *disordered                    |
|                   | obj.items() => arr * disordered              |                                                |
|                   | obj.keys() => arr * disordered               |                                                |
|                   | obj.values() => arr * disordered             |                                                |
| include           | a in {'a':1,'b':2} / a not in {'a':1,'b':2}  |                                                |
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
