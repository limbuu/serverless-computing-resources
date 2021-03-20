# Serverless Computing

## Cloud Vendors Serverless 
### [Google Cloud Serverless](https://cloud.google.com/serverless)
* [CloudFunctios](https://cloud.google.com/functions): Cloud Functions is serverless execution environment to deploy and run single purpose functions that are invoked in response to events triggers or HTTP requests. Main advantages of CloudFunctions are: no servers to provision, manage, or upgrade, automatically scale based on the load, integrated logging & monitoring with stackdriver, builtin security and key networking features for hybrid and multi-cloud senarios. But they come with some [limitations.](https://cloud.google.com/functions/quotas).   
* [Cloud Run](https://cloud.google.com/run): Cloud Run is fully managed google cloud service that can be used to develop and deploy highly scalable containeraized applications written in any language in fully managed serverless platform. This serverless platform is build upon an open standard Knative Serving, that enables rapid deployement of serverless containers in Kubernetes with 'scale to zero' functionality. 
* [App Engine](https://cloud.google.com/appengine): App Engine is gcp service that can be used to build and deploy highly availbale applications on fully managed serverless platform. It has support for wide range of languages in standard environment and any languages in case of flexible environment setup. 
### [AWS Serverless](https://aws.amazon.com/serverless/)
* [AWS Lambda](): AWS Lambda is a serverless compute service that lets you deploy and run code in wide range of runtimes, that can be configured to be triggered by 100s of AWS services or call it directly from web or mobile app . You can upload code as zip, container image, use template or write from scratch. Some advantages of AWS Lambda are: no servers to provision or manage, continuous scaling based on the size of workload and requests/triggers, integrated logging & monitoring with cloudwatch, cost-optimized with millisecond metering and . But they come with some [limitations.](https://docs.aws.amazon.com/lambda/latest/dg/gettingstarted-limits.html)
* [AWS Fargate](): AWS Fargate is fully managed serverless compute engine for containers that works with both [Amazon Elastic Container Service](https://aws.amazon.com/ecs) and [Amazon Elastic Kubernetes Service.](https://aws.amazon.com/eks)Fargate removes the need to provision and manage servers, lets you specify and pay for resources per application, and improves security through application isolation by design. 
* [AWS SQS](https://aws.amazon.com/sqs): AWS SQS is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications. SQS scales elastically with your application so you don’t have to worry about capacity planning and pre-provisioning. There is no limit to the number of messages per queue, and standard queues provide nearly unlimited throughput.
* [AWS DyanamoDB](https://aws.amazon.com/dynamodb/): AWS DyanamodDB is fully managed, key-value and document database that delivers very high performance in scale of single-digit millisecond at any scale. It is serverless with no need to provision and manage servers that automatically scales up and down the tables to adjust capacity based on load. 
* [Others](https://aws.amazon.com/serverless/): AWS also have other services that falls under serverless computing landscape such as: for application integration: Amazon EventBridge, AWS Setup Functions, Amazon SQS, Amazon SNS, Amazon API Gateway, Amazon AppSync and for data store: AWS S3, Amazon Dynamodb, Amazon RDS Proxy and Amazon Aurora Serverless. 

## Opensource Serverless Frameworks
* [Apache OpenWhisk](https://openwhisk.apache.org/): It is opensource serverless platform that allows to execute code in response 
to events at any scale. This framework written in `Scala` lanaguage, process the inputs from triggers like HTTP requests and later fires snippet of code on either JavaScript or Swift.
* [Fission](https://fission.io/): It is a serverless computing framework that enables developers to build short lived functions in Kubernetes, and map them to event triggers like HTTP requests.
* [IronFunctios](https://open.iron.io/): It is serverless computing framework that offers a cohesive microservices platform by integrating its existing services and embracing Docker. It is written in Go language.
* [Fn Project](https://fnproject.io/): It is opensource container native serverless platform that can be run anywhere cloud or 
premise.
* [Kubeless](https://kubeless.io/): It is kubernetes native serverless platform that lets you deploy small bits of code without having to worry about underlying K8s infrastructure. 
* [Knative Serving](https://knative.dev/): It is Kubernetes based serverless microservices with "scale-to-zero" functionality. With Knative serving, you can build and deploy serverless applications and functions in Kubernetes and used `Istio` to scale, rapidly deploy serverless containers, automatic scalig down to zero, routing and networking with Istio, point in time snapshots of deployed code and configuratiions. 
* [OpenFaas](https://docs.openfaas.com/): It is framework for building serverless functions with Docker and Kubernetes, with support for metrics. 
* [nuclio](https://nuclio.io/): A high-performance serverless framework focused on data, I/O, and compute intensive workloads. It is well integrated with popular data science tools, such as Jupyter and Kubeflow; supports a variety of data and streaming sources; and supports execution over CPUs and GPUs.
* [Hydrosphere Mist](https://github.com/Hydrospheredata/mist): It is serverless proxy for Apache Spark clusters.
* [Hydrosphere ML Lambda](https://github.com/Hydrospheredata/hydro-serving): It is Open source model management cluster for deploying, serving and monitoring machine learning models and ad-hoc algorithms with a FaaS architecture.

## Online Courses
* [Introduction to Serverless On Kubernetes](https://www.edx.org/course/introduction-to-serverless-on-kubernetes)
* [AWS Fundamentals: Building Serverless Applications
](https://www.coursera.org/learn/aws-fundamentals-building-serverless-applications)
* [Application Development using Microservices and Serverless](https://www.coursera.org/learn/applications-development-microservices-serverless-openshift)
* [Microservices, Serverless, OpenShift](https://www.edx.org/course/microservices-serverless-openshift)
* [7 Best Serverless and AWS Lambda Courses to Learn in 2021](https://medium.com/javarevisited/7-best-serverless-and-aws-lambda-courses-to-learn-in-2021-de1820111c85)
* [Other Online Courses](https://www.serverless.com/courses/)

## Articles and Blogs
### General Serverless
* [Serverless Architecture — Complete Reference Guide [2019]](https://medium.com/swlh/serverless-architecture-complete-reference-guide-2019-55363c08d1be)
* [Serverless Computing 101— What is it? Is it actually server-less](https://medium.com/swlh/serverless-computing-101-what-is-it-is-it-actually-server-less-747ef0523926)
* [What a typical 100% Serverless Architecture looks like in AWS!](https://medium.com/serverless-transformation/what-a-typical-100-serverless-architecture-looks-like-in-aws-40f252cd0ecb)
* [Will Serverless Computing Kill Docker Containers?](https://medium.com/hackernoon/will-serverless-computing-kill-docker-containers-222671bffdc4)
* [10 Things Serverless Architects Should Know](https://aws.amazon.com/blogs/architecture/ten-things-serverless-architects-should-know/)
* [Serverless Architecture WhitePaper](https://aws.amazon.com/lambda/serverless-architectures-learn-more/)

### Serverless for AI and Machine Learning
* [How Serverless Architecture Can Impact the Future of AI and ML Industries](https://blog.techmagic.co/how-serverless-impacts-the-ai-and-ml-industries/)
* [How I Built and Deployed a Fun Serverless Machine Learning App](https://towardsdatascience.com/building-and-deploying-cartoonify-b4786b382d7e)
* [Serverless machine learning architecture on leading cloud platforms](https://towardsdatascience.com/serverless-machine-learning-architecture-on-leading-cloud-platforms-c630dee8df15)
* [OS for AI: How Serverless Computing Enables the Next Gen of ML](https://medium.com/@ODSC/os-for-ai-how-serverless-computing-enables-the-next-gen-of-ml-aaecdd6df312)

## Current University Research
### George Mason University:
* Professors : [Yue cheng](https://cs.gmu.edu/~yuecheng/)
* Labs : [Leap Lab](https://mason-leap-lab.github.io/)
* Domains: [Serverless Computing](https://mason-leap-lab.github.io/research/#Serverless%20Computing), [Distributed Learning](https://mason-leap-lab.github.io/research/#Distributed%20Learning)
* Publications : [serverless research papers](https://mason-leap-lab.github.io/publications/)

### University of Chicago:
* Professors: [Andrew A. Chien](http://people.cs.uchicago.edu/~aachien/lssg/people/andrew-chien/), [Ian Foster](https://labs.globus.org/people.html), [Kyle Chard](https://labs.globus.org/people.html)
* Labs: [LSSG](http://people.cs.uchicago.edu/~aachien/), 
* Domains: [Real Time Serverless](http://people.cs.uchicago.edu/~aachien/lssg/research/zccloud/rtserverless/), [Data-Intensive Computing](https://labs.globus.org/), [Serverless SuperComputing](https://labs.globus.org/projects/funcx.html), [Python-based Parallel Scripting](https://labs.globus.org/projects/parsl.html)
* Pubications: [LSSG lab research papers](http://people.cs.uchicago.edu/~aachien/lssg/research/zccloud/rtserverless/), [globus labs research papers](https://labs.globus.org/publications.html)

### Georgia Tech:
* Professors: [Alexey Tumanov](https://www.cc.gatech.edu/~atumanov/)
* Labs: [SAIL Lab](https://www.cc.gatech.edu/~atumanov/index.html#researchgroup) 
* Domains: [Distributed Computing for AI workloads](https://www.cc.gatech.edu/~atumanov/index.html#Publications), [Serverless Computing for AI workloads](https://www.cc.gatech.edu/~atumanov/index.html#Publications)
* Pubications: [distributed computing and serverless research papers](https://www.cc.gatech.edu/~atumanov/index.html#Publications)

## International Serverless Conference
* [Internation Workshop Serverless Computing](https://www.serverlesscomputing.org/)
* [Serverless Architecture Conference](https://serverless-architecture.io/thehague/)

## Serverless Publications/Journals
* [Serverless on arxiv.org](https://arxiv.org/search/?query=serverless&searchtype=all&source=header)
* [Serverless on ieeexplore](https://ieeexplore.ieee.org/search/searchresult.jsp?newsearch=true&queryText=serverless)
* [Serverless on dl.acm.org](https://dl.acm.org/action/doSearch?AllField=serverless)
 

  

