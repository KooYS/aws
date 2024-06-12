# aws

```파일 복사 (로컬 -> EC2)
scp -i [pem] nginx.green.conf nginx.blue.conf docker-compose.blue.yaml docker-compose.green.yaml deploy.sh [ID]@[IP]:/home/ec2-user
```

```
인스턴스에서 nginx 설치 후 cd nginx-deploy 의 nginx.conf 파일 내용을 복사해서
```
