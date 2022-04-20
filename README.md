# ------------中文对话------------
# AdvertiseGen广告文案生成数据集
https://www.luge.ai/#/luge/dataDetail?id=9
## 数据集介绍
AdvertiseGen以商品网页的标签与文案的信息对应关系为基础构造，是典型的开放式生成任务，在模型基于key-value输入生成开放式文案时，与输入信息的事实一致性需要得到重点关注。
## 数据预览
任务描述：给定商品信息的关键词和属性列表kv-list，生成适合该商品的广告文案adv；
数据规模：训练集114k，验证集1k，测试集3k；
数据来源：清华大学CoAI小组；
数据样例：
```
{
  "content": "类型#上衣*材质#牛仔布*颜色#白色*风格#简约*图案#刺绣*衣样式#外套*衣款式#破洞",
  "summary": "简约而不简单的牛仔外套，白色的衣身十分百搭。衣身多处有做旧破洞设计，打破单调乏味，增加一丝造型看点。衣身后背处有趣味刺绣装饰，丰富层次感，彰显别样时尚。"
}
```
## 基线系统
本数据集提供的基线系统，基于百度提出的ERNIE-UNIMO统一模态预训练框架。在本次比赛的三个文本生成任务中，我们基于本基线使用的模型是UNIMO-text,是基于ERNIE-UNIMO框架在文本数据上预训练得到模型。
GitHub 基线系统
面向事实一致性的生成评测基线
## 数据集引用
如在学术论文中使用千言数据集，请添加相关引用说明，具体如下：
···
Shao, Zhihong, et al. "Long and Diverse Text Generation with Planning-based Hierarchical Variational Model." Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP). 2019.
···
## MD5
4be89fb276e8727923262d786cd3007c

# LCSTS_new中文短摘要生成数据集
https://www.luge.ai/#/luge/dataDetail?id=10
任务类型：文本生成
数据集大小：263.1M
使用权限：学术
特点：事实一致性
## 数据集介绍
LCSTS_new是中文短摘要最常用的LCSTS短摘要数据集的升级版本，在数据量、质量方面均有显著提升，在信息摘要与提炼的过程中，与原文的事实一致性需要得到重点关注。
## 数据预览
任务描述：给定文章正文doc，生成符合文章信息的摘要sum；
数据规模：训练集1500k，验证集 1k，测试集5k；
数据来源：LCSTS；
数据样例：
```
{
  "id": 6,
  "summary": "中国游客大增多国放宽签证",
  "content": "①北京和上海户籍的游客可获得韩国多次签证；②“整容客”可以不经由韩国使领馆、直接在网上申请签证；③中泰免签的实施日期尚未敲定；④越南已向中国持通行证旅游的公民全面开放。"
}
```
## 基线系统
本数据集提供的基线系统，基于百度提出的ERNIE-UNIMO统一模态预训练框架。在本次比赛的三个文本生成任务中，我们基于本基线使用的模型是UNIMO-text,是基于ERNIE-UNIMO框架在文本数据上预训练得到模型。
GitHub 基线系统
面向事实一致性的生成评测基线
## 数据集引用
如在学术论文中使用千言数据集，请添加相关引用说明，具体如下：
```
Hu, Baotian, Qingcai Chen, and Fangze Zhu. "LCSTS: A Large Scale Chinese Short Text Summarization Dataset." Proceedings of the 2015 Conference on Empirical Methods in Natural Language Processing. 2015.
```
## MD5
98479b44179f0657526f7bb32721ef22

# DuReader_QG问题生成数据集
https://www.luge.ai/#/luge/dataDetail?id=8
任务类型：文本生成
数据集大小：6M
使用权限：学术
特点：事实一致性
## 数据集介绍
DuReader robust旨在利用真实应用中的数据样本来衡量阅读理解模型的鲁棒性，评测模型的过敏感性、过稳定性以及泛化能力，是首个中文阅读理解鲁棒性数据集。
DuReader_QG是从DuReader robust中选择的问题生成任务子集
## 数据预览
任务描述：给定段落p和答案a，生成自然语言表述的问题q，且该问题符合段落和上下文的限制；
数据规模：训练集约14.5k，开发集约1k，测试集约1k；
数据样例：
```
{
  "context": "欠条是永久有效的,未约定还款期限的借款合同纠纷,诉讼时效自债权人主张债权之日起计算,时效为2年。 根据《中华人民共和国民法通则》第一百三十五条:向人民法院请求保护民事权利的诉讼时效期间为二年,法律另有规定的除外。 第一百三十七条:诉讼时效期间从知道或者应当知道权利被侵害时起计算。但是,从权利被侵害之日起超过二十年的,人民法院不予保护。有特殊情况的,人民法院可以延长诉讼时效期间。 第六十二条第(四)项:履行期限不明确的,债务人可以随时履行,债权人也可以随时要求履行,但应当给对方必要的准备时间。",
  "answer": "永久有效",
  "question": "欠条的有效期是多久",
  "id": 17
}
```
## 基线系统
本数据集提供的基线系统，基于百度提出的ERNIE-UNIMO统一模态预训练框架。在本次比赛的三个文本生成任务中，我们基于本基线使用的模型是UNIMO-text,是基于ERNIE-UNIMO框架在文本数据上预训练得到模型。
GitHub 基线系统
面向事实一致性的生成评测基线
## 数据集引用
如在学术论文中使用千言数据集，请添加相关引用说明，具体如下：
```
Tang, H., et al. (2021). DuReader_robust: A Chinese Dataset Towards Evaluating Robustness and Generalization of Machine Reading Comprehension in Real-World Applications. Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 2: Short Papers), 955–963.  
```
## MD5
63b8fc89decc610df8516ccf4c55768c

# ------------情感分析------------
# ChnSentiCorp句子级情感分类数据集
https://www.luge.ai/#/luge/dataDetail?id=25
## 数据集介绍
经典的句子级情感分类数据集，包含酒店、笔记本电脑和数据相关的网络评论数据，共包含积极、消极两个类别。
## 数据预览
本数据集任务类型为句子级情感分类。任务定义如下：
对于给定的文本d，系统需要根据文本的内容，给出其对应的情感类别或者情感得分s，类别s取值可以是“积极”、“消极”的离散值，表示情感类别。也可以是1-5的连续实数，表示情感得分（详见ASAP_SENTI数据集）。数据集中每个样本是一个二元组<d, s>，样例如下：
–输入文本（d）：15.4寸笔记本的键盘确实爽，基本跟台式机差不多了，蛮喜欢数字小键盘，输数字特方便，样子也很美观，做工也相当不错
–情感类别（s）：积极/4.0
数据集的具体统计数据如下表所示：
任务类别	数据集名称	训练集大小	开发集大小	测试集大小
句子级情感分类	ChnSentiCorp	9600	1200	1200
注：部分数据集并不包含开发集，用户在模型训练时可通过交叉验证的方式调节模型参数。
## 基线系统
GitHub 基线系统
SKEP: Sentiment Knowledge Enhanced Pre-training for Sentiment Analysis
## MD5
7ef61b08ad10fbddf2ba97613f071561

# SE-ABSA16观点级情感分类数据集
https://www.luge.ai/#/luge/dataDetail?id=18
数据集介绍
观点级情感分类是一种细粒度的情感分类任务，旨在评论分本中针对不同评价对象或者评论维度的情感分类。该数据集包含积极、消极两个类别。共覆盖手机、相机两个领域的数据。
数据预览
本数据集任务类型为评价对象级情感分类，任务定义如下：对于给定的文本d和文本中描述的一个评价对象a，给出针对该评价对象a的情感类别s，类别s一般只包含积极、消极两类，部分数据集涵盖更细粒度的分类体系。数据集中每个样本是一个三元组
，样例如下： –输入文本（d）：D4外形设计真的很成功不知道楼主摸没摸过D4真机非常成功的设计本以为D3系列很难超越了但是D4的流线风格显然不比D3差在整体感上还更胜一筹 –评价对象（a）：相机外形设计 –情感类别（s）：积极
任务类别	数据集名称	训练集大小	开发集大小	测试集大小
评价对象级情感分类	SE-ABSA16_PHNS	1336	/	529
评价对象级情感分类	SE-ABSA16-CAME	1317/505	/	/
注：部分数据集并不包含开发集，用户在模型训练时可通过交叉验证的方式调节模型参数。
基线系统
GitHub 基线系统
SKEP: Sentiment Knowledge Enhanced Pre-training for Sentiment Analysis
数据集引用
如在学术论文中使用千言数据集，请添加相关引用说明，具体如下：

Maria, P., et al. (2016) SemEval-2016 Task 5: Aspect based sentiment analysis. In Proceedings of the 10th International Workshop on Semantic Evaluation.
论文地址
MD5
6d8e4d6608afd65ade2d026a66e15583

