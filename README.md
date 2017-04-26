# <img src="https://imgsa.baidu.com/baike/w%3D268/sign=1e68cddb36adcbef0134790094ae2e0e/8d5494eef01f3a29e33f21d19e25bc315c607c3e.jpg" width="32" height="32" /> HUAJI Search

---
### Search Engine Module

- [x] Web Crawler
- [x] Links Extraction
- [x] Page Rank
- [x] TF-IDF
- [x] N-Gram
- [x] Top K
- [x] Inverted Index
- [x] [Recommender System](https://github.com/ZhangShiqiu1993/recommender_system)
- [x] Sentiment Analysis
- [x] Front page
- [x] Spelling Correction
- [x] Language Identifier
- [x] Auto Completion
- [x] Snippet

---
1. A well-functional search engine, including Web Crawler, Spelling Correction, Inverted index, PageRank Algorithm, TF-IDF Algorithm, AutoComplete, Recommender System and Sentiment Analysis
2. **Web Crawler**: Implemented a multithreading web crawler based on *crawler4j*
3. **Page Rank**: Extracted out-links from webpages collected by web crawler, built adjacent matrix from hyperlinks of each page, calculated *PageRank* based on page relation
4. **TF-IDF**: Parsed HTML pages, extracted content text and computed *TF-IDF*
5. **N-Gram**: generated language model, built real-time **AutoCompletion** based on N-Gram statistics
6. **Recommender System**: built video rating matrix from dataset, calculated video co-occurrence matrix, based on **Item Collaborative Filtering** algorithm
7. **Sentiment Analysis**: Extracted emotion feature from text and implemented sentiment analysis based on emotion dictionary
8. Implemented **Top K** algorithm and **Inverted Index**, increased the query efficiency
9. Implemented **Spelling Correction**
10. UI: built front pages with *PHP, Bootstrap and jQuery*

---
### demo

**enter a query**<br/>
the result will show up with docID, title, url, description and snippets
![query_result](https://github.com/ZhangShiqiu1993/search_engine/blob/master/demo/query_result.png?raw=true)

**AutoCompletion**: give user query suggestions
![auto_completion](https://github.com/ZhangShiqiu1993/search_engine/blob/master/demo/auto_completion.png?raw=true)

**Spelling Correction**: When I mis-typing *California* as **californa**, it will ask *"Are you looking for <u>California</u>"*
![spelling_correction](https://github.com/ZhangShiqiu1993/search_engine/blob/master/demo/spelling_correction.png?raw=true)

We can click on the spelling correction hint. It will help us redirect to the correct word.
![redirect](https://github.com/ZhangShiqiu1993/search_engine/blob/master/demo/result_redirect.png?raw=true)
