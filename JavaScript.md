# JavaScript WAT?

We all love NaN!
```javascript
> NaN === NaN
false
```

Array additions and subtractions!
```javascript
> [] + []
""
```
```javascript
> [] - []
0
```

Array + Object * headaches!
```javascript
> [] + {}
"[object Object]"
```
```javascript
> {} + {}
NaN
```

Undefined and null
```javascript
> undefined == null
true
```

Floating point imprecision
```javascript
> 0.1 + 0.7
0.7999999999999999
```

Weak typing + implicit conversions * headaches! Because we all love consistency.
```javascript
> "5" - 3
2
```
```javascript
> "5" + 3
"53"
```

String - String * Integer. WAT?
```javascript
> "5" + + "5"
"55"
```

Marvelous!
```javascript
> "foo" + + "foo"
"fooNaN"
```
```javascript
> "5" + - "2"
"5-2"
```

Apparently it's ok?
```javascript
> "5" + - + - - + - - + + - + - + - + - - - "-2"
"52"
```

Because fuck math!
```javascript
> var x = 3;
> '5' + x - x
50
```
