# bentoml_build
**运行flask服务**  
```Bash
python app.py
```
**构建和运行 Bento**  
```Bash
bentoml build
bentoml serve app:svc
```
**容器化 Bento**  
```Bash
 bentoml containerize sentiment_analysis_service:v6lu4ddcrknr4xb2
```
**在本地运行 Docker 镜像**
```Bash
docker run --rm -p 3000:3000 sentiment_analysis_service:v6lu4ddcrknr4xb2
```
