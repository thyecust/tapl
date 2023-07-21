# Untyped λ Calculus

## Renaming vs. Nameless

我们考虑 `[x → y z](λy. x y)`，是不能把 x 直接消去的，一个方法是对 bound variable 做 renaming，即 `[x → y z](λw. x w)` = `(λw. y z w)`。
Church 也把这个做法叫做 alpha-conversion。Link: conversion 5.3.4

另一个方案是转化到某个 nameless form，比如 de Bruijn index，这在 Chapter 6 中介绍。
