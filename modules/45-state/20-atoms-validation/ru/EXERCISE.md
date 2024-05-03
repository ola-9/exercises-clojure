Реализуйте функцию-валидатор `vec-even?`, которая проверяет, что атом является вектором и все его элементы четные (пустой вектор не является валидным случаем).

```clojure
(vec-even? [])        ; => false
(vec-even? [0 2 4 6]) ; => true
(vec-even? [1 3 5])   ; => false
```