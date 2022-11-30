# Blockchain Programming in Python

Let's program blockchain/bitcoin with
[Jimmy Song]'s wonderful [Programming Bitcoin].

## Primitives

- [FieldElement](ch01/ecc.py)

## Console

```
$ python
>>> from ch01.ecc import FieldElement
>>> a = FieldElement(7, 13)
>>> b = FieldFlement(12, 13)
>>> c = FieldElement(6, 13)
>>> print(a+b == c)
True
```

Happy Hacking!

[jimmy song]: https://programmingbitcoin.com/
[programming bitcoin]: https://programmingbitcoin.com/programming-bitcoin-book/
