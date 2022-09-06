### HTML
<details>
<summary>What are meta tags.</summary>
<div class="answer">
<code style="color:var(--single-code)">&ltmeta&gt</code> tag defines metadata about an HTML document. Metadata is basically information about data. <code style="color:var(--single-code)">&ltmeta&gt</code> tag always goes in the <code style="color:var(--single-code)">&lthead&gt</code> tag and is mostly used for SEO purposes. The metadata is not rendered on the website but is used by search engines to rank and display some data about your website when searching for it.
</div>
</details>


<details>
<summary>What is Semantic HTML.</summary>
<div class="answer">
Semantic elements are basically elements with a meaning. Semantic elements include - <code style="color:var(--single-code)">&ltarticle&gt</code>, <code style="color:var(--single-code)">&ltheader&gt</code>, <code style="color:var(--single-code)">&ltfooter&gt</code>, <code style="color:var(--single-code)">&ltfigure&gt</code>, <code style="color:var(--single-code)">&ltaside&gt</code>, etc. Using semantic elements will help search engines to better rank your website and also screen readers to help visually impaired users.
<br><br>
<b>For example</b> - If you want to add an article in your website then you should use the <code style="color:var(--single-code)">&ltarticle&gt</code> instead of <code style="color:var(--single-code)">&ltp&gt</code> element cause that will help the search engine know that its an article and also screen readers will read it as an article instead of a paragraph.
</div>
</details>


<details>
<summary>Difference between Block and Inline elements.</summary>
<div class="answer">
<li><b>Block elements</b> - Block elements always takes the full width available to it an a page and always starts on a new line. Some block elements include - <code style="color:var(--single-code)">&ltdiv&gt</code>, <code style="color:var(--single-code)">&ltp&gt</code>, <code style="color:var(--single-code)">&ltli&gt</code>, etc.</li>
<li><b>Inline elements</b> - Inline elements takes only the space required by the element itself. They do not start on new line and allow elements next to it which are inline. Also you cannot set padding and margin to the top and bottom to an Inline element.
<br>
Some inline elements include - <code style="color:var(--single-code)">&ltspan&gt</code>, <code style="color:var(--single-code)">&ltbutton&gt</code>, <code style="color:var(--single-code)">&ltinput&gt</code>, etc.</li>
</div>
</details>


<details>
<summary>Explain the difference between Semantic and Non-Semantic HTML.</summary>
<div class="answer">
<b>Semantic HTML</b> elements are basically elements with meaning and they tell what they are supposed to do. For example - <code style="color:var(--single-code)">&ltarticle&gt</code>, <code style="color:var(--single-code)">&ltnav&gt</code>, <code style="color:var(--single-code)">&ltfigure&gt</code>, etc.
<br>
<b>Non-Semantic HTML</b> elements don’t have any meaning and do not tell us anything about its content. For example - <code style="color:var(--single-code)">&ltdiv&gt</code>, <code style="color:var(--single-code)">&ltspan&gt</code>, etc.
</div>
</details>


<details>
<summary>What is the difference between <code style="color:var(--single-code)">class</code> and <code style="color:var(--single-code)">id</code></summary>
<div class="answer">
Both <code style="color:var(--single-code)">class</code> and <code style="color:var(--single-code)">id</code> are used by CSS and JavaScript to perform certain tasks to an element.
<ul>
<li><code style="color:var(--single-code)"><b>class</b></code> - The class attribute is used to specify one or more HTML element. <code style="color:var(--single-code)">class</code> name is selected in CSS by using <b>.</b> (dot)
</li>
<li><code style="color:var(--single-code)"><b>id</b></code> - The id attribute is used to select a single unique HTML element. <code style="color:var(--single-code)">id</code> name is selected in CSS by using <b>#</b> (hash)
</li>
</ul>
The only difference between the two is that there can be only 1 unique <code style="color:var(--single-code)">id</code> , while <code style="color:var(--single-code)">class</code> can be applied to multiple elements.
</div>
</details>


<details>
<summary>What is <code style="color:var(--single-code)">alt</code> attribute in an <code style="color:var(--single-code)">&ltimage&gt</code> tag used for.</summary>
<div class="answer">
The <b>alt</b> attribute is used to specify an alternate text if the image cannot be displayed and to help screen readers describe an image to visually impaired users.
</div>
</details>


