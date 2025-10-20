<!-- استفاده از تگ iframe -->
<iframe src="javascript:alert('XSS')">

<!-- استفاده از event handlers -->
<img src="x" onerror="alert('XSS')">

<!-- استفاده از javascript در لینک -->
[Click me](javascript:alert('XSS'))