# COTE中文观点抽取数据集
https://www.luge.ai/#/luge/dataDetail?id=19
数据集介绍
评价对象抽取任务旨在对于给定的评论文本，自动抽取其中包含的评价对象。该任务是情感分析中的基础任务之一，该数据集覆盖百度、点评和马蜂窝上抓取的数据。
数据预览
本数据集任务类型为评价对象抽取，任务定义如下：
对于给定的文本d，系统需要根据文本的内容，给出其中描述的评价对象a，其中评价对象一定在篇章文本d中出现。数据集中每个样本是一个二元组<d, a>，样例如下：

–输入文本（d）：重庆老灶火锅还是很赞的，有机会可以尝试一下！
–评价对象（a）：重庆老灶火锅 本数据集的具体统计数据如下表所示：
任务类别	数据集名称	训练集大小	开发集大小	测试集大小
观点抽取	COTE-BD	8533	/	3658
观点抽取	COTE-MFW	41253	/	17681
观点抽取	COTE-DP	25258	/	10825
注：部分数据集并不包含开发集，用户在模型训练时可通过交叉验证的方式调节模型参数。
基线系统
GitHub 基线系统
SKEP: Sentiment Knowledge Enhanced Pre-training for Sentiment Analysis
数据集引用
如在学术论文中使用千言数据集，请添加相关引用说明，具体如下：

Yan, L., et al. (2018) Character-based bilstm-crf incorporating pos and dictionaries for chinese opinion target extraction. In Asian Conference on Machine Learning.
论文地址
MD5
5e741b1326913ef497e7fcc59a239bdf

# NLPCC14-SC情感分类评测数据集
https://www.luge.ai/#/luge/dataDetail?id=20
数据集介绍
该数据集来自NLPCC 2014 情感分类评测任务数据集，旨在评估深度学习方法在情感分类任务上的效果，数据集覆盖多个领域（例如：书籍、DVD、电子等），共包含积极、消极两个类别。
数据预览
本数据集任务类型为句子级情感分类。任务定义如下： 对于给定的文本d，系统需要根据文本的内容，给出其对应的情感类别或者情感得分s，类别s取值可以是“积极”、“消极”的离散值，表示情感类别。也可以是1-5的连续实数，表示情感得分（详见ASAP_SENTI数据集）。数据集中每个样本是一个二元组<d, s>，样例如下：

–输入文本（d）：15.4寸笔记本的键盘确实爽，基本跟台式机差不多了，蛮喜欢数字小键盘，输数字特方便，样子也很美观，做工也相当不错
–情感类别（s）：积极/4.0

数据集的具体统计数据如下表所示：
任务类别	数据集名称	训练集大小	开发集大小	测试集大小
句子级情感分类	NLPCC14-SC	10000	/	2500
注：部分数据集并不包含开发集，用户在模型训练时可通过交叉验证的方式调节模型参数。
基线系统
GitHub 基线系统
SKEP: Sentiment Knowledge Enhanced Pre-training for Sentiment Analysis
MD5
4792a0982bc64b83d9a76dcce8bc00ad

# ASAP中文评论分析数据集
https://www.luge.ai/#/luge/dataDetail?id=17
数据集介绍
业界最大规模中文评论分析数据集ASAP，首次实现对评论得分预估和对象级情感分类两个任务的联合标注，数据全部源于真实的电商场景，从数据规模和标注质量上都远超其他数据集。
数据预览
本数据集任务类型包含句子级情感分类和观点级情感分类。 句子级情感分类数据集ASAP_SENT 任务定义如下：

对于给定的文本d，系统需要根据文本的内容，给出其对应的情感类别或者情感得分s，类别s取值可以是“积极”、“消极”的离散值，表示情感类别。也可以是1-5的连续实数，表示情感得分（详见ASAP_SENTI数据集）。

数据集中每个样本是一个二元组<d, s>，样例如下：

–输入文本（d）：15.4寸笔记本的键盘确实爽，基本跟台式机差不多了，蛮喜欢数字小键盘，输数字特方便，样子也很美观，做工也相当不错
–情感类别（s）：积极/4.0

观点级情感分类ASAP_SENT任务定义如下： 对于给定的文本d和文本中描述的一个评价对象a，给出针对该评价对象a的情感类别s，类别s一般只包含积极、消极两类，部分数据集涵盖更细粒度的分类体系。

数据集中每个样本是一个三元组<d, a, s>，样例如下：

–输入文本（d）：D4外形设计真的很成功不知道楼主摸没摸过D4真机非常成功的设计本以为D3系列很难超越了但是D4的流线风格显然不比D3差在整体感上还更胜一筹
–评价对象（a）：相机外形设计 –情感类别（s）：积极
任务类别	数据集名称	训练集大小	开发集大小	测试集大小
句子级情感分类	ASAP_SENT	36850	4940	4940
评价对象级级情感分类	ASAP_ASPECT	213371	29101	28363
注：部分数据集并不包含开发集，用户在模型训练时可通过交叉验证的方式调节模型参数。
数据集引用
如在学术论文中使用千言数据集，请添加相关引用说明，具体如下：

Bu, J., et al.(2021). ASAP: A Chinese Review Dataset Towards Aspect Category Sentiment Analysis and Rating. NACCL, 2069-2079.
论文地址
MD5
eab03c71e480a255c6b58dd04db8bee9

# DuVideoSenti多模态情感标签数据集
https://www.luge.ai/#/luge/dataDetail?id=21
数据集介绍
面向推荐场景推出多模态情感标签数据集DuVideoSenti，引入视频情感泛标签预测任务，构建了视频情感泛标签体系。该体系由人工定义的“文艺清新”、“时尚炫酷”、“舒适温馨”等11个情感泛标签组成，用以刻画用户浏览视频后的视觉和情感方面的感受。数据集为每个小视频标注了情感泛标签，并且提供了视频的标题、帧图特征用于模型的训练和预测。
数据预览
本数据集为多模情感分析数据集，包含视频情感泛标签抽取任务（Video Tagging），旨在验证模型在文本、视觉多模态数据上的效果。该任务的定义如下：

对于给定的视频v，系统需要根据视频的标题t，以及视频的帧图特征f，给出其对应的类别c。数据集中每个样本是一个三元组<t, f, c>，样例如下：

–视频标题（t）：#好看电影#《环太平洋2》
–视频特征（f）：0.013379, 1.836357, ….
–视频类别（c）：时尚炫酷

针对上述视频多分类任务，我们构建了视频情感泛标签数据集DuVideoSenti，该数据集的提出源于真实的个性化推荐需求：在个性化推荐场景中，往往存在大量内容题材、质量相同，但却能给用户带来不同视觉冲击和情感感受的资源。针对这类资源，需要构建能够刻画用户不同的视觉和情感感受的完备的标签体系。从而将其应用于个性化推荐，提升用户体验。基于此，我们构建了包含“文艺清新”、“时尚炫酷”、“舒适温馨”、“客观理性”、“家长里短”、“土里土气”、“呆萌可爱”、“奇葩低俗”、“正能量”、“负能量”、“其他”，共11个类别的情感范标签体系，且标注的视频资源完全来自于百度自有小视频资源，并且全部由人工标注，数据真实，标注质量高。

数据集的具体统计数据如下表所示：
任务类别	数据集名称	训练集大小	开发集大小	测试集大小
视频多分类	DuVideoSenti	4500	/	1130
注：部分数据集并不包含开发集，用户在模型训练时可通过交叉验证的方式调节模型参数。
数据集引用
如在学术论文中使用千言数据集，请添加相关引用说明，具体如下：

Tang, H., et al. (2021). A MultiModal Sentiment Dataset for Video Recommendation.

# SENTI_ROBUST中文情感鲁棒性数据集
https://www.luge.ai/#/luge/dataDetail?id=23
数据集介绍
“可信AI”的概念在近几年提出，并且逐渐成为全球共识。可信AI，就是保证AI系统的可解释性、鲁棒性和公平性，确保算法可被人信任。在情感分析技术的科学研究和产业落地中，可信情感分析系统需要具备较强的鲁棒性和可解释能力，也就是要求模型针对各种不同表达，既能给出精准的预测结果，还能给出其判断依据，从而保证模型的预测结果更加置信。


作为业界首个中文情感可信数据集，DuTrust基于人工标注的扰动数据和情感证据，全部来源于真实用户评论数据，同时测试模型的鲁棒性和可解释性，全面评估模型的可信能力。
数据预览
本数据集是DuTrust数据集中情感鲁棒性评估任务，该任务的定义如下：

对于给定的输入文本t，及其对应的情感极性s，根据人工定义的扰动类型（例如针对情感分析任务，我们预先定义扰动类型包括：“新词/冷门词替换”、“改为否定表达”、“不重要的term增删改”等），标注对应的扰动文本t’，并且标注扰动后样本所对应的情感极性s’。系统需要分别预测原始输入文本t以及扰动文本t’的情感分类结果，最终通过统计模型在全部预测数据（包括所有的预测文本以及扰动文本）上的准确率，作为模型鲁棒性的评价指标。样例如下：

