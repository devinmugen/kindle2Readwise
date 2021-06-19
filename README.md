# kindle2Readwise

解决中文 `My Clippings.txt` 上传到 Readwise 有误的问题，使用 CSV 文件可以解决中文字符的问题


## 使用方法：

复制 `My Clippings.txt` 到想要储存的路径
```
cd "含有 My Clippings.txt 的路径"
python3 kindle2Readwise.py
```

## 说明：
`Old-Clippings.txt` 将被移动到自动生成保存 txt 文件的 Clippings 文件夹（如果没有则自动生成一个新的空白文件）

`Old-Clippings.txt` 用于和新的 `My Clippings.txt` 对比，只上传之前没有导入的

`My Clippings.txt` 文件将被重命名为 `Old-Clippings.txt`

生成的 CSV 文件保存在 KindleCSV 文件夹中

log.txt 文件用于保存导入的数据

其他:
---
或者取消注释，更改路径
![image](https://user-images.githubusercontent.com/42215787/122644864-efbeaa80-d149-11eb-98eb-61ff55cc22df.png)

例图，注意执行 `python3 kindle2Readwise.py` 后 `My Clippings.txt` 将不会显示（已被改为 `Old-Clippings.txt`)，需要重新添加 `My Clippings.txt`

![image](https://user-images.githubusercontent.com/42215787/122644924-344a4600-d14a-11eb-849e-fd48531b7611.png)

