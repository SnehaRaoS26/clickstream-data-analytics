# clickstream-data-analytics

Refer the below link to install MongoDB, it is the database where the pre-processed data is written to for further analysis. This is for MacOS, but for windows need to search for some other link.

https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-os-x/

#### Dataset: [Fahsion Campus Dataset](https://www.kaggle.com/datasets/latifahhukma/fashion-campus?resource=download&select=click_strea)

#### Execution Flow:

The execution starts from the main.py file:

1. Pipeline is executed which reads the data, processes it and writes to MongoDB: service -> pipeline_service.py
2. Data quality checks are performed on the data in MongoDB: quality -> data_quality.py
3. Data analysis is performed: analysis -> data_analysis.py





