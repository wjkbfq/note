# cnlab

#### 20190203-SVM
- SVM介绍
    - 曾经最好的分类器，现在是深度学习
    - 相关方法：逻辑回归模型(Logistic Regression, LR)
        - Logistic回归的好处：能给出分类（样本属于哪个类别）的概率
        - SVM的好处：泛化能力好，分类的效果好
        - 不考虑训练效率的话，SVM的使用效果较好
- 相关概念（说法不一）
    - 线性可分支持向量机
        - 硬间隔SVM：100%可分，有排空区域
    - 线性SVM
        - 软间隔SVM：有交叉，不能线性完全分开
    - 非线性SVM：曲线，曲面，超曲面
        - 核函数kernel function
- ![20190204_053933-分割超平面](https://i.imgur.com/97nEjoy.png)
- ![分割超平面的思考](https://i.imgur.com/Nj0JXkr.png)
- ![](https://i.imgur.com/qmWaBhK.png)
- ![](https://i.imgur.com/teprgUz.png)
- ![](https://i.imgur.com/PtK6S1t.png)
- ![](https://i.imgur.com/pc4LqUN.png)

- 目标函数
    - 分割时，样本的地位不同
        - ABC样本起决定作用，支撑住分割超平面
        - 样本点是N维向量，支撑向量
        - 利用支撑向量得到machine，SVM
    - 



