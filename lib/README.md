# Rxify

### [Official Documentation](https://toonvanvr.github.io/rx-ify/)

## Usage

### In browser

```html
<html>
  <head>
    <script type="importmap">
      {
        "imports": {
          "@toonvanvr/rx-ify": "https://cdn.jsdelivr.net/npm/@toonvanvr/rx-ify@1.0.0-alpha.8/+esm",
          "rxjs": "https://cdn.jsdelivr.net/npm/rxjs@7.8.1/+esm"
        }
      }
    </script>
    <script type="module">
      import { interval, map, BehaviorSubject } from 'rxjs'
      import { $$ } from '@toonvanvr/rx-ify'

      const div = document.getElementById('counter')
      $$(div).innerHTML = interval(500)
    </script>
  </head>
  <body>
    <div id="counter">0</div>
  </body>
</html>
```

### Node.js

```js

```