原始文本（t）：六合唯一的跃层户型，就是价格高
原始文本对应的情感极性（s）：消极
扰动文本（t’）：六合唯一的跃层户型，就是价格感人（扰动类型“隐晦情感表达”）
扰动文本对应的情感极性（s’）：消极

针对上述情感鲁棒性评估任务，对应于SENTI_ROBUST数据集，该数据集包含所有的原始文本和人工构建的扰动文本，共计3,002条样本，用户需要在ChnSentiCorp数据集上训练，然后在SENTI_ROBUST上进行模型的鲁棒性评估。具体如下表所示：
任务类别	数据集名称	训练集大小	开发集大小	测试集大小
情感鲁棒性评估	SENTI_ROBUST	9600	/	3004
注：训练集数据推荐使用ChnSentiCorp。
数据集引用
如在学术论文中使用千言数据集，请添加相关引用说明，具体如下：

Wang,L., et al. (2021) A Sentiment Analysis Dataset for Trustworthiness Evaluation.
论文地址
MD5
02d3c29c83de848ad772ca773ce6c4d6

# SENTI_RATIONAL情感可解释性数据集
https://www.luge.ai/#/luge/dataDetail?id=22
数据集介绍
“可信AI”的概念在近几年提出，并且逐渐成为全球共识。可信AI，就是保证AI系统的可解释性、鲁棒性和公平性，确保算法可被人信任。在情感分析技术的科学研究和产业落地中，可信情感分析系统需要具备较强的鲁棒性和可解释能力，也就是要求模型针对各种不同表达，既能给出精准的预测结果，还能给出其判断依据，从而保证模型的预测结果更加置信。

作为业界首个中文情感可信数据集，DuTrust基于人工标注的扰动数据和情感证据，全部来源于真实用户评论数据，同时测试模型的鲁棒性和可解释性，全面评估模型的可信能力。
数据预览
本数据集是DuTrust数据集中情感可解释性评估任务，该任务的定义如下：

对于输入的文本t及其对应的情感极性s，人工标注预测极性s所依赖的证据。证据来自输入文本，且每一条证据均满足充分、简洁及可读可理解3个特性。参赛系统需要给出输入文本对应的预测依赖证据，也就是输入文本中对预测影响较大的若干部分。我们推荐使用飞桨的可解释性算法开源库InterpretDL[9]。InterpretDL遵循开箱即用『Plug-and-Play』的设计理念，现已集成16种主流的可解释性算法，如基于注意力权重、基于梯度[6],[7]以及LIME[8]等证据分析方法和工具，可供大家参考及使用。评估系统计算参赛系统提交的预测证据和标准证据的F1值，作为可解释性的评价指标。标准证据样例如下：

–文本ID：25
–文本(t)：陈老师人非常好，做事很细心
–情感极性(s)：积极
–情感类别：单情感
–文本分词：[“陈”, “老”, “师”, “人”, “非”, “常”, “好”, “，”, “做”, “事”, “很”, “细”, “心”]
–证据：[[“3”, “6”], [“11”, “12”]]

针对上述可解释性评测任务，对应于SENTI_RATIONAL数据集，该数据集包含所有的文本和人工标注的证据，共计3,004条样本，用户需要在SENTI_RATIONAL上进行模型的可解释性评测。具体如下表所示：
任务类别	数据集名称	训练集大小	开发集大小	测试集大小
情感可解释性评估	SENTI_RATIONAL	9600	/	3004
注：训练集数据推荐使用ChnSentiCorp。
数据集引用
如在学术论文中使用千言数据集，请添加相关引用说明，具体如下：

Wang,L., et al. (2021) A Sentiment Analysis Dataset for Trustworthiness Evaluation.
论文地址
MD5
fc04f4f7904da78ad60e3ba685471795

# ------------中文对话------------
# 豆瓣中文开放域对话数据集
https://www.luge.ai/#/luge/dataDetail?id=33
任务类型：中文对话
数据集大小：145M
特点：闲聊能力
## 数据集介绍
Douban是一个大规模中文开放域对话数据集，旨在考察模型在闲聊场景中，是否可以生成流畅的、与上下文相关的对话回复。
## 数据预览
该数据集的任务定义如下：
给定对话历史H(u_1, u_2, …, u_t-1)
要求参评系统预测：符合对话历史，且自然流畅、信息丰富的机器回复u_t。
``` {
  "kg": [
    [
      "沈阳",
      "2018-12-24",
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃"
    ],
    [
      "糖醋排骨",
      "成分",
      "猪肋排、姜片、葱、生抽、糖、醋、料酒、八角。"
    ],
    [
      "糖醋排骨",
      "类型",
      "热菜"
    ],
    [
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃",
      "适合吃",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "特色菜",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "评分",
      "4.8"
    ],
    [
      "大清花饺子（十一纬路店）",
      "人均价格",
      "50"
    ],
    [
      "大清花饺子（十一纬路店）",
      "地址",
      "沈河区十一纬路198号（近南二经街）"
    ],
    [
      "大清花饺子（十一纬路店）",
      "订单量",
      "1405"
    ]
  ],
  "user_profile": {
    "职业状态": "工作",
    "同意的新闻": " 何炅 的新闻",
    "没有接受的音乐": [
      " 还有我",
      "心火烧"
    ],
    "喜欢的音乐": " 另一个自己",
    "年龄区间": "大于50",
    "拒绝": " 电影",
    "喜欢的明星": " 何炅",
    "接受的音乐": [
      " 向前奔跑",
      "思念的距离",
      "我是大侦探",
      "希望爱",
      "现在爱",
      "再见",
      "一路走过"
    ],
    "居住地": "沈阳",
    "喜欢的poi": " 大清花饺子（十一纬路店）",
    "姓名": "陈轩奇",
    "同意的美食": " 糖醋排骨",
    "性别": "男"
  },
  "conversation": [
    "[1]今天是什么天气？",
    "今天沈阳: 晴, 西南风, 最高气温:2℃, 最低气温:-12℃，天气有点冷，注意保暖。",
    "你知道的真多。",
    "[2]这种天气温适合吃 『糖醋排骨』了呢。",
    "糖醋排骨可是我最喜欢的美食，真想现在就去吃糖醋排骨呢。",
    "[3]我正好知道有一家店，推荐您在 『大清花饺子（十一纬路店）』 订糖醋排骨。",
    "这家店的地址在哪里？",
    "这家店的地址：沈河区十一纬路198号（近南二经街）",
    "人均价格是多少？",
    "人均价格50元。",
    "评分是多少？",
    "评分是4.8",
    "今天中午12点半我一个人去吃，我预定一下。",
    "好的，这就为您预定。",
    "[4]先去准备一下，再见",
    "好的，再见，祝你生活愉快！"
  ],
  "goals": "[1]问天气(User主动，User问天气，根据给定知识，Bot回复完整的天气信息，User满足并好评)-->[2]美食推荐(Bot主动推荐，这种天气温适合吃 『糖醋排骨』, User接受。需要聊2轮)-->[3]poi推荐(Bot主动，Bot推荐在 『大清花饺子（十一纬路店）』 订 『糖醋排骨』, User问 『大清花饺子（十一纬路店）』 的『人均价格』、『地址』、『评分』，Bot逐一回答后，最终User接受并提供预订信息:『就餐时间』 和 『就餐人数』)-->[4]再见",
  "situation": "聊天时间:2018-12-24 中午12:00，在公司 星期一"
}
```
## 数据集引用
如在学术论文中使用千言数据集，请添加相关引用说明，具体如下：
```
Yu Wu, Wei Wu, Chen Xing, Ming Zhou, Zhoujun Li. 2017. Sequential Matching Network: A New Archtechture for Multi-turn Response Selection in Retrieval-based Chatbots. In ACL.
```
## MD5
557b8f289d57478af442ba67c25037ec

