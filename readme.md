# V8 performance wins

- keep function arguments the same length and same type every time
- use constructors and factory methods to ensure same properties are added in the same order
- keep object maps the same, declare all properties and values (event if null/undefined) so V8 can create proper maps
- avoid mixing types in arrays
- avoid excessive anonymous closure usage — use names functions
- keep your functions' overall size to fewer than 600 characters (bytes) in length

Thanks [Joe MacCann](https://twitter.com/joemccann)!
