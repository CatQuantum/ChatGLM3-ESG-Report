草稿，待整理

项目主要内容为使用开源大模型ChatGLM3-6B生成ESG报告

流程图：

输入ESG相关指标（excel） → E、S、G三个模块的数据分别依次填充到prompt模板中 → 多次对话，分别生成报告的相应章节，以markdown格式输出 → 拼接，markdown转PDF（可选）


Prompt示例：
```

```


前端：
【】

后端：
模型基座：ChatGLM3-6B

知识库挂载
Langchain

数据源：
ChatGLM金融大赛


与FATA框架结合：
【】

本地运行配置：
4090*1

展望：
接入文生图
