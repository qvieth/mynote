## report
- https://vietnamcredit.com.vn/news/outlook-for-vietnams-seafood-industry-in-2022_14768
- vietnamnet:
  - dbscl 3058
  - quan trac moi truong 276
  - trang trai thong minh 30
- zing:
  - dbscl 290
  - quan trac moi truong 365
  - trang trai thong minh 17
- tuoitre:
  - dbscl 1850
  - 
- start from the last week question:
  - the question:
    1. whether can we use machine translation + topic modeling
  - suggest why we should combine lexiconometrics or machine learning model into the research
    1. improve current topic model, lexiconometrics result
    2. improve the data source
  - task i did
    - see how other research related to working with vietnamese newspaper, how did they gathered the newspaper, their result

- level 1 question: how to structure the research
- there are little newspaper specifically about the climate service
- review these newspaper to see how are these field being applied to other areas of vietnam, then enquiry why are tthese not being applied to the most critical part of vietnam mekong delta
- newspapper will be related to:
  - smart algriculture, trang trai thong minh
  - quan trac moi truong
  - mekong delta
- what kind of result will be yeild by reading these newspaper: -> 
  - identify framing -> what kind of machine learning model to perform this task:
    - text classification model: transformer bert, identify some frames, then train a supervise learning model to classifi articles into different frames
  - text mining climate change doubt:
    - compile the largest corpus of climate sceptic claims-making activity to date, collecting over 16,000 documents from 19 organizations over the period 1998 to 2013 tank counter-claims in nearly 15 years.
    - providing the first systematic update of conservative think
    - introduce methodology to measure key themes in the corpus
    - see how this paper frame different articles into the cause of climate changeskepticism -> suggest similar way to frame our corpus 
  - 
- topic model, lexiconometrics as a preliminary research -> i have generate the different topics, then...
  - the question right now is how to make these result meaningful?


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
