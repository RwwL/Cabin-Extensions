##Cabin Extension: Debugging
This extensions is useful for debugging your project. It will detect and highlight:

###Links:
<ul>
	<li>Links with hash in the href</li>
	<li>Links missing the title attribute</li>
	<li>Links with empty title attribute</li>
	<li>Links that go to external URLS</li>
</ul>

###Images
<ul>
	<li>Images missing the alt attribute</li>
	<li>Images with a blank alt attribute</li>
</ul>

##How to use
Download the <code>debug.cabin.css</code> file and place it in your <code>/css</code> folder.

Give your <code>&lt;HTML&gt;</code> element a <code>class="debug"</code> for example:

<code>
&lt;HTML lang="en" class="debug"&rt;	
</code> 

Open up your HTML document and add the following in the <code>&lt;head&gt;</code> section:

<code>
&lt;link rel="stylesheet" href="css/cabin.css" /&gt;
<br />
&lt;link rel="stylesheet" href="css/debug.cabin.css" /&gt;
</code>