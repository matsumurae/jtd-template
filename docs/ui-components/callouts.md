---
layout: default
title: Callouts
parent: UI Components
nav_order: 7
---

# Callouts

{: .d-inline-block }

New (v0.4.0)
{: .label .label-green }

Markdown does not include support for callouts. However, you can style text as a callout using a Markdown extension supported by kramdown: [_block IALs_](https://kramdown.gettalong.org/quickref.html#block-attributes).

#### An untitled callout

{: .no_toc }

```markdown
{: .highlight }
A paragraph
```

{: .highlight }
A paragraph

#### A single paragraph callout

{: .no_toc }

```markdown
{: .note }
A paragraph
```

{: .note }
A paragraph

```markdown
{: .note-title }

> My note title
>
> A paragraph with a custom title callout
```

{: .note-title }

> My note title
>
> A paragraph with a custom title callout

#### A multi-paragraph callout

{: .no_toc }

```markdown
{: .important }

> A paragraph
>
> Another paragraph
>
> The last paragraph
```

{: .important }

> A paragraph
>
> Another paragraph
>
> The last paragraph

```markdown
{: .important-title }

> My important title
>
> A paragraph
>
> Another paragraph
>
> The last paragraph
```

{: .important-title }

> My important title
>
> A paragraph
>
> Another paragraph
>
> The last paragraph

#### An indented callout

{: .no_toc }

```markdown
> {: .highlight }
> A paragraph
```

> {: .highlight }
> A paragraph

#### Indented multi-paragraph callouts

{: .no_toc }

```markdown
> {: .new }
>
> > A paragraph
> >
> > Another paragraph
> >
> > The last paragraph
```

> {: .new }
>
> > A paragraph
> >
> > Another paragraph
> >
> > The last paragraph

#### Nested callouts

{: .no_toc }

```markdown
{: .important }

> {: .warning }
> A paragraph
```

{: .important }

> {: .warning }
> A paragraph

#### Opaque background

{: .no_toc }

```markdown
{: .important }

> {: .opaque }
>
> <div markdown="block">
> {: .warning }
> A paragraph
> </div>
```

{: .important }

> {: .opaque }
>
> <div markdown="block">
> {: .warning }
> A paragraph
> </div>
