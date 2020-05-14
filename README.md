## 东北大学本科毕业论文 latex模板 2020


修改自[neu_bachelor_thesis_template](https://github.com/Acytoo/neu_bachelor_thesis_template)。

### 使用方法
* `make`    生成论文 main.pdf；
* `make view`    生成论文 main.pdf 并查看生成的论文；
* `make clean`     删除中间文件（不含 main.pdf）；
* `make cleanall`  删除中间文件和生成的论文（main.pdf）；
----------------
### 下载

[Release](https://github.com/Acytoo/neu_bachelor_thesis_template/releases)

或者单击右上角绿色的按钮。

--------------------
### 注意

* 请使用xelatex


* 可能需要手动安装参考文献的标准，具体的安装方式请见[GBT7714-2005参考文献标准](https://github.com/Haixing-Hu/GBT7714-2005-BibTeX-Style)。使用GBT7714-2005参考文献标准，请删除cls文件中338行的注释。

* 如果你的目录页共有奇数页，一定要在目录后面加入一个空白页，或者将目录与正文分开打印，否则正文的第一页可能被打印在目录页的背面。

* 自定义添加图片，表格，记得修改字号为5号。

* 如果缺少相应的字体可能会无法编译或者编译结果与预期不同（虽然这种情况通常不会出现），请自行安装相应的字体。

* 附录里的代码使用了Monaco字体，如果你的电脑没有安装这种字体，可以在这里[下载](https://github.com/todylu/monaco.ttf)安装，或者删掉[cls](https://github.com/Acytoo/neu_bachelor_thesis_template/blob/master/csethesis.cls)文件中，代码段字体的设置项。

* 关于章标题的上下间距，可以参考这个issue:[设置每章的标题的上下间距在哪里可以调整？](https://github.com/ustctug/ustcthesis/issues/102)

