# diff-between-python-javascript
record the difference between python and javascript, during my learning

|                   | python                                       | javascript                                     |
|:----------------- |:-------------------------------------------- |:---------------------------------------------- |
| declare variable  | no need                                      | need let or const                              |
| comment           | # for single line, """ for multi line        |                                                |
| if                | elif                                         | elseif                                         |
| while             | while: else:                                 | while                                          |
|                   | for item in arr: else:                       |                                                |
|                   |                                              |                                                |
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
|                   |                                              |                                                |
| DICTIONARY/OBJECT |                                              |                                                |
| traversing        | for key in obj: *disordered                  | for key in obj: *disordered                    |
| sum               | sum(arr)                                     | arr.reduce(function(){}                        |
| print             | print 'a', 'b'                               |                                                |

## range
`range(6) # => [0,1,2,3,4,5]`
`range(1,6) # => [1,2,3,4,5]`
`range(1,6,3) # => [1,4]`
