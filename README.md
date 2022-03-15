# head_hunter_employer_review_competition
Create a model that determines whether a review will be published and the reason for rejecting moderation (encoded as numbers from 1 to 8 ). If the review is moderated, then instead of the reason for the refusal, you need to send 0.

# HeadHunter Employer Review Competition (competition on boosters.pro)
**Dataset description:** The dataset contains data on various employer reviews collected by the dreamjob service.
**Objective:** Create a model that determines whether a review will be published and the reason for rejecting moderation (encoded as numbers from 1 to 8 ). If the review is moderated, then instead of the reason for the refusal, you need to send 0.
**Process:** Primary data processing (filling in the gaps, processing of outliers) was done, the text feedback was converted using Tfidf Vectorizer, and 9 logistic regression models were built.
**Results achieved:** Based on the results of the models, a table of probabilities was compiled, probability thresholds were determined for each reason for moderation rejection, and the finished file was uploaded to the competition website.
**Tech stack:** Numpy, Pandas, Matplotlib, Seaborn, Tfidf Vectorizer, LogisticRegression, Gradient Boosting

# head_hunter_employer_review_competition
Создание модели, определяющую, будет ли опубликован отзыв и причину отклонения модерации (закодированы числами от 1 до 8 ). Если отзыв проходит модерацию, то вместо причины отказа нужно отправлять 0.

# HeadHunter Employer Review Competition (конкурс на boosters.pro)  
**Описание датасета:** В датасете представлены данные о разных отзывах о работодателе, которые собирает сервис dreamjob.   
**Поставленная задача:** Создать модель, определяющую, будет ли опубликован отзыв и причину отклонения модерации (закодированы числами от 1 до 8 ). Если отзыв проходит модерацию, то вместо причины отказа нужно отправлять 0.  
**Процесс выполнения:** Произведена первичная обработка данных (заполнение пропусков, обработка выбросов), текстовый отзыв преобразован при помощи Tfidf Vectorizer, и построены 9 моделей логистической регрессии.   
**Достигнутые результаты:** На основе полученных результатов моделей составлена таблица вероятностей, определены пороги вероятности для каждой причины отклонения модерации, и готовый файл загружен на сайт конкурса.  
**Стек технологий:** Numpy, Pandas, Matplotlib, Seaborn, Tfidf Vectorizer, LogisticRegression, Gradient Boosting
