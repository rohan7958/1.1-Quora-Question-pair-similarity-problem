👋 Welcome to Quora Question Pairs!

💡 Have you ever visited Quora and wondered if a question has already been answered before? This project aims to solve that problem by identifying which questions are duplicates of questions that have already been asked on the platform.

🎯 The business objective is to provide a better experience for seekers and writers on Quora, by reducing the time spent finding the best answer to their question and avoiding writers answering multiple versions of the same question.

📝 The project is a binary classification problem where given a pair of questions, we need to predict if they are duplicates or not.

🔍 The dataset for this project is a file Train.csv, which contains 5 columns: qid1, qid2, question1, question2, and is_duplicate. The size of the file is 60MB, and it has 404,290 rows.

📊 The performance metric for this project is log-loss and binary confusion matrix, with more details available on the Kaggle competition page: 
https://www.kaggle.com/c/quora-question-pairs#evaluation

🌟 Useful links for this project include:

- Discussions on Kaggle: 
https://www.kaggle.com/anokas/data-analysis-xgboost-starter-0-35460-lb/comments
- A Kaggle-winning solution and other approaches: 
https://www.dropbox.com/sh/93968nfnrzh8bp5/AACZdtsApc1QSTQc7X0H3QZ5a?dl=0
- Blog 1 discussing Semantic Question Matching with Deep Learning: 
https://engineering.quora.com/Semantic-Question-Matching-with-Deep-Learning
- Blog 2 discussing Identifying Duplicate Questions on Quora: 
https://towardsdatascience.com/identifying-duplicate-questions-on-quora-top-12-on-kaggle-4c1cf93f1c30

Note:
This Case-study/Project was covered in the Applied AI course.

🔥 With over 100 million monthly visitors on Quora, the impact of correctly identifying duplicate questions can be significant. Join us in our mission to improve the Quora experience for everyone!