# DuConv知识对话数据集
https://www.luge.ai/#/luge/dataDetail?id=30
数据集介绍
DuConv旨在考察模型是否可以在对话过程中充分利用外部知识(既包括结构化知识，也包括非结构化知识)，并且在生成对话回复的过程中引入外部知识，是首个bot主动的中文知识对话数据集。
数据预览
该数据集的任务定义如下：
给定对话目标g(部分数据集没有)、知识信息M、对话历史H(u_1, u_2, …, u_t-1)
要求参评系统预测：符合对话历史和对话目标，且自然流畅、信息丰富的机器回复u_t。
{
  "kg": [
    [
      "沈阳",
      "2018-12-24",
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃"
    ],
    [
      "糖醋排骨",
      "成分",
      "猪肋排、姜片、葱、生抽、糖、醋、料酒、八角。"
    ],
    [
      "糖醋排骨",
      "类型",
      "热菜"
    ],
    [
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃",
      "适合吃",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "特色菜",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "评分",
      "4.8"
    ],
    [
      "大清花饺子（十一纬路店）",
      "人均价格",
      "50"
    ],
    [
      "大清花饺子（十一纬路店）",
      "地址",
      "沈河区十一纬路198号（近南二经街）"
    ],
    [
      "大清花饺子（十一纬路店）",
      "订单量",
      "1405"
    ]
  ],
  "user_profile": {
    "职业状态": "工作",
    "同意的新闻": " 何炅 的新闻",
    "没有接受的音乐": [
      " 还有我",
      "心火烧"
    ],
    "喜欢的音乐": " 另一个自己",
    "年龄区间": "大于50",
    "拒绝": " 电影",
    "喜欢的明星": " 何炅",
    "接受的音乐": [
      " 向前奔跑",
      "思念的距离",
      "我是大侦探",
      "希望爱",
      "现在爱",
      "再见",
      "一路走过"
    ],
    "居住地": "沈阳",
    "喜欢的poi": " 大清花饺子（十一纬路店）",
    "姓名": "陈轩奇",
    "同意的美食": " 糖醋排骨",
    "性别": "男"
  },
  "conversation": [
    "[1]今天是什么天气？",
    "今天沈阳: 晴, 西南风, 最高气温:2℃, 最低气温:-12℃，天气有点冷，注意保暖。",
    "你知道的真多。",
    "[2]这种天气温适合吃 『糖醋排骨』了呢。",
    "糖醋排骨可是我最喜欢的美食，真想现在就去吃糖醋排骨呢。",
    "[3]我正好知道有一家店，推荐您在 『大清花饺子（十一纬路店）』 订糖醋排骨。",
    "这家店的地址在哪里？",
    "这家店的地址：沈河区十一纬路198号（近南二经街）",
    "人均价格是多少？",
    "人均价格50元。",
    "评分是多少？",
    "评分是4.8",
    "今天中午12点半我一个人去吃，我预定一下。",
    "好的，这就为您预定。",
    "[4]先去准备一下，再见",
    "好的，再见，祝你生活愉快！"
  ],
  "goals": "[1]问天气(User主动，User问天气，根据给定知识，Bot回复完整的天气信息，User满足并好评)-->[2]美食推荐(Bot主动推荐，这种天气温适合吃 『糖醋排骨』, User接受。需要聊2轮)-->[3]poi推荐(Bot主动，Bot推荐在 『大清花饺子（十一纬路店）』 订 『糖醋排骨』, User问 『大清花饺子（十一纬路店）』 的『人均价格』、『地址』、『评分』，Bot逐一回答后，最终User接受并提供预订信息:『就餐时间』 和 『就餐人数』)-->[4]再见",
  "situation": "聊天时间:2018-12-24 中午12:00，在公司 星期一"
}
测试集为JSON格式，样例数据如下：
{
  "kg": [
    [
      "沈阳",
      "2018-12-24",
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃"
    ],
    [
      "糖醋排骨",
      "成分",
      "猪肋排、姜片、葱、生抽、糖、醋、料酒、八角。"
    ],
    [
      "糖醋排骨",
      "类型",
      "热菜"
    ],
    [
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃",
      "适合吃",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "特色菜",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "评分",
      "4.8"
    ],
    [
      "大清花饺子（十一纬路店）",
      "人均价格",
      "50"
    ],
    [
      "大清花饺子（十一纬路店）",
      "地址",
      "沈河区十一纬路198号（近南二经街）"
    ],
    [
      "大清花饺子（十一纬路店）",
      "订单量",
      "1405"
    ]
  ],
  "user_profile": {
    "职业状态": "工作",
    "同意的新闻": " 何炅 的新闻",
    "没有接受的音乐": [
      " 还有我",
      "心火烧"
    ],
    "喜欢的音乐": " 另一个自己",
    "年龄区间": "大于50",
    "拒绝": " 电影",
    "喜欢的明星": " 何炅",
    "接受的音乐": [
      " 向前奔跑",
      "思念的距离",
      "我是大侦探",
      "希望爱",
      "现在爱",
      "再见",
      "一路走过"
    ],
    "居住地": "沈阳",
    "喜欢的poi": " 大清花饺子（十一纬路店）",
    "姓名": "陈轩奇",
    "同意的美食": " 糖醋排骨",
    "性别": "男"
  },
  "conversation": [
    "[1]今天是什么天气？",
    "今天沈阳: 晴, 西南风, 最高气温:2℃, 最低气温:-12℃，天气有点冷，注意保暖。",
    "你知道的真多。"
  ],
  "goals": "[1]问天气(User主动，User问天气，根据给定知识，Bot回复完整的天气信息，User满足并好评)-->…… -->[3]poi推荐(Bot主动，Bot推荐在 『大清花饺子（十一纬路店）』 订 『糖醋排骨』, User问 『大清花饺子（十一纬路店）』 的『人均价格』、『地址』、『评分』，Bot逐一回答后，最终User接受并提供预订信息:『就餐时间』 和 『就餐人数』)-->[4]再见",
  "situation": "聊天时间:2018-12-24 中午12:00，在公司 星期一"
}
基线系统
Aistudio平台基线系统
『2021语言与智能技术竞赛』-多技能对话任务基线系统
Github基线系统
LIC 2021对话比赛baseline
数据集引用
如在学术论文中使用千言数据集，请添加相关引用说明，具体如下：

Wenquan Wu, Zhen Guo, Xiangyang Zhou, Hua Wu, Xiyuan Zhang, Rongzhong Lian, and Haifeng Wang. 2019. Proactive human-machine conversation with explicit conversation goal. In ACL.

