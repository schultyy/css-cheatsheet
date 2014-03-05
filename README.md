# css-cheatsheet

## Position a div at bottom

In this case `inner` should be positioned below `outer`

```CSS

.outer {
  position: relative;
}

.inner {
  position: absolute;
  bottom: 0 px;
}

```

## Articles

The `article` tag represents an article which must be self contained. It should be possible to show the article without the surrounding page.

This means, it should include i.e. the header:


```HTML
<article>
  <h1>Yadda yadda</h1>
  <p>
    The awesome content here
  </p>
</article>
```
