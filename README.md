# Boox,Kindle,Moon Reader Clippings To Markdown

# 将文石Boox、kindle、静读天下专业版的标注转换为markdown格式

## Boox eink reader

Blog:https://my.oschina.net/wangandi/blog/3191259

if with no arguments, it convert all .txt file in the folder(include subs)，origin .txt not deleted

如果没有参数，就转换当前文件夹下的所有.txt文件为.md，不删除源文件。

if with arguments, it only convert the file to .md

如果有参数，就只转换那个文件

origin clippings file tested succeed in 2020.03.13

标注文件格式测试成功在2020.03.13

## Kindle

Auto detect kindle My Clippings.txt

自动检测到My Clippings.txt

if you dont's want the clippings sorted as book. Change ClippingsToMarkdownSorted.py to ClippingsToMarkdown.py

**如果你想保留原来的标注顺序，请把文件名ClippingsToMarkdownSorted.py 改成 ClippingsToMarkdown.py**

origin clippings file tested in 2020.03.13(My Clippings.txt created in 2018.10.14)

标注文件测试成功在2020.03.13(My Clippings.txt 文件在 2018.10.14 生成)

## Moon Reader

In moon reader pro, bookmark, output to file, it can convert .mrexpt to .md file

静读天下专业版中，书签，导出到文件，可以转换.mrexpt文件到.md