# DuRecDial对话推荐数据集
https://www.luge.ai/#/luge/dataDetail?id=31
数据集介绍
DuRecDial是首个融合多种对话类型的对话推荐数据集，它包含多种对话类型、多领域和丰富对话逻辑(考虑用户实时反馈)。在每个对话中，推荐者(bot)使用丰富的交互行为主动引导一个多类型对话不断接近推荐目标。DuRecDial旨在考察模型是否可以在对话过程中基于用户兴趣以及用户的实时反馈，主动给用户做出合理的推荐。
数据预览
该数据集的任务定义如下：
给定第一个对话目标g_1、最后两个对话目标g_L-1和g_L、知识信息M、用户Profile (画像)P、对话场景S、对话历史H(u_1, u_2, …, u_t-1)
要求参评系统预测：符合对话历史和对话目标序列，且自然流畅、信息丰富的机器回复u_t。
{
  "kg": [
    [
      "沈阳",
      "2018-12-24",
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃"
    ],
    [
      "糖醋排骨",
      "成分",
      "猪肋排、姜片、葱、生抽、糖、醋、料酒、八角。"
    ],
    [
      "糖醋排骨",
      "类型",
      "热菜"
    ],
    [
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃",
      "适合吃",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "特色菜",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "评分",
      "4.8"
    ],
    [
      "大清花饺子（十一纬路店）",
      "人均价格",
      "50"
    ],
    [
      "大清花饺子（十一纬路店）",
      "地址",
      "沈河区十一纬路198号（近南二经街）"
    ],
    [
      "大清花饺子（十一纬路店）",
      "订单量",
      "1405"
    ]
  ],
  "user_profile": {
    "职业状态": "工作",
    "同意的新闻": " 何炅 的新闻",
    "没有接受的音乐": [
      " 还有我",
      "心火烧"
    ],
    "喜欢的音乐": " 另一个自己",
    "年龄区间": "大于50",
    "拒绝": " 电影",
    "喜欢的明星": " 何炅",
    "接受的音乐": [
      " 向前奔跑",
      "思念的距离",
      "我是大侦探",
      "希望爱",
      "现在爱",
      "再见",
      "一路走过"
    ],
    "居住地": "沈阳",
    "喜欢的poi": " 大清花饺子（十一纬路店）",
    "姓名": "陈轩奇",
    "同意的美食": " 糖醋排骨",
    "性别": "男"
  },
  "conversation": [
    "[1]今天是什么天气？",
    "今天沈阳: 晴, 西南风, 最高气温:2℃, 最低气温:-12℃，天气有点冷，注意保暖。",
    "你知道的真多。",
    "[2]这种天气温适合吃 『糖醋排骨』了呢。",
    "糖醋排骨可是我最喜欢的美食，真想现在就去吃糖醋排骨呢。",
    "[3]我正好知道有一家店，推荐您在 『大清花饺子（十一纬路店）』 订糖醋排骨。",
    "这家店的地址在哪里？",
    "这家店的地址：沈河区十一纬路198号（近南二经街）",
    "人均价格是多少？",
    "人均价格50元。",
    "评分是多少？",
    "评分是4.8",
    "今天中午12点半我一个人去吃，我预定一下。",
    "好的，这就为您预定。",
    "[4]先去准备一下，再见",
    "好的，再见，祝你生活愉快！"
  ],
  "goals": "[1]问天气(User主动，User问天气，根据给定知识，Bot回复完整的天气信息，User满足并好评)-->[2]美食推荐(Bot主动推荐，这种天气温适合吃 『糖醋排骨』, User接受。需要聊2轮)-->[3]poi推荐(Bot主动，Bot推荐在 『大清花饺子（十一纬路店）』 订 『糖醋排骨』, User问 『大清花饺子（十一纬路店）』 的『人均价格』、『地址』、『评分』，Bot逐一回答后，最终User接受并提供预订信息:『就餐时间』 和 『就餐人数』)-->[4]再见",
  "situation": "聊天时间:2018-12-24 中午12:00，在公司 星期一"
}
测试集为JSON格式，样例数据如下：
{
  "kg": [
    [
      "沈阳",
      "2018-12-24",
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃"
    ],
    [
      "糖醋排骨",
      "成分",
      "猪肋排、姜片、葱、生抽、糖、醋、料酒、八角。"
    ],
    [
      "糖醋排骨",
      "类型",
      "热菜"
    ],
    [
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃",
      "适合吃",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "特色菜",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "评分",
      "4.8"
    ],
    [
      "大清花饺子（十一纬路店）",
      "人均价格",
      "50"
    ],
    [
      "大清花饺子（十一纬路店）",
      "地址",
      "沈河区十一纬路198号（近南二经街）"
    ],
    [
      "大清花饺子（十一纬路店）",
      "订单量",
      "1405"
    ]
  ],
  "user_profile": {
    "职业状态": "工作",
    "同意的新闻": " 何炅 的新闻",
    "没有接受的音乐": [
      " 还有我",
      "心火烧"
    ],
    "喜欢的音乐": " 另一个自己",
    "年龄区间": "大于50",
    "拒绝": " 电影",
    "喜欢的明星": " 何炅",
    "接受的音乐": [
      " 向前奔跑",
      "思念的距离",
      "我是大侦探",
      "希望爱",
      "现在爱",
      "再见",
      "一路走过"
    ],
    "居住地": "沈阳",
    "喜欢的poi": " 大清花饺子（十一纬路店）",
    "姓名": "陈轩奇",
    "同意的美食": " 糖醋排骨",
    "性别": "男"
  },
  "conversation": [
    "[1]今天是什么天气？",
    "今天沈阳: 晴, 西南风, 最高气温:2℃, 最低气温:-12℃，天气有点冷，注意保暖。",
    "你知道的真多。"
  ],
  "goals": "[1]问天气(User主动，User问天气，根据给定知识，Bot回复完整的天气信息，User满足并好评)-->…… -->[3]poi推荐(Bot主动，Bot推荐在 『大清花饺子（十一纬路店）』 订 『糖醋排骨』, User问 『大清花饺子（十一纬路店）』 的『人均价格』、『地址』、『评分』，Bot逐一回答后，最终User接受并提供预订信息:『就餐时间』 和 『就餐人数』)-->[4]再见",
  "situation": "聊天时间:2018-12-24 中午12:00，在公司 星期一"
}
基线系统
Aistudio平台基线系统
『2021语言与智能技术竞赛』-多技能对话任务基线系统
Github基线系统
LIC 2021对话比赛baseline
数据集引用
如在学术论文中使用千言数据集，请添加相关引用说明，具体如下：

Zeming Liu, Haifeng Wang, Zheng-Yu Niu, Hua Wu, Wanxiang Che, Ting Liu. 2020. Towards Conversational Recommendation over Multi-Type Dialogs. In ACL.

# LUGE-Dialogue开放域对话数据集合
https://www.luge.ai/#/luge/dataDetail?id=26
数据集介绍
本数据集旨在全面评测基于统一生成模型建模不同对话技能的整体效果，包括内容丰富度，多轮连贯性，知识准确率，对话主动性。


其中收集了一系列公开的开放域对话数据集，并对数据集进行了统一的整理以及提供了统一的评测方式，期望从多个技能、多个领域的角度对模型效果进行综合评价。该开源数据集旨在为研究人员和开发者提供学术和技术交流的平台，进一步提升开放域对话的研究水平，推动自然语言理解和人工智能领域技术的应用和发展。


同时，我们还收集并提供了开源的中文对话数据，参赛队可以基于这些对话数据构建自己的对话模型：


1.知识对话相关数据：百度的DuConv [1]。

2.推荐对话相关数据：百度的DuRecDial [2]。

3.画像对话数据：百度的画像数据集(DuPersona)。

4.其他对话数据：华为的微博数据 [3] ，北航和微软的豆瓣多轮对话 [4]，清华的LCCC数据集[5]，清华情感对话数据[6]，腾讯的检索辅助生成对话数据集 [7] ，清华的KdConv [8]。
数据预览
本数据集涵盖了多个对话场景：包括画像对话、知识对话、推荐对话等，旨在衡量开放域对话模型在各个不同技能上的效果和模型通用性。主要从三个方面评测开放领域对话模型的能力：

1.知识对话：是否可以在对话过程中充分利用外部知识，并且在生成对话回复的过程中引入外部知识。
2.推荐对话：是否可以在对话过程中基于用户兴趣以及用户的实时反馈，主动对用户做出推荐。
3.画像对话：是否可以生成流畅的、与角色信息一致的对话回复。

用户所构建的对话系统需要同时具备上述三项能力。下面详述这三个子任务的输入和输出：

子任务1：知识对话，评测开放领域对话模型是否可以在对话过程中充分利用外部知识，并且在生成对话回复的过程中引入外部知识
• 输入：对话目标g(部分数据集没有)、知识信息M、对话历史H(u_1, u_2, …, u_t-1)
• 输出：符合对话历史和对话目标，且自然流畅、信息丰富的机器回复u_t。

子任务2：推荐对话，评测开放领域对话模型是否可以在对话过程中基于用户兴趣以及用户的实时反馈，主动对用户做出合理的推荐
• 输入：第一个对话目标g_1、最后两个对话目标g_L-1和g_L、知识信息M、用户Profile (画像)P、对话场景S、对话历史H(u_1, u_2, …, u_t-1)
• 输出：符合对话历史和对话目标序列，且自然流畅、信息丰富的机器回复u_t。

子任务3：画像对话，评测开放领域对话模型是否可以在对话过程中充分利用给定的画像信息，并且输出保持画像一致的回复
• 输入：机器画像信息，对话历史H(u_1, u_2, …, u_t-1)
• 输出：符合对话历史和画像信息，且自然流畅、信息丰富的机器回复u_t。
对话技能名称	数据集	训练集样例数量	开发集样例数量	测试集样例数量	单/多轮	领域
知识对话	百度DuConv	19858	2000	5000	多轮	电影
推荐对话	百度DuRecDial	6618	946	4645	多轮	明星、电影、音乐、新闻、天气、美食、POI
画像对话	百度画像数据集(Chinese Persona Chat, CPC)	23000	1500	3000	多轮	开放域
其他	微博数据	3103764	1500	3000	多轮	开放域
其他	豆瓣多轮对话	500000	25001	1186	单轮	开放域
其他	清华LCCC	11987759	20000	10000	多轮	开放域
其他	清华情感数据集	899207	110000	110000	单轮	开放域
其他	腾讯检索辅助生成对话数据集	5498480	107332	156706	单轮	开放域
其他	清华kdConv	3000	300	2751	多轮	电影、音乐、旅游
注：部分数据集并不包含开发集，用户在模型训练时可通过交叉验证的方式调节模型参数。
基线系统
Aistudio平台基线系统
『2021语言与智能技术竞赛』-多技能对话任务基线系统
Github基线系统
LIC 2021对话比赛baseline
MD5
40e3ed52324c7aa7135d3d50a64e4255

