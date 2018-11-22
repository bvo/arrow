---
title: PSetter - arrow-optics
---

[arrow-optics](../../index.html) / [arrow.optics](../index.html) / [PSetter](./index.html)

# PSetter

`@higherkind interface PSetter<S, T, A, B> : `[`PSetterOf`](../-p-setter-of.html)`<`[`S`](index.html#S)`, `[`T`](index.html#T)`, `[`A`](index.html#A)`, `[`B`](index.html#B)`>`

A [Setter](../-setter.html) is an optic that allows to see into a structure and set or modify its focus.

A (polymorphic) [PSetter](./index.html) is useful when setting or modifying a value for a constructed type
i.e. PSetter&lt;List, List, Int, String&gt;

A [PSetter](./index.html) is a generalisation of a [arrow.Functor](#).
Functor::map   (fa: Kind&lt;F, A&gt;, f: (A) -&gt; B): Kind&lt;F, B&gt;
PSetter::modify(s: S,         f: (A) -&gt; B): T

### Parameters

`S` - the source of a [PSetter](./index.html)

`T` - the modified source of a [PSetter](./index.html)

`A` - the focus of a [PSetter](./index.html)

`B` - the modified focus of a [PSetter](./index.html)

### Functions

| [choice](choice.html) | `open infix fun <U, V> choice(other: `[`PSetter`](./index.html)`<`[`U`](choice.html#U)`, `[`V`](choice.html#V)`, `[`A`](index.html#A)`, `[`B`](index.html#B)`>): `[`PSetter`](./index.html)`<Either<`[`S`](index.html#S)`, `[`U`](choice.html#U)`>, Either<`[`T`](index.html#T)`, `[`V`](choice.html#V)`>, `[`A`](index.html#A)`, `[`B`](index.html#B)`>`<br>Join two [PSetter](./index.html) with the same target |
| [compose](compose.html) | `open infix fun <C, D> compose(other: `[`PSetter`](./index.html)`<`[`A`](index.html#A)`, `[`B`](index.html#B)`, `[`C`](compose.html#C)`, `[`D`](compose.html#D)`>): `[`PSetter`](./index.html)`<`[`S`](index.html#S)`, `[`T`](index.html#T)`, `[`C`](compose.html#C)`, `[`D`](compose.html#D)`>`<br>Compose a [PSetter](./index.html) with a [PSetter](./index.html)`open infix fun <C, D> compose(other: `[`POptional`](../-p-optional/index.html)`<`[`A`](index.html#A)`, `[`B`](index.html#B)`, `[`C`](compose.html#C)`, `[`D`](compose.html#D)`>): `[`PSetter`](./index.html)`<`[`S`](index.html#S)`, `[`T`](index.html#T)`, `[`C`](compose.html#C)`, `[`D`](compose.html#D)`>`<br>Compose a [PSetter](./index.html) with a [POptional](../-p-optional/index.html)`open infix fun <C, D> compose(other: `[`PPrism`](../-p-prism/index.html)`<`[`A`](index.html#A)`, `[`B`](index.html#B)`, `[`C`](compose.html#C)`, `[`D`](compose.html#D)`>): `[`PSetter`](./index.html)`<`[`S`](index.html#S)`, `[`T`](index.html#T)`, `[`C`](compose.html#C)`, `[`D`](compose.html#D)`>`<br>Compose a [PSetter](./index.html) with a [PPrism](../-p-prism/index.html)`open infix fun <C, D> compose(other: `[`PLens`](../-p-lens/index.html)`<`[`A`](index.html#A)`, `[`B`](index.html#B)`, `[`C`](compose.html#C)`, `[`D`](compose.html#D)`>): `[`PSetter`](./index.html)`<`[`S`](index.html#S)`, `[`T`](index.html#T)`, `[`C`](compose.html#C)`, `[`D`](compose.html#D)`>`<br>Compose a [PSetter](./index.html) with a [PLens](../-p-lens/index.html)`open infix fun <C, D> compose(other: `[`PIso`](../-p-iso/index.html)`<`[`A`](index.html#A)`, `[`B`](index.html#B)`, `[`C`](compose.html#C)`, `[`D`](compose.html#D)`>): `[`PSetter`](./index.html)`<`[`S`](index.html#S)`, `[`T`](index.html#T)`, `[`C`](compose.html#C)`, `[`D`](compose.html#D)`>`<br>Compose a [PSetter](./index.html) with a [PIso](../-p-iso/index.html)`open infix fun <C, D> compose(other: `[`PTraversal`](../-p-traversal/index.html)`<`[`A`](index.html#A)`, `[`B`](index.html#B)`, `[`C`](compose.html#C)`, `[`D`](compose.html#D)`>): `[`PSetter`](./index.html)`<`[`S`](index.html#S)`, `[`T`](index.html#T)`, `[`C`](compose.html#C)`, `[`D`](compose.html#D)`>`<br>Compose a [PSetter](./index.html) with a [PTraversal](../-p-traversal/index.html) |
| [lift](lift.html) | `open fun lift(f: (`[`A`](index.html#A)`) -> `[`B`](index.html#B)`): (`[`S`](index.html#S)`) -> `[`T`](index.html#T)<br>Lift a function [f](lift.html#arrow.optics.PSetter$lift(kotlin.Function1((arrow.optics.PSetter.A, arrow.optics.PSetter.B)))/f): `(A) -> B to the context of `S`: `(S) -&gt; T` |
| [modify](modify.html) | `abstract fun modify(s: `[`S`](index.html#S)`, f: (`[`A`](index.html#A)`) -> `[`B`](index.html#B)`): `[`T`](index.html#T)<br>Modify polymorphically the focus of a [PSetter](./index.html) with a function [f](modify.html#arrow.optics.PSetter$modify(arrow.optics.PSetter.S, kotlin.Function1((arrow.optics.PSetter.A, arrow.optics.PSetter.B)))/f). |
| [plus](plus.html) | `open operator fun <C, D> plus(o: `[`PSetter`](./index.html)`<`[`A`](index.html#A)`, `[`B`](index.html#B)`, `[`C`](plus.html#C)`, `[`D`](plus.html#D)`>): `[`PSetter`](./index.html)`<`[`S`](index.html#S)`, `[`T`](index.html#T)`, `[`C`](plus.html#C)`, `[`D`](plus.html#D)`>`<br>Plus operator overload to compose optionals`open operator fun <C, D> plus(o: `[`POptional`](../-p-optional/index.html)`<`[`A`](index.html#A)`, `[`B`](index.html#B)`, `[`C`](plus.html#C)`, `[`D`](plus.html#D)`>): `[`PSetter`](./index.html)`<`[`S`](index.html#S)`, `[`T`](index.html#T)`, `[`C`](plus.html#C)`, `[`D`](plus.html#D)`>`<br>`open operator fun <C, D> plus(o: `[`PPrism`](../-p-prism/index.html)`<`[`A`](index.html#A)`, `[`B`](index.html#B)`, `[`C`](plus.html#C)`, `[`D`](plus.html#D)`>): `[`PSetter`](./index.html)`<`[`S`](index.html#S)`, `[`T`](index.html#T)`, `[`C`](plus.html#C)`, `[`D`](plus.html#D)`>`<br>`open operator fun <C, D> plus(o: `[`PLens`](../-p-lens/index.html)`<`[`A`](index.html#A)`, `[`B`](index.html#B)`, `[`C`](plus.html#C)`, `[`D`](plus.html#D)`>): `[`PSetter`](./index.html)`<`[`S`](index.html#S)`, `[`T`](index.html#T)`, `[`C`](plus.html#C)`, `[`D`](plus.html#D)`>`<br>`open operator fun <C, D> plus(o: `[`PIso`](../-p-iso/index.html)`<`[`A`](index.html#A)`, `[`B`](index.html#B)`, `[`C`](plus.html#C)`, `[`D`](plus.html#D)`>): `[`PSetter`](./index.html)`<`[`S`](index.html#S)`, `[`T`](index.html#T)`, `[`C`](plus.html#C)`, `[`D`](plus.html#D)`>`<br>`open operator fun <C, D> plus(o: `[`PTraversal`](../-p-traversal/index.html)`<`[`A`](index.html#A)`, `[`B`](index.html#B)`, `[`C`](plus.html#C)`, `[`D`](plus.html#D)`>): `[`PSetter`](./index.html)`<`[`S`](index.html#S)`, `[`T`](index.html#T)`, `[`C`](plus.html#C)`, `[`D`](plus.html#D)`>` |
| [set](set.html) | `abstract fun set(s: `[`S`](index.html#S)`, b: `[`B`](index.html#B)`): `[`T`](index.html#T)<br>Set polymorphically the focus of a [PSetter](./index.html) with a value [b](set.html#arrow.optics.PSetter$set(arrow.optics.PSetter.S, arrow.optics.PSetter.B)/b). |

### Companion Object Functions

| [codiagonal](codiagonal.html) | `fun <S> codiagonal(): `[`Setter`](../-setter.html)`<Either<`[`S`](codiagonal.html#S)`, `[`S`](codiagonal.html#S)`>, `[`S`](codiagonal.html#S)`>`<br>[PSetter](./index.html) that takes either S or S and strips the choice of S. |
| [fromFunctor](from-functor.html) | `fun <F, A, B> fromFunctor(FF: Functor<`[`F`](from-functor.html#F)`>): `[`PSetter`](./index.html)`<Kind<`[`F`](from-functor.html#F)`, `[`A`](from-functor.html#A)`>, Kind<`[`F`](from-functor.html#F)`, `[`B`](from-functor.html#B)`>, `[`A`](from-functor.html#A)`, `[`B`](from-functor.html#B)`>`<br>Create a [PSetter](./index.html) from a [arrow.Functor](#) |
| [id](id.html) | `fun <S> id(): `[`PSetter`](./index.html)`<`[`S`](id.html#S)`, `[`S`](id.html#S)`, `[`S`](id.html#S)`, `[`S`](id.html#S)`>` |
| [invoke](invoke.html) | `operator fun <S, T, A, B> invoke(modify: (`[`S`](invoke.html#S)`, (`[`A`](invoke.html#A)`) -> `[`B`](invoke.html#B)`) -> `[`T`](invoke.html#T)`): `[`PSetter`](./index.html)`<`[`S`](invoke.html#S)`, `[`T`](invoke.html#T)`, `[`A`](invoke.html#A)`, `[`B`](invoke.html#B)`>`<br>Invoke operator overload to create a [PSetter](./index.html) of type `S` with target `A`. Can also be used to construct [Setter](../-setter.html) |

### Extension Properties

| [every](../../arrow.optics.typeclasses/-each/every.html) | `open val <T> `[`Setter`](../-setter.html)`<`[`T`](../../arrow.optics.typeclasses/-each/every.html#T)`, `[`S`](../../arrow.optics.typeclasses/-each/index.html#S)`>.every: `[`Setter`](../-setter.html)`<`[`T`](../../arrow.optics.typeclasses/-each/every.html#T)`, `[`A`](../../arrow.optics.typeclasses/-each/index.html#A)`>`<br>DSL to compose [Each](../../arrow.optics.typeclasses/-each/index.html) with a [Setter](../-setter.html) for a structure [S](../../arrow.optics.typeclasses/-each/index.html#S) to see all its foci [A](../../arrow.optics.typeclasses/-each/index.html#A) |
| [some](../../arrow.optics.dsl/some.html) | `val <T, S> `[`Setter`](../-setter.html)`<`[`T`](../../arrow.optics.dsl/some.html#T)`, Option<`[`S`](../../arrow.optics.dsl/some.html#S)`>>.some: `[`Setter`](../-setter.html)`<`[`T`](../../arrow.optics.dsl/some.html#T)`, `[`S`](../../arrow.optics.dsl/some.html#S)`>`<br>DSL to compose a [Prism](../-prism.html) with focus [arrow.core.Some](#) with a [Setter](../-setter.html) with a focus of [Option](#)&lt;[S](../../arrow.optics.dsl/some.html#S)&gt; |

### Extension Functions

| [assign_](../assign_.html) | `fun <S, A> `[`Setter`](../-setter.html)`<`[`S`](../assign_.html#S)`, `[`A`](../assign_.html#A)`>.assign_(a: `[`A`](../assign_.html#A)`): State<`[`S`](../assign_.html#S)`, `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>`<br>Set the focus [A](../assign_.html#A) referenced through the [Setter](../-setter.html). |
| [at](../../arrow.optics.dsl/at.html) | `fun <T, S, I, A> `[`Setter`](../-setter.html)`<`[`T`](../../arrow.optics.dsl/at.html#T)`, `[`S`](../../arrow.optics.dsl/at.html#S)`>.at(AT: `[`At`](../../arrow.optics.typeclasses/-at/index.html)`<`[`S`](../../arrow.optics.dsl/at.html#S)`, `[`I`](../../arrow.optics.dsl/at.html#I)`, `[`A`](../../arrow.optics.dsl/at.html#A)`>, i: `[`I`](../../arrow.optics.dsl/at.html#I)`): `[`Setter`](../-setter.html)`<`[`T`](../../arrow.optics.dsl/at.html#T)`, `[`A`](../../arrow.optics.dsl/at.html#A)`>`<br>DSL to compose [At](../../arrow.optics.typeclasses/-at/index.html) with a [Setter](../-setter.html) for a structure [S](../../arrow.optics.dsl/at.html#S) to focus in on [A](../../arrow.optics.dsl/at.html#A) at given index [I](../../arrow.optics.dsl/at.html#I). |
| [every](../../arrow.optics.dsl/every.html) | `fun <T, S, A> `[`Setter`](../-setter.html)`<`[`T`](../../arrow.optics.dsl/every.html#T)`, `[`S`](../../arrow.optics.dsl/every.html#S)`>.every(EA: `[`Each`](../../arrow.optics.typeclasses/-each/index.html)`<`[`S`](../../arrow.optics.dsl/every.html#S)`, `[`A`](../../arrow.optics.dsl/every.html#A)`>): `[`Setter`](../-setter.html)`<`[`T`](../../arrow.optics.dsl/every.html#T)`, `[`A`](../../arrow.optics.dsl/every.html#A)`>`<br>DSL to compose [Each](../../arrow.optics.typeclasses/-each/index.html) with a [Setter](../-setter.html) for a structure [S](../../arrow.optics.dsl/every.html#S) to see all its foci [A](../../arrow.optics.dsl/every.html#A) |
| [index](../../arrow.optics.dsl/--index--.html) | `fun <T, S, I, A> `[`Setter`](../-setter.html)`<`[`T`](../../arrow.optics.dsl/--index--.html#T)`, `[`S`](../../arrow.optics.dsl/--index--.html#S)`>.index(ID: `[`Index`](../../arrow.optics.typeclasses/-index/index.html)`<`[`S`](../../arrow.optics.dsl/--index--.html#S)`, `[`I`](../../arrow.optics.dsl/--index--.html#I)`, `[`A`](../../arrow.optics.dsl/--index--.html#A)`>, i: `[`I`](../../arrow.optics.dsl/--index--.html#I)`): `[`Setter`](../-setter.html)`<`[`T`](../../arrow.optics.dsl/--index--.html#T)`, `[`A`](../../arrow.optics.dsl/--index--.html#A)`>`<br>DSL to compose [Index](../../arrow.optics.typeclasses/-index/index.html) with a [Setter](../-setter.html) for a structure [S](../../arrow.optics.dsl/--index--.html#S) to focus in on [A](../../arrow.optics.dsl/--index--.html#A) at given index [I](../../arrow.optics.dsl/--index--.html#I) |
| [update_](../update_.html) | `fun <S, A> `[`Setter`](../-setter.html)`<`[`S`](../update_.html#S)`, `[`A`](../update_.html#A)`>.update_(f: (`[`A`](../update_.html#A)`) -> `[`A`](../update_.html#A)`): State<`[`S`](../update_.html#S)`, `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>`<br>Update the focus [A](../update_.html#A) referenced through the [Setter](../-setter.html). |
