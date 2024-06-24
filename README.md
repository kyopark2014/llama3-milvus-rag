# Llama3 RAG based on Milvus and Jina embedding

## Milvus Vectore Store

[milvus-vector-store.md](https://github.com/kyopark2014/llama3-milvus-jina/blob/main/milvus-vector-store.md)에서는 Milvus를 이용한 vector store에 대해 설명합니다.

## Local 설치

```text
docker pull milvusdb/milvus:latest
docker run -d --name milvus_cpu -p 19530:19530 -p 19121:19121 milvusdb/milvus:latest
```
## Reference 
[llama3-langchain-kor](https://github.com/kyopark2014/llama3-langchain-kor)

