# HHA504_assignment_functions
The objective of this assignment is an introduction to serverless computing and the use of cron jobs in cloud environments. Deploy serverless functions on both Azure and Google Cloud Platform (GCP), and create a scheduled task using GitHub Actions.
# 1. Deploy a Serverless Function
### *Azure*
![Azure Serverless Function](https://github.com/user-attachments/assets/92b94495-6e85-4869-9cc7-fd930e4174a7)

### *GCP*
![GCP Serverless Functions](https://github.com/user-attachments/assets/667edfc1-2caa-42ab-ad80-62377f0dbd20)

![GCP Function Colab](https://github.com/user-attachments/assets/a5fdc1cb-c13c-49ce-9da2-a5069520fafc)

# 2. Create a Cron Job
### Github Actions
![Github Actions](https://github.com/user-attachments/assets/e68a6d23-91e7-4ae8-8580-f7269ea14495
)

![Github Actions Error](https://github.com/user-attachments/assets/b8d9367c-8974-4167-b180-eaa1abbc79ce)

# 3. Explore Functions as a Service (FaaS)
Serverless Functions are used for responding to events like HTTP request, uploading files, and changing databases as well as serve for API backend services. In addition, it can be used for data processing such as used for IoT devices, aggregating data, and performing scheduled tasks. 
### *Azure*
#### Benefits
* They are cost-effective as they have option of consumption plan which has defaulty pricing based on actual usuage as well as pay-per-execution meaning you only pay for the resources during the execution
* They are able to autoscale based on demand
* Contain quick develoment which allow users to quickly deploy functions and contain many programming language support such as python, java, and C#
* Contain Development tools such as visual studio, azure functions core tools and azure portal integration
* Have multiple plans such as consumption, premium, app service to fit each indivudal's needs
#### Limitations 
* Has an execution time limit of maximum 10 mins for consumption plan
* Have limited memory and execution time 
### *GCP*
#### Benefits 
* They are cost-effective as they have option of pay per pricing which allow you to only pay for the time your functions are executed and no infrastructure management which eliminates costs associated with managing servers or infrastructure
* Contains seamless scaling allowing automatic scaling based on demand
* Contain rapid development allowing developer to quickly deploy functions without the overhead of server management and have several programming languages such as Node.js, Python, Go, Java, and .NET
* Is integrated with GCP Services such as Pub/Sub, Cloud Storage, Firestore and supports HTTP triggers, background events from GCP services, and third-party webhooks
#### Limitations
* Has an execution time limit of maximum 9 mins
* Have limited memory and CPU as they are limited up to 2 GB of memory
