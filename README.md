# ChatLM-Keyword

一个基于ChatGLM的将输入文本做关键词抽取，词频统计并绘制词云图的关键词抽取项目。

## 1. 项目预期目标

- **第一阶段**：用户输入文本或直接上传文章，抽取出相应关键词并统计关键词的出现频率，依据词频结合Echarts进行词云图的绘制，并在前端页面呈现出来。

- **第二阶段**：在第一阶段的基础上结合Echarts继续丰富项目的可视化功能。剩下的可增加的功能有两个思路：
  
  - 尝试对用户上传的JSON或CSV文件进行多维度分析。
  
  - 结合音频信号处理相关领域的知识，尝试对用户上传的视频文件进行分析。

## 2. 项目实现基本功能（截至2023/06/06）

- 用户在上传需要进行分析的文本或文章时，可以自定义统计关键词的数量。

- 项目能够对用户上传的文本或文章进行关键词的抽取操作，并统计关键词的词频在前端界面呈现给用户。

- 项目采用Echarts技术对抽取出的关键词进行词云图的绘制，并展现在前端界面。

- 用户可以在前端界面手动对词云图效果进行更换。

### 3. 项目已经解决的问题（截至2023/06/06）

- 增加模型缓存，解决每次上传文件重新加载模型问题

## 4. 项目呈现效果（截至2023/06/06）

![](imgs/Picture_01.png)

## 5. 项目贡献名单

| 贡献者   | 贡献内容 |
| ----- | ---- |
| 星辰 | 队长 |
| 沉淀 | 应用方向调研、gpt能力调研、langchain-chatglm部署等 |
| 何材 | streamlit前端技术学习，pyecharts词云页面设计 |
| 小陈 | 跟踪并汇总热点项目和往期优秀项目，辅助沉淀部署ChatGLM |
| 小杨 | 跟踪并汇总热点项目和往期优秀项目，实现词云显示效果 |
| 小萝卜 | 参与项目讨论，部署ChatGLM，设计抽取关键词的prompt |
| Betterme | 参与项目讨论，提供解决思路 |




