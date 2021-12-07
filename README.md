#  jQuery XSS

jQuery with XSS, Testing and Secure Version

修复了参考版本中9521和11290无法弹窗的问题，11974新增一个payload，可以验证一些之前11974无法验证的jQuery，并新增3个新的XSSpayload

使用时只需要修改开头<script>标签里的src即可

## Bug list:

- [#9521](https://bugs.jquery.com/ticket/9521)
- [#11290](https://bugs.jquery.com/ticket/11290)
- [#11974](https://bugs.jquery.com/ticket/11974)
- [#CVE-2020-11022/CVE-2020-11023](https://cloud.tencent.com/developer/article/1638163)

## Test version:

- [test](http://research.insecurelabs.org/jquery/test/)

## Safe version：

- 1.12.0, 1.12.1
- 2.2.0, 2.2.1
- 3.0.0, 3.0.1, 3.1.0, 3.1.1

参考：

https://github.com/mahp/jQuery-with-XSS

https://cloud.tencent.com/developer/article/1638163

