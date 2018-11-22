---
title: FlowableKTraverseInstance - arrow-effects-rx2-instances
---

[arrow-effects-rx2-instances](../../index.html) / [arrow.effects](../index.html) / [FlowableKTraverseInstance](./index.html)

# FlowableKTraverseInstance

`@extension interface FlowableKTraverseInstance : Traverse<ForFlowableK>`

### Functions

| [foldLeft](fold-left.html) | `open fun <A, B> Kind<ForFlowableK, `[`A`](fold-left.html#A)`>.foldLeft(b: `[`B`](fold-left.html#B)`, f: (`[`B`](fold-left.html#B)`, `[`A`](fold-left.html#A)`) -> `[`B`](fold-left.html#B)`): `[`B`](fold-left.html#B) |
| [foldRight](fold-right.html) | `open fun <A, B> Kind<ForFlowableK, `[`A`](fold-right.html#A)`>.foldRight(lb: Eval<`[`B`](fold-right.html#B)`>, f: (`[`A`](fold-right.html#A)`, Eval<`[`B`](fold-right.html#B)`>) -> Eval<`[`B`](fold-right.html#B)`>): Eval<`[`B`](fold-right.html#B)`>` |
| [map](map.html) | `open fun <A, B> Kind<ForFlowableK, `[`A`](map.html#A)`>.map(f: (`[`A`](map.html#A)`) -> `[`B`](map.html#B)`): FlowableK<`[`B`](map.html#B)`>` |
| [traverse](traverse.html) | `open fun <G, A, B> FlowableKOf<`[`A`](traverse.html#A)`>.traverse(AP: Applicative<`[`G`](traverse.html#G)`>, f: (`[`A`](traverse.html#A)`) -> Kind<`[`G`](traverse.html#G)`, `[`B`](traverse.html#B)`>): Kind<`[`G`](traverse.html#G)`, FlowableK<`[`B`](traverse.html#B)`>>` |

### Inheritors

| [FlowableKContext](../-flowable-k-context/index.html) | `object FlowableKContext : `[`FlowableKConcurrentEffectInstance`](../-flowable-k-concurrent-effect-instance/index.html)`, `[`FlowableKTraverseInstance`](./index.html) |
