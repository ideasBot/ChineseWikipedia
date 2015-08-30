# ChineseWikipedia
用于中文维基百科的拓展
# Usage
```php
//该函数用于将小于50kB,且无删除或速删模版的条目进行标记:{{Substub}},如果条目内容为空,则直接G1
ext_zhwp_check_50()


//该函数用于从最近更改中检测新创建的广告条目,并将其标记
ext_zhwp_check_ad()

//该函数用于清空中文维基百科沙盒
//目前只支持大小为267字节的沙箱
ext_zhwp_clean_sandbox($sandboxname="Wikipedia:沙盒")

//该函数用于清空中文维基百科图片沙盒之文件描述
//目前只支持大小为279字节的沙箱
ext_zhwp_clean_pic_sandbox()
```
