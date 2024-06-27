# .-R2-R2-HW.ipynb

[紀錄實作卡住的點]
1. 部分套件沒有安裝好，導致此行指令跑不出來：from langchain_huggingface import HuggingFacePipeline, ChatHuggingFace
  解法：
  # 安裝 langchain 和相關的 huggingface 庫
  !pip install langchain transformers
  
  !pip install bitsandbytes
  !pip install bitsandbytes==0.39.0

  
