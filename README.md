# 100DaysOfMLCode
100DaysOfMLCode

2018-08-06-Day01
-----
* 安装依赖包 python -m pip install [name]
* 按up button直接复制上一行
* 按right button原位复制填充
* 按shift+方向键 选择
* 读取csv文件 pandas.read_csv('name.csv')
* 为数据帧的变量构建矩阵和向量dataset.iloc[].values
* 缺失数据补齐sklearn.preprocessing imputer.transform
* 标签sklearn.preprocessing labelencoder
* 	创建虚拟变量onehotencoder
* 分训练测试集sklearn.crossvalidation train_test_split()
* 特征标准化 sklearn.preprocessing StandardScalar

2018-08-07-Day02
-----
* train_test_split
* 	test_size 样本占比（样本数）, random_state 随机数种子
* matplotlib.pyplot 强大画图库-visualization
* 	plt.scatter 散点
* 	plt.plot 连续图像
* 	plt.show() 画图！
  
2018-08-08-Day03
------
* 与simple linear regression对比：
* 	dataset.iloc中：	x 1 -1 y 1  4
* 	加入dummy var (bool型) //using onehotencoder

* qusetions: 1.单一因变量？ 2.plt函数奇葩图像
    
2018-08-09-Day04
------
* 强烈需要学习matplotlib库！！！！！唔

2018-08-10-Day05
-----
* numpy.ndarray n维数组
* plt.plot(X_, **, 'ro', **)中'ro'相当于scatter
* confusion_matrix

2018-08-11-Day06
------
* ndarray类比C语言多维数组
* 面对ndarray的plot or scatter 可采取for遍历……可惜比较复杂
* 搜寻简单方法

2018-08-12-Day07
------
* K nearest neighbors 简称KNN
* 库： from sklearn.neighbors import KNeighborsClassifier
* KNN针对该Social_Network_Ads.csv数据比LR更准确

2018-08-13-Day08
-------
* bug：sns.pairplot(df, hue='class', size=2.5)
* seaborn也是画图软件？
* 交互式编程与编译器的差异
* binary参数可用LR 多类数据必须用softmat回归

2018-08-14-Day09
--------
* 超平面！

2018-08-15-Day10
--------
* 发现matplotlib实现方案
* enumerate np.meshgrid ravel np.unique np.arrange
* []中真值表达式等价一句话if

2018-08-16-Day11
---------
* 搭建vultr服务器……

2018-08-17-Day12
---------
* 先验概率P(c) 后验概率P(c|x)
* 朴素贝叶斯分类器(Naive Bayes Classification)
* 拉普拉斯修正(Laplacian correction)

2018-08-18-Day13
------
* 发现Youtube新course ML for Hackers
* 快两周了 着手完成 ML in 3 Months 的Month1部分
