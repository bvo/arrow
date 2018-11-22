---
title: arrow.effects.fluxk.applicative - arrow-effects-reactor-instances
---

[arrow-effects-reactor-instances](../index.html) / [arrow.effects.fluxk.applicative](./index.html)

## Package arrow.effects.fluxk.applicative

### Extensions for External Classes

| [arrow.Kind](arrow.-kind/index.html) |  |

### Functions

| [just](just.html) | `fun <A> `[`A`](just.html#A)`.just(): FluxK<`[`A`](just.html#A)`>` |
| [map](map.html) | `fun <A, B, Z> map(arg0: Kind<ForFluxK, `[`A`](map.html#A)`>, arg1: Kind<ForFluxK, `[`B`](map.html#B)`>, arg2: (Tuple2<`[`A`](map.html#A)`, `[`B`](map.html#B)`>) -> `[`Z`](map.html#Z)`): FluxK<`[`Z`](map.html#Z)`>`<br>`fun <A, B, C, Z> map(arg0: Kind<ForFluxK, `[`A`](map.html#A)`>, arg1: Kind<ForFluxK, `[`B`](map.html#B)`>, arg2: Kind<ForFluxK, `[`C`](map.html#C)`>, arg3: (Tuple3<`[`A`](map.html#A)`, `[`B`](map.html#B)`, `[`C`](map.html#C)`>) -> `[`Z`](map.html#Z)`): FluxK<`[`Z`](map.html#Z)`>`<br>`fun <A, B, C, D, Z> map(arg0: Kind<ForFluxK, `[`A`](map.html#A)`>, arg1: Kind<ForFluxK, `[`B`](map.html#B)`>, arg2: Kind<ForFluxK, `[`C`](map.html#C)`>, arg3: Kind<ForFluxK, `[`D`](map.html#D)`>, arg4: (Tuple4<`[`A`](map.html#A)`, `[`B`](map.html#B)`, `[`C`](map.html#C)`, `[`D`](map.html#D)`>) -> `[`Z`](map.html#Z)`): FluxK<`[`Z`](map.html#Z)`>`<br>`fun <A, B, C, D, E, Z> map(arg0: Kind<ForFluxK, `[`A`](map.html#A)`>, arg1: Kind<ForFluxK, `[`B`](map.html#B)`>, arg2: Kind<ForFluxK, `[`C`](map.html#C)`>, arg3: Kind<ForFluxK, `[`D`](map.html#D)`>, arg4: Kind<ForFluxK, `[`E`](map.html#E)`>, arg5: (Tuple5<`[`A`](map.html#A)`, `[`B`](map.html#B)`, `[`C`](map.html#C)`, `[`D`](map.html#D)`, `[`E`](map.html#E)`>) -> `[`Z`](map.html#Z)`): FluxK<`[`Z`](map.html#Z)`>`<br>`fun <A, B, C, D, E, FF, Z> map(arg0: Kind<ForFluxK, `[`A`](map.html#A)`>, arg1: Kind<ForFluxK, `[`B`](map.html#B)`>, arg2: Kind<ForFluxK, `[`C`](map.html#C)`>, arg3: Kind<ForFluxK, `[`D`](map.html#D)`>, arg4: Kind<ForFluxK, `[`E`](map.html#E)`>, arg5: Kind<ForFluxK, `[`FF`](map.html#FF)`>, arg6: (Tuple6<`[`A`](map.html#A)`, `[`B`](map.html#B)`, `[`C`](map.html#C)`, `[`D`](map.html#D)`, `[`E`](map.html#E)`, `[`FF`](map.html#FF)`>) -> `[`Z`](map.html#Z)`): FluxK<`[`Z`](map.html#Z)`>`<br>`fun <A, B, C, D, E, FF, G, Z> map(arg0: Kind<ForFluxK, `[`A`](map.html#A)`>, arg1: Kind<ForFluxK, `[`B`](map.html#B)`>, arg2: Kind<ForFluxK, `[`C`](map.html#C)`>, arg3: Kind<ForFluxK, `[`D`](map.html#D)`>, arg4: Kind<ForFluxK, `[`E`](map.html#E)`>, arg5: Kind<ForFluxK, `[`FF`](map.html#FF)`>, arg6: Kind<ForFluxK, `[`G`](map.html#G)`>, arg7: (Tuple7<`[`A`](map.html#A)`, `[`B`](map.html#B)`, `[`C`](map.html#C)`, `[`D`](map.html#D)`, `[`E`](map.html#E)`, `[`FF`](map.html#FF)`, `[`G`](map.html#G)`>) -> `[`Z`](map.html#Z)`): FluxK<`[`Z`](map.html#Z)`>`<br>`fun <A, B, C, D, E, FF, G, H, Z> map(arg0: Kind<ForFluxK, `[`A`](map.html#A)`>, arg1: Kind<ForFluxK, `[`B`](map.html#B)`>, arg2: Kind<ForFluxK, `[`C`](map.html#C)`>, arg3: Kind<ForFluxK, `[`D`](map.html#D)`>, arg4: Kind<ForFluxK, `[`E`](map.html#E)`>, arg5: Kind<ForFluxK, `[`FF`](map.html#FF)`>, arg6: Kind<ForFluxK, `[`G`](map.html#G)`>, arg7: Kind<ForFluxK, `[`H`](map.html#H)`>, arg8: (Tuple8<`[`A`](map.html#A)`, `[`B`](map.html#B)`, `[`C`](map.html#C)`, `[`D`](map.html#D)`, `[`E`](map.html#E)`, `[`FF`](map.html#FF)`, `[`G`](map.html#G)`, `[`H`](map.html#H)`>) -> `[`Z`](map.html#Z)`): FluxK<`[`Z`](map.html#Z)`>`<br>`fun <A, B, C, D, E, FF, G, H, I, Z> map(arg0: Kind<ForFluxK, `[`A`](map.html#A)`>, arg1: Kind<ForFluxK, `[`B`](map.html#B)`>, arg2: Kind<ForFluxK, `[`C`](map.html#C)`>, arg3: Kind<ForFluxK, `[`D`](map.html#D)`>, arg4: Kind<ForFluxK, `[`E`](map.html#E)`>, arg5: Kind<ForFluxK, `[`FF`](map.html#FF)`>, arg6: Kind<ForFluxK, `[`G`](map.html#G)`>, arg7: Kind<ForFluxK, `[`H`](map.html#H)`>, arg8: Kind<ForFluxK, `[`I`](map.html#I)`>, arg9: (Tuple9<`[`A`](map.html#A)`, `[`B`](map.html#B)`, `[`C`](map.html#C)`, `[`D`](map.html#D)`, `[`E`](map.html#E)`, `[`FF`](map.html#FF)`, `[`G`](map.html#G)`, `[`H`](map.html#H)`, `[`I`](map.html#I)`>) -> `[`Z`](map.html#Z)`): FluxK<`[`Z`](map.html#Z)`>`<br>`fun <A, B, C, D, E, FF, G, H, I, J, Z> map(arg0: Kind<ForFluxK, `[`A`](map.html#A)`>, arg1: Kind<ForFluxK, `[`B`](map.html#B)`>, arg2: Kind<ForFluxK, `[`C`](map.html#C)`>, arg3: Kind<ForFluxK, `[`D`](map.html#D)`>, arg4: Kind<ForFluxK, `[`E`](map.html#E)`>, arg5: Kind<ForFluxK, `[`FF`](map.html#FF)`>, arg6: Kind<ForFluxK, `[`G`](map.html#G)`>, arg7: Kind<ForFluxK, `[`H`](map.html#H)`>, arg8: Kind<ForFluxK, `[`I`](map.html#I)`>, arg9: Kind<ForFluxK, `[`J`](map.html#J)`>, arg10: (Tuple10<`[`A`](map.html#A)`, `[`B`](map.html#B)`, `[`C`](map.html#C)`, `[`D`](map.html#D)`, `[`E`](map.html#E)`, `[`FF`](map.html#FF)`, `[`G`](map.html#G)`, `[`H`](map.html#H)`, `[`I`](map.html#I)`, `[`J`](map.html#J)`>) -> `[`Z`](map.html#Z)`): FluxK<`[`Z`](map.html#Z)`>` |
| [tupled](tupled.html) | `fun <A, B> tupled(arg0: Kind<ForFluxK, `[`A`](tupled.html#A)`>, arg1: Kind<ForFluxK, `[`B`](tupled.html#B)`>): FluxK<Tuple2<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`>>`<br>`fun <A, B, C> tupled(arg0: Kind<ForFluxK, `[`A`](tupled.html#A)`>, arg1: Kind<ForFluxK, `[`B`](tupled.html#B)`>, arg2: Kind<ForFluxK, `[`C`](tupled.html#C)`>): FluxK<Tuple3<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`, `[`C`](tupled.html#C)`>>`<br>`fun <A, B, C, D> tupled(arg0: Kind<ForFluxK, `[`A`](tupled.html#A)`>, arg1: Kind<ForFluxK, `[`B`](tupled.html#B)`>, arg2: Kind<ForFluxK, `[`C`](tupled.html#C)`>, arg3: Kind<ForFluxK, `[`D`](tupled.html#D)`>): FluxK<Tuple4<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`, `[`C`](tupled.html#C)`, `[`D`](tupled.html#D)`>>`<br>`fun <A, B, C, D, E> tupled(arg0: Kind<ForFluxK, `[`A`](tupled.html#A)`>, arg1: Kind<ForFluxK, `[`B`](tupled.html#B)`>, arg2: Kind<ForFluxK, `[`C`](tupled.html#C)`>, arg3: Kind<ForFluxK, `[`D`](tupled.html#D)`>, arg4: Kind<ForFluxK, `[`E`](tupled.html#E)`>): FluxK<Tuple5<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`, `[`C`](tupled.html#C)`, `[`D`](tupled.html#D)`, `[`E`](tupled.html#E)`>>`<br>`fun <A, B, C, D, E, FF> tupled(arg0: Kind<ForFluxK, `[`A`](tupled.html#A)`>, arg1: Kind<ForFluxK, `[`B`](tupled.html#B)`>, arg2: Kind<ForFluxK, `[`C`](tupled.html#C)`>, arg3: Kind<ForFluxK, `[`D`](tupled.html#D)`>, arg4: Kind<ForFluxK, `[`E`](tupled.html#E)`>, arg5: Kind<ForFluxK, `[`FF`](tupled.html#FF)`>): FluxK<Tuple6<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`, `[`C`](tupled.html#C)`, `[`D`](tupled.html#D)`, `[`E`](tupled.html#E)`, `[`FF`](tupled.html#FF)`>>`<br>`fun <A, B, C, D, E, FF, G> tupled(arg0: Kind<ForFluxK, `[`A`](tupled.html#A)`>, arg1: Kind<ForFluxK, `[`B`](tupled.html#B)`>, arg2: Kind<ForFluxK, `[`C`](tupled.html#C)`>, arg3: Kind<ForFluxK, `[`D`](tupled.html#D)`>, arg4: Kind<ForFluxK, `[`E`](tupled.html#E)`>, arg5: Kind<ForFluxK, `[`FF`](tupled.html#FF)`>, arg6: Kind<ForFluxK, `[`G`](tupled.html#G)`>): FluxK<Tuple7<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`, `[`C`](tupled.html#C)`, `[`D`](tupled.html#D)`, `[`E`](tupled.html#E)`, `[`FF`](tupled.html#FF)`, `[`G`](tupled.html#G)`>>`<br>`fun <A, B, C, D, E, FF, G, H> tupled(arg0: Kind<ForFluxK, `[`A`](tupled.html#A)`>, arg1: Kind<ForFluxK, `[`B`](tupled.html#B)`>, arg2: Kind<ForFluxK, `[`C`](tupled.html#C)`>, arg3: Kind<ForFluxK, `[`D`](tupled.html#D)`>, arg4: Kind<ForFluxK, `[`E`](tupled.html#E)`>, arg5: Kind<ForFluxK, `[`FF`](tupled.html#FF)`>, arg6: Kind<ForFluxK, `[`G`](tupled.html#G)`>, arg7: Kind<ForFluxK, `[`H`](tupled.html#H)`>): FluxK<Tuple8<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`, `[`C`](tupled.html#C)`, `[`D`](tupled.html#D)`, `[`E`](tupled.html#E)`, `[`FF`](tupled.html#FF)`, `[`G`](tupled.html#G)`, `[`H`](tupled.html#H)`>>`<br>`fun <A, B, C, D, E, FF, G, H, I> tupled(arg0: Kind<ForFluxK, `[`A`](tupled.html#A)`>, arg1: Kind<ForFluxK, `[`B`](tupled.html#B)`>, arg2: Kind<ForFluxK, `[`C`](tupled.html#C)`>, arg3: Kind<ForFluxK, `[`D`](tupled.html#D)`>, arg4: Kind<ForFluxK, `[`E`](tupled.html#E)`>, arg5: Kind<ForFluxK, `[`FF`](tupled.html#FF)`>, arg6: Kind<ForFluxK, `[`G`](tupled.html#G)`>, arg7: Kind<ForFluxK, `[`H`](tupled.html#H)`>, arg8: Kind<ForFluxK, `[`I`](tupled.html#I)`>): FluxK<Tuple9<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`, `[`C`](tupled.html#C)`, `[`D`](tupled.html#D)`, `[`E`](tupled.html#E)`, `[`FF`](tupled.html#FF)`, `[`G`](tupled.html#G)`, `[`H`](tupled.html#H)`, `[`I`](tupled.html#I)`>>`<br>`fun <A, B, C, D, E, FF, G, H, I, J> tupled(arg0: Kind<ForFluxK, `[`A`](tupled.html#A)`>, arg1: Kind<ForFluxK, `[`B`](tupled.html#B)`>, arg2: Kind<ForFluxK, `[`C`](tupled.html#C)`>, arg3: Kind<ForFluxK, `[`D`](tupled.html#D)`>, arg4: Kind<ForFluxK, `[`E`](tupled.html#E)`>, arg5: Kind<ForFluxK, `[`FF`](tupled.html#FF)`>, arg6: Kind<ForFluxK, `[`G`](tupled.html#G)`>, arg7: Kind<ForFluxK, `[`H`](tupled.html#H)`>, arg8: Kind<ForFluxK, `[`I`](tupled.html#I)`>, arg9: Kind<ForFluxK, `[`J`](tupled.html#J)`>): FluxK<Tuple10<`[`A`](tupled.html#A)`, `[`B`](tupled.html#B)`, `[`C`](tupled.html#C)`, `[`D`](tupled.html#D)`, `[`E`](tupled.html#E)`, `[`FF`](tupled.html#FF)`, `[`G`](tupled.html#G)`, `[`H`](tupled.html#H)`, `[`I`](tupled.html#I)`, `[`J`](tupled.html#J)`>>` |

### Companion Object Functions

| [applicative](applicative.html) | `fun FluxK.Companion.applicative(): `[`FluxKApplicativeInstance`](../arrow.effects/-flux-k-applicative-instance/index.html) |