<details><summary>In the <code style="color:var(--single-code)">&ltlabel&gt</code> tag what can be passed into its <code style="color:var(--single-code)">for</code> attribute and how is it related to the <code style="color:var(--single-code)">&ltinput&gt</code> tag.</summary>
<div class="answer">
The <code style="color:var(--single-code)">for</code> attribute associates a label with an input element. The <code style="color:var(--single-code)">for</code> attribute has the value of <code style="color:var(--single-code)">id</code> of the input element. This is useful when using Checkboxes or Radio-buttons, cause instead of clicking the Checkboxes which are relatively small, you can click the <code style="color:var(--single-code)">label</code> text instead which are much easier to click.
</div>
</details>


---
### CSS
<details>
<summary>What is CSS Box Model.</summary>
<div class="answer">
The CSS Box Model is basically a box that wraps around every HTML element. The box model consists of 4 things - the actual content, padding, border and margin, in that order from inside out.
<li><b>Content</b> - The area where the text and images appear.</li>
<li><b>Padding</b> - The space around the content.</li>
<li><b>Border</b> - Border goes around the padding.</li>
<li><b>Margin</b> - The space around the border.</li>
</div>
</details>


<details>
<summary>What are the different ways of applying CSS.</summary>
<div class="answer">
<li><b>Inline</b> - Using the <code style="color:var(--single-code)">style</code> attribute inside HTML elements.</li>
<li><b>Internal</b> - Using the <code style="color:var(--single-code)">&ltstyle&gt</code> element inside the <code style="color:var(--single-code)">&lthead&gt</code> element.</li>
<li><b>External</b> - Using a separate <code style="color:var(--single-code)">.css</code> file and linking it in the HTML document by using <code style="color:var(--single-code)">&ltlink&gt</code> tag.</li>
</div>
</details>


<details>
<summary>If a particular HTML element has all the 3 types of styles applied <code style="color:var(--single-code)">inline, internal and external</code> then which one will be applied.</summary>
<div class="answer">
<b>Inline</b> styles has the highest priority. Then comes <b>Internal</b> styles i.e. <code style="color:var(--single-code)">&ltstyle&gt</code> in the <code style="color:var(--single-code)">&lthead&gt</code> tag and then the <b>External</b> css file which has the least priority.
</div>
</details>


<details>
<summary>Which style will be applied when using <code style="color:var(--single-code)">class</code> and <code style="color:var(--single-code)">id</code> at the same time.</summary>
<div class="answer">
<code style="color:var(--single-code)">id</code> gets the first priority and then <code style="color:var(--single-code)">class</code>
</div>
</details>


<details>
<summary>What is the use CSS variables.</summary>
<div class="answer">
CSS variables also known as <b>Custom Properties</b> work just like JavaScript variables, where you can store a value and use it anywhere. The variable should be prefixed with two hypens <code style="color:var(--single-code)">--</code> and are accessed using the <code style="color:var(--single-code)">var()</code> function. A common best practice is to define custom properties in the <code style="color:var(--single-code)">:root</code> pseudo-class, so that it can be applied globally across your HTML document.
For example - 
<pre>
<code style="color:white">:root {
	<span style="color:orange">--main-color</span>: #5496ff;
}
<span style="color:#a7ff3b">h1</span> {
	<span style="color:#e2b7f7">font-color</span>: var(<span style="color:orange">--main-color</span>);
}</code>
</pre>
</div>
</details>


<details>
<summary>Explain the difference between <code style="color:var(--single-code)">display:none</code> and <code style="color:var(--single-code)">visibility:hidden</code></summary>
<div class="answer">
<li><code style="color:var(--single-code)">display:none</code> removes the element completely from the page allowing other elements to fill in the space.</li>
<li><code style="color:var(--single-code)">visibility:hidden</code> removes the element from the page but the space is still allocated to it thus other elements cannot fill it in.</li>
</div>
</details>


---
### JavaScript
<details>
<summary>What is DOM.</summary>
<div class="answer">
<b>DOM</b> stands for Document Object Model and is a programming interface for a web page. Web page is basically a document the can be displayed in the browser window and the DOM represents the document as nodes and objects. The DOM then allows us to manipulate the document and with the help of JavaScript allowing us to create, change, remove elements from the document. We can also add events to elements to make the page more dynamic.
</div>
</details>


