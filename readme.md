DATABASE

* 批量将PDF文件转换为PNG文件：

~~~bash
for i in *.pdf; do sips -s format png -s formatOptions 150 "${i}" --out "${i%pdf}png"; done
~~~
