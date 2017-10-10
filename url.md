# 测试
## CSDN-markdown编辑器语法——字体、字号与颜色


<!--sublime-->
<link         href="http://cdn.bootcss.com/highlight.js/8.0/styles/monokai_sublime.min.css" rel="stylesheet">

<script src="http://cdn.bootcss.com/highlight.js/8.0/highlight.min.js"></script>  
<script >hljs.initHighlightingOnLoad();</script>

<!--mono-->
<!--<link rel="stylesheet" href="http://yandex.st/highlightjs/8.0/styles/solarized_dark.min.css">
<script src="http://yandex.st/highlightjs/8.0/highlight.min.js">        </script>
<script>hljs.initHighlightingOnLoad();</script>-->

<!--segmentfault-->
<link rel="stylesheet" href="https://sf-static.b0.upaiyun.com/v-576b52d9/3rd/highlightjs/styles/solarized_light.css">
<script src="http://cdn.bootcss.com/highlight.js/8.0/highlight.min.js">        </script>  
<script >hljs.initHighlightingOnLoad();</script>-->

<?php

$var = 0;
// Evaluates to true because $var is empty
if (empty($var)) {
    echo '$var is either 0, empty, or not set at all';
}

// Evaluates as true because $var is set
if (isset($var)) {
    echo '$var is set even though it is empty';
}
?>
