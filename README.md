# 🥅 Task Planning Papers

A collection of task planning papers.

## Papers

[arXiv 29 Aug 2023] [**TaskLAMA: Probing the Complex Task Understanding of Language Models**](https://arxiv.org/abs/2308.15299)
![Resource](https://img.shields.io/badge/Resource-green) ![LLM](https://img.shields.io/badge/LLM-red)<br />
_Quan Yuan, Mehran Kazemi, Xin Xu, Isaac Noble, Vaiva Imbrasaite, Deepak Ramachandran_<br />
[[Dataset]](https://storage.googleapis.com/gresearch/tasklama/tasklama.zip)<br />
> Structured Complex Task Decomposition (SCTD) is the problem of breaking down a complex real-world task (such as planning a wedding) into a directed acyclic graph over individual steps that contribute to achieving the task, with edges specifying temporal dependencies between them. SCTD is an important component of assistive planning tools, and a challenge for commonsense reasoning systems. We probe how accurately SCTD can be done with the knowledge extracted from Large Language Models (LLMs). We introduce a high-quality human-annotated dataset for this problem and novel metrics to fairly assess performance of LLMs against several baselines. Our experiments reveal that LLMs are able to decompose complex tasks into individual steps effectively, with a relative improvement of 15% to 280% over the best baseline. We also propose a number of approaches to further improve their performance, with a relative improvement of 7% to 37% over the base model. However, we find that LLMs still struggle to predict pairwise temporal dependencies, which reveals a gap in their understanding of complex tasks.
