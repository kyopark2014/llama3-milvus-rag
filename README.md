# Llama3 RAG 

여기서는 Milvus knowledge store와 GPT-J embedding을 이용해 RAG를 구현합니다.

<img src="https://github.com/kyopark2014/llama3-rag/assets/52392004/33fbbd6d-b35e-44f3-abcb-a2ac968dd3a3" width="800">

## Milvus Vector Store

[What is Milvus?](https://milvus.io/blog/how-to-get-started-with-milvus.md)와 같이 Milvus는 텍스트, 이미지, 오디오를 위핸 오픈소스 벡터 데이터베이스로서 대용량의 비정형 데이터를 처리할 수 있습니다. 이것 high dimension을 가지는 데이터를 효과적으로 검색할 수  ㅣㅆ고 대규모의 데이터셋을 다루기 위해 scalability를 제공합니다. 


[milvus-vector-store.md](https://github.com/kyopark2014/llama3-milvus-jina/blob/main/milvus-vector-store.md)에서는 Milvus를 이용한 vector store에 대해 설명합니다.

[AWS Lambda Now Supports Up to 10 GB Ephemeral Storage](https://aws.amazon.com/ko/blogs/aws/aws-lambda-now-supports-up-to-10-gb-ephemeral-storage/)와 같이 Lambda는 /tmp에 최대 10GB까지 임시데이터를 저장할 수 있습니다. 기본은 512MB이며 최대 10GB 이상일 경우에 EFS를 이용합니다. Lambda console에서 "Ephemeral storag"을 변경합니다.

## Jina Embeddings v2 Base - en

8192 sequence length


## Reference 

[llama3-langchain-kor](https://github.com/kyopark2014/llama3-langchain-kor)

[HuggingFace Jina Embedding v2](https://huggingface.co/jinaai/jina-embeddings-v2-base-en)


