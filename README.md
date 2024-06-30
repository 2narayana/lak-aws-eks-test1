
docker build -t lak/aws-eks-test-app .
docker login
docker push lak/aws-eks-test-app



eksctl create cluster --name lak-cluster1


conda activate ml_test_env_v2
streamlit run app.py


cd /Users/lakshminarayana/Documents/Lak_ML_Projs/AWS-EKS-TEST1-main

docker build -t lak/aws-eks-test-app .
docker push lak/aws-eks-test-app


lak/aws-eks-test-app:latest


docker login -u "narayana2012" -p "Kiran@1234" docker.io

docker build -t lak-aws-eks-test-app3 .

docker tag lak-aws-eks-test-app3 narayana2012/lak-aws-eks-test-app3:lak-aws-eks-test-app3

docker push narayana2012/lak-aws-eks-test-app3:lak-aws-eks-test-app3


docker build -t narayana2012/lak-aws-eks-test-app .

docker push narayana2012/lak-aws-eks-test-app

kubectl version --client

eksctl create cluster --name lak-cluster2

kubectl apply -f streamlit-app-deployment.yaml

kubectl get pods

kubectl get deployments

kubectl get services

