 <h1 align="center">Fursa HW5 Kubernetes Summary Task</h3>
  <h1 align="center">Elie Haddad</h3>
  
<p align="center" >
  <img src="https://1000logos.net/wp-content/uploads/2022/07/Kubernetes-Logo-768x432.png" alt="drawing" style="width:300px;"/>
</p>

#### We created an ingress that directs the traffic to the ynet and bitcoin applications we built in homework 3 and 4:



#### **To run the servers:**
> 1. Clone the project : git Clone https://github.com/elie111/k8sHW.git

> 2. kubectl apply  -f .

> 3. check if the servers are running: kubectl get po,svc

<p align="center" >
  <img src="/Images/servers.png" alt="drawing" style="width:700px;"/>
</p>

#### And then to deploy the applications using nginx:

> 1. minikube start

> 2. minikube addons enable ingress

> 3. minikube tunnel

<p align="center" >
  <img src="/images/minikube.png" alt="drawing" style="width:700px;"/>
</p>


#### First thing I dockerized the ynet and bitcoin applications I built in hw3 and hw4 and pushed the images to docker hub 

<p align="center" >
  <img src="/images/dockerhub.png" alt="drawing" style="width:700px;"/>
</p>


#### And we should be able to access the applications in localhost/ynet and localhost/bitcoin

<p align="center" >
  <img src="/images/bitcoin.png" alt="drawing" style="width:700px;"/>
</p>

<p align="center" >
  <img src="/images/ynet.png" alt="drawing" style="width:700px;"/>
</p>

