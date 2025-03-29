# Gradio UI

## Introduction

Gradio UI deployment for LLM testing.


### Environment variables

- name: APP_TITLE
  value: Chat with your Knowledge Base
- name: SHOW_TITLE_IMAGE
  value: "True"
- name: INFERENCE_SERVER_URL
  value: https://phi4.demo.svc.cluster.local/v1
- name: MODEL_NAME
  value: phi4
- name: MAX_TOKENS
  value: "2048"
- name: TOP_P
  value: "0.95"
- name: TEMPERATURE
  value: "0.5"
- name: PRESENCE_PENALTY
  value: "1.03"
- name: MILVUS_HOST
  value: milvus.milvus.svc.cluster.local
- name: MILVUS_PORT
  value: "19530"
- name: MILVUS_USERNAME
  value: your_milvus_username
- name: MILVUS_PASSWORD
  value: your_milvus_password
- name: MILVUS_COLLECTIONS_FILE
  value: /opt/app-root/src/collections.json
- name: DEFAULT_COLLECTION
  value: rhoai_embeddings
- name: PROMPT_FILE
  value: prompt.txt
- name: MAX_RETRIEVED_DOCS
  value: "3"
- name: SCORE_THRESHOLD
  value: "0.99"
- name: PHOENIX_COLLECTOR_ENDPOINT
  value: http://phoenix.phoenix.svc.cluster.local:6006/v1/traces
- name: PHOENIX_PORT
  value: "6006"
- name: EMBEDDING_MODEL
  value: intfloat/multilingual-e5-small