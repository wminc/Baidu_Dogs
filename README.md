# Baidu_Dogs
1、对近100种狗的图片进行分类。
2、使用数据增强扩充图片，在单模型的基础上提高了近一个百分点。
3、使用fast-rcnn切割图片，将数据分为全图，狗身，狗头三部分。将三部分特征级联，单模型下提高了几个千分点。
4、采用投票策略集成resNet,Inception,Xception和denseNet等模型。最终准确率为81.4%