# MulThreadDownload
HTTP协议实现断点续传下载

代码原文来自：http://www.open-open.com/lib/view/open1361322936603.html

利用RandomAccessFile类实现多线程下载，另一种做法在http://gundumw100.iteye.com/blog/906072提到多线程下载文件的不同部分，最后再合并成一个文件，速度会快些，实现起来也会麻烦些．
