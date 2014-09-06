##  using git stash

Now we'll stash our awesome changes.

```bash
$ git stash
```

Now look at the helloWorld.js file again.

<p class="terminal fragment" data-fragment-index="1"><code>helloWorld.js</code></p>

```javascript
var name = 'Jimmy';

console.log('Hello ' + name);
```
<!-- .element: class="fragment" data-fragment-index="1" -->

You're back to the working directory's last commit before any changes. And free to go off on a completely different path if needed. <!-- .element: class="fragment" data-fragment-index="1" -->
