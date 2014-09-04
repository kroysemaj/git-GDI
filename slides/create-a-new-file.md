##  Add a new file to our repo

You can add new files to the project:

Let's create a file called &lt;your-name&gt;.js, add it to the repo (stage it), and commit it.

<br>
```bash
$ touch james.js
```
Just like before we need to put something in our file: <!-- .element: class="fragment" data-fragment-index="1" -->
<p class="terminal fragment" data-fragment-index="1"><code>james.js</code></p>
```javascript
console.log("James");
```
<!-- .element: class="fragment" data-fragment-index="1" -->

Then add and commit <!-- .element: class="fragment" data-fragment-index="2" -->

```bash
$ git status
$ git add james.js
$ git commit -m "I added a new file!"
```
<!-- .element: class="fragment" data-fragment-index="2" -->