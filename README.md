# goslacknlp
Slack NLP in Go

converse and learn adaptively

![alt text](https://github.com/bhagvank/arc/blob/master/goslacknlp.png)

* [SlackNLP Demo](https://floating-crag-10115.herokuapp.com/nlp/)

Video content management, AI, Blockchain and Virtual/Augmented reality technologies are changing the learning management platforms. Customer focused learning systems are emerging in enterprises. Enterprises are structuring their curriculum products to help solve the high value use cases of their customers. Members of the LMS system can tailor their educational experience by choosing courses based on their learning styles. The courses are becoming more effective and helping members retain information. Platforms are differentiating by providing better, faster ways to find relevant content, whenever and wherever learners need it. Modern learning management platform is an end-to-end eLearning solution which has capabilities to create, distribute, edit and manage entire courses from start to finish independent of the content. Educational success and fulfilment are achieved through personalization and optimization of the learner’s path through courses and gaining of competencies. This new class of learning technology vendors is making it possible to augment their systems with cloud-based applications which can be easily integrated with an enterprise-scale technology ecosystem. Enterprises are now tracking and analyzing learning experiences with incredible precision which can be used to improve ongoing program and business outcomes. Tracking and reporting comes in learner-oriented dashboards and reports built for the staff. 

AI based NLP engine scans and parses the messages from Slack. Slack is used for communicating new courses, mentor conversations, cohort groups, general discussions and other posting from students. NLP engine has the capability of identifying threads and conversations. This will help to know and analyse  the sentiments, tone, mood,emotions, utterances and other parameters  from the conversations. This will help in using the historical data about the students and their preferences to adapt the learning path and course content.   Adaptive Learning is used to change the ongoing content of materials and assessments  based on the educational goals. NLP engine helps in capturing time to mastery, completion rates, material reading complexity, language complexity and complexity of content topics. These areas are important for historical data which will be used for adaptive learning.

# Instructions for setting up locally
1. Ensure that go and postgres is installed

  * [Go](https://golang.org/dl/)

  * [Mysql](https://dev.mysql.com/downloads/mysql/)
  
  
2.git clone this repository
```
git clone https://github.com/bhagvank/goslacknlp.git

```

3. set up the mysql driver
```
go get -u github.com/go-sql-driver/mysql
```
4. create slack api token and google service accounts

   * [Slack](https://api.slack.com/custom-integrations/legacy-tokens)
   * [Google](https://cloud.google.com/compute/docs/access/service-accounts)
   
5. start the go web forms
```
go run slacknlp.go slacknlp_database_operations.go
```
  


