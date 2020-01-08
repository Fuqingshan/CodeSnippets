-r 是递归的意思，会把问价下的子文件目录都会复制
-f 参数是强制复制，比如你在a文件中有个文件名叫b，然后你把c文件夹里面的另一个文件名叫做b的复制到a里面，这个时候回冲突，然后会提示你要不要继续复制，加上-f就不会提示你了。

下载之后复制：

```
cd CodeSnippets
cp -rf CodeSnippets ~/Library/Developer/Xcode/UserData/CodeSnippets
```