<details>
<summary>What are the different ways of adding JavaScript to your web page.</summary>
<div class="answer">
<li><b>Inline</b> - This method is used when we have to call a function in the HTML element. For eg - 
<pre><code style="color:white">&lt<span style="color:#e2b7f7">button</span> <span  style="color:#a7ff3b">onClick</span>="<span style="color:#8bf799">alert('Hello World')</span>"&gtSubmit&lt/<span style="color:#e2b7f7">button</span>&gt
</code></pre>
</li>
<li><b>In the <code style="color:var(--single-code)">&lthead&gt</code> using <code style="color:var(--single-code)">&ltscript&gt</code></b> - The <code style="color:var(--single-code)">&ltscript&gt</code> tag is used to include our JavaScript inside the <code style="color:var(--single-code)">&lthead&gt</code> tag. For eg - 
<pre><code style=color:white>&lt<span style="color:#e2b7f7">head</span>>
	&lt<span style="color:#e2b7f7">script</span>>
		function <span style="color:orange">msg()</span> {
			console.log('Hello World');
		}
	&lt/<span style="color:#e2b7f7">script</span>>
&lt/<span style="color:#e2b7f7">head</span>><br>
&lt<span style="color:#e2b7f7">body</span>>
	&lt<span style="color:#e2b7f7">button</span> <span style="color:#a7ff3b">onClick</span>='<span style="color:orange">msg()</span>'>Submit&lt/<span style="color:#e2b7f7">button</span>>
&lt/<span style="color:#e2b7f7">body</span>>
</code></pre>
</li>
<li><b>External</b> - Using a separate .js file and linking it in the HTML document by using <code style="color:var(--single-code)">&ltscript&gt</code> tag.
</li>
</div>
</details>


<details>
<summary>Difference between React JS and Vanilla JS.</summary>
<div class="answer">
<b style="color:orange">JavaScript is Imperative</b>, meaning we have to tell every step about what we need to do. For example if we want to show a message on the click of a button in JavaScript we have to first select the button, then add an `eventlistener` to the button and then the main function of printing our a message, then selecting the output element where we want to print the message, then add an <code style="color:var(--single-code)">innerText</code> property to it to finally show the message on the page. Whereas <b style="color:orange">React is Declarative</b>, meaning we have to just tell React what we need to render on the page and rest is taken care of. For the same above example we can just use <code style="color:var(--single-code)">useState()</code> and achieve the same thing.
<hr>
React uses <b style="color:orange">Components</b> which are functions that returns HTML by using JSX. With the help of components you break up the user interface into separate pieces that can then be reused and handled independently.<hr>
<b style="color:orange">JavaScript uses DOM</b> but on the other hand <b style="color:orange">React uses Virtual DOM</b>. The Virtual DOM is like a lightweight copy of the actual DOM. So for every object/node that exists in the original DOM, there is an object/node for that in React Virtual DOM. Whenever DOM gets updated, the updated element and its children have to be rendered again to update the UI of our page. As an example, lets say we have a list that contains 10 items. You check off the 1st item. DOM would rebuild the entire list. That’s ten times more work than necessary. Only one item changed, but the remaining 9 get rebuilt exactly how they were before. Now modern websites use huge amounts of DOM manipulation thus slowing the site. So, whenever there is a change in the state of any element, a new Virtual DOM tree is created. This new Virtual DOM tree is then compared with the previous Virtual DOM tree and makes a note of the changes. After this, it finds the best possible ways to make these changes to the real DOM. Now only the updated elements will get rendered on the page.
</div>
</details>


<details>
<summary>What are different ways you can select an element and what’s your favorite one.</summary>
<div class="answer">
<li><code style="color:var(--single-code)">getElementById</code> - Select element by its <code style="color:var(--single-code)">id</code></li>
<li><code style="color:var(--single-code)">getElementByClassName</code> - Select element by its <code style="color:var(--single-code)">classname</code></li>
<li><code style="color:var(--single-code)">getElementsByTagName</code> - Selects all elements by Tag name.</li>
<li><code style="color:var(--single-code)">querySelector</code> - Select an element using CSS selectors.</li>
<li><code style="color:var(--single-code)">querySelectorAll</code> - Selects all elements using CSS selectors.</li>
<hr>
I use <code style="color:var(--single-code)">querySelector</code> and <code style="color:var(--single-code)">querySelectorAll</code> cause they are the most versatile.
</div>
</details>


