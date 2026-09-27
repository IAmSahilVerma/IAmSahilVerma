# Hi, I'm Sahil

I build and evaluate machine learning and LLM systems. Before that, I spent three years writing CAD automation tools in C# and Python on Siemens NX Open for manufacturing clients, so I care a lot about software that real engineers actually use.

MSc Artificial Intelligence and Data Science (Distinction), University of Hull · BEng Mechanical Engineering · Based in Hull, UK

## What I work on
- Applied LLM engineering: RAG, fine-tuning, and checking whether a system actually works
- AI for engineering software: bringing ML into CAD and design workflows
- Controlled experiments with fair baselines, including the results that don't go my way

## Selected work

**[rag-vs-finetune-showdown](https://github.com/IAmSahilVerma/rag-vs-finetune-showdown)**
Compared a zero-shot baseline, a RAG pipeline and a QLoRA fine-tuned Phi-2 on ML research Q&A, trained on a 6GB laptop GPU. Fine-tuning won on ROUGE and BERTScore, mostly because the eval questions matched the training distribution and RAG couldn't retrieve the exact source papers. The real lesson: retrieval quality is the bottleneck.

**[memory-caching-benchmark](https://github.com/IAmSahilVerma/memory-caching-benchmark)**
Small-scale independent replication of Behrouz et al.'s memory-caching RNN paper. I found and fixed two fairness bugs in my own setup (a parameter-count mismatch and a learning-rate asymmetry) before trusting the results. The paper's claim held only partly.

**[insurance-claims-ai](https://github.com/IAmSahilVerma/insurance-claims-ai)**
Fraud risk scoring with LightGBM, SHAP explanations, retrieval over fraud rules, and an LLM that turns it all into a structured investigation report.

**[Spec2Photo_ML](https://github.com/IAmSahilVerma/Spec2Photo_ML)**
My MSc dissertation: estimating galaxy stellar mass from photometry using 900,000+ SDSS DR17 records, reaching an MAE of 0.0484 dex.

**[Highlight_Dimension](https://github.com/IAmSahilVerma/Highlight_Dimension)**
A C# NX Open tool that highlights every drawing dimension linked to the underlying 3D model.

## Tools I use most
Python, C#, PyTorch, scikit-learn, XGBoost, LightGBM, Hugging Face, LangChain, ChromaDB, FastAPI, Docker, MLflow, Siemens NX Open

## Get in touch
[LinkedIn](YOUR_LINKEDIN_URL) · sahilverma2399@gmail.com
