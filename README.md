# Llama3 RAG 

여기서는 Milvus knowledge store와 GPT-J embedding을 이용해 RAG를 구현합니다.

<img src="https://github.com/kyopark2014/llama3-rag/assets/52392004/33fbbd6d-b35e-44f3-abcb-a2ac968dd3a3" width="800">

## Milvus Vector Store

[milvus-vector-store.md](https://github.com/kyopark2014/llama3-milvus-jina/blob/main/milvus-vector-store.md)에서는 Milvus를 이용한 vector store에 대해 설명합니다.

[AWS Lambda Now Supports Up to 10 GB Ephemeral Storage](https://aws.amazon.com/ko/blogs/aws/aws-lambda-now-supports-up-to-10-gb-ephemeral-storage/)와 같이 Lambda는 /tmp에 최대 10GB까지 임시데이터를 저장할 수 있습니다. 기본은 512MB이며 최대 10GB 이상일 경우에 EFS를 이용합니다. Lambda console에서 "Ephemeral storag"을 변경합니다.

## Jina Embeddings v2 Base - en

8192 sequence length


## Reference 

[llama3-langchain-kor](https://github.com/kyopark2014/llama3-langchain-kor)

[HuggingFace Jina Embedding v2](https://huggingface.co/jinaai/jina-embeddings-v2-base-en)



