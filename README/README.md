1. what is kubernetes?
sol:- kubernetes is a container orchestration tool it support one of the runtime in docker and k8s is a open-source for automating and deploying and scalling the applications.

2. different types of services?
sol:- 
1.NodePort      --> it opens the range of ip addresses like 30000 to 32727 and exposes the app to outside the world.
2.LoadBalancer   --> it launches cloud native load balancer for a service.
3.Cluster IP     --> make a service for private
4.External Name  --> it can be map the server that are running outside the cluster.

3. what is replica set?
sol:- it is high availability and scalability for example we are all creating one after one pods by using yaml file creating, replica set is also using yaml file but inside the yaml file replica has we mention how many pods want to create (give a numeber like 3) it will create at a time 3 pods.

4. what is deployment?
sol:- deployment object offer rolling update for example first it creates pods and service it creates one by one.

5. what is namespace?
sol:- it has one cluster we use namespace commands it can create cluster inside the small cluster.

6. default namespcaes in k8s?
sol:- 
1.default
2.kube-public
3.kube-system