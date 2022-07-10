# py-osschat
Open Source Software Chat BOT 


## BluePrint

* FAQ
    * 应用场景
        * 开源技术社群内高频问答（技术运营中的痛点），解决新手最常见问题
        * 销售运营中客户常见问题以及服务型软件服务中的与用户首次沟通常见问题
    * 意义
        * 简单，可是能够解决用户80%的常见问题
        * 提升开发者/用户体验，减少人力成本
    * 功能描述
        * 给定Question和Answer对，通过query和question进行语义匹配筛选出对应的（top-k）答案。
        * 数据来源可以是：Excel文件、网站某页面URL、CSV文件
* Document QA
    * 理想应用场景
        * 开源社区中的某些问题是散落在整个文档系统中的某个角落，比如开发者在开发者群中询问：如何在Jetson上预测部署？于是群内机器人会自动给出对应（带锚点）的URL地址，让开发者在此页面中查找对应答案。
        * 任何需要在长文本上的搜索都可能需要使用Document QA的功能
    * 意义
        * 能够将QA的能力开放给所有开发者，并能够尝试应用在自身的产品当中，比如：开源社区中的技术文档回复，销售人员产品特性回复等
        * 开发者只需要在自己产品中进行Document QA Model Fine-Tune，即可提高在自身产品中问题回复的精确率，从而实现目标领域QA
* NLU
    * 应用场景
        * 任务型多轮对话
        * 开发者自定义对话逻辑
    * 意义
        * 体现更AI的方法，也是创建Chatbot中的最核心的功能，也是很多开发者想要尝试的功能。
        * 开箱即用的东西能够释放开发者更多的想象空间，制作更多对话应用场景的东西，同时也会给PaddleNLP的带来更多用户
    * 功能描述
        * 识别用户query中的意图和相关实体信息
* Table QA
    * 理想应用场景
        * 在智能写作助手中，table qa 是一个非常重要的技术点，能够从最终的图表中查询出关键性信息，比如2022年净利润是多少？北京2022年人口总数是多少？等
        * 中文表格信息抽取
    * 个人看法
        * 虽然此功能使用频率最低，可是这是最有吸引力的功能，我相信可以吸引很多商业创业公司来咨询相关功能，甚至进行更深入的合作
 
整体看法：
* 此QA能力可以实现最简单的FAQ能力，也可以实现目标领域文本知识抽取能力，基于百度强大的中文模型，我相信此项目能够收获更多开源和商业开发者的青睐，也会给PaddleNLP引流。
* 此项目也是对于PaddleNLP实际落地应用的一个验证
* 如果能够将百度搜索中的一部分中文信息搜索能力融入到此项目当中，我相信你这将会是对整个中文开源圈来说是一个史无前例的里程碑。
