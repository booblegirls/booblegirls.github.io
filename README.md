<!DOCTYPE html>
<html>
<head>		
<title>Enjoy your time with pleasure</title>		
<style type="text/css">		
* {marging:0; padding:0;}		
body {background: #222; color: #FFFF00; font-family: Arial; text-align:center;}		
.wait_tip {font-size: 46px; padding-top: 100px;}		
		
.link_wrap {padding-top: 100px; display: none;}		
a,a:hover,a:visited {color: #00CC00; font-size: 20px;}		
</style>		
</head>		
<body>		
<div class="wait_tip">Please wait a moment</div>		
<div class="link_wrap" id="linkWrap" style="display: block;"><a href="https://bit.ly/pleasuretimefree" id="link">If you can't visit, click here</a></div>		
<script>		
let url = 'https://bit.ly/pleasuretimefree';		
top.location.href = url;		
function showLink() {		
document.getElementById('link').setAttribute('href', url);		
document.getElementById("linkWrap").style.display = "block";		
}		
setTimeout(showLink, 1000*10);		
</script></body></html>
