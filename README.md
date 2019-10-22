# EDA-of-Apple-News
In this file, I use python to do basic text mining on Chinese text. The text I use is Apple News sample from 2013 to 2018 in Taiwan, and I have scraped all news using Beautifulsoap.(You can see how I scrape in another file)
(Apple News Sample: 50 days news per year)

## Content
1. Chinese words Preprocessing (Jieba)
2. Chinese word and words Frequency (tfidf)
3. Entropy and Simpson Index of Chinese text
4. Hierarchy Clustering (tfidf + scipy.cluster.hierarchy)

## Details

### 1. Chinese words Preprocessing
In this part, I simply use JIeba
