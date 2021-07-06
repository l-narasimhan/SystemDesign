# Twitter POST API

#### _Objective_ - The aim is to go step by step identify failure points and address them and take the next logical step. It includes 3 steps 
1. Design a system 
2. Identify Problems
3. Enhance 
4. And Do 1-3 Until its meets the requirements



##  Requirements 

+ Design a Twitter Post creation api (Create tweet API)
+ Other requirements like "Like", "Re-tweet" are NOT required now 
+ Model the DB entities 
+ Persist the tweet 
+ No Loss of Tweets (**Very Important**)
  
---

## NFRs 

+ 60k tweets/sec 
+ System should be highly Available 

60k tweets/sec = 60k * 60 * 60 * 24 = 5184000000 tweets/day

---

**Step - 1** -  Design the most basic system. 

Service Layer - Java Springboot App 
DB: Oracle 
API Gateway - Zuul 

Deployment: App running in Cloud(any) using Kubernetes for orchestration 

DB Model: 