# Tencent中文开放域对话数据集
https://www.luge.ai/#/luge/dataDetail?id=36
数据集介绍
Tencent是一个大规模的检索辅助生成的中文开放域对话数据集，旨在考察模型在闲聊场景中，是否可以生成流畅的、与上下文相关的对话回复。
数据预览
该数据集的任务定义如下：
给定对话历史H(u_1, u_2, …, u_t-1)
要求参评系统预测：符合对话历史，且自然流畅、信息丰富的机器回复u_t。
{
  "kg": [
    [
      "沈阳",
      "2018-12-24",
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃"
    ],
    [
      "糖醋排骨",
      "成分",
      "猪肋排、姜片、葱、生抽、糖、醋、料酒、八角。"
    ],
    [
      "糖醋排骨",
      "类型",
      "热菜"
    ],
    [
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃",
      "适合吃",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "特色菜",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "评分",
      "4.8"
    ],
    [
      "大清花饺子（十一纬路店）",
      "人均价格",
      "50"
    ],
    [
      "大清花饺子（十一纬路店）",
      "地址",
      "沈河区十一纬路198号（近南二经街）"
    ],
    [
      "大清花饺子（十一纬路店）",
      "订单量",
      "1405"
    ]
  ],
  "user_profile": {
    "职业状态": "工作",
    "同意的新闻": " 何炅 的新闻",
    "没有接受的音乐": [
      " 还有我",
      "心火烧"
    ],
    "喜欢的音乐": " 另一个自己",
    "年龄区间": "大于50",
    "拒绝": " 电影",
    "喜欢的明星": " 何炅",
    "接受的音乐": [
      " 向前奔跑",
      "思念的距离",
      "我是大侦探",
      "希望爱",
      "现在爱",
      "再见",
      "一路走过"
    ],
    "居住地": "沈阳",
    "喜欢的poi": " 大清花饺子（十一纬路店）",
    "姓名": "陈轩奇",
    "同意的美食": " 糖醋排骨",
    "性别": "男"
  },
  "conversation": [
    "[1]今天是什么天气？",
    "今天沈阳: 晴, 西南风, 最高气温:2℃, 最低气温:-12℃，天气有点冷，注意保暖。",
    "你知道的真多。",
    "[2]这种天气温适合吃 『糖醋排骨』了呢。",
    "糖醋排骨可是我最喜欢的美食，真想现在就去吃糖醋排骨呢。",
    "[3]我正好知道有一家店，推荐您在 『大清花饺子（十一纬路店）』 订糖醋排骨。",
    "这家店的地址在哪里？",
    "这家店的地址：沈河区十一纬路198号（近南二经街）",
    "人均价格是多少？",
    "人均价格50元。",
    "评分是多少？",
    "评分是4.8",
    "今天中午12点半我一个人去吃，我预定一下。",
    "好的，这就为您预定。",
    "[4]先去准备一下，再见",
    "好的，再见，祝你生活愉快！"
  ],
  "goals": "[1]问天气(User主动，User问天气，根据给定知识，Bot回复完整的天气信息，User满足并好评)-->[2]美食推荐(Bot主动推荐，这种天气温适合吃 『糖醋排骨』, User接受。需要聊2轮)-->[3]poi推荐(Bot主动，Bot推荐在 『大清花饺子（十一纬路店）』 订 『糖醋排骨』, User问 『大清花饺子（十一纬路店）』 的『人均价格』、『地址』、『评分』，Bot逐一回答后，最终User接受并提供预订信息:『就餐时间』 和 『就餐人数』)-->[4]再见",
  "situation": "聊天时间:2018-12-24 中午12:00，在公司 星期一"
}
基线系统
Aistudio平台基线系统
『2021语言与智能技术竞赛』-多技能对话任务基线系统
Github基线系统
LIC 2021对话比赛baseline
数据集引用
如在学术论文中使用千言数据集，请添加相关引用说明，具体如下：

Deng Cai, Yan Wang, Wei Bi, Zhaopeng Tu, Xiaojiang Liu, Shuming Shi. 2019. Retrieval-guided Dialogue Response Generation via a Matching-to-Generation Framework. In EMNLP.
论文地址
MD5
e0d00555e486e99296c36a6332530bd0

# 微博开放域短文本对话数据集
https://www.luge.ai/#/luge/dataDetail?id=32
数据集介绍
Weibo是一个大规模中文开放域短文本对话数据集，旨在考察模型在闲聊场景中，是否可以生成流畅的、与上下文相关的对话回复。
数据预览
该数据集的任务定义如下：
给定对话历史H(u_1, u_2, …, u_t-1)
要求参评系统预测：符合对话历史，且自然流畅、信息丰富的机器回复u_t。
{
  "kg": [
    [
      "沈阳",
      "2018-12-24",
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃"
    ],
    [
      "糖醋排骨",
      "成分",
      "猪肋排、姜片、葱、生抽、糖、醋、料酒、八角。"
    ],
    [
      "糖醋排骨",
      "类型",
      "热菜"
    ],
    [
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃",
      "适合吃",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "特色菜",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "评分",
      "4.8"
    ],
    [
      "大清花饺子（十一纬路店）",
      "人均价格",
      "50"
    ],
    [
      "大清花饺子（十一纬路店）",
      "地址",
      "沈河区十一纬路198号（近南二经街）"
    ],
    [
      "大清花饺子（十一纬路店）",
      "订单量",
      "1405"
    ]
  ],
  "user_profile": {
    "职业状态": "工作",
    "同意的新闻": " 何炅 的新闻",
    "没有接受的音乐": [
      " 还有我",
      "心火烧"
    ],
    "喜欢的音乐": " 另一个自己",
    "年龄区间": "大于50",
    "拒绝": " 电影",
    "喜欢的明星": " 何炅",
    "接受的音乐": [
      " 向前奔跑",
      "思念的距离",
      "我是大侦探",
      "希望爱",
      "现在爱",
      "再见",
      "一路走过"
    ],
    "居住地": "沈阳",
    "喜欢的poi": " 大清花饺子（十一纬路店）",
    "姓名": "陈轩奇",
    "同意的美食": " 糖醋排骨",
    "性别": "男"
  },
  "conversation": [
    "[1]今天是什么天气？",
    "今天沈阳: 晴, 西南风, 最高气温:2℃, 最低气温:-12℃，天气有点冷，注意保暖。",
    "你知道的真多。",
    "[2]这种天气温适合吃 『糖醋排骨』了呢。",
    "糖醋排骨可是我最喜欢的美食，真想现在就去吃糖醋排骨呢。",
    "[3]我正好知道有一家店，推荐您在 『大清花饺子（十一纬路店）』 订糖醋排骨。",
    "这家店的地址在哪里？",
    "这家店的地址：沈河区十一纬路198号（近南二经街）",
    "人均价格是多少？",
    "人均价格50元。",
    "评分是多少？",
    "评分是4.8",
    "今天中午12点半我一个人去吃，我预定一下。",
    "好的，这就为您预定。",
    "[4]先去准备一下，再见",
    "好的，再见，祝你生活愉快！"
  ],
  "goals": "[1]问天气(User主动，User问天气，根据给定知识，Bot回复完整的天气信息，User满足并好评)--&gt;[2]美食推荐(Bot主动推荐，这种天气温适合吃 『糖醋排骨』, User接受。需要聊2轮)--&gt;[3]poi推荐(Bot主动，Bot推荐在 『大清花饺子（十一纬路店）』 订 『糖醋排骨』, User问 『大清花饺子（十一纬路店）』 的『人均价格』、『地址』、『评分』，Bot逐一回答后，最终User接受并提供预订信息:『就餐时间』 和 『就餐人数』)--&gt;[4]再见",
  "situation": "聊天时间:2018-12-24 中午12:00，在公司 星期一"
}
基线系统
Aistudio平台基线系统
『2021语言与智能技术竞赛』-多技能对话任务基线系统
Github基线系统
LIC 2021对话比赛baseline
数据集引用
如在学术论文中使用千言数据集，请添加相关引用说明，具体如下：

Lifeng Shang, Zhengdong Lu, Hang Li. 2015. Neural Responding Machine for Short-Text Conversation. In ACL.
论文地址
MD5
d1e6913d32312ebc3e9d65afe2988a2d

