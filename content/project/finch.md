+++
title = 'Finch'
description = "a random .f95 file"
+++

```f95
function big_eq_int (b, i)
result (bi)

type (big_integer), intent
(in) : : b
integer, intent (in) : : i
logical : : bi
integer : : i0, i1
i0 = modulo (i, base)
i1 = i / base
bi = b % digit (0) ==
i0 .and. & b % digit (1) ==
i1 .and. &
all (b % digit (2 :
or_of_digits) == 0)
and function big_eq_int
```
