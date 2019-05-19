# Python Annoying Intuitives
Sometimes you write down a line of code quite intuitive which costs you a whole working day. This repository contains some of the most annoying one of them.

### os.path.join

``` python
from os.path import join

print(join('foo', '/bar'))
```

**Expectation**
> foo/bar

**Reality**
> /bar


