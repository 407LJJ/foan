# foan
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>期末作业(runoob.com)</title>
</head>
<body>

<p>点击按钮查看输入的对话框。</p>
<button onclick="myFunction()">点我</button>
<p id="demo"></p>
<script>
function myFunction(){
	var x;
	var person=prompt("请输入你的名字","Harry Potter");
	if (person!=null && person!=""){
	    x="你好 " + person + "! 今天感觉如何?";
	    document.getElementById("demo").innerHTML=x;
	}
}
</script>

</body>
</html>
