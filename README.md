# modelv
A LLM dataset and model for your culture and background.

## 名人名言价值观数据集
### 第一阶段工作总结
- 名人名言数据库第一阶段的整理工作从2023年10月1日起到2023年12月31日结束。通过三个月的名人名言数据整理，结合整理过程中与技术组人员、首师大蔡可老师的讨论，现对第一阶段数据整理中的发现的问题和整理的思路进行总结，以期对下一阶段的工作提供借鉴：
###	价值观二级分类的问题
在名人名言数据整理过程中，我们发现与价值观分类相关的主要问题是，有些名人名言找不到对应的价值观二级分类，考虑新增二级价值观分类，以下供参考：
1. A道德伦理：豁达、悠闲、真实、兼容、适度、淡泊；
2．B健康生活：情感、热爱、热情、温和、耐心、前瞻、孤独、运动、锻炼、预防、远见、忧患、笃行、柔韧、可塑、庄重、敏思、果断、周全、希望、信仰；
3．C求知成长：专注、细致、博识、积累、顺势、适度、机遇、恒心、时机、尽职、极致、条理、局限、对比、规律、本源、变化、全局、观察、智慧、天赋、筹谋；
4．D人际关系：合作、沟通、分享、亲情、和睦、尊重、信任、思乡、知音、忠诚、师生、惜贤；
5．E人与社会：文化、和谐、民主、归属、改革、责任、管理、互利、名誉、合作、法治、教化、规则、治国、安民；
6．F人与自然：规律、和谐、相通、变迁、孤寂、对立统一、局限。
### 作者的统一问题
1．作者名字的统一标准问题
1.1多位作者问题：比如《老子》中的名言作者统一写老子？《论语》中的名言作者统一写孔子？《庄子》中的名言作者统一写庄子？《圣经》里的名言作者统一写摩西、马太、马可等？
1.2佚名作者问题：比如《五卷书》、《诗经》、《增广贤文》、《尚书》等统一写佚名。
1.3国外作者名字：存在中文译名的完整性和准确性问题，比如英国的弗兰西斯·培根，有的可能只写培根，数据集中至少一个人的名字需要统一。
2.名人角度对下一步工作的思考
名人名言虽然条目众多，但从古至今各国的名人名言相对集中在最出名的百多个人身上，比如印度的泰戈尔，俄国的屠格涅夫、列夫·托尔斯泰、普希金，中国的李白、杜甫、白居易、苏轼、孔子、老子、鲁迅、林语堂、巴金，法国的雨果、大仲马，英国的莎士比亚、狄更斯，德国的歌德、海涅， 美国的爱默生、爱因斯坦、华盛顿、富兰克林等。这样为下一步名人名言的工作打下基础，以名人为基础不仅可以进行下一轮人工智能和人相结合的筛选和扩充，还可以加上名人的身份、时代、文化背景加以深度学习和分析，使价值观体系更加丰盈有故事。
### 国家的统一标准问题
1．国家标注中存在的问题
国家的问题主要集中在已经消失的几个古代文明上，比如古波斯、古印度、古希腊，还有就是苏联和俄国的时间分界问题，极个别处存在爱尔兰、苏格兰的不同表述，需要统一标准。
2.国家角度对下一步工作的思考
名人属于不同的国家，从国家角度加以分类总结这些名人名言 ，可以看到不同国家的历史进程中，对其产生影响的名人曾经留下的文字语言和价值体系。在目前逆全球化的时代，也提供了一个的渠道去审视在不同文明的价值观形成的历史脉络，更好的看到和理解人类价值体系的同和不同。
### 文化的选择标准问题
名人名言所属文化选择的问题比较突出，名人名言有的出自史书，有的出自戏剧、有的出自小说，有的出自论文或演讲，还有很多没有出处；而名人名言本身内容上又涉及到道德、哲理、科学、政治、家庭、爱情等方方面面。所以，按什么优先顺序确定名人名言的文化归类，需要一个统一标准。目前名人名言的文化归类，我们按照出处、作者、内容的先后优先顺位进行标注：
1.第一顺位“出处”
如果名人名言有出处，则以出处是判断名人名言文化属性的第一标准，如“君子挟才以为善，小人挟才以为恶”出自《资治通鉴》，文化处选“历史”；如“要像农民耕种那样努力寻找智慧，而后你才能指望丰收”出自《圣经》，文化处选“宗教”。
2.第二顺位“作者”
如果名人名言没有出处，则结合名人的身份标签判断名人名言的文化属性，如蔡元培的“一个平庸的计划胜于无计划的瞎摸索”，鉴于蔡元培近代教育家的身份标签，文化处选“社科”。
3.第三顺位“内容”
如果名人名言没有出处，且名人有多个身份标签，则结合名人名言的内容和名人身份判断，如爱因斯坦“凡在小事上对真理持轻率态度的人，在大事上也是不足信的”未找到出处，鉴于名言的内容和爱因斯坦物理学家、思想家的身份标签，文化处选“社科”。
如周恩来“没有现代化的技术，就没有现代化的工业”，出自《把我国建设成为强大的社会主义的现代化的工业国家》，鉴于名言的内容和周恩来政治家的身份标签，文化处选“社科”。
### 年代的统一标注问题
1．年代的统一标注问题
名人名言的年代标注是根据作者进行的标注，其中中国古代按朝代标注，比如李白的名言标注为“唐代”；中国近现代和中国之外其他国家，按作者的生卒年代标注到纪年，比如爱因斯坦生卒为1879年3月14日至1955年4月18日，则他的名言年代标注为19-20世纪。
2.年代角度对下一步工作的思考
名人属于不同的年代，从年代角度加以分类总结这些名人名言 ，可以看到不同年代的名人其价值观体系的变迁，以及从古至今并没有实质性改变的价值观。在目前逆全球化的时代，也提供了一个的渠道去审视在不同文明的国家人们的价值观形成的历史脉络，更好的看到和理解人类价值体系的同和不同。
### 出处的补全问题
名人名言中至少有一半左右没有找到出处，中国古代的诗词名句基本都有，但中国现代的以及国外的名人名言好多找不到出处。在整理时的基本做法是，分别搜索查询百度前三页和“深言达意”网站，找不到出处就放弃了。第二阶段中建议尝试用人工智能及外网扩大搜索范围，至少用谷歌再检索一下，应该能找到更多出处。
### 数据集的应用思考
我们下一步需要更深入探讨的可能是，如何运用人工智能对名人名言数据集进行深度灵活的学习，成为一个价值观判断方面的专家，作为一个工具或是标准更好的引导AI走向良知、理性的文明世界，更好的服务于人类。
1.	教育行业
比如青少年的价值观教育方面，能否从一线工作的中学老师特别是班主任、德育老师等入手，调查他们观察到青少年在日常学习生活中哪些现实问题，特别是涉及到精神和价值观层面的问题，汇集起来后，让深度学习了数据集的AI，结合名人名言及其价值观判断给予有效的答复。
2.	To B产品
随着ChatGTP的不断进化，会出来很多的AI应用产品。这些AI产品在提供服务时，可以用我们训练后的价值观机器人给予评估或是辅助判断，使AI产品更加符合人类价值观安全伦理标准。
3.	To G产品
训练后的价值观机器人作为价值判断的工具还可以考虑与网络安全的产品结合，比其他工具可能更柔性，具有说服力。
另外，在逆全球化的浪潮下，各国之间的隔阂和壁垒更为突出，文明价值观的理解有利于突破国家的界限，让不同文明体系下的人们更好的连接。比如我们可以按文明区域划分，去收集和整理阿拉伯的名人名言，理解他们的价值判断。特定区域或国家的价值判断机器人可以作为对外贸易、对外交流的工具，提供给从事涉外工作的机构或是人员。
### 下一阶段工作计划
接下来的三个月，项目组可以分工合作从事以下具体工作：
1.现有数据集的梳理，按最新的价值观分类标准及前述统一后的标注标准重新调整后，提给技术组；同时，大家讨论找一个或多个角度，比如国家、名人或是文化、年代等，调整变换数据集，和技术组一起看看能否有新的收获（一个月）；
2.教育领域找到一个切口，请一线的老师帮忙重新提出具体问题，同时，我们结合调整后的数据集，与技术组结合更好的提问，汇集整理问题后，提给技术组（一个月）；
3.考虑扩充和筛选数据，看如何让人工智能与人结合扩充新的数据进来。同时，建立一个统一的筛选或是归类机制，提升数据集质量（一个月）。
