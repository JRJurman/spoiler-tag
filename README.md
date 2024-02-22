# deco-spoiler-tag

Spoiler Tag Web Component written in Tram-Deco

[text "Thorn shouts to the surrounding crowd," and then there is black bar where there should be text](./preview.png)

[Live Example on Codepen](https://codepen.io/JRJurman/pen/zYbQzMg)

## How to use

```html
<script src="https://unpkg.com/deco-spoiler-tag@1"></script>

<p>
  Thorn shouts to the surrounding crowd,
  <spoiler-tag>"Soylent Green is people!"</spoiler-tag>
</p>
```

## API

The component takes in a single slot, which is the hidden content.

You can style the control for the spoiler using `::part(control)::after`.

```html
<style>
  spoiler-tag::part(control)::after {
    background: green;
    color: green;
  }
</style>
```
