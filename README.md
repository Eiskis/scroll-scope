
<h1><em>scroll-scope.js</em></h1>

<p>Small JS plugin to keep parent elements still when scrolling an element past their boundaries</p>



<h2>Usage</h2>

<p>Include and initialize plugin:</p>

```html
<div class="my-scrollable-element" <strong>data-scroll="scope"</strong>>

<script type="text/javascript" src="//code.jquery.com/jquery-2.1.4.min.js"></script>
<script type="text/javascript" src="scroll-scope.js"></script>
<script type="text/javascript">
	$(document).scrollScope();
</script>
```



<h3>Options</h3>

<p>By default, <code>data-scroll="scope"</code> elements are targeted, but you can choose this upon initialization:</p>

```js
$(document).scrollScope('.results, .some-scrollable-element');
```

<p>By default, the plugin catches the events <code>DOMMouseScroll mousewheel</code>, but you can choose this upon initialization:</p>

```js
$(document).scrollScope(null, 'DOMMouseScroll mousewheel my:event');
```



<h2>Credits</h2>

<p>Plugin by <a href="http://eiskis.net/">Jerry Jäppinen</a> (under <a href="https://github.com/Eiskis/scroll-scope/blob/master/LICENSE">MIT</a>).</p>
