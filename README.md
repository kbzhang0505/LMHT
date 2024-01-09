# LMHT
After the paper is accepted, we will provide code for the paper: Lightweight Multi-Scale Hybrid Transformer for Image 
Super-Resolution(LMHT)
# Abstract
In this letter, we elaborate on a novel lightweight multi-scale hybrid transformer (LMHT) for SR. The LMHT consists of three crucial components, namely multi-head multi-scale spatial self-attention (MMSSA), multi-head channel self-attention (MCSA), and dual spatial-gate feed-forward network (DSGFN). Specifically, the MMSSA models long-term dependencies by splitting the attention head into different groups and each group performs spatial self-attention within the corresponding scale. While the MCSA accomplishes global channel self-attention by computing the attention scores between the channel tokens to complement the feature interaction among channels. Furthermore, the DSGFN is applied to enrich local context information
through a dual spatial-gate mechanism. Experimental results demonstrate that the proposed LMHT outperforms other existing
leading methods in terms of both quantitative and qualitative assessments on five benchmark dataset while maintaining
competitive lightweight level.
# Results
![image](https://github.com/kbzhang0505/LMHT/assets/97494153/811540d8-a20b-4f91-8b07-e1a41b7ff2e6)
![image](https://github.com/kbzhang0505/LMHT/assets/97494153/fd4d28d1-0050-4baa-a4e1-ae0a9575f6a6)
# Ablation Study
![image](https://github.com/kbzhang0505/LMHT/assets/97494153/795b2ed5-c514-4dcb-a04e-227127f5d77b)
