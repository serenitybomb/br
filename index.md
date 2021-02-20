<!DOCTYPE>
<html lang="en">

<head>
<meta charset="utf-8">
<title>&lt;br&gt; go brrrrr</title>
<style>
body{
background-color: #1d1f21;
margin: 20px;
}
div#divsupondivs {
font-family: monospace;
font-size: 20;
color: #6c9ef8;
}

div#fuckyoucss {
width: 400;
height: 200;
margin-left: auto;
margin-right: auto;
text-align: center;

}

div#br {
display: table-cell;
background-color: #6c9ef8;
height: inherit;
width: inherit;
border: 5px solid black;
border-radius: 50px;
font-family: monospace;
vertical-align: middle;
}

</style>
</head>

<body>
<div id="divsupondivs">
&lt;br&gt;
</div>
<div id="fuckyoucss" onmousemove="aaa()">
<div id="br">
<h1>mouse me over to make <br> &lt;br&gt; go brrrr</h1>
</div>
</div>

<script>
var stupid = document.querySelector("div#divsupondivs")

function aaa() {
stupid.innerHTML = stupid.innerHTML + "<br>&lt;br&gt;";

window.scroll({
top: stupid.offsetHeight,
left: 100,
behavior: 'smooth'
});
}

</script>
</body>


</html>
