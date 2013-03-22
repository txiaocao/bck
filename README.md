<header>
			<h2>bck · mk</h2>
			<h3>browsercheck 浏览器选择器</h3>
		</header>
		<div class="content">
		<p>通过简单的class标记来让你的样式脚本标记等。只在该浏览器下呈现，以便于解决浏览器之间的差异。：）</p>
		<p>编写方式示例：</p>
		<span>• JavaScript</span>
		<pre>&lt;script class="mozilla" type=" bck"&gt;//console.log("I am Mozilla");&lt;/script&gt;</pre>
		
		<span>• Style</span>
		<pre>&lt;link href="style/mozilla.css" class="mozilla" type="bck" rel="stylesheet" &gt;</pre>
		<pre>
&lt;style class="chrome"  type="bck"&gt;
	#some{
	...
	}
&lt;/style&gt;
		</pre>
		
		<span>• Mark</span>
		
		<pre>
IE下可见
&lt;span class="chrome"&gt;
     谷歌下可见
     &lt;span class="mozilla"&gt;
          火狐下可见
     &lt;/span&gt;
     &lt;span class="mozilla"&gt;
          火狐下可见
     &lt;/span&gt;
&lt;/span&gt;
		</pre>
		
		<span>引用方式</span>
		<pre>&lt;script src="jquery-1.8.2.js" type="text/javascript"&gt;&lt;/script&gt;</pre>
		<pre>&lt;script src="bck/bck.js" type="text/javascript"&gt;&lt;/script&gt;</pre>
		</div>
