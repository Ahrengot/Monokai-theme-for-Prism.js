# Soda Monokai theme for Prism.js
![Example of HTML highlighting](http://cl.ly/image/2Y3U1S1E2i0o/highlighting.png)

**Demo at http://ahrengot.github.io/Monokai-theme-for-Prism.js/**

## Usage
[Prism.js](http://prismjs.com/) is a lightweight syntax highlighter with no dependencies. It's quite easy to work with too ... All you need to do is include `js/libs/prism.js` and `styles/syntax-highlighting.css

### Example
Wrap your snippet in a `<code class="language-*language*"></code>` tag. That `<code>`-tag can optionally be wrapped in a `<pre>` tag if you want preformatted output.
```
<pre><code class="language-*lang*">
    <!-- Preformatted code -->
</code></pre>
```

In other words, wrap in a pre-tag if you want multiple lines as opposed to inline code.
Beware that indentation can mess up the padding around the code a bit, so if you get big marins try un-indenting your code snippet

### The theme supports the following languages

1. HTML
2. SCSS (Sass/Compass)
3. CSS
4. JavaScript
5. PHP