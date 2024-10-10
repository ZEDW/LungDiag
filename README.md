# LungDiag
1.annotation_example展示的是用于训练的数据格式，它是将.txt文本格式经过PIAT标注之后生成的json文本，PIAT算法的相关描述见https://ieeexplore.ieee.org/document/9780554/。

2.Train_set用于存储训练集的数据,Test_set是用于验证的测试集数据，二者文件都是上述json文件形式，文件名为“疾病名称_住院号”来命名。

3.disease_classification_name.xlsx是用来呼吸系统疾病诊断名称标准化的文件。

4.clinical_features_synonym.xlsx是用来构建LungDiag临床特征的标准化文件
