# langchain_law_search_application



# 部署方式

直接下载ipynb文件，放入colab即可一键运行。





该项目主要用到了

langchain，selenium，openai



通过将用户的输入的问句经过chatgpt4转换为

关键词+布尔运算符的形式，来进行威科先行知识库的搜索。

然后使用selenium，捕获结果的top3排名的链接。



# 目前尚未解决的问题

无法让chatgpt对捕获到的链接进行摘要，因为威科先行的页面采用的是动态加载的方式。

python里的request和selenium似乎处理起来不是很方便，个人目前没有找到很好的方法来解决。