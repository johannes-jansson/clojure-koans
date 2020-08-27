## 01 Equality
Loose equality: ==
"string" :keyword

## 02 Strings

## 03 Lists
'() makes lists
Lists are sequences
(cons) adds first element before second list (construct)
? (conj) adds last element before first list, kind of

## 04 Vectors `[]`

## 05 Sets `#{}`

## 06 Maps `{}`
"add" using assoc
"remove" using dissoc
(immutable)

## 07 Functions
(fn [n] (* 5 n))
```#(* 5 %)```
```#(+ %1 %2)```

## 08 Conditionals

## 09 Higher_order_functions
(map function sequence)
(filter function sequence)
? (reduce function sequence) chains

## 10 Runtime_polymorphism ?
(defmulti diet (fn [x] (:eater x)))
(defmethod diet :herbivore [a] (str (a :name) " eats veggies."))

## 11 Lazy_sequences

## 12 Sequence_comprehensions
(for [x (range 6)] x)
(for [x (range 6) :when (odd? x)] x)

## 13 Creating_functions
(let [name (return-stuff)] (name input))
(partial)
(comp) composes

## 14 Recursion
## 15 Destructuring
## 16 Refs
## 17 Atoms
## 18 Quote
## 19 Datatypes
## 20 Java_interop
## 21 Partition
## 22 Group_by
## 23 Meta
## 24 Macros
## 25 Threading_macros
## 26 Transducers
## 27 Multimethods
