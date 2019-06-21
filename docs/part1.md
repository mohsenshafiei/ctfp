- Functional programming is not only about composing functions and algebraic data structures. It makes concurrency composable - something that virtually impossible with other program paradigms.

- Changes in hardware and the growing complexity of software are forcing us to rethink the foundations of programming

- The essence of a category is composition or if you prefer the essence of composition is a category

- Arrows compose, so if you have an arrow from A to B and then there is an arrow from B to C then there should be an arrow from A to C.

- There are two important  properties that the composition in any category must satisfy:
  * composition is associative
    ```console
      h o (g o f) = (h o g) o f = h o g o f
    ```
    Associativity is pretty obvious when dealing with functions but it may not be obvious in other categories.
  * For every object A there is an arrow which is a unit of composition. This arrow loops from the object to itself.


- A functor is a mapping between categories. . Given two categories, C and D, a functor F maps objects in C to objects in D - it is a function on objects.

- So if a morphism f in C connect object a to object b,
```console
f:: a => b
```
the image of f in D, Ff, will connect the image of a to the image of b:
```console
Ff:: Fa => Fb
```

- Note that functors must preserve the structure of a category.
