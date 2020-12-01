<div align="center">
  <img src="../../src/assets/images/html_css_javascript_infographic.png">
</div> <br />


## :rocket: Tecnologias utilizadas:

  <div>✔️ CSS</div>
  <div>✔️ HTML</div>
  <div>✔️ Javascript</div>

________________________________________________________

  - Remember, when I have several `css` that apply the same style the last one that `prevails`.

  - Avoid using `absolute` measures (.px), prefer to use measures in `%`.

________________________________________________________

### Tips for fonts units.

 `em` - relative to parent element
 `rem`  - relative to root (html), by pattern html has 16px

________________________________________________________

 - Devices with width exact
```css
    @media (width: 800px) {
      body {
        background: #7159c1;
      }
    }
```
 - Minimum width can be used (`min-width`)
 - Devices with width max
```css
    @media (max-width: 600px) {
      html {
        font-size: 50%;
      }
    }
```

 - can be combined with the "and" operator

```css
    @media (max-width: 1000px) and (max-width: 800px) {
      body {
        background: #7159c1;
      }
    }
```

 - More than one can be used

 ```css
    @media (max-width: 1000px) {
      body {
        background: #7159c1;
      }
    }
```

 ```css
    @media (max-width: 800px) {
      body {
        background: blue;
      }
    }
```

- Remember, when I have several `css` that apply the same style the last one that `prevails`.