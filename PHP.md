# PHP WAT?

Floating point imprecision
```php
> 0.1 + 0.7
0.7999999999999999
```

How PHP increments strings
```php
> $a = 1;
> $b = 3;
```

```php
> echo $a++ + $b;
4
```

```php
> echo $a + ++$b;
6
```

```php
> echo ++$a + $b++;
7
```

```php
> $a = 'fact_2';
> echo ++$a;
fact_3
```

```php
> $a = '2nd_fact';
> echo ++$a;
2nd_facu
```

```php
> $a = 'a_fact';
> echo ++$a;
a_facu
```

```php
> $a = 'a_fact?';
> echo ++$a;
a_fact?
```

The mystery of value appearance
```php
> $array = array('isReady' => false, 'isPHP' => true, 'isStrange' => true);
> in_array('sitepoint.com', $array);
true
```

```php
> $array = array('count' => 1, 'references' => 0, 'ghosts' => 1);
> in_array('aurelio', $array, true);
true
```

---

#### References

* [3 Strange PHP Facts You May Not Know](http://www.sitepoint.com/3-strange-php-facts-you-may-not-know)
