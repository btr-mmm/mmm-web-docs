---
sidebar-position: 2
---

# Lists

A set of paragraphs is

```html
<ul>
  <li>List item</li>
  <li>List item</li>
  <li>List item</li>
  <!-- etc -->
</ul>
```

However, Vizergy renders all `<ul>` tags like this, with a red angle bracket:

![Vizergy unordered list](./img/vizergy-ul.png)

I have not found a way to remove these bullet images - rather than replacing the bullet ()

If the client gives you a long list of items, but doesn't want the red angle brackets, I recommend the following HTML markup:

```html
<div role="list">
  <p role="listitem">List item</p>
  <p role="listitem">List item</p>
  <p role="listitem">List item</p>
  <!-- etc -->
</div>
```

