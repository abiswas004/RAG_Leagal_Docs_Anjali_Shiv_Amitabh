# RAG_Leagal_Docs_Anjali_Shiv_Amitabh
The RAG system retrieved contextually accurate clauses from legal documents and provided relevant answers for benchmark questions.
RAG_Legal_Docs_Amitabh_Biswas/
│
├── RAG_Assg_Legal_Documents_Solution.ipynb     ← Your main Jupyter notebook
├── README.md                                   ← Overview of your project
├── requirements.txt                            ← (optional but recommended)
│
├── data/
│   ├── corpus/                                 ← text files (contracts, privacy, etc.)
│   │   ├── contractnli/ (few sample txts)
│   │   ├── cuad/
│   │   ├── maud/
│   │   └── privacy_qa/
│   └── benchmarks/                             ← benchmark JSONs
│       ├── contractnli.json
│       ├── cuad.json
│       ├── maud.json
│       └── privacy_qa.json
│
├── outputs/
│   ├── df_chunks.parquet                       ← processed chunk data
│   ├── faiss_index.index                       ← FAISS vector index
│   ├── metadata.parquet                        ← metadata file for FAISS
│   ├── benchmark_QA_set.csv                    ← all Q&A pairs from benchmark
│   └── RAG_Evaluation_Results.csv              ← model evaluation output
│
└── images/                                     ← screenshots (optional)
