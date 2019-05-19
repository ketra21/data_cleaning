
## Act_Report
1. 整理后数据共计1994条记录，时间范围为2015年11月-2017年0月，其中主要集中在2015年11，12月;

![](https://raw.githubusercontent.com/ketra21/data_cleaning/master/date_distributing.png)

- 评分的分母（rating_denominator）大部分为10，平均分为10.53，评分的分子（rating_numerator）大部分略大于10，平均分为11.57，可见作者总体对狗狗评分高于标准值； 
- 大部分记录中只有一张照片，最高有4张照片； 
- 平均转发数为2787，点赞数为9295；
- 数量排名前五位的狗狗名字分别是：'Charlie', 'Cooper', 'Oliver', 'Tucker', 'Lucy';
- 在所有的1477条记录中，狗狗品种共有111 种,其中排名前10位的狗狗品种 ['golden_retriever', 'Labrador_retriever', 'Pembroke', 'Chihuahua', 'pug', 'chow', 'Samoyed', 'Pomeranian', 'toy_poodle', 'malamute'] 的数量占狗狗总数量的43.0%;
![](https://raw.githubusercontent.com/ketra21/data_cleaning/master/se_count.png)
- 评分最高的前10位的狗狗品种分别是：'clumber', 'soft-coated_wheaten_terrier', 'West_Highland_white_terrier','Great_Pyrenees', 'borzoi', 'Labrador_retriever', 'Siberian_husky','golden_retriever', 'Pomeranian', 'Saluki'：
- retweet_count和favorite_count呈现正相关性；

![](https://raw.githubusercontent.com/ketra21/data_cleaning/master/retweet_coun_favorite_count.png)
- 转发数和评分的相关性不大.

![](https://raw.githubusercontent.com/ketra21/data_cleaning/master/retweet_coun_rating_numerator.png)
