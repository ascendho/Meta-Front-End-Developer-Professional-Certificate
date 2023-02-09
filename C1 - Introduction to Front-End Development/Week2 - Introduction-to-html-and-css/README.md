---
typora-copy-images-to: ./..\..\img
---

### Box-model

![Screenshot 2023-02-01 151820](../../img/Screenshot%202023-02-01%20151820.png)



### Block vs Inline

![Screenshot 2023-02-01 151904](../../img/Screenshot%202023-02-01%20151904.png)



### Element with Class Selector

```html
<p class="introduction"></p>
```



```css
p.introduction { 
  margin: 2px;
}
```



### Descendant Selectors

```html
<div id="blog">
  <h1>Latest News</h1>
  <div>
    <h1>Today's Weather</h1>
    <p>The weather will be sunny</p>
  </div>
  <p>Subscribe for more news</p>
</div>
<div>
  <h1>Archives</h1>
</div>


```



```css
#blog h1 {
  color: blue;
}
```

Archives的h1不会被选中



### Child Selectors

```html
<div id="blog">
  <h1>Latest News</h1>
  <div>
    <h1>Today's Weather</h1>
    <p>The weather will be sunny</p>
  </div>
  <p>Subscribe for more news</p>
</div>
```



```css
#blog > h1 {
  color: blue;
}
```

只选中Latest News的h1