# KdConv中文知识对话数据集
https://www.luge.ai/#/luge/dataDetail?id=35
数据集介绍
KdConv是一个多领域的中文知识对话数据集，旨在考察模型是否可以在对话过程中充分利用外部知识，并且在生成对话回复的过程中引入外部知识。
数据预览
该数据集的任务定义如下：
给定对话目标g(部分数据集没有)、知识信息M、对话历史H(u_1, u_2, …, u_t-1)
要求参评系统预测：符合对话历史和对话目标，且自然流畅、信息丰富的机器回复u_t。
{
  "kg": [
    [
      "沈阳",
      "2018-12-24",
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃"
    ],
    [
      "糖醋排骨",
      "成分",
      "猪肋排、姜片、葱、生抽、糖、醋、料酒、八角。"
    ],
    [
      "糖醋排骨",
      "类型",
      "热菜"
    ],
    [
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃",
      "适合吃",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "特色菜",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "评分",
      "4.8"
    ],
    [
      "大清花饺子（十一纬路店）",
      "人均价格",
      "50"
    ],
    [
      "大清花饺子（十一纬路店）",
      "地址",
      "沈河区十一纬路198号（近南二经街）"
    ],
    [
      "大清花饺子（十一纬路店）",
      "订单量",
      "1405"
    ]
  ],
  "user_profile": {
    "职业状态": "工作",
    "同意的新闻": " 何炅 的新闻",
    "没有接受的音乐": [
      " 还有我",
      "心火烧"
    ],
    "喜欢的音乐": " 另一个自己",
    "年龄区间": "大于50",
    "拒绝": " 电影",
    "喜欢的明星": " 何炅",
    "接受的音乐": [
      " 向前奔跑",
      "思念的距离",
      "我是大侦探",
      "希望爱",
      "现在爱",
      "再见",
      "一路走过"
    ],
    "居住地": "沈阳",
    "喜欢的poi": " 大清花饺子（十一纬路店）",
    "姓名": "陈轩奇",
    "同意的美食": " 糖醋排骨",
    "性别": "男"
  },
  "conversation": [
    "[1]今天是什么天气？",
    "今天沈阳: 晴, 西南风, 最高气温:2℃, 最低气温:-12℃，天气有点冷，注意保暖。",
    "你知道的真多。",
    "[2]这种天气温适合吃 『糖醋排骨』了呢。",
    "糖醋排骨可是我最喜欢的美食，真想现在就去吃糖醋排骨呢。",
    "[3]我正好知道有一家店，推荐您在 『大清花饺子（十一纬路店）』 订糖醋排骨。",
    "这家店的地址在哪里？",
    "这家店的地址：沈河区十一纬路198号（近南二经街）",
    "人均价格是多少？",
    "人均价格50元。",
    "评分是多少？",
    "评分是4.8",
    "今天中午12点半我一个人去吃，我预定一下。",
    "好的，这就为您预定。",
    "[4]先去准备一下，再见",
    "好的，再见，祝你生活愉快！"
  ],
  "goals": "[1]问天气(User主动，User问天气，根据给定知识，Bot回复完整的天气信息，User满足并好评)-->[2]美食推荐(Bot主动推荐，这种天气温适合吃 『糖醋排骨』, User接受。需要聊2轮)-->[3]poi推荐(Bot主动，Bot推荐在 『大清花饺子（十一纬路店）』 订 『糖醋排骨』, User问 『大清花饺子（十一纬路店）』 的『人均价格』、『地址』、『评分』，Bot逐一回答后，最终User接受并提供预订信息:『就餐时间』 和 『就餐人数』)-->[4]再见",
  "situation": "聊天时间:2018-12-24 中午12:00，在公司 星期一"
}
基线系统
Aistudio平台基线系统
『2021语言与智能技术竞赛』-多技能对话任务基线系统
Github基线系统
LIC 2021对话比赛baseline
数据集引用
如在学术论文中使用千言数据集，请添加相关引用说明，具体如下：

Hao Zhou, Chujie Zheng, Kaili Huang, Minlie Huang, Xiaoyan Zhu. 2020. KdConv: A Chinese Multi-domain Dialogue Dataset Towards Multi-turn Knowledge-driven Conversation. In ACL.
论文地址
MD5
e0c06b164bd64717cca57300eb4baa66

# LCCC开放域短文本对话数据集
闲聊数据集，考察模型在闲聊场景中，是否可以生成流畅的、与上下文相关的对话回复
https://www.luge.ai/#/luge/dataDetail?id=34
数据集介绍
LCCC是一个大规模中文开放域短文本对话数据集，旨在考察模型在闲聊场景中，是否可以生成流畅的、与上下文相关的对话回复。
数据预览
该数据集的任务定义如下：
给定对话历史H(u_1, u_2, …, u_t-1)
要求参评系统预测：符合对话历史，且自然流畅、信息丰富的机器回复u_t。
{
  "kg": [
    [
      "沈阳",
      "2018-12-24",
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃"
    ],
    [
      "糖醋排骨",
      "成分",
      "猪肋排、姜片、葱、生抽、糖、醋、料酒、八角。"
    ],
    [
      "糖醋排骨",
      "类型",
      "热菜"
    ],
    [
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃",
      "适合吃",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "特色菜",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "评分",
      "4.8"
    ],
    [
      "大清花饺子（十一纬路店）",
      "人均价格",
      "50"
    ],
    [
      "大清花饺子（十一纬路店）",
      "地址",
      "沈河区十一纬路198号（近南二经街）"
    ],
    [
      "大清花饺子（十一纬路店）",
      "订单量",
      "1405"
    ]
  ],
  "user_profile": {
    "职业状态": "工作",
    "同意的新闻": " 何炅 的新闻",
    "没有接受的音乐": [
      " 还有我",
      "心火烧"
    ],
    "喜欢的音乐": " 另一个自己",
    "年龄区间": "大于50",
    "拒绝": " 电影",
    "喜欢的明星": " 何炅",
    "接受的音乐": [
      " 向前奔跑",
      "思念的距离",
      "我是大侦探",
      "希望爱",
      "现在爱",
      "再见",
      "一路走过"
    ],
    "居住地": "沈阳",
    "喜欢的poi": " 大清花饺子（十一纬路店）",
    "姓名": "陈轩奇",
    "同意的美食": " 糖醋排骨",
    "性别": "男"
  },
  "conversation": [
    "[1]今天是什么天气？",
    "今天沈阳: 晴, 西南风, 最高气温:2℃, 最低气温:-12℃，天气有点冷，注意保暖。",
    "你知道的真多。",
    "[2]这种天气温适合吃 『糖醋排骨』了呢。",
    "糖醋排骨可是我最喜欢的美食，真想现在就去吃糖醋排骨呢。",
    "[3]我正好知道有一家店，推荐您在 『大清花饺子（十一纬路店）』 订糖醋排骨。",
    "这家店的地址在哪里？",
    "这家店的地址：沈河区十一纬路198号（近南二经街）",
    "人均价格是多少？",
    "人均价格50元。",
    "评分是多少？",
    "评分是4.8",
    "今天中午12点半我一个人去吃，我预定一下。",
    "好的，这就为您预定。",
    "[4]先去准备一下，再见",
    "好的，再见，祝你生活愉快！"
  ],
  "goals": "[1]问天气(User主动，User问天气，根据给定知识，Bot回复完整的天气信息，User满足并好评)-->[2]美食推荐(Bot主动推荐，这种天气温适合吃 『糖醋排骨』, User接受。需要聊2轮)-->[3]poi推荐(Bot主动，Bot推荐在 『大清花饺子（十一纬路店）』 订 『糖醋排骨』, User问 『大清花饺子（十一纬路店）』 的『人均价格』、『地址』、『评分』，Bot逐一回答后，最终User接受并提供预订信息:『就餐时间』 和 『就餐人数』)-->[4]再见",
  "situation": "聊天时间:2018-12-24 中午12:00，在公司 星期一"
}
基线系统
Aistudio平台基线系统
『2021语言与智能技术竞赛』-多技能对话任务基线系统
Github基线系统
LIC 2021对话比赛baseline
数据集引用
如在学术论文中使用千言数据集，请添加相关引用说明，具体如下：

Yida Wang, Pei Ke, Yinhe Zheng, Kaili Huang, Yong Jiang, Xiaoyan Zhu, Minlie Huang. 2020. A Large-Scale Chinese Short-Text Conversation Dataset. In NLPCC
论文地址
MD5
19aa6f1064e2f61ecc72b74817a5995f

