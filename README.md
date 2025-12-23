# Devops-Project


![Uploading image.png…]()

PS C:\Users\Prerana\Downloads\the-devops-project-main\the-devops-project-main\k8s> history

  Id CommandLine
  -- -----------
   1 try { . "c:\Users\Prerana\AppData\Local\Programs\Microsoft VS Code\resources\app\out\vs\workbench\contrib\terminal\common\scrip... 
   2 ls
   3 git add .
   4 git --version
   5 git init
   7 git branch
   8 git remote add origin https://github.com/prernask/Devops-Project.git
  13 git push -u origin main
  14 git pull
  15 git push -u origin main
  16 git pull main
  17 git push -u origin main
  18 git pull origin main
  19 git push -u origin main
  20 git pull origin main --allow-unrelated-histories
  21 git status
  22 git add .
  23 git commit -m "initial stage"
  24 git push -u origin main
  25 ls
  26 cd .\the-devops-project-main\

  29 cd app
  30 ls
  31 python --version
  32 python run app.py
  33 python .\app.py
  34 pip --version
  35 pip install flask
  36 flask --version
  37 python .\app.py
  38 docker login
  39 docker login
  40 docker --version
  41 cd ..
  42 ls

  45 docker build -t preranakarande/prerana:latest .
  47 docker push preranakarande/prerana
  48 docker run -d -p 3000:5000 preranakarande/prerana:latest
  49 docker container ls
  50 docker ps
  51 docker container start cdd3a2dcbe3f
  52 docker run -d -p 5000:5000 preranakarande/prerana:latest
  53 docker container ls
  54 docker container start 742a3b2c149c
  55 eksctl version
  57 eksctl create cluster --name mycluster --region ap-south-1 --nodegroup-name mynodes --node-type c7i-flex.large  --nodes 2 --nod...
  58 kubectl get nodes
  59 docker images
  69 kubectl apply -f .\k8s\
  70 kubectl get pods
  72 cd .\k8s\
  73 kubectl apply -f deployment.yaml
  74 kubectl apply -f deployment.yaml
  75 kubectl get pods
  76 kubectl decribe pods flask-app-6d8946dddb-jgkqg
  77 kubectl describe pods flask-app-6d8946dddb-jgkqg
  78 kubectl delete pod -l app=flask-app
  79 kubectl get pods
  80 docker push preranakarande/prerana:latest
  81 kubectl apply -f deployment.yaml
  82 cd .\k8s\
  83 cd ..
  84 kubectl apply -f .\k8s\
  85 kubectl get pods
  86 cd .\k8s\
  87 kubectl apply -f service.yaml
  88 kubectl apply -f deployment.yaml
  89 kubectl delete pod flask-app-6d8946dddb-mjcc5
  90 kubectl delete deployment flask-app
  91 kubectl get pods
  92 cd ..
  93 kubectl apply -f .\k8s\
  94 kubectl get pods
  95 kubectl describe pods
  96 docker images
  97 kubectl delete deployment flask-app
  98 kubectl describe pods
  99 docker images
 100 docker rmi preranakarande/prerana
 101 docker rmi preranakarande/prerana:latest
 102 docker images
 103 docker container list
 104 docker rm 742a3b2c149c
 105 docker container stop 742a3b2c149c
 106 docker container stop cdd3a2dcbe3f
 107 docker rm cdd3a2dcbe3f
 108 docker rm 742a3b2c149c
 109 docker container list
 110 docker images
 111 docker rmi preranakarande/prerana:latest
 112 docker images
 113 ls
 114 docker build -t preranakarande/devopsnew:latest .
 115 docker push preranakarande/devopsnew:latest
 116 kubectl apply -f .\k8s\
 117 kubectl describe pods
 118 kubectl get pods
 119 kubectl delete service flask-app-service
 120 cd .\k8s\
 121 kubectl delete service flask-app-service
 122 kubectl apply -f service.yaml
 123 kubectl apply -f .\deployment.yaml
 124 kubectl get pods
 125 cd ..
 126 kubectl delete deployment
 127 kubectl delete deployment flask-app
 128 kubectl get pods
 129 cd .\k8s\
 130 kubectl apply -f .\deployment.yaml
 131 kubectl apply -f service.yaml
 132 kubectl get pods
 133 kubectl get deployment
 134 kubectl get pods
 135 kubectl decribe pods
 136 kubectl describe pods
 137 kubectl get pods
 138 kubectl describe pods flask-app-6865774c46-7lxvp
 139 kubectl create secret docker-registry regcred --docker-username=preranakarande --docker-password=Psk@132001 --docker-server=doc... 
 140 kubectl get secrets
 141 kubectl get pods
 142 kubectl delete deployment flask-app
 143 kubectl get pods
 144 kubectl apply -f .\deployment.yaml
 145 kubectl apply -f service.yaml
 146 kubectl get pods
 147 kubectl describe pods
 148 kubectl get pods
 149 kubectl get pods
 150 kkectl ge services
 151 kubectl  get services
 152 eksctl delete cluster --name mycluster --region ap-south-1


PS C:\Users\Prerana\Downloads\the-devops-project-main\the-devops-project-main\k8s> 
