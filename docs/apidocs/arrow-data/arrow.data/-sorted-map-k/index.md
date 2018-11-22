---
title: SortedMapK - arrow-data
---

[arrow-data](../../index.html) / [arrow.data](../index.html) / [SortedMapK](./index.html)

# SortedMapK

`@higherkind data class SortedMapK<A : `[`Comparable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)`<`[`A`](index.html#A)`>, B> : `[`SortedMapKOf`](../-sorted-map-k-of.html)`<`[`A`](index.html#A)`, `[`B`](index.html#B)`>, `[`SortedMapKKindedJ`](../-sorted-map-k-kinded-j.html)`<`[`A`](index.html#A)`, `[`B`](index.html#B)`>, `[`SortedMap`](../-sorted-map.html)`<`[`A`](index.html#A)`, `[`B`](index.html#B)`>`

### Constructors

| [&lt;init&gt;](-init-.html) | `SortedMapK(map: `[`SortedMap`](../-sorted-map.html)`<`[`A`](index.html#A)`, `[`B`](index.html#B)`>)` |

### Functions

| [ap](ap.html) | `fun <C> ap(ff: `[`SortedMapK`](./index.html)`<`[`A`](index.html#A)`, (`[`B`](index.html#B)`) -> `[`C`](ap.html#C)`>): `[`SortedMapK`](./index.html)`<`[`A`](index.html#A)`, `[`C`](ap.html#C)`>` |
| [ap2](ap2.html) | `fun <C, Z> ap2(f: `[`SortedMapK`](./index.html)`<`[`A`](index.html#A)`, (`[`B`](index.html#B)`, `[`C`](ap2.html#C)`) -> `[`Z`](ap2.html#Z)`>, fc: `[`SortedMapK`](./index.html)`<`[`A`](index.html#A)`, `[`C`](ap2.html#C)`>): `[`SortedMap`](../-sorted-map.html)`<`[`A`](index.html#A)`, `[`Z`](ap2.html#Z)`>` |
| [equals](equals.html) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [flatMap](flat-map.html) | `fun <C> flatMap(f: (`[`B`](index.html#B)`) -> `[`SortedMapK`](./index.html)`<`[`A`](index.html#A)`, `[`C`](flat-map.html#C)`>): `[`SortedMapK`](./index.html)`<`[`A`](index.html#A)`, `[`C`](flat-map.html#C)`>` |
| [foldLeft](fold-left.html) | `fun <C> foldLeft(c: `[`C`](fold-left.html#C)`, f: (`[`C`](fold-left.html#C)`, `[`B`](index.html#B)`) -> `[`C`](fold-left.html#C)`): `[`C`](fold-left.html#C)<br>`fun <C> foldLeft(c: `[`SortedMapK`](./index.html)`<`[`A`](index.html#A)`, `[`C`](fold-left.html#C)`>, f: (`[`SortedMapK`](./index.html)`<`[`A`](index.html#A)`, `[`C`](fold-left.html#C)`>, Tuple2<`[`A`](index.html#A)`, `[`B`](index.html#B)`>) -> `[`SortedMapK`](./index.html)`<`[`A`](index.html#A)`, `[`C`](fold-left.html#C)`>): `[`SortedMapK`](./index.html)`<`[`A`](index.html#A)`, `[`C`](fold-left.html#C)`>` |
| [foldRight](fold-right.html) | `fun <C> foldRight(c: Eval<`[`C`](fold-right.html#C)`>, f: (`[`B`](index.html#B)`, Eval<`[`C`](fold-right.html#C)`>) -> Eval<`[`C`](fold-right.html#C)`>): Eval<`[`C`](fold-right.html#C)`>` |
| [hashCode](hash-code.html) | `fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [map](map.html) | `fun <C> map(f: (`[`B`](index.html#B)`) -> `[`C`](map.html#C)`): `[`SortedMapK`](./index.html)`<`[`A`](index.html#A)`, `[`C`](map.html#C)`>` |
| [map2](map2.html) | `fun <C, Z> map2(fc: `[`SortedMapK`](./index.html)`<`[`A`](index.html#A)`, `[`C`](map2.html#C)`>, f: (`[`B`](index.html#B)`, `[`C`](map2.html#C)`) -> `[`Z`](map2.html#Z)`): `[`SortedMapK`](./index.html)`<`[`A`](index.html#A)`, `[`Z`](map2.html#Z)`>` |
| [map2Eval](map2-eval.html) | `fun <C, Z> map2Eval(fc: Eval<`[`SortedMapK`](./index.html)`<`[`A`](index.html#A)`, `[`C`](map2-eval.html#C)`>>, f: (`[`B`](index.html#B)`, `[`C`](map2-eval.html#C)`) -> `[`Z`](map2-eval.html#Z)`): Eval<`[`SortedMapK`](./index.html)`<`[`A`](index.html#A)`, `[`Z`](map2-eval.html#Z)`>>` |
| [traverse](traverse.html) | `fun <G, C> traverse(GA: Applicative<`[`G`](traverse.html#G)`>, f: (`[`B`](index.html#B)`) -> Kind<`[`G`](traverse.html#G)`, `[`C`](traverse.html#C)`>): Kind<`[`G`](traverse.html#G)`, `[`SortedMapK`](./index.html)`<`[`A`](index.html#A)`, `[`C`](traverse.html#C)`>>` |

### Extension Functions

| [ap](../arrow.-kind/ap.html) | `fun <E, A, B> `[`ValidatedOf`](../-validated-of.html)`<`[`E`](../arrow.-kind/ap.html#E)`, `[`A`](../arrow.-kind/ap.html#A)`>.ap(SE: Semigroup<`[`E`](../arrow.-kind/ap.html#E)`>, f: `[`Validated`](../-validated/index.html)`<`[`E`](../arrow.-kind/ap.html#E)`, (`[`A`](../arrow.-kind/ap.html#A)`) -> `[`B`](../arrow.-kind/ap.html#B)`>): `[`Validated`](../-validated/index.html)`<`[`E`](../arrow.-kind/ap.html#E)`, `[`B`](../arrow.-kind/ap.html#B)`>`<br>From Apply: if both the function and this value are Valid, apply the function |
| [combine](../arrow.-kind/combine.html) | `fun <E, A> `[`ValidatedOf`](../-validated-of.html)`<`[`E`](../arrow.-kind/combine.html#E)`, `[`A`](../arrow.-kind/combine.html#A)`>.combine(SE: Semigroup<`[`E`](../arrow.-kind/combine.html#E)`>, SA: Semigroup<`[`A`](../arrow.-kind/combine.html#A)`>, y: `[`ValidatedOf`](../-validated-of.html)`<`[`E`](../arrow.-kind/combine.html#E)`, `[`A`](../arrow.-kind/combine.html#A)`>): `[`Validated`](../-validated/index.html)`<`[`E`](../arrow.-kind/combine.html#E)`, `[`A`](../arrow.-kind/combine.html#A)`>` |
| [combineK](../arrow.-kind/combine-k.html) | `fun <A> `[`ListKOf`](../-list-k-of.html)`<`[`A`](../arrow.-kind/combine-k.html#A)`>.combineK(y: `[`ListKOf`](../-list-k-of.html)`<`[`A`](../arrow.-kind/combine-k.html#A)`>): `[`ListK`](../-list-k/index.html)`<`[`A`](../arrow.-kind/combine-k.html#A)`>`<br>`fun <A> `[`NonEmptyListOf`](../-non-empty-list-of.html)`<`[`A`](../arrow.-kind/combine-k.html#A)`>.combineK(y: `[`NonEmptyListOf`](../-non-empty-list-of.html)`<`[`A`](../arrow.-kind/combine-k.html#A)`>): `[`NonEmptyList`](../-non-empty-list/index.html)`<`[`A`](../arrow.-kind/combine-k.html#A)`>`<br>`fun <A> `[`SequenceKOf`](../-sequence-k-of.html)`<`[`A`](../arrow.-kind/combine-k.html#A)`>.combineK(y: `[`SequenceKOf`](../-sequence-k-of.html)`<`[`A`](../arrow.-kind/combine-k.html#A)`>): `[`SequenceK`](../-sequence-k/index.html)`<`[`A`](../arrow.-kind/combine-k.html#A)`>`<br>`fun <A> `[`SetKOf`](../-set-k-of.html)`<`[`A`](../arrow.-kind/combine-k.html#A)`>.combineK(y: `[`SetKOf`](../-set-k-of.html)`<`[`A`](../arrow.-kind/combine-k.html#A)`>): `[`SetK`](../-set-k/index.html)`<`[`A`](../arrow.-kind/combine-k.html#A)`>`<br>`fun <E, A> `[`ValidatedOf`](../-validated-of.html)`<`[`E`](../arrow.-kind/combine-k.html#E)`, `[`A`](../arrow.-kind/combine-k.html#A)`>.combineK(SE: Semigroup<`[`E`](../arrow.-kind/combine-k.html#E)`>, y: `[`ValidatedOf`](../-validated-of.html)`<`[`E`](../arrow.-kind/combine-k.html#E)`, `[`A`](../arrow.-kind/combine-k.html#A)`>): `[`Validated`](../-validated/index.html)`<`[`E`](../arrow.-kind/combine-k.html#E)`, `[`A`](../arrow.-kind/combine-k.html#A)`>` |
| [findValid](../arrow.-kind/find-valid.html) | `fun <E, A> `[`ValidatedOf`](../-validated-of.html)`<`[`E`](../arrow.-kind/find-valid.html#E)`, `[`A`](../arrow.-kind/find-valid.html#A)`>.findValid(SE: Semigroup<`[`E`](../arrow.-kind/find-valid.html#E)`>, that: () -> `[`Validated`](../-validated/index.html)`<`[`E`](../arrow.-kind/find-valid.html#E)`, `[`A`](../arrow.-kind/find-valid.html#A)`>): `[`Validated`](../-validated/index.html)`<`[`E`](../arrow.-kind/find-valid.html#E)`, `[`A`](../arrow.-kind/find-valid.html#A)`>`<br>If `this` is valid return `this`, otherwise if `that` is valid return `that`, otherwise combine the failures. This is similar to [orElse](../arrow.-kind/or-else.html) except that here failures are accumulated. |
| [foldLeft](../kotlin.collections.-map/fold-left.html) | `fun <K, A, B> `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`K`](../kotlin.collections.-map/fold-left.html#K)`, `[`A`](../kotlin.collections.-map/fold-left.html#A)`>.foldLeft(b: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`K`](../kotlin.collections.-map/fold-left.html#K)`, `[`B`](../kotlin.collections.-map/fold-left.html#B)`>, f: (`[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`K`](../kotlin.collections.-map/fold-left.html#K)`, `[`B`](../kotlin.collections.-map/fold-left.html#B)`>, `[`Entry`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/-entry/index.html)`<`[`K`](../kotlin.collections.-map/fold-left.html#K)`, `[`A`](../kotlin.collections.-map/fold-left.html#A)`>) -> `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`K`](../kotlin.collections.-map/fold-left.html#K)`, `[`B`](../kotlin.collections.-map/fold-left.html#B)`>): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`K`](../kotlin.collections.-map/fold-left.html#K)`, `[`B`](../kotlin.collections.-map/fold-left.html#B)`>` |
| [foldLeft](../java.util.-sorted-map/fold-left.html) | `fun <A, B, C> `[`SortedMap`](../-sorted-map.html)`<`[`A`](../java.util.-sorted-map/fold-left.html#A)`, `[`B`](../java.util.-sorted-map/fold-left.html#B)`>.foldLeft(b: `[`SortedMap`](../-sorted-map.html)`<`[`A`](../java.util.-sorted-map/fold-left.html#A)`, `[`C`](../java.util.-sorted-map/fold-left.html#C)`>, f: (`[`SortedMap`](../-sorted-map.html)`<`[`A`](../java.util.-sorted-map/fold-left.html#A)`, `[`C`](../java.util.-sorted-map/fold-left.html#C)`>, `[`Entry`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/-entry/index.html)`<`[`A`](../java.util.-sorted-map/fold-left.html#A)`, `[`B`](../java.util.-sorted-map/fold-left.html#B)`>) -> `[`SortedMap`](../-sorted-map.html)`<`[`A`](../java.util.-sorted-map/fold-left.html#A)`, `[`C`](../java.util.-sorted-map/fold-left.html#C)`>): `[`SortedMap`](../-sorted-map.html)`<`[`A`](../java.util.-sorted-map/fold-left.html#A)`, `[`C`](../java.util.-sorted-map/fold-left.html#C)`>` |
| [foldRight](../kotlin.collections.-map/fold-right.html) | `fun <K, A, B> `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`K`](../kotlin.collections.-map/fold-right.html#K)`, `[`A`](../kotlin.collections.-map/fold-right.html#A)`>.foldRight(b: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`K`](../kotlin.collections.-map/fold-right.html#K)`, `[`B`](../kotlin.collections.-map/fold-right.html#B)`>, f: (`[`Entry`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/-entry/index.html)`<`[`K`](../kotlin.collections.-map/fold-right.html#K)`, `[`A`](../kotlin.collections.-map/fold-right.html#A)`>, `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`K`](../kotlin.collections.-map/fold-right.html#K)`, `[`B`](../kotlin.collections.-map/fold-right.html#B)`>) -> `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`K`](../kotlin.collections.-map/fold-right.html#K)`, `[`B`](../kotlin.collections.-map/fold-right.html#B)`>): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`K`](../kotlin.collections.-map/fold-right.html#K)`, `[`B`](../kotlin.collections.-map/fold-right.html#B)`>` |
| [foldRight](../java.util.-sorted-map/fold-right.html) | `fun <A : `[`Comparable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)`<`[`A`](../java.util.-sorted-map/fold-right.html#A)`>, B, C> `[`SortedMap`](../-sorted-map.html)`<`[`A`](../java.util.-sorted-map/fold-right.html#A)`, `[`B`](../java.util.-sorted-map/fold-right.html#B)`>.foldRight(b: `[`SortedMap`](../-sorted-map.html)`<`[`A`](../java.util.-sorted-map/fold-right.html#A)`, `[`C`](../java.util.-sorted-map/fold-right.html#C)`>, f: (`[`Entry`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/-entry/index.html)`<`[`A`](../java.util.-sorted-map/fold-right.html#A)`, `[`B`](../java.util.-sorted-map/fold-right.html#B)`>, `[`SortedMap`](../-sorted-map.html)`<`[`A`](../java.util.-sorted-map/fold-right.html#A)`, `[`C`](../java.util.-sorted-map/fold-right.html#C)`>) -> `[`SortedMap`](../-sorted-map.html)`<`[`A`](../java.util.-sorted-map/fold-right.html#A)`, `[`C`](../java.util.-sorted-map/fold-right.html#C)`>): `[`SortedMap`](../-sorted-map.html)`<`[`A`](../java.util.-sorted-map/fold-right.html#A)`, `[`C`](../java.util.-sorted-map/fold-right.html#C)`>` |
| [getOption](../kotlin.collections.-map/get-option.html) | `fun <K, A> `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`K`](../kotlin.collections.-map/get-option.html#K)`, `[`A`](../kotlin.collections.-map/get-option.html#A)`>.getOption(k: `[`K`](../kotlin.collections.-map/get-option.html#K)`): Option<`[`A`](../kotlin.collections.-map/get-option.html#A)`>` |
| [getOption](../java.util.-sorted-map/get-option.html) | `fun <A, B> `[`SortedMap`](../-sorted-map.html)`<`[`A`](../java.util.-sorted-map/get-option.html#A)`, `[`B`](../java.util.-sorted-map/get-option.html#B)`>.getOption(k: `[`A`](../java.util.-sorted-map/get-option.html#A)`): Option<`[`B`](../java.util.-sorted-map/get-option.html#B)`>` |
| [getOrElse](../arrow.-kind/get-or-else.html) | `fun <E, B> `[`ValidatedOf`](../-validated-of.html)`<`[`E`](../arrow.-kind/get-or-else.html#E)`, `[`B`](../arrow.-kind/get-or-else.html#B)`>.getOrElse(default: () -> `[`B`](../arrow.-kind/get-or-else.html#B)`): `[`B`](../arrow.-kind/get-or-else.html#B)<br>Return the Valid value, or the default if Invalid |
| [handleLeftWith](../arrow.-kind/handle-left-with.html) | `fun <E, A> `[`ValidatedOf`](../-validated-of.html)`<`[`E`](../arrow.-kind/handle-left-with.html#E)`, `[`A`](../arrow.-kind/handle-left-with.html#A)`>.handleLeftWith(f: (`[`E`](../arrow.-kind/handle-left-with.html#E)`) -> `[`ValidatedOf`](../-validated-of.html)`<`[`E`](../arrow.-kind/handle-left-with.html#E)`, `[`A`](../arrow.-kind/handle-left-with.html#A)`>): `[`Validated`](../-validated/index.html)`<`[`E`](../arrow.-kind/handle-left-with.html#E)`, `[`A`](../arrow.-kind/handle-left-with.html#A)`>` |
| [mapFilter](../arrow.-kind/map-filter.html) | `fun <F, A, B> `[`OptionTOf`](../-option-t-of.html)`<`[`F`](../arrow.-kind/map-filter.html#F)`, `[`A`](../arrow.-kind/map-filter.html#A)`>.mapFilter(FF: Functor<`[`F`](../arrow.-kind/map-filter.html#F)`>, f: (`[`A`](../arrow.-kind/map-filter.html#A)`) -> Option<`[`B`](../arrow.-kind/map-filter.html#B)`>): `[`OptionT`](../-option-t/index.html)`<`[`F`](../arrow.-kind/map-filter.html#F)`, `[`B`](../arrow.-kind/map-filter.html#B)`>` |
| [orElse](../arrow.-kind/or-else.html) | `fun <E, A> `[`ValidatedOf`](../-validated-of.html)`<`[`E`](../arrow.-kind/or-else.html#E)`, `[`A`](../arrow.-kind/or-else.html#A)`>.orElse(default: () -> `[`Validated`](../-validated/index.html)`<`[`E`](../arrow.-kind/or-else.html#E)`, `[`A`](../arrow.-kind/or-else.html#A)`>): `[`Validated`](../-validated/index.html)`<`[`E`](../arrow.-kind/or-else.html#E)`, `[`A`](../arrow.-kind/or-else.html#A)`>`<br>Return this if it is Valid, or else fall back to the given default. The functionality is similar to that of [findValid](../arrow.-kind/find-valid.html) except for failure accumulation, where here only the error on the right is preserved and the error on the left is ignored. |
| [orNull](../arrow.-kind/or-null.html) | `fun <E, B> `[`ValidatedOf`](../-validated-of.html)`<`[`E`](../arrow.-kind/or-null.html#E)`, `[`B`](../arrow.-kind/or-null.html#B)`>.orNull(): `[`B`](../arrow.-kind/or-null.html#B)`?`<br>Return the Valid value, or null if Invalid |
| [runM](../arrow.-kind/run-m.html) | `fun <F, S, A> `[`StateTOf`](../-state-t-of.html)`<`[`F`](../arrow.-kind/run-m.html#F)`, `[`S`](../arrow.-kind/run-m.html#S)`, `[`A`](../arrow.-kind/run-m.html#A)`>.runM(MF: Monad<`[`F`](../arrow.-kind/run-m.html#F)`>, initial: `[`S`](../arrow.-kind/run-m.html#S)`): Kind<`[`F`](../arrow.-kind/run-m.html#F)`, Tuple2<`[`S`](../arrow.-kind/run-m.html#S)`, `[`A`](../arrow.-kind/run-m.html#A)`>>`<br>Run the stateful computation within the context `F`. |
| [stateT](../arrow.-kind/state-t.html) | `fun <F, S, A> `[`StateTFunOf`](../-state-t-fun-of.html)`<`[`F`](../arrow.-kind/state-t.html#F)`, `[`S`](../arrow.-kind/state-t.html#S)`, `[`A`](../arrow.-kind/state-t.html#A)`>.stateT(): `[`StateT`](../-state-t/index.html)`<`[`F`](../arrow.-kind/state-t.html#F)`, `[`S`](../arrow.-kind/state-t.html#S)`, `[`A`](../arrow.-kind/state-t.html#A)`>`<br>Wrap the function with [StateT](../-state-t/index.html). |
| [toIor](../arrow.-kind/to-ior.html) | `fun <E, A> `[`ValidatedOf`](../-validated-of.html)`<`[`E`](../arrow.-kind/to-ior.html#E)`, `[`A`](../arrow.-kind/to-ior.html#A)`>.toIor(): `[`Ior`](../-ior/index.html)`<`[`E`](../arrow.-kind/to-ior.html#E)`, `[`A`](../arrow.-kind/to-ior.html#A)`>`<br>Converts the value to an Ior&lt;E, A&gt; |
| [toList](../arrow.-kind/to-list.html) | `fun <A> `[`SequenceKOf`](../-sequence-k-of.html)`<`[`A`](../arrow.-kind/to-list.html#A)`>.toList(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`A`](../arrow.-kind/to-list.html#A)`>` |
| [traverse](../arrow.-kind/traverse.html) | `fun <G, E, A, B> `[`ValidatedOf`](../-validated-of.html)`<`[`E`](../arrow.-kind/traverse.html#E)`, `[`A`](../arrow.-kind/traverse.html#A)`>.traverse(GA: Applicative<`[`G`](../arrow.-kind/traverse.html#G)`>, f: (`[`A`](../arrow.-kind/traverse.html#A)`) -> Kind<`[`G`](../arrow.-kind/traverse.html#G)`, `[`B`](../arrow.-kind/traverse.html#B)`>): Kind<`[`G`](../arrow.-kind/traverse.html#G)`, `[`Validated`](../-validated/index.html)`<`[`E`](../arrow.-kind/traverse.html#E)`, `[`B`](../arrow.-kind/traverse.html#B)`>>` |
| [updated](../updated.html) | `fun <A : `[`Comparable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)`<`[`A`](../updated.html#A)`>, B> `[`SortedMapK`](./index.html)`<`[`A`](../updated.html#A)`, `[`B`](../updated.html#B)`>.updated(k: `[`A`](../updated.html#A)`, value: `[`B`](../updated.html#B)`): `[`SortedMapK`](./index.html)`<`[`A`](../updated.html#A)`, `[`B`](../updated.html#B)`>` |
| [valueOr](../arrow.-kind/value-or.html) | `fun <E, B> `[`ValidatedOf`](../-validated-of.html)`<`[`E`](../arrow.-kind/value-or.html#E)`, `[`B`](../arrow.-kind/value-or.html#B)`>.valueOr(f: (`[`E`](../arrow.-kind/value-or.html#E)`) -> `[`B`](../arrow.-kind/value-or.html#B)`): `[`B`](../arrow.-kind/value-or.html#B)<br>Return the Valid value, or the result of f if Invalid |
