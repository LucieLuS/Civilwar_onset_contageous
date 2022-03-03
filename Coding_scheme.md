## 可直接删掉的类型（给机器学习时）：
- 没有标题和没有网址的
- 外媒报道（bbc monitoring除外）

## 判断三个variables: news_relevance; relevance_category; news_country

news_relevance: 
- 0（不相关）
- 1（相关）

relevance_category
- 0（不相关）
- 1（同区域相关）
- 2（非洲不同区域相关）
- 3（本国/其他国/IO或AF）：如果文章跟我们关注的那个conflict相关, 那IO或泛AF新闻都标注并保留


news_country：
- 国家名字
- IO
- AF

## 出现过的IO或AF

### IO

- International Crsis Group
- The New Humanitarian


### AF
- Inter Press Service (IPS)
- African Arguments
- AllAfrica
- FrontPage Africa
