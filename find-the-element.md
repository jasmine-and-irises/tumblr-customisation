### Finding the element to style
<ol><li>Open your blog in a new tab, then open <mark>Developer Tools</mark> in your browser.</li>
<ul><li>You can do it by right-clicking on any object on the page, then in the pop-over mini-menu select the <quote>"Inspect"</quote> option. In Chrome, it is the last one on the mini-menu list.</li> 
<li>This will allow you to see the page's code (as it's rendered, in its current state).</li>
<li>The code will be visible in a panel on the left or right side of your screen.</li></ul><br>
<li>Once you have the DevTools opened, find an object on your page that you'd like to style. Right-click on it, select the "Inspect" option.</li>
<ul><li>This will scroll the page's code to the verse where the HTML element related to this object occurs. The verse will be highlighted.</li></ul><br>
<li>Look at the element, especially its opening tag (in left-to-right text, the opening tag is always the one on left, placed between the lesser-than <code><</code>  and greater than <code>></code> symbols. 
The closing tag occurs after the opening one, is constructed in a similar manner, but doesn't have any attributes provided + before the tag's name, a slash symbol <code>/</code> is added. See: <code>&lt;some-tag&gt;some content&lt;/some-tag&gt;</code>, where <code>&lt;some-tag&gt;</code> is the opening an <code>&lt;/some-text&gt;</code> is the closing tag).</li><br>
<li>The opening tag will have several things declared. The most important ones regarding styling are: element name (always present, identifying the tag; in the non-existent example above, this will be the <code>opening-tag</code>), and from the element's attributes: id (<code>id="some-id-name"</code>) and class (<code>class="class-name"</code>).</li></br>
<pre>&lt;some-tag id="some-id-name" class="some-class-name"&gt;some content&lt;/some-tag&gt;</pre>
<ul><li>Also check if the element has any inline CSS provided (it would be present inside the opening tag, too, as the <code>style</code> attribute — <code>style="property1: value1; property2: value2;"</code>). If there is the <code>style</code> attribute provided, better remove it. You can cut it off from the code by pressing <kbd>ctrl</kbd> + <kbd>X</kbd> and then paste to your Notebook app (<kbd>ctrl</kbd> + <kbd>V</kbd>) if you don't wish to lose it.</li></ul></ol>
