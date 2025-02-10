### **Setup Prometheus in EKS Cluster** 
## Setup a cluster in EKS and deploy prometheus in it.

There are several moving parts and components in prometheus monitoring stack. How do you go ahead deploying the various moving parts in a kubernetes cluster.
 There are various ways of doing this, which includes;

 1. Creating all configuration YAML files yourself and executing them in the right order.
 2. A more efficient way is **"using an Operator"**.
 Think of an operator as a manager of all individual prometheus components. Stateful sets and deployment for example will manage thier pod replicas; like restart them when they die, make sure they are accessible. 

 In this option, you will have to find an operator for promethues and deploy it in a cluster.