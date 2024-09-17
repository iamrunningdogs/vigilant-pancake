# this-essay

首先感谢[主页](./br)的推荐。

今天回到了R语言，主要学到了下面的命令：

第一步：安装软件包

`install.packages("Bioconductor")`

第二步：编写代码,开启代码大窗口\[File\]→\[New File\]→\[R Script\]

第三步：下载安装Rtools

第三步：plot(rnorm(50))是第一个画图的函数。

第四步：runif(n,min=0,max=1)是第一个数理函数

第五步：定义函数<-

第六步：定义向量c

第七步：显示第几行的函数head(,n)

第八步：定位、删除函数分别是df\[row,col\]简化df$**col**_n_、df\[-row,-col\]

当然，你也可以把特定的列数命个名，然后根据命名寻找：

df\[,c("col2")\]

也可以使用colnames(df)获取列名，使用colnames(df) <- c("...",)命名一列。

library(readr)后才能read_csv、read_tsv，还可以使用as.data.frame规整数据

library(readxl)后使用read_excel。