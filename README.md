# Smart-Banking-Fraud-detection-analysis
this is the spark streaming code to detect the fraud credit card transactions.
inthis project we are using kafka as input sourse means we read transaction logs from the kafka topics in real time.
then we creat the Dstreams using Apache Streaming service and then coverted it into the Data Frames.
them performed the fraud detection logic on the logs to fecth the details of the customers where the potential fraud can be there.
then using those details we can send the trigger warnings or messages to inform the customers about the fraud.