<details>
<summary>Is JavaScript synchronous or asynchronous.</summary>
<div class="answer">
JavaScript is <b>synchronous</b> i.e. in sequence meaning the code gets executed one by one. So a code statement has to wait for the earlier statement to get executed.
<br>
JavaScript allows <b>asynchronous</b> code where the <b>synchronous</b> code will block further execution of the remaining code until it finishes the current one. For example - <code style="color:var(--single-code)">setTimeout</code>
</div>
</details>


<details>
<summary>Explain promises.</summary>
<div class="answer">
A promise basically represents the completion or failure of an asynchronous code. It is used to find out if the asynchronous operation is successfully completed or not. A promise may have 3 states.
<ul>
<li><b>Pending</b> - Initial state, neither <b>fulfilled</b> nor <b>rejected</b>.</li>
<li><b>Fulfilled/Resolved</b> - Operation completed successful.</li>
<li><b>Rejected</b> - Operation failed.</li>
</ul>
An example of promises would be using <code style="color:var(--single-code)">fetch()</code> which allows us to make network requests to get resources. <code style="color:var(--single-code)">fetch()</code> takes an argument, which is the path to the resource you want to get and returns a <b>promise</b> If we get a response that means the promise has been <b>Resolved</b> and if we get an error meaning the promise has been <b>Rejected</b>.
</div>
</details>


<details>
<summary>What is <code style="color:var(--single-code)">fetch()</code></summary>
<div class="answer">
<code style="color:var(--single-code)">fetch()</code> method starts the process of fetching a resource, returning a promise which is fulfilled once the response is available. It takes an argument, which is the path to the resource you want to get and returns a promise. If we get a response that means the promise has been <b>Fulfilled</b> and if we get an error meaning the promise has been <b>Rejected</b>.
</div>
</details>


<details>
<summary>What are the different ways of using <code style="color:var(--single-code)">fetch()</code></summary>
<div class="answer">
<li>Video - <a href="https://www.youtube.com/watch?v=hOXWY9Ng_KU">How to use fetch in JavaScript: GET, POST, PUT and DELETE requests</a>
</li>
<li>Article - <a href="https://openjavascript.info/2022/01/03/using-fetch-to-make-get-post-put-and-delete-requests">Using fetch to make GET, POST, PUT and DELETE requests
</a>
</li>
</div>
</details>


<details>
<summary>What is the use of <code style="color:var(--single-code)">typeof</code></summary>
<div class="answer">
<code style="color:var(--single-code)">typeof</code> returns the data type of a JavaScript variable or value.
<pre><code style="color:white;"><span style="color:pink">const</span> a = 9;
<span style="color:pink">console.log</span>(<span style="color:orange">typeof</span> a);   //<span style="color:limegreen">number</span>
<span style="color:pink">console.log</span>(<span style="color:orange">typeof</span> '9');   //<span style="color:limegreen">string</span>
<span style="color:pink">console.log</span>(<span style="color:orange">typeof</span> false);   //<span style="color:limegreen">boolean</span>
</code></pre>
</div>
</details>


<details>
<summary>Explain the difference between <code style="color:var(--single-code)">innerText</code> and <code style="color:var(--single-code)">innerHTML</code></summary>
<div class="answer">
<li><code style="color:var(--single-code)"><b>innerText</b></code> -  is used to set or return the <b>Plain Text</b> content of an element..</li>
<li><code style="color:var(--single-code)"><b>innerHTML</b></code> -  is used to set or return the <b>HTML</b> content of an element.</li>
</div>
</details>


---
### React
<details>
<summary>What is your favorite feature of React.</summary>
<div class="answer">
My favorite feature of React is the use of <b>Components</b>. It makes the task of building UI's much easier. With the help of components, the UI can be broken down into separate pieces that can then be reused and handled independently. For example, you can create a header and footer as a component and you can then use it on any page on your site instead of writing the whole code again and again. A react component returns a React Element which can be rendered on the screen. For Example - 
<pre><code style="color:white"><span style="color:gray">// Header.js</span>
<span style="color:var(--code-block)">export default function</span> <span style="color:orange">Header</span>() {
	return (
		<span style="color:pink">&ltheader&gt</span>
			<span style="color:pink">&lth1&gt</span>Welcome 👋 to my site<span style="color:pink">&lt/h1&gt</span>
		<span style="color:pink">&lt/header&gt</span>
	);
};</code></pre>
<pre><code style="color:white"><span style="color:gray">// App.js</span>
<span style="color:var(--code-block)">import <span style="color:orange">Header</span> from <span style="color:lightblue">"Header.js"</span></span>;
<span style="color:var(--code-block)">export default function</span> <span style="color:orange">App()</span> {
  return (
    &lt<span style="color:pink">div</span>&gt
      &lt<span style="color:orange">Header /</span>&gt
    &lt<span style="color:pink">/div</span>&gt
  );
};</code></pre>
</div>
</details>


