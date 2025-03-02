## List and GFM Tasks

1. First
2. Second
   1. 2.1
   2. 2.2
      1. 3.1
3. Third
4. Fourth

- [ ] Checkbox
- [x] Checkbox Completed

---

- Line
  - Line 1.1
- Line 2

## Definition lists

Term 1

: Definition 1
with lazy continuation.

Term 2 with _inline markup_

: Definition 2

        { some code, part of Definition 2 }

    Third paragraph of definition 2.

_Compact style:_

Term 1
~ Definition 1

Term 2
~ Definition 2a
~ Definition 2b

## [Abbreviations](https://github.com/markdown-it/markdown-it-abbr)

This is HTML abbreviation example.

It converts "HTML", but keep intact partial entries like "xxxHTMLyyy" and so on.

\*[HTML]: Hyper Text Markup Language

## Table

| 表达内容                                                                                                                                 | 示例          |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| 表示文件                                                                                                                                 | `options.txt` |
| 表示变量                                                                                                                                 | <版本名>      |
| 在文件或文件夹末尾加上 `!` 表示 Minecraft 本体，分发这些文件违反了 [Minecraft Eula](https://account.mojang.com/documents/minecraft_eula) | libraries !   |
| 在文件或文件夹末尾加上 `*` 表示可删除，`**` 表示建议删除，`***` 表示必须删除                                                             | libraries \*  |

## Token

This is a ||Spoiler||

A `code`.

==mark== it.

++Something Insert++

## Latex

$ c = \pm\sqrt{a^2 + b^2} $

## Container

::: warning
_here be dragons_
:::

::: banner {error}
_here be dragons_
:::

::: gallery
https://loremflickr.com/640/480/city?1
https://loremflickr.com/640/480/city?2
https://loremflickr.com/640/480/city?3
![](https://loremflickr.com/640/480/city?4 'Image')
:::

## Rich Link

```
https://github.com/Innei/Shiro
```

https://github.com/Innei/Shiro

```
https://twitter.com/zhizijun/status/1649822091234148352?s=20
```

https://twitter.com/zhizijun/status/1649822091234148352?s=20

```
https://www.youtube.com/watch?v=N93cTbtLCIM
```

https://www.youtube.com/watch?v=N93cTbtLCIM

```
https://gist.github.com/Innei/94b3e8f078d29e1820813a24a3d8b04e
```

https://gist.github.com/Innei/94b3e8f078d29e1820813a24a3d8b04e

```
https://github.com/vuejs/vitepress/commit/71eb11f72e60706a546b756dc3fd72d06e2ae4e2
```

https://github.com/vuejs/vitepress/commit/71eb11f72e60706a546b756dc3fd72d06e2ae4e2

```
https://codesandbox.io/s/framer-motion-layoutroot-prop-forked-p39g96
```

https://codesandbox.io/s/framer-motion-layoutroot-prop-forked-p39g96

```
https://github.com/Innei/Shiro/blob/108d4c3e927e1c9c9304e41a0631f91958477d9f/src/providers/root/modal-stack-provider.tsx
```

https://github.com/Innei/Shiro/blob/108d4c3e927e1c9c9304e41a0631f91958477d9f/src/providers/root/modal-stack-provider.tsx

```
https://github.com/Innei/Shiro/pull/129
```

https://github.com/Innei/Shiro/pull/129


```
https://github.com/Innei/Shiro/commit/6957e011439eb2d3cbf42bfb67ed81b07d4bcc2a
```

https://github.com/Innei/Shiro/commit/6957e011439eb2d3cbf42bfb67ed81b07d4bcc2a

```
https://trpc.io/docs/client/react/useInfiniteQuery
```

https://trpc.io/docs/client/react/useInfiniteQuery

```
[TRPC](https://trpc.io/docs/client/react/useInfiniteQuery)
```

[TRPC](https://trpc.io/docs/client/react/useInfiniteQuery)

## LinkCard

```
<LinkCard source="gh" id="mx-space/kami">
```

<LinkCard source="gh" id="mx-space/kami">

```
<LinkCard source="gh-commit" id="mx-space/kami/commit/e1eee4136c21ab03ab5690e17025777984c362a0">
```

<LinkCard source="gh-commit" id="mx-space/kami/commit/e1eee4136c21ab03ab5690e17025777984c362a0">

## Inline Link Parser

```
Inline [Innei](https://github.com/Innei)
```

Inline [Innei](https://github.com/Innei)

```
Inline [pseudoyu](https://twitter.com/pseudo_yu)
```

Inline [pseudoyu](https://twitter.com/pseudo_yu)

```
Inline <https://github.com/Innei>
```

Inline <https://github.com/Innei>

```
Inline https://github.com/Innei
```

Inline https://github.com/Innei

## Mention

```
[Innei]{GH@Innei}
```

[Innei 太菜了]{GH@Innei}

## Alerts

```
> [!NOTE]
> Highlights information that users should take into account, even when skimming.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.
```

> [!NOTE]
> Highlights information that users should take into account, even when skimming.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.

## KateX

```
$ c = \pm\sqrt{a^2 + b^2} $
```

$ c = \pm\sqrt{a^2 + b^2} $

```
$c = \pm\sqrt{a^2 + b^2}$
```
$c = \pm\sqrt{a^2 + b^2}$

$P(x) = a_nx^n+a_{n-1}x^{n-1} + \dots + a_1x + a_0$

```
$P(x) = a_nx^n+a_{n-1}x^{n-1} + \dots + a_1x + a_0$
```

```
$$

P\left(U,T\right)=100\left.\left(0.6\min\left(1,\frac{U-0.70}{0.90-0.70}\right)+0.4\min\left(1,\frac{T-4000}{14000-4000}\right)\right)\right.

$$
```

$$

P\left(U,T\right)=100\left.\left(0.6\min\left(1,\frac{U-0.70}{0.90-0.70}\right)+0.4\min\left(1,\frac{T-4000}{14000-4000}\right)\right)\right.

$$

-