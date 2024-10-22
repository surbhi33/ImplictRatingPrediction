
This project was Kaggle Competition to accurately predict item ratings for users based on implicit feedback. The train dataset provided had interactions between users and items historically and test dataset rquired to predict probability of each user liking the corresponding item. Due to no negative samples available, those were sampled based on inverse of frequency of  user and item interactions.
- Idea was acquired from http://fi.ee.tsinghua.edu.cn/public/publications/7544a62c-92b2-11eb-96bc-0242ac120003.pdf.
- For predicting likeness, Matrix Factorization , XGboost and Neural Network (NeuMF) of which NeuMF and MF ensemble performed best. NeuralMF(NeuMF) was implemented from research paper
https://f1000researchdata.s3.amazonaws.com/manuscripts/76881/6e10934e-1599-499a-a58d-3b511e7a94ba_73240_-_kok_why_ng.pdf?doi=10.12688/f1000research.73240.1&numberOfBrowsableCollections=41&numberOfBrowsableInstitutionalCollections=4&numberOfBrowsableGateways=38
- And code help from https://d2l.ai/chapter_recommender-systems/neumf.html. 
- LogLoss 0.41 was achieved on test data