<details>
<summary>Why use React instead of JavaScript.</summary>
<div class="answer">
<b style="color:orange">JavaScript is Imperative</b>, meaning we have to tell every step about what we need to do. For example if we want to show a message on the click of a button in JavaScript we have to first select the button, then add an `eventlistener` to the button and then the main function of printing our a message, then selecting the output element where we want to print the message, then add an <code style="color:var(--single-code)">innerText</code> property to it to finally show the message on the page. Whereas <b style="color:orange">React is Declarative</b>, meaning we have to just tell React what we need to render on the page and rest is taken care of. For the same above example we can just use <code style="color:var(--single-code)">useState()</code> and achieve the same thing.
<hr>
React uses <b style="color:orange">Components</b> which are functions that returns HTML by using JSX. With the help of components you break up the user interface into separate pieces that can then be reused and handled independently.<hr>
<b style="color:orange">JavaScript uses DOM</b> but on the other hand <b style="color:orange">React uses Virtual DOM</b>. The Virtual DOM is like a lightweight copy of the actual DOM. So for every object/node that exists in the original DOM, there is an object/node for that in React Virtual DOM. Whenever DOM gets updated, the updated element and its children have to be rendered again to update the UI of our page. As an example, lets say we have a list that contains 10 items. You check off the 1st item. DOM would rebuild the entire list. That’s ten times more work than necessary. Only one item changed, but the remaining 9 get rebuilt exactly how they were before. Now modern websites use huge amounts of DOM manipulation thus slowing the site. So, whenever there is a change in the state of any element, a new Virtual DOM tree is created. This new Virtual DOM tree is then compared with the previous Virtual DOM tree and makes a note of the changes. After this, it finds the best possible ways to make these changes to the real DOM. Now only the updated elements will get rendered on the page.
</div>
</details>


<details>
<summary>Explain the use of <code style="color:var(--single-code)">useState()</code></summary>
<div class="answer">
<code style="color:var(--single-code)">useState()</code> is a React hook that allows us to have state variable in a functional component. It takes one argument which will be the initial state and returns the state value and a function to update it. When you update your state, your component re-renders. For example - 
<pre><code style="color:white"><span style="color:var(--code-block)">import <span style="color:orange">React</span> from <span style="color:lightblue">"react"</span></span>;
<span style="color:var(--code-block)">export default function <span style="color:orange">App()</span></span> {
	const [count, setCount] = <span style="color:orange">React</span>.<span style="color:pink">useState</span>(<span style="color:lightblue">0</span>);
	<span style="color:var(--code-block)">function</span> <span style="color:#df80ff">plus</span>() {
		setCount(count<span style="color:lightblue">-1</span>);
	}
	<span style="color:var(--code-block)">function</span> <span style="color:#df80ff">minus</span>() {
		setCount(count<span style="color:lightblue">+1</span>);
	}
	<span style="color:var(--code-block)">return</span> (
		&lt<span style="color:pink">div</span>&gt
		    &lt<span style="color:pink">button</span> <span  style="color:#8bf799">onClick</span>={<span style="color:#df80ff">minus</span>}&gt–&lt<span style="color:pink">/button</span>&gt
			&lt<span style="color:pink">h1</span>&gt{count}&lt<span style="color:pink">/h1</span>&gt
		    &lt<span style="color:pink">button</span> <span  style="color:#8bf799">onClick</span>={<span style="color:#df80ff">plus</span>}&gt+&lt<span style="color:pink">/button</span>&gt
	    &lt<span style="color:pink">/div</span>&gt
	);
}
</code></pre>
</div>
</details>


