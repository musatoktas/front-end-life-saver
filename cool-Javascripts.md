Change html on page load
-----

```

  <!DOCTYPE html>
<html>
<body onload="logoDegistir()">

<div class="top-logo">First div element with class="example".</div>

<div class="top-logo">Second div element with class="example".</div>

<p>Click the button to change the text of the first div element with class="example" (index 0).</p>

<button onclick="myFunction()">Try it</button>

<p><strong>Note:</strong> The getElementsByClassName() method is not supported in Internet Explorer 8 and earlier versions.</p>

<script>
function logoDegistir() {
  var x = document.getElementsByClassName("top-logo");
  x[0].innerHTML = "<a href='https://zehrapolat.com/'><img alt='Logo' class='logo1 logo-dark' style='max-height:40px;' src='http://zehrapolat.com/wp-content/uploads/2021/06/zehra-polat-siyah-logo.png'><img alt='Logo' class='logo1 logo-white' style='max-height:40px;' src='https://zehrapolat.com/wp-content/uploads/2020/08/zehra-polat-beyaz-logo.png'></a> ";
}
</script>

</body>
</html>
  </code>
```

Try It https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_document_getelementsbyclassname
