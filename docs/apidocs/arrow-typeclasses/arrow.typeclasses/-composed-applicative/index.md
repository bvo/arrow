---
title: ComposedApplicative - arrow-typeclasses
---

[arrow-typeclasses](../../index.html) / [arrow.typeclasses](../index.html) / [ComposedApplicative](./index.html)

# ComposedApplicative

`interface ComposedApplicative<F, G> : `[`Applicative`](../-applicative/index.html)`<`[`Nested`](../-nested.html)`<`[`F`](index.html#F)`, `[`G`](index.html#G)`>>, `[`ComposedFunctor`](../-composed-functor/index.html)`<`[`F`](index.html#F)`, `[`G`](index.html#G)`>`

### Functions

| [F](-f.html) | `abstract fun F(): `[`Applicative`](../-applicative/index.html)`<`[`F`](index.html#F)`>` |
| [G](-g.html) | `abstract fun G(): `[`Applicative`](../-applicative/index.html)`<`[`G`](index.html#G)`>` |
| [ap](ap.html) | `open fun <A, B> `[`NestedType`](../-nested-type.html)`<`[`F`](index.html#F)`, `[`G`](index.html#G)`, `[`A`](ap.html#A)`>.ap(ff: Kind<`[`Nested`](../-nested.html)`<`[`F`](index.html#F)`, `[`G`](index.html#G)`>, (`[`A`](ap.html#A)`) -> `[`B`](ap.html#B)`>): `[`NestedType`](../-nested-type.html)`<`[`F`](index.html#F)`, `[`G`](index.html#G)`, `[`B`](ap.html#B)`>` |
| [apC](ap-c.html) | `open fun <A, B> `[`UnnestedType`](../-unnested-type.html)`<`[`F`](index.html#F)`, `[`G`](index.html#G)`, `[`A`](ap-c.html#A)`>.apC(ff: Kind<`[`F`](index.html#F)`, Kind<`[`G`](index.html#G)`, (`[`A`](ap-c.html#A)`) -> `[`B`](ap-c.html#B)`>>): `[`UnnestedType`](../-unnested-type.html)`<`[`F`](index.html#F)`, `[`G`](index.html#G)`, `[`B`](ap-c.html#B)`>` |
| [just](just.html) | `open fun <A> just(a: `[`A`](just.html#A)`): `[`NestedType`](../-nested-type.html)`<`[`F`](index.html#F)`, `[`G`](index.html#G)`, `[`A`](just.html#A)`>` |
| [map](map.html) | `open fun <A, B> `[`NestedType`](../-nested-type.html)`<`[`F`](index.html#F)`, `[`G`](index.html#G)`, `[`A`](map.html#A)`>.map(f: (`[`A`](map.html#A)`) -> `[`B`](map.html#B)`): `[`NestedType`](../-nested-type.html)`<`[`F`](index.html#F)`, `[`G`](index.html#G)`, `[`B`](map.html#B)`>` |

### Inherited Functions

| [just](../-applicative/just.html) | `open fun <A> `[`A`](../-applicative/just.html#A)`.just(dummy: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit): Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/just.html#A)`>` |
| [map](../-applicative/map.html) | `open fun <A, B, Z> map(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/map.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/map.html#B)`>, lbd: (Tuple2<`[`A`](../-applicative/map.html#A)`, `[`B`](../-applicative/map.html#B)`>) -> `[`Z`](../-applicative/map.html#Z)`): Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/map.html#Z)`>`<br>`open fun <A, B, C, Z> map(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/map.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/map.html#B)`>, c: Kind<`[`F`](../-applicative/index.html#F)`, `[`C`](../-applicative/map.html#C)`>, lbd: (Tuple3<`[`A`](../-applicative/map.html#A)`, `[`B`](../-applicative/map.html#B)`, `[`C`](../-applicative/map.html#C)`>) -> `[`Z`](../-applicative/map.html#Z)`): Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/map.html#Z)`>`<br>`open fun <A, B, C, D, Z> map(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/map.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/map.html#B)`>, c: Kind<`[`F`](../-applicative/index.html#F)`, `[`C`](../-applicative/map.html#C)`>, d: Kind<`[`F`](../-applicative/index.html#F)`, `[`D`](../-applicative/map.html#D)`>, lbd: (Tuple4<`[`A`](../-applicative/map.html#A)`, `[`B`](../-applicative/map.html#B)`, `[`C`](../-applicative/map.html#C)`, `[`D`](../-applicative/map.html#D)`>) -> `[`Z`](../-applicative/map.html#Z)`): Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/map.html#Z)`>`<br>`open fun <A, B, C, D, E, Z> map(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/map.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/map.html#B)`>, c: Kind<`[`F`](../-applicative/index.html#F)`, `[`C`](../-applicative/map.html#C)`>, d: Kind<`[`F`](../-applicative/index.html#F)`, `[`D`](../-applicative/map.html#D)`>, e: Kind<`[`F`](../-applicative/index.html#F)`, `[`E`](../-applicative/map.html#E)`>, lbd: (Tuple5<`[`A`](../-applicative/map.html#A)`, `[`B`](../-applicative/map.html#B)`, `[`C`](../-applicative/map.html#C)`, `[`D`](../-applicative/map.html#D)`, `[`E`](../-applicative/map.html#E)`>) -> `[`Z`](../-applicative/map.html#Z)`): Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/map.html#Z)`>`<br>`open fun <A, B, C, D, E, FF, Z> map(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/map.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/map.html#B)`>, c: Kind<`[`F`](../-applicative/index.html#F)`, `[`C`](../-applicative/map.html#C)`>, d: Kind<`[`F`](../-applicative/index.html#F)`, `[`D`](../-applicative/map.html#D)`>, e: Kind<`[`F`](../-applicative/index.html#F)`, `[`E`](../-applicative/map.html#E)`>, f: Kind<`[`F`](../-applicative/index.html#F)`, `[`FF`](../-applicative/map.html#FF)`>, lbd: (Tuple6<`[`A`](../-applicative/map.html#A)`, `[`B`](../-applicative/map.html#B)`, `[`C`](../-applicative/map.html#C)`, `[`D`](../-applicative/map.html#D)`, `[`E`](../-applicative/map.html#E)`, `[`FF`](../-applicative/map.html#FF)`>) -> `[`Z`](../-applicative/map.html#Z)`): Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/map.html#Z)`>`<br>`open fun <A, B, C, D, E, FF, G, Z> map(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/map.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/map.html#B)`>, c: Kind<`[`F`](../-applicative/index.html#F)`, `[`C`](../-applicative/map.html#C)`>, d: Kind<`[`F`](../-applicative/index.html#F)`, `[`D`](../-applicative/map.html#D)`>, e: Kind<`[`F`](../-applicative/index.html#F)`, `[`E`](../-applicative/map.html#E)`>, f: Kind<`[`F`](../-applicative/index.html#F)`, `[`FF`](../-applicative/map.html#FF)`>, g: Kind<`[`F`](../-applicative/index.html#F)`, `[`G`](../-applicative/map.html#G)`>, lbd: (Tuple7<`[`A`](../-applicative/map.html#A)`, `[`B`](../-applicative/map.html#B)`, `[`C`](../-applicative/map.html#C)`, `[`D`](../-applicative/map.html#D)`, `[`E`](../-applicative/map.html#E)`, `[`FF`](../-applicative/map.html#FF)`, `[`G`](../-applicative/map.html#G)`>) -> `[`Z`](../-applicative/map.html#Z)`): Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/map.html#Z)`>`<br>`open fun <A, B, C, D, E, FF, G, H, Z> map(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/map.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/map.html#B)`>, c: Kind<`[`F`](../-applicative/index.html#F)`, `[`C`](../-applicative/map.html#C)`>, d: Kind<`[`F`](../-applicative/index.html#F)`, `[`D`](../-applicative/map.html#D)`>, e: Kind<`[`F`](../-applicative/index.html#F)`, `[`E`](../-applicative/map.html#E)`>, f: Kind<`[`F`](../-applicative/index.html#F)`, `[`FF`](../-applicative/map.html#FF)`>, g: Kind<`[`F`](../-applicative/index.html#F)`, `[`G`](../-applicative/map.html#G)`>, h: Kind<`[`F`](../-applicative/index.html#F)`, `[`H`](../-applicative/map.html#H)`>, lbd: (Tuple8<`[`A`](../-applicative/map.html#A)`, `[`B`](../-applicative/map.html#B)`, `[`C`](../-applicative/map.html#C)`, `[`D`](../-applicative/map.html#D)`, `[`E`](../-applicative/map.html#E)`, `[`FF`](../-applicative/map.html#FF)`, `[`G`](../-applicative/map.html#G)`, `[`H`](../-applicative/map.html#H)`>) -> `[`Z`](../-applicative/map.html#Z)`): Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/map.html#Z)`>`<br>`open fun <A, B, C, D, E, FF, G, H, I, Z> map(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/map.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/map.html#B)`>, c: Kind<`[`F`](../-applicative/index.html#F)`, `[`C`](../-applicative/map.html#C)`>, d: Kind<`[`F`](../-applicative/index.html#F)`, `[`D`](../-applicative/map.html#D)`>, e: Kind<`[`F`](../-applicative/index.html#F)`, `[`E`](../-applicative/map.html#E)`>, f: Kind<`[`F`](../-applicative/index.html#F)`, `[`FF`](../-applicative/map.html#FF)`>, g: Kind<`[`F`](../-applicative/index.html#F)`, `[`G`](../-applicative/map.html#G)`>, h: Kind<`[`F`](../-applicative/index.html#F)`, `[`H`](../-applicative/map.html#H)`>, i: Kind<`[`F`](../-applicative/index.html#F)`, `[`I`](../-applicative/map.html#I)`>, lbd: (Tuple9<`[`A`](../-applicative/map.html#A)`, `[`B`](../-applicative/map.html#B)`, `[`C`](../-applicative/map.html#C)`, `[`D`](../-applicative/map.html#D)`, `[`E`](../-applicative/map.html#E)`, `[`FF`](../-applicative/map.html#FF)`, `[`G`](../-applicative/map.html#G)`, `[`H`](../-applicative/map.html#H)`, `[`I`](../-applicative/map.html#I)`>) -> `[`Z`](../-applicative/map.html#Z)`): Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/map.html#Z)`>`<br>`open fun <A, B, C, D, E, FF, G, H, I, J, Z> map(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/map.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/map.html#B)`>, c: Kind<`[`F`](../-applicative/index.html#F)`, `[`C`](../-applicative/map.html#C)`>, d: Kind<`[`F`](../-applicative/index.html#F)`, `[`D`](../-applicative/map.html#D)`>, e: Kind<`[`F`](../-applicative/index.html#F)`, `[`E`](../-applicative/map.html#E)`>, f: Kind<`[`F`](../-applicative/index.html#F)`, `[`FF`](../-applicative/map.html#FF)`>, g: Kind<`[`F`](../-applicative/index.html#F)`, `[`G`](../-applicative/map.html#G)`>, h: Kind<`[`F`](../-applicative/index.html#F)`, `[`H`](../-applicative/map.html#H)`>, i: Kind<`[`F`](../-applicative/index.html#F)`, `[`I`](../-applicative/map.html#I)`>, j: Kind<`[`F`](../-applicative/index.html#F)`, `[`J`](../-applicative/map.html#J)`>, lbd: (Tuple10<`[`A`](../-applicative/map.html#A)`, `[`B`](../-applicative/map.html#B)`, `[`C`](../-applicative/map.html#C)`, `[`D`](../-applicative/map.html#D)`, `[`E`](../-applicative/map.html#E)`, `[`FF`](../-applicative/map.html#FF)`, `[`G`](../-applicative/map.html#G)`, `[`H`](../-applicative/map.html#H)`, `[`I`](../-applicative/map.html#I)`, `[`J`](../-applicative/map.html#J)`>) -> `[`Z`](../-applicative/map.html#Z)`): Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/map.html#Z)`>` |
| [map2](../-applicative/map2.html) | `open fun <A, B, Z> Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/map2.html#A)`>.map2(fb: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/map2.html#B)`>, f: (Tuple2<`[`A`](../-applicative/map2.html#A)`, `[`B`](../-applicative/map2.html#B)`>) -> `[`Z`](../-applicative/map2.html#Z)`): Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/map2.html#Z)`>` |
| [map2Eval](../-applicative/map2-eval.html) | `open fun <A, B, Z> Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/map2-eval.html#A)`>.map2Eval(fb: Eval<Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/map2-eval.html#B)`>>, f: (Tuple2<`[`A`](../-applicative/map2-eval.html#A)`, `[`B`](../-applicative/map2-eval.html#B)`>) -> `[`Z`](../-applicative/map2-eval.html#Z)`): Eval<Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/map2-eval.html#Z)`>>` |
| [mapC](../-composed-functor/map-c.html) | `open fun <A, B> `[`UnnestedType`](../-unnested-type.html)`<`[`F`](../-composed-functor/index.html#F)`, `[`G`](../-composed-functor/index.html#G)`, `[`A`](../-composed-functor/map-c.html#A)`>.mapC(f: (`[`A`](../-composed-functor/map-c.html#A)`) -> `[`B`](../-composed-functor/map-c.html#B)`): `[`UnnestedType`](../-unnested-type.html)`<`[`F`](../-composed-functor/index.html#F)`, `[`G`](../-composed-functor/index.html#G)`, `[`B`](../-composed-functor/map-c.html#B)`>` |
| [plus](../-applicative/plus.html) | `open operator fun Kind<`[`F`](../-applicative/index.html#F)`, `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`>.plus(other: Kind<`[`F`](../-applicative/index.html#F)`, `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`>): Kind<`[`F`](../-applicative/index.html#F)`, `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`>` |
| [product](../-applicative/product.html) | `open fun <A, B> Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/product.html#A)`>.product(fb: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/product.html#B)`>): Kind<`[`F`](../-applicative/index.html#F)`, Tuple2<`[`A`](../-applicative/product.html#A)`, `[`B`](../-applicative/product.html#B)`>>`<br>`open fun <A, B, Z> Kind<`[`F`](../-applicative/index.html#F)`, Tuple2<`[`A`](../-applicative/product.html#A)`, `[`B`](../-applicative/product.html#B)`>>.product(other: Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/product.html#Z)`>, dummyImplicit: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit): Kind<`[`F`](../-applicative/index.html#F)`, Tuple3<`[`A`](../-applicative/product.html#A)`, `[`B`](../-applicative/product.html#B)`, `[`Z`](../-applicative/product.html#Z)`>>`<br>`open fun <A, B, C, Z> Kind<`[`F`](../-applicative/index.html#F)`, Tuple3<`[`A`](../-applicative/product.html#A)`, `[`B`](../-applicative/product.html#B)`, `[`C`](../-applicative/product.html#C)`>>.product(other: Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/product.html#Z)`>, dummyImplicit: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit2: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit): Kind<`[`F`](../-applicative/index.html#F)`, Tuple4<`[`A`](../-applicative/product.html#A)`, `[`B`](../-applicative/product.html#B)`, `[`C`](../-applicative/product.html#C)`, `[`Z`](../-applicative/product.html#Z)`>>`<br>`open fun <A, B, C, D, Z> Kind<`[`F`](../-applicative/index.html#F)`, Tuple4<`[`A`](../-applicative/product.html#A)`, `[`B`](../-applicative/product.html#B)`, `[`C`](../-applicative/product.html#C)`, `[`D`](../-applicative/product.html#D)`>>.product(other: Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/product.html#Z)`>, dummyImplicit: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit2: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit3: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit): Kind<`[`F`](../-applicative/index.html#F)`, Tuple5<`[`A`](../-applicative/product.html#A)`, `[`B`](../-applicative/product.html#B)`, `[`C`](../-applicative/product.html#C)`, `[`D`](../-applicative/product.html#D)`, `[`Z`](../-applicative/product.html#Z)`>>`<br>`open fun <A, B, C, D, E, Z> Kind<`[`F`](../-applicative/index.html#F)`, Tuple5<`[`A`](../-applicative/product.html#A)`, `[`B`](../-applicative/product.html#B)`, `[`C`](../-applicative/product.html#C)`, `[`D`](../-applicative/product.html#D)`, `[`E`](../-applicative/product.html#E)`>>.product(other: Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/product.html#Z)`>, dummyImplicit: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit2: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit3: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit4: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit): Kind<`[`F`](../-applicative/index.html#F)`, Tuple6<`[`A`](../-applicative/product.html#A)`, `[`B`](../-applicative/product.html#B)`, `[`C`](../-applicative/product.html#C)`, `[`D`](../-applicative/product.html#D)`, `[`E`](../-applicative/product.html#E)`, `[`Z`](../-applicative/product.html#Z)`>>`<br>`open fun <A, B, C, D, E, FF, Z> Kind<`[`F`](../-applicative/index.html#F)`, Tuple6<`[`A`](../-applicative/product.html#A)`, `[`B`](../-applicative/product.html#B)`, `[`C`](../-applicative/product.html#C)`, `[`D`](../-applicative/product.html#D)`, `[`E`](../-applicative/product.html#E)`, `[`FF`](../-applicative/product.html#FF)`>>.product(other: Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/product.html#Z)`>, dummyImplicit: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit2: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit3: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit4: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit5: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit): Kind<`[`F`](../-applicative/index.html#F)`, Tuple7<`[`A`](../-applicative/product.html#A)`, `[`B`](../-applicative/product.html#B)`, `[`C`](../-applicative/product.html#C)`, `[`D`](../-applicative/product.html#D)`, `[`E`](../-applicative/product.html#E)`, `[`FF`](../-applicative/product.html#FF)`, `[`Z`](../-applicative/product.html#Z)`>>`<br>`open fun <A, B, C, D, E, FF, G, Z> Kind<`[`F`](../-applicative/index.html#F)`, Tuple7<`[`A`](../-applicative/product.html#A)`, `[`B`](../-applicative/product.html#B)`, `[`C`](../-applicative/product.html#C)`, `[`D`](../-applicative/product.html#D)`, `[`E`](../-applicative/product.html#E)`, `[`FF`](../-applicative/product.html#FF)`, `[`G`](../-applicative/product.html#G)`>>.product(other: Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/product.html#Z)`>, dummyImplicit: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit2: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit3: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit4: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit5: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit6: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit): Kind<`[`F`](../-applicative/index.html#F)`, Tuple8<`[`A`](../-applicative/product.html#A)`, `[`B`](../-applicative/product.html#B)`, `[`C`](../-applicative/product.html#C)`, `[`D`](../-applicative/product.html#D)`, `[`E`](../-applicative/product.html#E)`, `[`FF`](../-applicative/product.html#FF)`, `[`G`](../-applicative/product.html#G)`, `[`Z`](../-applicative/product.html#Z)`>>`<br>`open fun <A, B, C, D, E, FF, G, H, Z> Kind<`[`F`](../-applicative/index.html#F)`, Tuple8<`[`A`](../-applicative/product.html#A)`, `[`B`](../-applicative/product.html#B)`, `[`C`](../-applicative/product.html#C)`, `[`D`](../-applicative/product.html#D)`, `[`E`](../-applicative/product.html#E)`, `[`FF`](../-applicative/product.html#FF)`, `[`G`](../-applicative/product.html#G)`, `[`H`](../-applicative/product.html#H)`>>.product(other: Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/product.html#Z)`>, dummyImplicit: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit2: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit3: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit4: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit5: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit6: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit7: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit): Kind<`[`F`](../-applicative/index.html#F)`, Tuple9<`[`A`](../-applicative/product.html#A)`, `[`B`](../-applicative/product.html#B)`, `[`C`](../-applicative/product.html#C)`, `[`D`](../-applicative/product.html#D)`, `[`E`](../-applicative/product.html#E)`, `[`FF`](../-applicative/product.html#FF)`, `[`G`](../-applicative/product.html#G)`, `[`H`](../-applicative/product.html#H)`, `[`Z`](../-applicative/product.html#Z)`>>`<br>`open fun <A, B, C, D, E, FF, G, H, I, Z> Kind<`[`F`](../-applicative/index.html#F)`, Tuple9<`[`A`](../-applicative/product.html#A)`, `[`B`](../-applicative/product.html#B)`, `[`C`](../-applicative/product.html#C)`, `[`D`](../-applicative/product.html#D)`, `[`E`](../-applicative/product.html#E)`, `[`FF`](../-applicative/product.html#FF)`, `[`G`](../-applicative/product.html#G)`, `[`H`](../-applicative/product.html#H)`, `[`I`](../-applicative/product.html#I)`>>.product(other: Kind<`[`F`](../-applicative/index.html#F)`, `[`Z`](../-applicative/product.html#Z)`>, dummyImplicit: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit2: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit3: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit4: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit5: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit6: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit7: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit, dummyImplicit9: `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = Unit): Kind<`[`F`](../-applicative/index.html#F)`, Tuple10<`[`A`](../-applicative/product.html#A)`, `[`B`](../-applicative/product.html#B)`, `[`C`](../-applicative/product.html#C)`, `[`D`](../-applicative/product.html#D)`, `[`E`](../-applicative/product.html#E)`, `[`FF`](../-applicative/product.html#FF)`, `[`G`](../-applicative/product.html#G)`, `[`H`](../-applicative/product.html#H)`, `[`I`](../-applicative/product.html#I)`, `[`Z`](../-applicative/product.html#Z)`>>` |
| [tupled](../-applicative/tupled.html) | `open fun <A, B> tupled(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/tupled.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/tupled.html#B)`>): Kind<`[`F`](../-applicative/index.html#F)`, Tuple2<`[`A`](../-applicative/tupled.html#A)`, `[`B`](../-applicative/tupled.html#B)`>>`<br>`open fun <A, B, C> tupled(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/tupled.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/tupled.html#B)`>, c: Kind<`[`F`](../-applicative/index.html#F)`, `[`C`](../-applicative/tupled.html#C)`>): Kind<`[`F`](../-applicative/index.html#F)`, Tuple3<`[`A`](../-applicative/tupled.html#A)`, `[`B`](../-applicative/tupled.html#B)`, `[`C`](../-applicative/tupled.html#C)`>>`<br>`open fun <A, B, C, D> tupled(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/tupled.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/tupled.html#B)`>, c: Kind<`[`F`](../-applicative/index.html#F)`, `[`C`](../-applicative/tupled.html#C)`>, d: Kind<`[`F`](../-applicative/index.html#F)`, `[`D`](../-applicative/tupled.html#D)`>): Kind<`[`F`](../-applicative/index.html#F)`, Tuple4<`[`A`](../-applicative/tupled.html#A)`, `[`B`](../-applicative/tupled.html#B)`, `[`C`](../-applicative/tupled.html#C)`, `[`D`](../-applicative/tupled.html#D)`>>`<br>`open fun <A, B, C, D, E> tupled(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/tupled.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/tupled.html#B)`>, c: Kind<`[`F`](../-applicative/index.html#F)`, `[`C`](../-applicative/tupled.html#C)`>, d: Kind<`[`F`](../-applicative/index.html#F)`, `[`D`](../-applicative/tupled.html#D)`>, e: Kind<`[`F`](../-applicative/index.html#F)`, `[`E`](../-applicative/tupled.html#E)`>): Kind<`[`F`](../-applicative/index.html#F)`, Tuple5<`[`A`](../-applicative/tupled.html#A)`, `[`B`](../-applicative/tupled.html#B)`, `[`C`](../-applicative/tupled.html#C)`, `[`D`](../-applicative/tupled.html#D)`, `[`E`](../-applicative/tupled.html#E)`>>`<br>`open fun <A, B, C, D, E, FF> tupled(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/tupled.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/tupled.html#B)`>, c: Kind<`[`F`](../-applicative/index.html#F)`, `[`C`](../-applicative/tupled.html#C)`>, d: Kind<`[`F`](../-applicative/index.html#F)`, `[`D`](../-applicative/tupled.html#D)`>, e: Kind<`[`F`](../-applicative/index.html#F)`, `[`E`](../-applicative/tupled.html#E)`>, f: Kind<`[`F`](../-applicative/index.html#F)`, `[`FF`](../-applicative/tupled.html#FF)`>): Kind<`[`F`](../-applicative/index.html#F)`, Tuple6<`[`A`](../-applicative/tupled.html#A)`, `[`B`](../-applicative/tupled.html#B)`, `[`C`](../-applicative/tupled.html#C)`, `[`D`](../-applicative/tupled.html#D)`, `[`E`](../-applicative/tupled.html#E)`, `[`FF`](../-applicative/tupled.html#FF)`>>`<br>`open fun <A, B, C, D, E, FF, G> tupled(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/tupled.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/tupled.html#B)`>, c: Kind<`[`F`](../-applicative/index.html#F)`, `[`C`](../-applicative/tupled.html#C)`>, d: Kind<`[`F`](../-applicative/index.html#F)`, `[`D`](../-applicative/tupled.html#D)`>, e: Kind<`[`F`](../-applicative/index.html#F)`, `[`E`](../-applicative/tupled.html#E)`>, f: Kind<`[`F`](../-applicative/index.html#F)`, `[`FF`](../-applicative/tupled.html#FF)`>, g: Kind<`[`F`](../-applicative/index.html#F)`, `[`G`](../-applicative/tupled.html#G)`>): Kind<`[`F`](../-applicative/index.html#F)`, Tuple7<`[`A`](../-applicative/tupled.html#A)`, `[`B`](../-applicative/tupled.html#B)`, `[`C`](../-applicative/tupled.html#C)`, `[`D`](../-applicative/tupled.html#D)`, `[`E`](../-applicative/tupled.html#E)`, `[`FF`](../-applicative/tupled.html#FF)`, `[`G`](../-applicative/tupled.html#G)`>>`<br>`open fun <A, B, C, D, E, FF, G, H> tupled(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/tupled.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/tupled.html#B)`>, c: Kind<`[`F`](../-applicative/index.html#F)`, `[`C`](../-applicative/tupled.html#C)`>, d: Kind<`[`F`](../-applicative/index.html#F)`, `[`D`](../-applicative/tupled.html#D)`>, e: Kind<`[`F`](../-applicative/index.html#F)`, `[`E`](../-applicative/tupled.html#E)`>, f: Kind<`[`F`](../-applicative/index.html#F)`, `[`FF`](../-applicative/tupled.html#FF)`>, g: Kind<`[`F`](../-applicative/index.html#F)`, `[`G`](../-applicative/tupled.html#G)`>, h: Kind<`[`F`](../-applicative/index.html#F)`, `[`H`](../-applicative/tupled.html#H)`>): Kind<`[`F`](../-applicative/index.html#F)`, Tuple8<`[`A`](../-applicative/tupled.html#A)`, `[`B`](../-applicative/tupled.html#B)`, `[`C`](../-applicative/tupled.html#C)`, `[`D`](../-applicative/tupled.html#D)`, `[`E`](../-applicative/tupled.html#E)`, `[`FF`](../-applicative/tupled.html#FF)`, `[`G`](../-applicative/tupled.html#G)`, `[`H`](../-applicative/tupled.html#H)`>>`<br>`open fun <A, B, C, D, E, FF, G, H, I> tupled(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/tupled.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/tupled.html#B)`>, c: Kind<`[`F`](../-applicative/index.html#F)`, `[`C`](../-applicative/tupled.html#C)`>, d: Kind<`[`F`](../-applicative/index.html#F)`, `[`D`](../-applicative/tupled.html#D)`>, e: Kind<`[`F`](../-applicative/index.html#F)`, `[`E`](../-applicative/tupled.html#E)`>, f: Kind<`[`F`](../-applicative/index.html#F)`, `[`FF`](../-applicative/tupled.html#FF)`>, g: Kind<`[`F`](../-applicative/index.html#F)`, `[`G`](../-applicative/tupled.html#G)`>, h: Kind<`[`F`](../-applicative/index.html#F)`, `[`H`](../-applicative/tupled.html#H)`>, i: Kind<`[`F`](../-applicative/index.html#F)`, `[`I`](../-applicative/tupled.html#I)`>): Kind<`[`F`](../-applicative/index.html#F)`, Tuple9<`[`A`](../-applicative/tupled.html#A)`, `[`B`](../-applicative/tupled.html#B)`, `[`C`](../-applicative/tupled.html#C)`, `[`D`](../-applicative/tupled.html#D)`, `[`E`](../-applicative/tupled.html#E)`, `[`FF`](../-applicative/tupled.html#FF)`, `[`G`](../-applicative/tupled.html#G)`, `[`H`](../-applicative/tupled.html#H)`, `[`I`](../-applicative/tupled.html#I)`>>`<br>`open fun <A, B, C, D, E, FF, G, H, I, J> tupled(a: Kind<`[`F`](../-applicative/index.html#F)`, `[`A`](../-applicative/tupled.html#A)`>, b: Kind<`[`F`](../-applicative/index.html#F)`, `[`B`](../-applicative/tupled.html#B)`>, c: Kind<`[`F`](../-applicative/index.html#F)`, `[`C`](../-applicative/tupled.html#C)`>, d: Kind<`[`F`](../-applicative/index.html#F)`, `[`D`](../-applicative/tupled.html#D)`>, e: Kind<`[`F`](../-applicative/index.html#F)`, `[`E`](../-applicative/tupled.html#E)`>, f: Kind<`[`F`](../-applicative/index.html#F)`, `[`FF`](../-applicative/tupled.html#FF)`>, g: Kind<`[`F`](../-applicative/index.html#F)`, `[`G`](../-applicative/tupled.html#G)`>, h: Kind<`[`F`](../-applicative/index.html#F)`, `[`H`](../-applicative/tupled.html#H)`>, i: Kind<`[`F`](../-applicative/index.html#F)`, `[`I`](../-applicative/tupled.html#I)`>, j: Kind<`[`F`](../-applicative/index.html#F)`, `[`J`](../-applicative/tupled.html#J)`>): Kind<`[`F`](../-applicative/index.html#F)`, Tuple10<`[`A`](../-applicative/tupled.html#A)`, `[`B`](../-applicative/tupled.html#B)`, `[`C`](../-applicative/tupled.html#C)`, `[`D`](../-applicative/tupled.html#D)`, `[`E`](../-applicative/tupled.html#E)`, `[`FF`](../-applicative/tupled.html#FF)`, `[`G`](../-applicative/tupled.html#G)`, `[`H`](../-applicative/tupled.html#H)`, `[`I`](../-applicative/tupled.html#I)`, `[`J`](../-applicative/tupled.html#J)`>>` |

### Companion Object Functions

| [invoke](invoke.html) | `operator fun <F, G> invoke(FF: `[`Applicative`](../-applicative/index.html)`<`[`F`](invoke.html#F)`>, GF: `[`Applicative`](../-applicative/index.html)`<`[`G`](invoke.html#G)`>): `[`Applicative`](../-applicative/index.html)`<`[`Nested`](../-nested.html)`<`[`F`](invoke.html#F)`, `[`G`](invoke.html#G)`>>` |

### Extension Functions

| [compose](../compose.html) | `fun <F, G> `[`Invariant`](../-invariant/index.html)`<`[`F`](../compose.html#F)`>.compose(GF: `[`Invariant`](../-invariant/index.html)`<`[`G`](../compose.html#G)`>): `[`Invariant`](../-invariant/index.html)`<`[`Nested`](../-nested.html)`<`[`F`](../compose.html#F)`, `[`G`](../compose.html#G)`>>`<br>`fun <F, G> `[`Functor`](../-functor/index.html)`<`[`F`](../compose.html#F)`>.compose(GF: `[`Functor`](../-functor/index.html)`<`[`G`](../compose.html#G)`>): `[`Functor`](../-functor/index.html)`<`[`Nested`](../-nested.html)`<`[`F`](../compose.html#F)`, `[`G`](../compose.html#G)`>>`<br>`fun <F, G> `[`Applicative`](../-applicative/index.html)`<`[`F`](../compose.html#F)`>.compose(GA: `[`Applicative`](../-applicative/index.html)`<`[`G`](../compose.html#G)`>): `[`Applicative`](../-applicative/index.html)`<`[`Nested`](../-nested.html)`<`[`F`](../compose.html#F)`, `[`G`](../compose.html#G)`>>` |
| [composeContravariant](../compose-contravariant.html) | `fun <F, G> `[`Invariant`](../-invariant/index.html)`<`[`F`](../compose-contravariant.html#F)`>.composeContravariant(GF: `[`Contravariant`](../-contravariant/index.html)`<`[`G`](../compose-contravariant.html#G)`>): `[`Invariant`](../-invariant/index.html)`<`[`Nested`](../-nested.html)`<`[`F`](../compose-contravariant.html#F)`, `[`G`](../compose-contravariant.html#G)`>>`<br>`fun <F, G> `[`Functor`](../-functor/index.html)`<`[`F`](../compose-contravariant.html#F)`>.composeContravariant(GF: `[`Contravariant`](../-contravariant/index.html)`<`[`G`](../compose-contravariant.html#G)`>): `[`Contravariant`](../-contravariant/index.html)`<`[`Nested`](../-nested.html)`<`[`F`](../compose-contravariant.html#F)`, `[`G`](../compose-contravariant.html#G)`>>` |
| [composeFunctor](../compose-functor.html) | `fun <F, G> `[`Invariant`](../-invariant/index.html)`<`[`F`](../compose-functor.html#F)`>.composeFunctor(GF: `[`Functor`](../-functor/index.html)`<`[`G`](../compose-functor.html#G)`>): `[`Invariant`](../-invariant/index.html)`<`[`Nested`](../-nested.html)`<`[`F`](../compose-functor.html#F)`, `[`G`](../compose-functor.html#G)`>>` |

### Inheritors

| [ComposedAlternative](../-composed-alternative/index.html) | `interface ComposedAlternative<F, G> : `[`Alternative`](../-alternative.html)`<`[`Nested`](../-nested.html)`<`[`F`](../-composed-alternative/index.html#F)`, `[`G`](../-composed-alternative/index.html#G)`>>, `[`ComposedApplicative`](./index.html)`<`[`F`](../-composed-alternative/index.html#F)`, `[`G`](../-composed-alternative/index.html#G)`>, `[`ComposedMonoidK`](../-composed-monoid-k/index.html)`<`[`F`](../-composed-alternative/index.html#F)`, `[`G`](../-composed-alternative/index.html#G)`>` |
