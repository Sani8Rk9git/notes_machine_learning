**BATCH vs ONLINE LEARNING**



\-> Types of machine learning based on how the ML model work/train in production

&#x09;-> production means the server on which the code is going to run

&#x09;-> software create --> deploy on server --> customer has ip of server --> use

&#x09;-> ML software are also deployed on server 

&#x09;-> the server environment where ML code is running is production environment



\-> Batch ML

\-> Online ML



\-> Batch/offline ML

&#x09;-> we use the complete dataset to train the ML model

&#x09;-> The model is trained on the local machine (offline)

&#x09;-> then the trained model is put on the server

&#x09;

&#x09;-> The problem with batch learning: 

&#x09;	-> data is dynamic and change 

&#x09;	-> our ML model is needs to be retrained after some time in batch

&#x09;		learning

&#x09;-> get the model offline --> train with new + old data --> then deploy



&#x09;=> Disadvantage

&#x09;	-> lots of data can cause model training difficult

&#x09;	-> model updation after some time can cause loss of some 

&#x09;		functionality



\-> Online ML

&#x09;-> training of the model is done incrementally

&#x09;-> we feed small data batches to ML model and train

&#x09;-> This is done on the server so called Online 

&#x09;-> Initially with small data ML model is trained and tested

&#x09;	-> then deployed on the server 

&#x09;	-> Server has a continuous inflow of data 

&#x09;	-> Model is predicting and also learning from the data on the server

&#x09;-> Ex: chatbots, youtube



\-> When the business scenario is continuously changing --> do online learning 

&#x09;-> stock exchange

&#x09;-> e-commerce



\-> Online learning --> cost effective



\-> Learning Rate

&#x09;-> how frequently we train data in online learning

&#x09;-> we need to choose right learning rate so that we do not forget the older

&#x09;	and is not slow to learn new data

&#x09;



\-> Out of core learning

&#x09;-> data is so huge that we cannot load it in memory

&#x09;-> here online learning is used

&#x09;	-> we break the data into small chunks

&#x09;	-> feed to the model 

&#x09;-> this is done offline 



\-> Disadvantage of online learning

&#x09;-> this is tricky as various things are going on the server

&#x09;-> risky as if data gets corrupted and the model gets biased

&#x09;	-> so we need to monitor the system continuously

&#x09;	-> 







