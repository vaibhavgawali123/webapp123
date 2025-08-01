# KUBERNETES DEPLOYMENT  
**Company**: CODTECH IT SOLUTIONS  
**Name**: Vaibhav Gawali  
**Intern ID**: CT04DH1004  
**Domain**: DEVOPS  
**Duration**: 4 WEEKS  
**Mentor**: NEELA SANTOSH  
As part of my internship at Codtech IT Solutions, I was assigned the task to deploy a microservices-based application on a Kubernetes cluster. The main goal of this task was to understand how modern applications are deployed and managed using container orchestration tools like Kubernetes. Microservices architecture involves breaking down an application into smaller, independent services that can be developed, deployed, and scaled individually. This is widely used in real-world projects for better performance, scalability, and maintainability.
To complete this task, I created and worked with multiple microservices (such as a frontend service, a backend service, and a database service) and containerized each one using Docker. I then wrote Kubernetes YAML configuration files for each service, including Deployment, Service, and ConfigMap or Secret definitions where needed. These YAML files define how each microservice should run on the Kubernetes cluster, how many replicas should be maintained, and how the services should communicate with each other.
I used either Minikube (for local testing) or a cloud-based Kubernetes service like Amazon EKS, Google GKE, or Azure AKS to create the Kubernetes cluster. After setting up the cluster, I applied the YAML configuration files using the kubectl apply -f command to deploy each microservice. I also verified the deployment by checking the status of the pods, services, and logs using commands like kubectl get pods, kubectl get services, and kubectl logs.
Through this task, I learned how to organize and deploy a multi-service application in a Kubernetes environment, how to manage service discovery between microservices, and how to scale or restart individual components without affecting the whole application. The final deliverables included all the YAML configuration files used for the deployment and detailed documentation explaining the architecture, the purpose of each microservice, and how the deployment was done step-by-step.
This task helped me build a solid foundation in Kubernetes and microservices deployment, which is a valuable skill in DevOps and modern cloud-native application development.
