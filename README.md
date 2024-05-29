

-------------------

<!DOCTYPE html> 
<html> 
<head> 
<meta charset="utf-8"> 
<title>菜鸟教程(runoob.com)</title> 
</head>
<body> 

<div style="text-align:center"> 
  <button onclick="playPause()">播放/暂停</button> 
  <button onclick="makeBig()">放大</button>
  <button onclick="makeSmall()">缩小</button>
  <button onclick="makeNormal()">普通</button>
  <br> 
  <video id="video1" width="620">
    <source src="<video width="600" height="340" controls>
  <source src="https://59-47-225-53.pd1.123pan.cn:30443/download-cdn.123pan.cn/123-556/bbba14f3/1811986226-0/bbba14f3509dc34546a823f9ea9a622c/c-m5?v=5&t=1717093428&s=1717093428ee335607da4d4b4b82c07e8a39c330db&r=PQ661M&bzc=1&bzs=1811986226&filename=BV1Nt411Y745.mp4&x-mf-biz-cid=a2c32146-e995-4824-a7bb-9c1124bca3a3-6eaa77&auto_redirect=0&ndcp=1&cache_type=1&xmfcid=2ac7afe5-9dc1-491b-9b28-23b7bd0e4014-0-abf611255" type="video/mp4">
  </video>
</div> 

<script> 
var myVideo=document.getElementById("video1"); 

function playPause()
{ 
	if (myVideo.paused) 
	  myVideo.play(); 
	else 
	  myVideo.pause(); 
} 

	function makeBig()
{ 
	myVideo.width=560; 
} 

	function makeSmall()
{ 
	myVideo.width=320; 
} 

	function makeNormal()
{ 
	myVideo.width=420; 
} 
</script> 

</body> 
</html>
