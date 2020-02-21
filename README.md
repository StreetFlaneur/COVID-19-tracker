# 新冠疫情确诊患者轨迹结构化数据
   随着新冠疫情发展与国家疫情相关数据公开，新冠疫情确诊患者轨迹、所在小区及相关移动信息等成为在疫情防控中大众关心的热点信息，越来越多政府部门也陆续公开相关确诊患者的非隐私信息。同时，该部分数据也为相关研究人人、政府部门研究疫情传播与防控提供了重要数据参考。

  但是由于全国公开数据分散，多为文本非结构化数据，难以直接迅速形成有价值的结构化信息为后续的研究提供深度支撑。北航大数据高精尖中心研究团队进行数据来源的整理与获取，利用自然语言处理等技术从已公开全国4626确诊患者轨迹中抽取了基本信息（性别、年龄、常住地、工作、武汉/湖北接触史等）、轨迹（时间、地点、交通工具、事件）及病患关系形成结构化信息。希望能为疫情传播与防控相关研究提供有效数据支撑。数据会保持持续更新、提高数据抽取精准性工作，欢迎各位自然语言处理 数据分析研究者取用。

## 数据介绍
本数据集采集自全国政府官网、卫健委等官方途径，现共获取4626位确诊患者轨迹信息（截至至2月21日，数据将持续更新）

## 结构化数据属性
![image](https://github.com/BDBC-KG-NLP/track_data/blob/master/IMG/%E5%8E%9F%E5%A7%8B%E6%95%B0%E6%8D%AE.png)
原始数据

![image](https://github.com/BDBC-KG-NLP/track_data/blob/master/IMG/json%E6%A0%BC%E5%BC%8F.png)
抽取结构化json数据

公开数据以患者为单位，分为基本信息和轨迹信息两类信息：

基本信息包括编号、性别、年龄、常住地、工作、位置（省、市、区县）、是否病患、确诊时间、武汉（湖北）接触史、武汉（湖北）接触史描述，共10种属性。轨迹信息包括轨迹编号、时间、事件、交通工具、途经地（起点终点）及经纬度、描述，共6种属性。


## 确诊患者轨迹可视化分析与查询
北航大数据科学与脑机智能高精尖中心研究团队也已开发‘确诊患者轨迹可视化分析与查询’可视化系统，系统目前正在完善中，即将发布，敬请期待

## 致谢
特此感谢支持数据公开与系统研发工作的北航高精尖中心及参与这项工作的各位团队成员（排名按字母、不分先后）：

关旭涛 何睿智 李卓然 罗培祥 齐楚涵 张淑慧 郑春晓 孙凯 杨凤涛

## 数据使用说明
本数据仅开源作为研究使用，相关科研成果请引用。

   中文署名：北京航空航天大学大数据科学与脑机智能高精尖创新中心，北京， 100191 

   英文署名： Beijing Advanced Innovation Center for Big Data and Brain Computing, Beihang University, Beijing, 100191

如有商业用途请联系我们.

## 关于我们

![北京市大数据科学与脑机智能高精尖创新中心]（http://bdbc.buaa.edu.cn/?lang=zh）

## English version will come soon
