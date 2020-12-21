---
title: Pointed.ts
nav_order: 53
parent: Modules
---

## Pointed overview

Added in v3.0.0

---

<h2 class="text-delta">Table of contents</h2>

- [type classes](#type-classes)
  - [Pointed (interface)](#pointed-interface)
  - [Pointed1 (interface)](#pointed1-interface)
  - [Pointed2 (interface)](#pointed2-interface)
  - [Pointed2C (interface)](#pointed2c-interface)
  - [Pointed3 (interface)](#pointed3-interface)
  - [Pointed3C (interface)](#pointed3c-interface)
  - [Pointed4 (interface)](#pointed4-interface)

---

# type classes

## Pointed (interface)

**Signature**

```ts
export interface Pointed<F> extends Functor<F> {
  readonly of: <A>(a: A) => HKT<F, A>
}
```

Added in v3.0.0

## Pointed1 (interface)

**Signature**

```ts
export interface Pointed1<F extends URIS> extends Functor1<F> {
  readonly of: <A>(a: A) => Kind<F, A>
}
```

Added in v3.0.0

## Pointed2 (interface)

**Signature**

```ts
export interface Pointed2<F extends URIS2> extends Functor2<F> {
  readonly of: <E, A>(a: A) => Kind2<F, E, A>
}
```

Added in v3.0.0

## Pointed2C (interface)

**Signature**

```ts
export interface Pointed2C<F extends URIS2, E> extends Functor2C<F, E> {
  readonly of: <A>(a: A) => Kind2<F, E, A>
}
```

Added in v3.0.0

## Pointed3 (interface)

**Signature**

```ts
export interface Pointed3<F extends URIS3> extends Functor3<F> {
  readonly of: <R, E, A>(a: A) => Kind3<F, R, E, A>
}
```

Added in v3.0.0

## Pointed3C (interface)

**Signature**

```ts
export interface Pointed3C<F extends URIS3, E> extends Functor3C<F, E> {
  readonly of: <R, A>(a: A) => Kind3<F, R, E, A>
}
```

Added in v3.0.0

## Pointed4 (interface)

**Signature**

```ts
export interface Pointed4<F extends URIS4> extends Functor4<F> {
  readonly of: <S, R, E, A>(a: A) => Kind4<F, S, R, E, A>
}
```

Added in v3.0.0