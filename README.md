# postpone-load-demo
you can take postpone load demo up resource from other

当你的资源还在加载的时候，你需要一个加载demo  来缓冲资源的加载画面

减少加载中的误操作，对使用造成一定的影响

引入资源
<link rel="stylesheet" href="/js/loading/css/jquery.mloading.css" type="text/css"/>

<script type="text/javascript" src="/js/loading/jquery.mloading.js"></script>

在js中 直接使用 

$('body').mLoading("show")  加载demo显现

$('body').mLoading("hide")  加载demo隐藏