<details>
<summary>What is Virtual DOM in React.</summary>
<div class="answer">
<b style="color:orange">JavaScript uses DOM</b> but on the other hand <b style="color:orange">React uses Virtual DOM</b>. The Virtual DOM is like a lightweight copy of the actual DOM. So for every object/node that exists in the original DOM, there is an object/node for that in React Virtual DOM. Whenever DOM gets updated, the updated element and its children have to be rendered again to update the UI of our page. As an example, lets say we have a list that contains 10 items. You check off the 1st item. DOM would rebuild the entire list. That’s ten times more work than necessary. Only one item changed, but the remaining 9 get rebuilt exactly how they were before. Now modern websites use huge amounts of DOM manipulation thus slowing the site. So, whenever there is a change in the state of any element, a new Virtual DOM tree is created. This new Virtual DOM tree is then compared with the previous Virtual DOM tree and makes a note of the changes. After this, it finds the best possible ways to make these changes to the real DOM. Now only the updated elements will get rendered on the page.
</div>
</details>


<details>
<summary>Why is React called Declarative and JavaScript Imperative.</summary>
<div class="answer">
<b style="color:orange">JavaScript is Imperative</b>, meaning we have to tell every step about what we need to do. For example if we want to show a message on the click of a button in JavaScript we have to first select the button, then add an `eventlistener` to the button and then the main function of printing our a message, then selecting the output element where we want to print the message, then add an <code style="color:var(--single-code)">innerText</code> property to it to finally show the message on the page. Whereas <b style="color:orange">React is Declarative</b>, meaning we have to just tell React what we need to render on the page and rest is taken care of. For the same above example we can just use <code style="color:var(--single-code)">useState()</code> and achieve the same thing.
</div>
</details>


---
### Misc.
<details>
<summary>What is an API.</summary>
<div class="answer">
<b>API</b> stands for <b>Application Programming Interface</b>. An API allows your application to interact with an external service. In JavaScript there are mainly 2 types of APIs.
<ul>
<li>
<b style="color:orange">Browser APIs</b> - These are built in your browser and allow developers to perform complex operations without dealing with the sophisticated lower-level code. Some of the Browser APIs include - 
<ul>
<li><b style="color:#ffb875">Fetch API</b> - Its is used to make HTTP requests to a web server that recieves a response which can then be used in our web app.
</li>
<li><b style="color:#ffb875">DOM</b> - Allows you to manipulate HTML and CSS. Creating, removing and changing HTML, dynamically applying new styles to your page, etc.
</li>
<li><b style="color:#ffb875">Canvas API</b> - Used to draw graphics using JavaScript and HTML. It can be used for animation, game graphics, data visualization, photo manipulation, and real-time video processing.
</li>
</ul>
</li>
<li>
<b style="color:orange">Third-Party APIs</b> - These APIs are provided by third parties — generally companies such as Twitter, Youtube, etc. to allow you to access their functionality to use it on your site. Some of the popular APIs include - 
<ul>
<li><b style="color:#ffb875">Twitter API</b> - Allows you to do things like displaying tweets on your website.
</li>
<li><b style="color:#ffb875">YouTube API</b> - Allows you to embed YouTube videos on your site, search YouTube, build playlists, and more.
</li>
<li><b style="color:#ffb875">Twilio API</b> - Provides a framework for building voice and video call functionality into your app, sending SMS/MMS from your apps, and more.
</li>
</ul>
</li>
</ul>
</div>
</details>


<details>
<summary>Explain Git and GitHub.</summary>
<div class="answer">
<li><b style="color:orange">Git</b> - It is a version control system for tracking changes in a source code. It can be used by teams when developing apps so that we can know who made what changes in the source code. It is mostly used as a CLI tool but also offers a GUI version.
</li>
<li><b style="color:orange">Github</b> - It is a software that has the functionality of git and also its own set of features like collaboration, bug tracking, etc. It is a hosting service for git repositories. Since its online other users on Github can see your code online and make edits to them which you can then approve if you like.
</li>
</div>
</details>


<details>
<summary>Explain the flow of using Git and GitHub.</summary>
<div class="answer">
<a href="https://www.freecodecamp.org/news/learn-the-basics-of-git-in-under-10-minutes-da548267cc91/#:~:text=in%20this%20tutorial.-,Step%204%3A%20Let%E2%80%99s%20Git,-Create%20a%20new">freecodecamp.org - Git Basics</a>
<br>
<a href="https://www.atlassian.com/git#:~:text=for%20software%20development.-,How%20Git%20works,-Here%20is%20a">Basic overview of how Git works</a>
</div>
</details>
