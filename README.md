### 컨테이너 빌드
```
docker run -d -t --name qqq -v $(pwd):/workspace --gpus all cuda_default:v1.0
```
### 컨테이너 실행
```
vscode 연결 or
docker exec -it qqq  /bin/bash
```