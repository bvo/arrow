---
title: ConsPattern - arrow-docs
---

[arrow-docs](../../index.html) / [arrow.recursion](../index.html) / [ConsPattern](./index.html)

# ConsPattern

`@higherkind data class ConsPattern<out A> : `[`IntListPattern`](../-int-list-pattern.html)`<`[`A`](index.html#A)`>`

### Constructors

| [&lt;init&gt;](-init-.html) | `ConsPattern(head: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, tail: `[`A`](index.html#A)`)` |

### Properties

| [head](head.html) | `val head: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [tail](tail.html) | `val tail: `[`A`](index.html#A) |

### Extension Functions

| [as](../../arrow.aql.box.functor/arrow.-kind/as.html) | `fun <A, B> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.functor/arrow.-kind/as.html#A)`>.as(arg1: `[`B`](../../arrow.aql.box.functor/arrow.-kind/as.html#B)`): `[`Box`](../../arrow.aql/-box/index.html)`<`[`B`](../../arrow.aql.box.functor/arrow.-kind/as.html#B)`>` |
| [as](../arrow.-kind/as.html) | `fun <A, B> Kind<`[`ForIntListPattern`](../-for-int-list-pattern.html)`, `[`A`](../arrow.-kind/as.html#A)`>.as(arg1: `[`B`](../arrow.-kind/as.html#B)`): `[`IntListPattern`](../-int-list-pattern.html)`<`[`B`](../arrow.-kind/as.html#B)`>` |
| [collect](../../arrow.aql.box.functor-filter/arrow.-kind/collect.html) | `fun <A, B> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.functor-filter/arrow.-kind/collect.html#A)`>.collect(arg1: PartialFunction<`[`A`](../../arrow.aql.box.functor-filter/arrow.-kind/collect.html#A)`, `[`B`](../../arrow.aql.box.functor-filter/arrow.-kind/collect.html#B)`>): `[`Box`](../../arrow.aql/-box/index.html)`<`[`B`](../../arrow.aql.box.functor-filter/arrow.-kind/collect.html#B)`>` |
| [combineAll](../../arrow.aql.box.foldable/arrow.-kind/combine-all.html) | `fun <A> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/combine-all.html#A)`>.combineAll(arg1: Monoid<`[`A`](../../arrow.aql.box.foldable/arrow.-kind/combine-all.html#A)`>): `[`A`](../../arrow.aql.box.foldable/arrow.-kind/combine-all.html#A) |
| [exists](../../arrow.aql.box.foldable/arrow.-kind/exists.html) | `fun <A> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/exists.html#A)`>.exists(arg1: (`[`A`](../../arrow.aql.box.foldable/arrow.-kind/exists.html#A)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [filter](../../arrow.aql.box.functor-filter/arrow.-kind/filter.html) | `fun <A> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.functor-filter/arrow.-kind/filter.html#A)`>.filter(arg1: (`[`A`](../../arrow.aql.box.functor-filter/arrow.-kind/filter.html#A)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Box`](../../arrow.aql/-box/index.html)`<`[`A`](../../arrow.aql.box.functor-filter/arrow.-kind/filter.html#A)`>` |
| [find](../../arrow.aql.box.foldable/arrow.-kind/find.html) | `fun <A> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/find.html#A)`>.find(arg1: (`[`A`](../../arrow.aql.box.foldable/arrow.-kind/find.html#A)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): Option<`[`A`](../../arrow.aql.box.foldable/arrow.-kind/find.html#A)`>` |
| [fold](../../arrow.aql.box.foldable/arrow.-kind/fold.html) | `fun <A> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/fold.html#A)`>.fold(arg1: Monoid<`[`A`](../../arrow.aql.box.foldable/arrow.-kind/fold.html#A)`>): `[`A`](../../arrow.aql.box.foldable/arrow.-kind/fold.html#A) |
| [foldLeft](../../arrow.aql.box.foldable/arrow.-kind/fold-left.html) | `fun <A, B> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/fold-left.html#A)`>.foldLeft(arg1: `[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-left.html#B)`, arg2: (`[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-left.html#B)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/fold-left.html#A)`) -> `[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-left.html#B)`): `[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-left.html#B) |
| [foldM](../../arrow.aql.box.foldable/arrow.-kind/fold-m.html) | `fun <G, A, B> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/fold-m.html#A)`>.foldM(arg1: Monad<`[`G`](../../arrow.aql.box.foldable/arrow.-kind/fold-m.html#G)`>, arg2: `[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-m.html#B)`, arg3: (`[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-m.html#B)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/fold-m.html#A)`) -> Kind<`[`G`](../../arrow.aql.box.foldable/arrow.-kind/fold-m.html#G)`, `[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-m.html#B)`>): Kind<`[`G`](../../arrow.aql.box.foldable/arrow.-kind/fold-m.html#G)`, `[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-m.html#B)`>` |
| [foldMap](../../arrow.aql.box.foldable/arrow.-kind/fold-map.html) | `fun <A, B> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/fold-map.html#A)`>.foldMap(arg1: Monoid<`[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-map.html#B)`>, arg2: (`[`A`](../../arrow.aql.box.foldable/arrow.-kind/fold-map.html#A)`) -> `[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-map.html#B)`): `[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-map.html#B) |
| [foldMapM](../../arrow.aql.box.foldable/arrow.-kind/fold-map-m.html) | `fun <G, A, B, MA : Monad<`[`G`](../../arrow.aql.box.foldable/arrow.-kind/fold-map-m.html#G)`>, MO : Monoid<`[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-map-m.html#B)`>> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/fold-map-m.html#A)`>.foldMapM(arg1: `[`MA`](../../arrow.aql.box.foldable/arrow.-kind/fold-map-m.html#MA)`, arg2: `[`MO`](../../arrow.aql.box.foldable/arrow.-kind/fold-map-m.html#MO)`, arg3: (`[`A`](../../arrow.aql.box.foldable/arrow.-kind/fold-map-m.html#A)`) -> Kind<`[`G`](../../arrow.aql.box.foldable/arrow.-kind/fold-map-m.html#G)`, `[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-map-m.html#B)`>): Kind<`[`G`](../../arrow.aql.box.foldable/arrow.-kind/fold-map-m.html#G)`, `[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-map-m.html#B)`>` |
| [foldRight](../../arrow.aql.box.foldable/arrow.-kind/fold-right.html) | `fun <A, B> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/fold-right.html#A)`>.foldRight(arg1: Eval<`[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-right.html#B)`>, arg2: (`[`A`](../../arrow.aql.box.foldable/arrow.-kind/fold-right.html#A)`, Eval<`[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-right.html#B)`>) -> Eval<`[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-right.html#B)`>): Eval<`[`B`](../../arrow.aql.box.foldable/arrow.-kind/fold-right.html#B)`>` |
| [forAll](../../arrow.aql.box.foldable/arrow.-kind/for-all.html) | `fun <A> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/for-all.html#A)`>.forAll(arg1: (`[`A`](../../arrow.aql.box.foldable/arrow.-kind/for-all.html#A)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [fproduct](../../arrow.aql.box.functor/arrow.-kind/fproduct.html) | `fun <A, B> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.functor/arrow.-kind/fproduct.html#A)`>.fproduct(arg1: (`[`A`](../../arrow.aql.box.functor/arrow.-kind/fproduct.html#A)`) -> `[`B`](../../arrow.aql.box.functor/arrow.-kind/fproduct.html#B)`): `[`Box`](../../arrow.aql/-box/index.html)`<Tuple2<`[`A`](../../arrow.aql.box.functor/arrow.-kind/fproduct.html#A)`, `[`B`](../../arrow.aql.box.functor/arrow.-kind/fproduct.html#B)`>>` |
| [fproduct](../arrow.-kind/fproduct.html) | `fun <A, B> Kind<`[`ForIntListPattern`](../-for-int-list-pattern.html)`, `[`A`](../arrow.-kind/fproduct.html#A)`>.fproduct(arg1: (`[`A`](../arrow.-kind/fproduct.html#A)`) -> `[`B`](../arrow.-kind/fproduct.html#B)`): `[`IntListPattern`](../-int-list-pattern.html)`<Tuple2<`[`A`](../arrow.-kind/fproduct.html#A)`, `[`B`](../arrow.-kind/fproduct.html#B)`>>` |
| [get](../../arrow.aql.box.foldable/arrow.-kind/get.html) | `fun <A> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/get.html#A)`>.get(arg1: Monad<Kind<ForEither, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/get.html#A)`>>, arg2: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): Option<`[`A`](../../arrow.aql.box.foldable/arrow.-kind/get.html#A)`>` |
| [imap](../../arrow.aql.box.functor/arrow.-kind/imap.html) | `fun <A, B> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.functor/arrow.-kind/imap.html#A)`>.imap(arg1: (`[`A`](../../arrow.aql.box.functor/arrow.-kind/imap.html#A)`) -> `[`B`](../../arrow.aql.box.functor/arrow.-kind/imap.html#B)`, arg2: (`[`B`](../../arrow.aql.box.functor/arrow.-kind/imap.html#B)`) -> `[`A`](../../arrow.aql.box.functor/arrow.-kind/imap.html#A)`): `[`Box`](../../arrow.aql/-box/index.html)`<`[`B`](../../arrow.aql.box.functor/arrow.-kind/imap.html#B)`>` |
| [imap](../arrow.-kind/imap.html) | `fun <A, B> Kind<`[`ForIntListPattern`](../-for-int-list-pattern.html)`, `[`A`](../arrow.-kind/imap.html#A)`>.imap(arg1: (`[`A`](../arrow.-kind/imap.html#A)`) -> `[`B`](../arrow.-kind/imap.html#B)`, arg2: (`[`B`](../arrow.-kind/imap.html#B)`) -> `[`A`](../arrow.-kind/imap.html#A)`): `[`IntListPattern`](../-int-list-pattern.html)`<`[`B`](../arrow.-kind/imap.html#B)`>` |
| [isEmpty](../../arrow.aql.box.foldable/arrow.-kind/is-empty.html) | `fun <A> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/is-empty.html#A)`>.isEmpty(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [map](../../arrow.aql.box.functor/arrow.-kind/map.html) | `fun <A, B> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.functor/arrow.-kind/map.html#A)`>.map(arg1: (`[`A`](../../arrow.aql.box.functor/arrow.-kind/map.html#A)`) -> `[`B`](../../arrow.aql.box.functor/arrow.-kind/map.html#B)`): `[`Box`](../../arrow.aql/-box/index.html)`<`[`B`](../../arrow.aql.box.functor/arrow.-kind/map.html#B)`>` |
| [map](../arrow.-kind/map.html) | `fun <A, B> Kind<`[`ForIntListPattern`](../-for-int-list-pattern.html)`, `[`A`](../arrow.-kind/map.html#A)`>.map(arg1: (`[`A`](../arrow.-kind/map.html#A)`) -> `[`B`](../arrow.-kind/map.html#B)`): `[`IntListPattern`](../-int-list-pattern.html)`<`[`B`](../arrow.-kind/map.html#B)`>` |
| [mapFilter](../../arrow.aql.box.functor-filter/arrow.-kind/map-filter.html) | `fun <A, B> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.functor-filter/arrow.-kind/map-filter.html#A)`>.mapFilter(arg1: (`[`A`](../../arrow.aql.box.functor-filter/arrow.-kind/map-filter.html#A)`) -> Option<`[`B`](../../arrow.aql.box.functor-filter/arrow.-kind/map-filter.html#B)`>): `[`Box`](../../arrow.aql/-box/index.html)`<`[`B`](../../arrow.aql.box.functor-filter/arrow.-kind/map-filter.html#B)`>` |
| [nonEmpty](../../arrow.aql.box.foldable/arrow.-kind/non-empty.html) | `fun <A> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/non-empty.html#A)`>.nonEmpty(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [query](../../arrow.aql.box.select/arrow.-kind/query.html) | `infix fun <A, Z> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.select/arrow.-kind/query.html#A)`>.query(arg1: Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.select/arrow.-kind/query.html#A)`>.() -> `[`Z`](../../arrow.aql.box.select/arrow.-kind/query.html#Z)`): `[`Z`](../../arrow.aql.box.select/arrow.-kind/query.html#Z) |
| [reduceLeftOption](../../arrow.aql.box.foldable/arrow.-kind/reduce-left-option.html) | `fun <A> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/reduce-left-option.html#A)`>.reduceLeftOption(arg1: (`[`A`](../../arrow.aql.box.foldable/arrow.-kind/reduce-left-option.html#A)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/reduce-left-option.html#A)`) -> `[`A`](../../arrow.aql.box.foldable/arrow.-kind/reduce-left-option.html#A)`): Option<`[`A`](../../arrow.aql.box.foldable/arrow.-kind/reduce-left-option.html#A)`>` |
| [reduceLeftToOption](../../arrow.aql.box.foldable/arrow.-kind/reduce-left-to-option.html) | `fun <A, B> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/reduce-left-to-option.html#A)`>.reduceLeftToOption(arg1: (`[`A`](../../arrow.aql.box.foldable/arrow.-kind/reduce-left-to-option.html#A)`) -> `[`B`](../../arrow.aql.box.foldable/arrow.-kind/reduce-left-to-option.html#B)`, arg2: (`[`B`](../../arrow.aql.box.foldable/arrow.-kind/reduce-left-to-option.html#B)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/reduce-left-to-option.html#A)`) -> `[`B`](../../arrow.aql.box.foldable/arrow.-kind/reduce-left-to-option.html#B)`): Option<`[`B`](../../arrow.aql.box.foldable/arrow.-kind/reduce-left-to-option.html#B)`>` |
| [reduceRightOption](../../arrow.aql.box.foldable/arrow.-kind/reduce-right-option.html) | `fun <A> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/reduce-right-option.html#A)`>.reduceRightOption(arg1: (`[`A`](../../arrow.aql.box.foldable/arrow.-kind/reduce-right-option.html#A)`, Eval<`[`A`](../../arrow.aql.box.foldable/arrow.-kind/reduce-right-option.html#A)`>) -> Eval<`[`A`](../../arrow.aql.box.foldable/arrow.-kind/reduce-right-option.html#A)`>): Eval<Option<`[`A`](../../arrow.aql.box.foldable/arrow.-kind/reduce-right-option.html#A)`>>` |
| [reduceRightToOption](../../arrow.aql.box.foldable/arrow.-kind/reduce-right-to-option.html) | `fun <A, B> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/reduce-right-to-option.html#A)`>.reduceRightToOption(arg1: (`[`A`](../../arrow.aql.box.foldable/arrow.-kind/reduce-right-to-option.html#A)`) -> `[`B`](../../arrow.aql.box.foldable/arrow.-kind/reduce-right-to-option.html#B)`, arg2: (`[`A`](../../arrow.aql.box.foldable/arrow.-kind/reduce-right-to-option.html#A)`, Eval<`[`B`](../../arrow.aql.box.foldable/arrow.-kind/reduce-right-to-option.html#B)`>) -> Eval<`[`B`](../../arrow.aql.box.foldable/arrow.-kind/reduce-right-to-option.html#B)`>): Eval<Option<`[`B`](../../arrow.aql.box.foldable/arrow.-kind/reduce-right-to-option.html#B)`>>` |
| [select](../../arrow.aql.box.select/arrow.-kind/select.html) | `infix fun <A, Z> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.select/arrow.-kind/select.html#A)`>.select(arg1: `[`A`](../../arrow.aql.box.select/arrow.-kind/select.html#A)`.() -> `[`Z`](../../arrow.aql.box.select/arrow.-kind/select.html#Z)`): Query<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.select/arrow.-kind/select.html#A)`, `[`Z`](../../arrow.aql.box.select/arrow.-kind/select.html#Z)`>` |
| [selectAll](../../arrow.aql.box.select/arrow.-kind/select-all.html) | `fun <A> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.select/arrow.-kind/select-all.html#A)`>.selectAll(): Query<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.select/arrow.-kind/select-all.html#A)`, `[`A`](../../arrow.aql.box.select/arrow.-kind/select-all.html#A)`>` |
| [size](../../arrow.aql.box.foldable/arrow.-kind/size.html) | `fun <A> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/size.html#A)`>.size(arg1: Monoid<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [startF](../../arrow.effects/arrow.-kind/start-f.html) | `fun <A> DeferredKOf<`[`A`](../../arrow.effects/arrow.-kind/start-f.html#A)`>.startF(ctx: `[`CoroutineContext`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-coroutine-context/index.html)` = Dispatchers.Default): DeferredK<Fiber<ForDeferredK, `[`A`](../../arrow.effects/arrow.-kind/start-f.html#A)`>>` |
| [traverse_](../../arrow.aql.box.foldable/arrow.-kind/traverse_.html) | `fun <G, A, B> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.foldable/arrow.-kind/traverse_.html#A)`>.traverse_(arg1: Applicative<`[`G`](../../arrow.aql.box.foldable/arrow.-kind/traverse_.html#G)`>, arg2: (`[`A`](../../arrow.aql.box.foldable/arrow.-kind/traverse_.html#A)`) -> Kind<`[`G`](../../arrow.aql.box.foldable/arrow.-kind/traverse_.html#G)`, `[`B`](../../arrow.aql.box.foldable/arrow.-kind/traverse_.html#B)`>): Kind<`[`G`](../../arrow.aql.box.foldable/arrow.-kind/traverse_.html#G)`, `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>` |
| [tupleLeft](../../arrow.aql.box.functor/arrow.-kind/tuple-left.html) | `fun <A, B> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.functor/arrow.-kind/tuple-left.html#A)`>.tupleLeft(arg1: `[`B`](../../arrow.aql.box.functor/arrow.-kind/tuple-left.html#B)`): `[`Box`](../../arrow.aql/-box/index.html)`<Tuple2<`[`B`](../../arrow.aql.box.functor/arrow.-kind/tuple-left.html#B)`, `[`A`](../../arrow.aql.box.functor/arrow.-kind/tuple-left.html#A)`>>` |
| [tupleLeft](../arrow.-kind/tuple-left.html) | `fun <A, B> Kind<`[`ForIntListPattern`](../-for-int-list-pattern.html)`, `[`A`](../arrow.-kind/tuple-left.html#A)`>.tupleLeft(arg1: `[`B`](../arrow.-kind/tuple-left.html#B)`): `[`IntListPattern`](../-int-list-pattern.html)`<Tuple2<`[`B`](../arrow.-kind/tuple-left.html#B)`, `[`A`](../arrow.-kind/tuple-left.html#A)`>>` |
| [tupleRight](../../arrow.aql.box.functor/arrow.-kind/tuple-right.html) | `fun <A, B> Kind<`[`ForBox`](../../arrow.aql/-for-box.html)`, `[`A`](../../arrow.aql.box.functor/arrow.-kind/tuple-right.html#A)`>.tupleRight(arg1: `[`B`](../../arrow.aql.box.functor/arrow.-kind/tuple-right.html#B)`): `[`Box`](../../arrow.aql/-box/index.html)`<Tuple2<`[`A`](../../arrow.aql.box.functor/arrow.-kind/tuple-right.html#A)`, `[`B`](../../arrow.aql.box.functor/arrow.-kind/tuple-right.html#B)`>>` |
| [tupleRight](../arrow.-kind/tuple-right.html) | `fun <A, B> Kind<`[`ForIntListPattern`](../-for-int-list-pattern.html)`, `[`A`](../arrow.-kind/tuple-right.html#A)`>.tupleRight(arg1: `[`B`](../arrow.-kind/tuple-right.html#B)`): `[`IntListPattern`](../-int-list-pattern.html)`<Tuple2<`[`A`](../arrow.-kind/tuple-right.html#A)`, `[`B`](../arrow.-kind/tuple-right.html#B)`>>` |
