## 根据文件前两个字节来判断文件类型
[CheckFileType.php ](https://github.com/suifeng412/php-lib/blob/master/CheckFileType.php) 
有点：精准  
缺点：每次都要fopen文件流，当文件不存在时会报错，因此需要特别地去校验