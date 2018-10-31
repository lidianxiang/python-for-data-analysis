# 利用Python进行数据分析
## Python for Data Analysis:Data Wrangling with Pandas,Numpy,and Ipython

---
## 1. 本书目录
[第三章--内建数据结构、函数及文件](https://github.com/lidianxiang/python-for-data-analysis/blob/master/%E7%AC%AC%E4%B8%89%E7%AB%A0--%E5%86%85%E5%BB%BA%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E3%80%81%E5%87%BD%E6%95%B0%E5%8F%8A%E6%96%87%E4%BB%B6.ipynb)  
[第四章--Numpy基础：数组与向量化计算](https://github.com/lidianxiang/python-for-data-analysis/blob/master/%E7%AC%AC%E5%9B%9B%E7%AB%A0--Numpy%E5%9F%BA%E7%A1%80%EF%BC%9A%E6%95%B0%E7%BB%84%E4%B8%8E%E5%90%91%E9%87%8F%E5%8C%96%E8%AE%A1%E7%AE%97.ipynb)  
[第五章--Pandas入门](https://github.com/lidianxiang/python-for-data-analysis/blob/master/%E7%AC%AC%E4%BA%94%E7%AB%A0--pandas%E5%85%A5%E9%97%A8.ipynb)  
[第六章--数据载入、存储及文件格式](https://github.com/lidianxiang/python-for-data-analysis/blob/master/%E7%AC%AC%E5%85%AD%E7%AB%A0--%E6%95%B0%E6%8D%AE%E8%BD%BD%E5%85%A5%E3%80%81%E5%AD%98%E5%82%A8%E5%8F%8A%E6%96%87%E4%BB%B6%E6%A0%BC%E5%BC%8F.ipynb)  
[第七章--数据清洗与准备](https://github.com/lidianxiang/python-for-data-analysis/blob/master/%E7%AC%AC%E4%B8%83%E7%AB%A0--%E6%95%B0%E6%8D%AE%E6%B8%85%E6%B4%97%E4%B8%8E%E5%87%86%E5%A4%87.ipynb)  
[第八章--数据规整：聚合、合并和重塑](https://github.com/lidianxiang/python-for-data-analysis/blob/master/%E7%AC%AC%E5%85%AB%E7%AB%A0--%E6%95%B0%E6%8D%AE%E8%A7%84%E6%95%B4%EF%BC%9A%E8%81%9A%E5%90%88%E3%80%81%E5%90%88%E5%B9%B6%E5%92%8C%E9%87%8D%E5%A1%91.ipynb)  
[第九章--绘图和可视化](https://github.com/lidianxiang/python-for-data-analysis/blob/master/%E7%AC%AC%E4%B9%9D%E7%AB%A0--%E7%BB%98%E5%9B%BE%E5%92%8C%E5%8F%AF%E8%A7%86%E5%8C%96.ipynb)  
[第十章--数据聚合与分组运算](https://github.com/lidianxiang/python-for-data-analysis/blob/master/%E7%AC%AC%E5%8D%81%E7%AB%A0--%E6%95%B0%E6%8D%AE%E8%81%9A%E5%90%88%E4%B8%8E%E5%88%86%E7%BB%84%E8%BF%90%E7%AE%97.ipynb)  
[第十一章--时间序列](https://github.com/lidianxiang/python-for-data-analysis/blob/master/%E7%AC%AC%E5%8D%81%E4%B8%80%E7%AB%A0--%E6%97%B6%E9%97%B4%E5%BA%8F%E5%88%97.ipynb)  
[第十二章--pandas高级应用](https://github.com/lidianxiang/python-for-data-analysis/blob/master/%E7%AC%AC%E5%8D%81%E4%BA%8C%E7%AB%A0--pandas%E9%AB%98%E7%BA%A7%E5%BA%94%E7%94%A8.ipynb)  
[第十三章--Python建模库介绍](https://github.com/lidianxiang/python-for-data-analysis/blob/master/%E7%AC%AC%E5%8D%81%E4%B8%89%E7%AB%A0--Python%E5%BB%BA%E6%A8%A1%E5%BA%93%E4%BB%8B%E7%BB%8D.ipynb)  
[第十四章--数据分析案例](https://github.com/lidianxiang/python-for-data-analysis/blob/master/%E7%AC%AC%E5%8D%81%E5%9B%9B%E7%AB%A0--%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E6%A1%88%E4%BE%8B.ipynb)  

---

作者[Wes McKinney](https://github.com/wesm)是pandas的创作者，所以书中关于pandas的讲解也是最实用的部分。

![](https://upload-images.jianshu.io/upload_images/7178691-0d965cf51eb5af9e.png?imageMogr2/auto-orient/)

这本书自2013年第一版发行后，就广受好评。第一版的时候作者用的是Python2，不过随着Python2的维护年限将近（2020），以及Python3的推广，整个社群向Python3转变已经成为不可扭转的趋势。所以在第二版里，作者使用了Python3.6。而我实际写的代码则是基于Python3.5，使用上几乎没有任何差别。

> 第二版主要的更新：
> 1. 所有代码，包括Python教程，都升级到了Python3.6（第一版用的是Python2.7）  
> 2. 更新了Python的安装介绍。这次改用Anaconda Python发行版，以及其他一些需要的Python包  
> 3. 使用了最新的2017版pandas  
> 4. 新增了一章，用来介绍pandas的高级应用工具，和其他一些有用的小贴士  
> 5. 简单介绍了如何使用statsmodels和scikit-learn  

---

## 2. 使用代码示例
可以通过本书的GitHub仓库获得本书的每一章的数据文件和相关材料。GitHub仓库地址请[点击这里](https://github.com/wesm/pydata-book)

---

## 3. 感悟
第一次完整的重现了书中的所有代码，感觉这是一本非常非常好的书，值的一读再读。
