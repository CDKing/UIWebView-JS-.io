## ① iOS -> JS
### 原理：通过WebView的方法直接调用JS代码
[WebView stringByEvaluatingJavaScriptFromString:@"A"];
// 这里的 A 就是WebView中的html所对应的JS代码

eg.
1）这里一个html所包含的js文件内的一个public方法
