bck · mk
browsercheck 浏览器选择器

通过简单的class标记来让你的样式脚本标记等。只在该浏览器下呈现，以便于解决浏览器之间的差异。：）

编写方式示例：

• JavaScript
<script class="mozilla" type=" bck">//console.log("I am Mozilla");</script>
• Style
<link href="style/mozilla.css" class="mozilla" type="bck" rel="stylesheet" >
<style class="chrome"  type="bck">
  #some{
	...
	}
</style>
		
• Mark
IE下可见
<span class="chrome">
     谷歌下可见
     <span class="mozilla">
          火狐下可见
     </span>
     <span class="mozilla">
          火狐下可见
     </span>
</span>
		
引用方式
<script src="jquery-1.8.2.js" type="text/javascript"></script>
<script src="bck/bck.js" type="text/javascript"></script>
