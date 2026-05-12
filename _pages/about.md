---
permalink: /
title: "Yihang Xu | AI Algorithm Engineer (LLMs · Agents)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I received my B.Eng. in Artificial Intelligence from the **School of Future Science and Engineering, Soochow University** (*Sept 2021 – Jun 2025*). 
I work on **large language models, RAG, agents, and production-ready AI systems**, from modeling to deployment and integration.

## Education
**Soochow University** · School of Future Science and Engineering · B.Eng. in Artificial Intelligence · *Sept 2021 – Jun 2025*
- GPA: 3.5 / 4.0  
- Coursework: image processing, computer vision, machine learning, deep learning, neural networks  
## Selected Projects
### AsteriaDoctor: Clinical Q&A with LLMs and a Medical Knowledge Vector Store
Built an intelligent doctor–patient Q&A and decision-support system that combines **LLMs with a domain knowledge vector store** to improve factual accuracy and reduce hallucinations in medical settings.
- Core modeling: **BioBERT + ChatGLM2-6B** backbone, **FFN**-based semantic encoding of patient queries, and a medical vector index for precise retrieval; chain-of-thought style reasoning for richer case analysis; dual-role (patient / physician) token routing for guided answers.  
- Product positioning vs. **MedGPT**, **BioMedLM**, and similar systems on accuracy, feature completeness, and cost (~**CNY 1,500 per million tokens**); APIs and documentation for integration; supports knowledge-base refresh and fine-tuning; connected to hospital information systems, piloted with datasets at the affiliated hospital of Soochow University.  
### Zhisao Tong: Agent-Based Customer Support for Robot Vacuums
An **Agent + LangChain** customer-service stack with **RAG** and a **ReAct**-style workflow for complex, knowledge-intensive user questions.
- Led the **Agent** architecture and LangChain orchestration for semantic retrieval and answer generation.  
- **Qwen text-embedding-v4** for document embeddings, **Qwen3-max** for response generation, **Chroma** for the vector store; automatic ingestion of PDF/TXT corpora with **MD5 deduplication**; YAML-driven configuration; **Streamlit** UI with streaming responses.  
## Skills
- **Languages & tooling**: strong **Python**; familiar with C, C++, Java; Cursor, Trae, Hugging Face, and typical ML engineering workflows.  
- **Deep learning**: TensorFlow, PyTorch; LLM fine-tuning and application development; OpenCV and standard CV preprocessing / augmentation / feature workflows.  
- **LLMs & agents**: Transformer fundamentals; experience with DeepSeek, GPT, BERT, Qwen; **LoRA**, **SFT**; **RAG**, prompt engineering, **LangChain**, and end-to-end agent projects.  
- **Apps & runtime**: Ollama, Streamlit, Chatbox, and similar tooling.  
## Honors
- **Oct 30, 2024** — National AI Application Scenario Innovation Challenge, *Intelligent Healthcare Track*, **Second Prize**  
- **Nov 2024** — National AI Algorithm Elite Competition (Jiangsu), *Algorithm Innovation*, **Second Prize**  
- **Dec 2024** — National AI Algorithm Elite Competition, *Algorithm Innovation*, **Third Prize**  
## Research Output
- Patent (pending, **first inventor**): *Diabetic retinopathy segmentation based on Poisson-blend data augmentation*  
---

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