# 中文画像对话（Chinese Persona Chat）数据集
画像对话数据集，考察对话模型在闲聊场景中是否可以生成与给定画像一致的回复
https://www.luge.ai/#/luge/dataDetail?id=38
数据集介绍
画像对话数据集，考察对话模型在闲聊场景中是否可以生成符合对话历史和画像信息，且自然流畅、信息丰富的机器回复。
数据预览
该数据集的任务定义如下： • 输入：机器画像信息，对话历史H(u_1, u_2, …, u_t-1) • 输出：符合对话历史和画像信息，且自然流畅、信息丰富的机器回复u_t。
{
  "kg": [
    [
      "沈阳",
      "2018-12-24",
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃"
    ],
    [
      "糖醋排骨",
      "成分",
      "猪肋排、姜片、葱、生抽、糖、醋、料酒、八角。"
    ],
    [
      "糖醋排骨",
      "类型",
      "热菜"
    ],
    [
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃",
      "适合吃",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "特色菜",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "评分",
      "4.8"
    ],
    [
      "大清花饺子（十一纬路店）",
      "人均价格",
      "50"
    ],
    [
      "大清花饺子（十一纬路店）",
      "地址",
      "沈河区十一纬路198号（近南二经街）"
    ],
    [
      "大清花饺子（十一纬路店）",
      "订单量",
      "1405"
    ]
  ],
  "user_profile": {
    "职业状态": "工作",
    "同意的新闻": " 何炅 的新闻",
    "没有接受的音乐": [
      " 还有我",
      "心火烧"
    ],
    "喜欢的音乐": " 另一个自己",
    "年龄区间": "大于50",
    "拒绝": " 电影",
    "喜欢的明星": " 何炅",
    "接受的音乐": [
      " 向前奔跑",
      "思念的距离",
      "我是大侦探",
      "希望爱",
      "现在爱",
      "再见",
      "一路走过"
    ],
    "居住地": "沈阳",
    "喜欢的poi": " 大清花饺子（十一纬路店）",
    "姓名": "陈轩奇",
    "同意的美食": " 糖醋排骨",
    "性别": "男"
  },
  "conversation": [
    "[1]今天是什么天气？",
    "今天沈阳: 晴, 西南风, 最高气温:2℃, 最低气温:-12℃，天气有点冷，注意保暖。",
    "你知道的真多。",
    "[2]这种天气温适合吃 『糖醋排骨』了呢。",
    "糖醋排骨可是我最喜欢的美食，真想现在就去吃糖醋排骨呢。",
    "[3]我正好知道有一家店，推荐您在 『大清花饺子（十一纬路店）』 订糖醋排骨。",
    "这家店的地址在哪里？",
    "这家店的地址：沈河区十一纬路198号（近南二经街）",
    "人均价格是多少？",
    "人均价格50元。",
    "评分是多少？",
    "评分是4.8",
    "今天中午12点半我一个人去吃，我预定一下。",
    "好的，这就为您预定。",
    "[4]先去准备一下，再见",
    "好的，再见，祝你生活愉快！"
  ],
  "goals": "[1]问天气(User主动，User问天气，根据给定知识，Bot回复完整的天气信息，User满足并好评)-->[2]美食推荐(Bot主动推荐，这种天气温适合吃 『糖醋排骨』, User接受。需要聊2轮)-->[3]poi推荐(Bot主动，Bot推荐在 『大清花饺子（十一纬路店）』 订 『糖醋排骨』, User问 『大清花饺子（十一纬路店）』 的『人均价格』、『地址』、『评分』，Bot逐一回答后，最终User接受并提供预订信息:『就餐时间』 和 『就餐人数』)-->[4]再见",
  "situation": "聊天时间:2018-12-24 中午12:00，在公司 星期一"
}
测试集为JSON格式，样例数据如下：
{
  "kg": [
    [
      "沈阳",
      "2018-12-24",
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃"
    ],
    [
      "糖醋排骨",
      "成分",
      "猪肋排、姜片、葱、生抽、糖、醋、料酒、八角。"
    ],
    [
      "糖醋排骨",
      "类型",
      "热菜"
    ],
    [
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃",
      "适合吃",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "特色菜",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "评分",
      "4.8"
    ],
    [
      "大清花饺子（十一纬路店）",
      "人均价格",
      "50"
    ],
    [
      "大清花饺子（十一纬路店）",
      "地址",
      "沈河区十一纬路198号（近南二经街）"
    ],
    [
      "大清花饺子（十一纬路店）",
      "订单量",
      "1405"
    ]
  ],
  "user_profile": {
    "职业状态": "工作",
    "同意的新闻": " 何炅 的新闻",
    "没有接受的音乐": [
      " 还有我",
      "心火烧"
    ],
    "喜欢的音乐": " 另一个自己",
    "年龄区间": "大于50",
    "拒绝": " 电影",
    "喜欢的明星": " 何炅",
    "接受的音乐": [
      " 向前奔跑",
      "思念的距离",
      "我是大侦探",
      "希望爱",
      "现在爱",
      "再见",
      "一路走过"
    ],
    "居住地": "沈阳",
    "喜欢的poi": " 大清花饺子（十一纬路店）",
    "姓名": "陈轩奇",
    "同意的美食": " 糖醋排骨",
    "性别": "男"
  },
  "conversation": [
    "[1]今天是什么天气？",
    "今天沈阳: 晴, 西南风, 最高气温:2℃, 最低气温:-12℃，天气有点冷，注意保暖。",
    "你知道的真多。"
  ],
  "goals": "[1]问天气(User主动，User问天气，根据给定知识，Bot回复完整的天气信息，User满足并好评)-->…… -->[3]poi推荐(Bot主动，Bot推荐在 『大清花饺子（十一纬路店）』 订 『糖醋排骨』, User问 『大清花饺子（十一纬路店）』 的『人均价格』、『地址』、『评分』，Bot逐一回答后，最终User接受并提供预订信息:『就餐时间』 和 『就餐人数』)-->[4]再见",
  "situation": "聊天时间:2018-12-24 中午12:00，在公司 星期一"
}
基线系统
Aistudio平台基线系统
『2021语言与智能技术竞赛』-多技能对话任务基线系统
Github基线系统
LIC 2021对话比赛baseline
MD5
62c6f13b4686ce1e47b95b8cdbd01fec

# Emotional STC （ESTC）情感对话数据集
情感对话数据集，考察模型是否可以在对话过程中充分利用情感信息，并生成具有正确情感倾向、且与上下文相关的对话回复
https://www.luge.ai/#/luge/dataDetail?id=37
数据集介绍
ECM是一个大规模的中文情感对话数据集，旨在考察模型是否可以在对话过程中充分利用情感信息，并生成具有正确情感倾向、且与上下文相关的对话回复。
数据预览
该数据集的任务定义如下：
给定对话历史H(u_1, u_2, …, u_t-1)
要求参评系统预测：符合对话历史，且自然流畅、信息丰富的机器回复u_t。
{
  "kg": [
    [
      "沈阳",
      "2018-12-24",
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃"
    ],
    [
      "糖醋排骨",
      "成分",
      "猪肋排、姜片、葱、生抽、糖、醋、料酒、八角。"
    ],
    [
      "糖醋排骨",
      "类型",
      "热菜"
    ],
    [
      "晴, 西南风, 最高气温:2℃, 最低气温:-12℃",
      "适合吃",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "特色菜",
      "糖醋排骨"
    ],
    [
      "大清花饺子（十一纬路店）",
      "评分",
      "4.8"
    ],
    [
      "大清花饺子（十一纬路店）",
      "人均价格",
      "50"
    ],
    [
      "大清花饺子（十一纬路店）",
      "地址",
      "沈河区十一纬路198号（近南二经街）"
    ],
    [
      "大清花饺子（十一纬路店）",
      "订单量",
      "1405"
    ]
  ],
  "user_profile": {
    "职业状态": "工作",
    "同意的新闻": " 何炅 的新闻",
    "没有接受的音乐": [
      " 还有我",
      "心火烧"
    ],
    "喜欢的音乐": " 另一个自己",
    "年龄区间": "大于50",
    "拒绝": " 电影",
    "喜欢的明星": " 何炅",
    "接受的音乐": [
      " 向前奔跑",
      "思念的距离",
      "我是大侦探",
      "希望爱",
      "现在爱",
      "再见",
      "一路走过"
    ],
    "居住地": "沈阳",
    "喜欢的poi": " 大清花饺子（十一纬路店）",
    "姓名": "陈轩奇",
    "同意的美食": " 糖醋排骨",
    "性别": "男"
  },
  "conversation": [
    "[1]今天是什么天气？",
    "今天沈阳: 晴, 西南风, 最高气温:2℃, 最低气温:-12℃，天气有点冷，注意保暖。",
    "你知道的真多。",
    "[2]这种天气温适合吃 『糖醋排骨』了呢。",
    "糖醋排骨可是我最喜欢的美食，真想现在就去吃糖醋排骨呢。",
    "[3]我正好知道有一家店，推荐您在 『大清花饺子（十一纬路店）』 订糖醋排骨。",
    "这家店的地址在哪里？",
    "这家店的地址：沈河区十一纬路198号（近南二经街）",
    "人均价格是多少？",
    "人均价格50元。",
    "评分是多少？",
    "评分是4.8",
    "今天中午12点半我一个人去吃，我预定一下。",
    "好的，这就为您预定。",
    "[4]先去准备一下，再见",
    "好的，再见，祝你生活愉快！"
  ],
  "goals": "[1]问天气(User主动，User问天气，根据给定知识，Bot回复完整的天气信息，User满足并好评)-->[2]美食推荐(Bot主动推荐，这种天气温适合吃 『糖醋排骨』, User接受。需要聊2轮)-->[3]poi推荐(Bot主动，Bot推荐在 『大清花饺子（十一纬路店）』 订 『糖醋排骨』, User问 『大清花饺子（十一纬路店）』 的『人均价格』、『地址』、『评分』，Bot逐一回答后，最终User接受并提供预订信息:『就餐时间』 和 『就餐人数』)-->[4]再见",
  "situation": "聊天时间:2018-12-24 中午12:00，在公司 星期一"
}
基线系统
Aistudio平台基线系统
『2021语言与智能技术竞赛』-多技能对话任务基线系统
Github基线系统
LIC 2021对话比赛baseline
数据集引用
如在学术论文中使用千言数据集，请添加相关引用说明，具体如下：

Hao Zhou, Minlie Huang, Tianyang Zhang, Xiaoyan Zhu, Bing Liu. 2019. Emotional Chatting Machine: Emotional Conversation Generation with Internal and External Memory. In AAAI.
论文地址
MD5
a5ba4df8c3a51d63d7c0d6e4994f8690











