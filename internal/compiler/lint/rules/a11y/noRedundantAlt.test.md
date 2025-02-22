# `harness.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/compiler/lint/rules/harness.test.ts --update-snapshots` to update.

## `a11y/noRedundantAlt`

### `0`

```

 lint/a11y/noRedundantAlt/reject/1/file.tsx:1 lint/a11y/noRedundantAlt ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid the words "image", "picture", or "photo" in img element alt text.

    <img src="src" alt="photo content" />
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Screen readers announce img elements as "images", so it is not necessary to redeclare this in
    alternative text.


```

### `0: formatted`

```tsx
<img src="src" alt="photo content" />;

```

### `1`

```

 lint/a11y/noRedundantAlt/reject/2/file.tsx:1 lint/a11y/noRedundantAlt ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid the words "image", "picture", or "photo" in img element alt text.

    <img src="src" alt="picture content" />
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Screen readers announce img elements as "images", so it is not necessary to redeclare this in
    alternative text.


```

### `1: formatted`

```tsx
<img src="src" alt="picture content" />;

```

### `2`

```

 lint/a11y/noRedundantAlt/reject/3/file.tsx:1 lint/a11y/noRedundantAlt ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid the words "image", "picture", or "photo" in img element alt text.

    <img src="src" alt="image content" />
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Screen readers announce img elements as "images", so it is not necessary to redeclare this in
    alternative text.


```

### `2: formatted`

```tsx
<img src="src" alt="image content" />;

```

### `3`

```

 lint/a11y/noRedundantAlt/reject/4/file.tsx:1 lint/a11y/noRedundantAlt ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid the words "image", "picture", or "photo" in img element alt text.

    <img src="src" alt="Photo content" />
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Screen readers announce img elements as "images", so it is not necessary to redeclare this in
    alternative text.


```

### `3: formatted`

```tsx
<img src="src" alt="Photo content" />;

```

### `4`

```

 lint/a11y/noRedundantAlt/reject/5/file.tsx:1 lint/a11y/noRedundantAlt ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid the words "image", "picture", or "photo" in img element alt text.

    <img src="src" alt="Picture content" />
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Screen readers announce img elements as "images", so it is not necessary to redeclare this in
    alternative text.


```

### `4: formatted`

```tsx
<img src="src" alt="Picture content" />;

```

### `5`

```

 lint/a11y/noRedundantAlt/reject/6/file.tsx:1 lint/a11y/noRedundantAlt ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid the words "image", "picture", or "photo" in img element alt text.

    <img src="src" alt="Image content" />
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Screen readers announce img elements as "images", so it is not necessary to redeclare this in
    alternative text.


```

### `5: formatted`

```tsx
<img src="src" alt="Image content" />;

```

### `6`

```

```

### `6: formatted`

```tsx
<img src="src" alt="alt" />;

```

### `7`

```

```

### `7: formatted`

```tsx
<img src="src" alt={photo} />;

```

### `8`

```

 lint/a11y/noRedundantAlt/reject/1/file.html:1 lint/a11y/noRedundantAlt ━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid the words "image", "picture", or "photo" in img element alt text.

    <img src="src" alt="photo content" />
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Screen readers announce img elements as "images", so it is not necessary to redeclare this in
    alternative text.


```

### `8: formatted`

```html
<img src="src" alt="photo content" />

```

### `9`

```

 lint/a11y/noRedundantAlt/reject/2/file.html:1 lint/a11y/noRedundantAlt ━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid the words "image", "picture", or "photo" in img element alt text.

    <img src="src" alt="picture content" />
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Screen readers announce img elements as "images", so it is not necessary to redeclare this in
    alternative text.


```

### `9: formatted`

```html
<img src="src" alt="picture content" />

```

### `10`

```

 lint/a11y/noRedundantAlt/reject/3/file.html:1 lint/a11y/noRedundantAlt ━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid the words "image", "picture", or "photo" in img element alt text.

    <img src="src" alt="image content" />
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Screen readers announce img elements as "images", so it is not necessary to redeclare this in
    alternative text.


```

### `10: formatted`

```html
<img src="src" alt="image content" />

```

### `11`

```

 lint/a11y/noRedundantAlt/reject/4/file.html:1 lint/a11y/noRedundantAlt ━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid the words "image", "picture", or "photo" in img element alt text.

    <img src="src" alt="Photo content" />
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Screen readers announce img elements as "images", so it is not necessary to redeclare this in
    alternative text.


```

### `11: formatted`

```html
<img src="src" alt="Photo content" />

```

### `12`

```

 lint/a11y/noRedundantAlt/reject/5/file.html:1 lint/a11y/noRedundantAlt ━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid the words "image", "picture", or "photo" in img element alt text.

    <img src="src" alt="Picture content" />
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Screen readers announce img elements as "images", so it is not necessary to redeclare this in
    alternative text.


```

### `12: formatted`

```html
<img src="src" alt="Picture content" />

```

### `13`

```

 lint/a11y/noRedundantAlt/reject/6/file.html:1 lint/a11y/noRedundantAlt ━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid the words "image", "picture", or "photo" in img element alt text.

    <img src="src" alt="Image content" />
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Screen readers announce img elements as "images", so it is not necessary to redeclare this in
    alternative text.


```

### `13: formatted`

```html
<img src="src" alt="Image content" />

```

### `14`

```

```

### `14: formatted`

```html
<img src="src" alt="content" />

```
