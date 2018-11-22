---
title: arrow.instances.id.applicative.arrow.Kind - arrow-instances-core
---

[arrow-instances-core](../../index.html) / [arrow.instances.id.applicative](../index.html) / [arrow.Kind](./index.html)

### Extensions for arrow.Kind

| [ap](ap.html) | `fun <A, B> Kind<ForId, `[`A`](ap.html#A)`>.ap(arg1: Kind<ForId, (`[`A`](ap.html#A)`) -> `[`B`](ap.html#B)`>): Id<`[`B`](ap.html#B)`>` |
| [map](map.html) | `fun <A, B> Kind<ForId, `[`A`](map.html#A)`>.map(arg1: (`[`A`](map.html#A)`) -> `[`B`](map.html#B)`): Id<`[`B`](map.html#B)`>` |
| [map2](map2.html) | `fun <A, B, Z> Kind<ForId, `[`A`](map2.html#A)`>.map2(arg1: Kind<ForId, `[`B`](map2.html#B)`>, arg2: (Tuple2<`[`A`](map2.html#A)`, `[`B`](map2.html#B)`>) -> `[`Z`](map2.html#Z)`): Id<`[`Z`](map2.html#Z)`>` |
| [map2Eval](map2-eval.html) | `fun <A, B, Z> Kind<ForId, `[`A`](map2-eval.html#A)`>.map2Eval(arg1: Eval<Kind<ForId, `[`B`](map2-eval.html#B)`>>, arg2: (Tuple2<`[`A`](map2-eval.html#A)`, `[`B`](map2-eval.html#B)`>) -> `[`Z`](map2-eval.html#Z)`): Eval<Kind<ForId, `[`Z`](map2-eval.html#Z)`>>` |
| [plus](plus.html) | `operator fun Kind<ForId, `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`>.plus(arg1: Kind<ForId, `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`>): Id<`[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`>` |
| [product](product.html) | `fun <A, B> Kind<ForId, `[`A`](product.html#A)`>.product(arg1: Kind<ForId, `[`B`](product.html#B)`>): Id<Tuple2<`[`A`](product.html#A)`, `[`B`](product.html#B)`>>`<br>`fun <A, B, Z> Kind<ForId, Tuple2<`[`A`](product.html#A)`, `[`B`](product.html#B)`>>.product(arg1: Kind<ForId, `[`Z`](product.html#Z)`>): Id<Tuple3<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`Z`](product.html#Z)`>>`<br>`fun <A, B, C, Z> Kind<ForId, Tuple3<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`>>.product(arg1: Kind<ForId, `[`Z`](product.html#Z)`>): Id<Tuple4<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`Z`](product.html#Z)`>>`<br>`fun <A, B, C, D, Z> Kind<ForId, Tuple4<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`>>.product(arg1: Kind<ForId, `[`Z`](product.html#Z)`>): Id<Tuple5<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`Z`](product.html#Z)`>>`<br>`fun <A, B, C, D, E, Z> Kind<ForId, Tuple5<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`>>.product(arg1: Kind<ForId, `[`Z`](product.html#Z)`>): Id<Tuple6<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`Z`](product.html#Z)`>>`<br>`fun <A, B, C, D, E, FF, Z> Kind<ForId, Tuple6<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`>>.product(arg1: Kind<ForId, `[`Z`](product.html#Z)`>): Id<Tuple7<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`Z`](product.html#Z)`>>`<br>`fun <A, B, C, D, E, FF, G, Z> Kind<ForId, Tuple7<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`>>.product(arg1: Kind<ForId, `[`Z`](product.html#Z)`>): Id<Tuple8<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`, `[`Z`](product.html#Z)`>>`<br>`fun <A, B, C, D, E, FF, G, H, Z> Kind<ForId, Tuple8<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`, `[`H`](product.html#H)`>>.product(arg1: Kind<ForId, `[`Z`](product.html#Z)`>): Id<Tuple9<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`, `[`H`](product.html#H)`, `[`Z`](product.html#Z)`>>`<br>`fun <A, B, C, D, E, FF, G, H, I, Z> Kind<ForId, Tuple9<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`, `[`H`](product.html#H)`, `[`I`](product.html#I)`>>.product(arg1: Kind<ForId, `[`Z`](product.html#Z)`>): Id<Tuple10<`[`A`](product.html#A)`, `[`B`](product.html#B)`, `[`C`](product.html#C)`, `[`D`](product.html#D)`, `[`E`](product.html#E)`, `[`FF`](product.html#FF)`, `[`G`](product.html#G)`, `[`H`](product.html#H)`, `[`I`](product.html#I)`, `[`Z`](product.html#Z)`>>` |
