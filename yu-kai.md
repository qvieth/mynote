- send the relevant paper to yu-kai, suggesting the interesting method these paper use:
  - text mining the climate change doubt -> probabilistic topic modeling LDA
  - Overcoming Language Barriers: Assessing the Potential of Machine Translation and Topic Modeling for the Comparative Analysis of Multilingual Text Corpora
  - book Environment, Media, and Popular Culture in Southeast Asia: Chapter 13 Climate Change Reporting in Vietnam’s Online Mainstream News Websites and Beyond
=> should put at least one line what you find most interesting in each paper

- searching for newspaper about climate change vietnam data:
  - the book climate change in southest asia: chapter 13 mention alot about vietnam cliamte change news situation
- [ ] suggest ask choose those newspaper, suggest more popular paper
- [ ] ask for suggestion for improve the program:
- which keyword you need the result to appear:
  - tom, song cuu long,...
  - climate services, rice, shrimp, saline water intrusion, and environmental monitroing
  - dich vu khi hau, ngap mang, quang trac moi truong, quan li moi truong, phan tich moi truong, 
  - https://nchmf.gov.vn/Kttv/vi-VN/1/index.html
  - report cuc khi tuong, da downloa


- newspaper data, oranize in table format that has features: title, text, date, link, category
- plot date of publish to see is there a pattern, then use these data with climate data

## TASK TO DO:
1. [ ] web crawling -> reason for the most comprehensive data extracting method -> tuoi tre vs vnexpress
2. [ ] perform topic model -> there will be many reprocesing steps, understand the steps more carefully:
3. [ ] lexiconometrics

## questions
- for any preprocesing steps, there are many studies about each of its steps robustness or accuracy:
  - for example: Stop word removal and the removal of terms with fewer than three characters (e.g., “to,” “on,” “dr,” “mp”) was done to remove terms that are extremely frequent or unspecific and thus not helpful as indicators for a document’s content -> whether this is true for vietnamese?
  - for differnt language, there must be different study

- topic model: choose a framework: strutural topic model framework vs LDA, vs ... -> figure out what is the best framework for this study
  - how to choose most optimal number of topics: 3 diagnostic indicator
  - lda, topic model,... optimal number of topics -> choosing the k for clustering,...
  -  In fact, it has recently been shown that machine translation and topic modeling can be combined to study public communication (Lucas et al., 2015; de Vries, Schoonevelde & Schumacher, 2018). 
  -
