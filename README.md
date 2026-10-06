<div align="center">

<img src="assets/headers/banner.svg" width="100%" alt="Gregory Harutyunyan - AI/ML Engineer · Mathematician" />

<br><br>

<img src="https://img.shields.io/badge/Available%20for%20hire-Open%20to%20Work-2EA043?style=for-the-badge" alt="Available for hire / Open to Work" />

<br>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=2196F3&center=true&vCenter=true&width=600&lines=AI%2FML+Engineer+%C2%B7+Mathematician;LLMs+in+production%3A+FastAPI+%2B+LangChain;Data+Engineering%3A+Spark+%C2%B7+Kafka+%C2%B7+BigQuery;NLP+%C2%B7+Vision+%C2%B7+Anomalies+%C2%B7+LLMOps;From+mathematical+rigor+to+deployment" alt="typing-svg" />
</a>

<br>



<br><br>

<a href="https://www.linkedin.com/in/gregory-hgev">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="mailto:greg.hgev@gmail.com">
  <img src="https://img.shields.io/badge/Email-1A1A1A?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="assets/CV.pdf">
  <img src="https://img.shields.io/badge/Curriculum_Vitae-2196F3?style=for-the-badge&logo=readthedocs&logoColor=white" alt="CV" />
</a>

</div>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/headers/sobre-mi-dark.svg">
  <img src="assets/headers/sobre-mi-light.svg" width="480" alt="About me">
</picture>

**AI / Machine Learning Engineer** with a background in **Mathematics** (UGR - #1 Mathematics degree in Spain, ShanghaiRanking 2025) and a **Master's in AI + Data Engineering specialization** (UNIR) in its final stage. EU citizen based in Granada, open to relocation and **available for internships or junior roles**.

During my internship at **Qualígrafo**, I worked on the LLM inference engine of Mimesis, an AI platform that helps psychologists and researchers turn hours of interviews into customised surveys, extracting relevant patterns and generating conclusions automatically.

I'm finishing an MSc in Artificial Intelligence with a specialization in Data Engineering (UNIR). My Master's thesis uses **machine learning and graph neural networks** to predict, before execution, how much noise will degrade a quantum circuit, so that poor executions can be avoided and quantum processor time and costs can be reduced.

I have worked hands-on across the main branches of AI: natural language processing (transformers, RAG/KAG), computer vision, deep learning (CNNs, GNNs), unsupervised learning and anomaly detection. The Data Engineering specialization adds the cloud-at-scale side: streaming pipelines with **Spark + Kafka** on **Dataproc**, analytics with **BigQuery** and MLOps tooling (Docker, MLflow, W&B, DVC).

I work particularly well in team environments and I pick up new stacks quickly. I am comfortable across the entire data lifecycle: from exploration and preprocessing to deploying inference services.


<br>

<p align="center">
<img src="assets/cards/pilar-matematica.svg" width="24%" alt="Mathematical foundation" /><img src="assets/cards/pilar-produccion.svg" width="24%" alt="AI in production" /><img src="assets/cards/pilar-ml.svg" width="24%" alt="Advanced ML" /><img src="assets/cards/pilar-data.svg" width="24%" alt="Data &amp; Cloud" />
</p>



---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/headers/experiencia-dark.svg">
  <img src="assets/headers/experiencia-light.svg" width="480" alt="Experience">
</picture>

### Backend AI Engineer / LLMOps - Internship · Qualígrafo S.L. · Mimesis Platform
> Mar 2026 – May 2026 · 3 months · Granada (Remote)

> <code>Python</code> · <code>FastAPI</code> · <code>LangChain</code> · <code>Pydantic</code> · <code>Groq API</code> · <code>Azure OpenAI</code> · <code>Ollama</code> · <code>HPC (SCAYLE)</code>
>
> - **AI Assistant Backend (HPC):** Migrated the API of an AI assistant for psychologists and researchers (2 mixed-methods pipelines of 4 phases each, with 10 endpoints) to an asynchronous job-based system. Validated the architecture for the SCAYLE supercomputing cluster.
> - **Hallucination mitigation:** Implemented JSON Schemas and real-time validation with Pydantic for 8 prompt stages in an orchestrated LLM pipeline.
> - **Inference flexibility:** Developed an abstraction layer with LangChain to switch between 3 LLM providers (Ollama, Groq, Azure OpenAI) to optimize latency and cost depending on the environment.

<br>

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/headers/tfm-dark.svg">
  <img src="assets/headers/tfm-light.svg" width="480" alt="Master's Thesis">
</picture>

### Quantum Noise Mitigation with AI &nbsp; [![Master's Thesis (PDF, in Spanish)](https://img.shields.io/badge/Master%27s%20Thesis-PDF%20%C2%B7%20Spanish-7B61FF?style=flat-square&logo=readthedocs&logoColor=white)](assets/master-thesis.pdf)
> Submitted · 2026 · Master's in AI · UNIR

> <code>Python</code> · <code>PyTorch Geometric</code> · <code>Qiskit Aer</code> · <code>Scikit-learn</code> · <code>W&amp;B</code> · <code>DVC</code> · <code>GCP</code>
>
> **Can we predict, before running a quantum circuit, how much noise will degrade its result?** Current error-mitigation techniques act after measurement and require running the circuit many times, which consumes an expensive and scarce resource: quantum processor time. This thesis studies whether that degradation can be anticipated from the circuit structure and the processor calibration alone.

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/cards/tfm-pipeline-dark.svg">
  <img src="assets/cards/tfm-pipeline-light.svg" width="90%" alt="Thesis pipeline: quantum circuit, representation, models and predicted survival factor">
</picture>
</p>

> - **Dataset:** 20,000 circuits of 5 to 15 qubits, labeled with their exact degradation using 42 days of real calibration data from an IBM processor, and split along 3 independent generalization axes (circuit type, size and time).
> - **Target:** the signed degradation turned out not to be predictable before execution; reformulated as a *survival factor* (the fraction of signal that remains after noise), it is.
> - **Results:** Random Forest wins overall and is the only model that never worsens the corrected observable (up to 81% relative improvement). Graph neural networks only pay off when extrapolating to larger circuits (+0.21 and +0.23 R² over Random Forest on the X observable at 14 and 15 qubits).

<br>

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/headers/stack-dark.svg">
  <img src="assets/headers/stack-light.svg" width="480" alt="Stack">
</picture>

**Languages &amp; Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)

**Machine Learning · NLP · Vision**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Unsupervised Learning](https://img.shields.io/badge/Unsupervised%20Learning-0F766E?style=flat-square)

**LLMs &amp; GenAI**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Llama 3.3](https://img.shields.io/badge/Llama%203.3-0866FF?style=flat-square&logo=meta&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)
![RAG / KAG](https://img.shields.io/badge/RAG%20%2F%20KAG-7B61FF?style=flat-square)

**Deep Learning**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![PyTorch Geometric (GNNs)](https://img.shields.io/badge/PyTorch%20Geometric%20%28GNNs%29-3C2179?style=flat-square&logo=pyg&logoColor=white)

**Quantum Computing**

![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=flat-square&logo=qiskit&logoColor=white)
![Qiskit Aer](https://img.shields.io/badge/Qiskit%20Aer-6929C4?style=flat-square&logo=qiskit&logoColor=white)
![IBM Quantum Runtime](https://img.shields.io/badge/IBM%20Quantum%20Runtime-052FAD?style=flat-square)

**Cloud &amp; Data Engineering**

![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![Cloud Storage](https://img.shields.io/badge/Cloud%20Storage-4285F4?style=flat-square&logo=googlecloudstorage&logoColor=white)
![Dataproc](https://img.shields.io/badge/Dataproc-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**Infrastructure &amp; MLOps**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/Weights%20%26%20Biases-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=flat-square&logo=dvc&logoColor=white)
![Uvicorn](https://img.shields.io/badge/Uvicorn-2094F3?style=flat-square)
![Microservices](https://img.shields.io/badge/Microservices-6E40C9?style=flat-square)

**AI-Assisted Development**

![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=claude&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub%20Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

<br>

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/headers/proyectos-dark.svg">
  <img src="assets/headers/proyectos-light.svg" width="480" alt="Projects">
</picture>

<p align="center">
<a href="https://github.com/greghgev/hate-speech-classification-mlops"><img src="assets/cards/p1.svg" width="40%" alt="Hate Speech MLOps - Classification pipeline" /></a><a href="https://github.com/greghgev/hate-speech-analysis-nlp"><img src="assets/cards/p2.svg" width="40%" alt="NLP Feature Extraction &amp; Characterization" /></a>
</p>
<p align="center">
<a href="https://github.com/greghgev/master-ia-unir/tree/main/tecnicas-aa/covertype-rf-svm-comparison"><img src="assets/cards/p3.svg" width="40%" alt="Covertype: Random Forest vs SVM" /></a><a href="https://github.com/greghgev/master-ia-unir/tree/main/pln/pln_rag_kag_comparison"><img src="assets/cards/p4.svg" width="40%" alt="RAG vs KAG - University Regulations Assistant" /></a>
</p>
<p align="center">
<a href="https://github.com/greghgev/master-ia-unir/tree/main/vision-artificial/retinoblastoma-spatial-vs-morphology"><img src="assets/cards/p5.svg" width="40%" alt="Retinoblastoma - Spatial Filters vs Morphology" /></a><a href="#"><img src="assets/cards/p6.svg" width="40%" alt="E-Commerce Fraud - Anomaly Detection" /></a>
</p>

<br>

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/headers/formacion-dark.svg">
  <img src="assets/headers/formacion-light.svg" width="480" alt="Education">
</picture>


### Master's Degree in Artificial Intelligence + Data Engineering specialization - UNIR &nbsp; [![Repository](https://img.shields.io/badge/master--ia--unir-2196F3?style=flat-square&logo=github&logoColor=white)](https://github.com/greghgev/master-ia-unir) [![Master's Thesis (PDF, in Spanish)](https://img.shields.io/badge/Master%27s%20Thesis-PDF%20%C2%B7%20Spanish-7B61FF?style=flat-square&logo=readthedocs&logoColor=white)](assets/master-thesis.pdf)
> <p><sub><b>In progress · Nov 2025 – Jul 2026</b></sub></p>
> 
> - **Master's Thesis:** application of AI techniques for noise mitigation in quantum computing.
> - **Data Engineering:** labs on continuous processing pipelines (Apache Kafka, Spark Streaming) and analytical ingestion in the cloud (GCP, BigQuery).

### Bachelor's Degree in Mathematics - University of Granada (UGR) &nbsp; [![Bachelor's Thesis (PDF, in Spanish)](https://img.shields.io/badge/Bachelor%27s%20Thesis-PDF%20%C2%B7%20Spanish-2196F3?style=flat-square&logo=readthedocs&logoColor=white)](assets/bachelor-thesis.pdf)
> <p><sub><b>2021 – 2025</b></sub></p>
> 
> - Completed in the standard time (4 years) in the Mathematics degree ranked **#1 in Spain**.
> - **Bachelor's Thesis:** extensions of isometries between subsets of certain Banach spaces.

<br>


<font color="#2196F3"><b>Master's courses</b></font>

<!-- ===========================================================
  HOW TO EDIT THE ACTIVITIES:
  Inside each course's <ul>, add or remove lines in HTML
  (it sits inside a table cell, so it is NOT markdown):
        <li><a href="https://github.com/greghgev/REPO-NAME">Activity name</a></li>
============================================================ -->

<table>
  <tr>
    <td valign="top", width="35%">
      <b>Natural Language Processing</b>
      <ul>
        <li><a href="https://github.com/greghgev/master-ia-unir/tree/main/pln/newsgroups-embeddings-vs-transformers">Word Embeddings vs Transformers - Text classification (20 Newsgroups)</a></li>
        <li><a href="https://github.com/greghgev/master-ia-unir/tree/main/pln/pln_rag_kag_comparison">RAG vs KAG - University regulations assistant with a knowledge graph</a></li>
      </ul>
    </td>
    <td valign="top"><img src="https://img.shields.io/badge/completed-2EA043?style=flat-square" alt="completed" /></td>
    <td valign="top"><small>spaCy, Hugging Face, Freeling; morphosyntax, LLM fine-tuning and chatbots.</small></td>
  </tr>
  <tr>
    <td valign="top">
      <b>Machine Learning Techniques</b>
      <ul>
        <li><a href="https://github.com/greghgev/master-ia-unir/tree/main/tecnicas-aa/airquality-linear-regression-vs-decision-tree">Linear Regression vs Decision Tree - Benzene prediction (AirQualityUCI)</a></li>
        <li><a href="https://github.com/greghgev/master-ia-unir/tree/main/tecnicas-aa/covertype-rf-svm-comparison">SVM vs Random Forest - Multiclass forest cover classification (Covertype)</a></li>
      </ul>
    </td>
    <td valign="top"><img src="https://img.shields.io/badge/completed-2EA043?style=flat-square" alt="completed" /></td>
    <td valign="top"><small>Naive Bayes, decision trees, metrics (F1, recall, ROC) and hyperparameter optimization.</small></td>
  </tr>
  <tr>
    <td valign="top">
      <b>Computer Vision</b>
      <ul>
        <li><a href="https://github.com/greghgev/master-ia-unir/tree/main/vision-artificial/retinoblastoma-spatial-vs-morphology">Spatial filters vs mathematical morphology - Retinoblastoma detection</a></li>
        <li><a href="https://github.com/greghgev/master-ia-unir/tree/main/vision-artificial/amazon-deforestation-segmentation">HSV segmentation on Landsat images - Amazon deforestation (2000–2019)</a></li>
      </ul>
    </td>
    <td valign="top"><img src="https://img.shields.io/badge/completed-2EA043?style=flat-square" alt="completed" /></td>
    <td valign="top"><small>Time/frequency-domain processing, feature extraction, textures and multiscale analysis.</small></td>
  </tr>
  <tr>
    <td valign="top">
      <b>Automated Reasoning and Planning</b>
    </td>
    <td valign="top"><img src="https://img.shields.io/badge/completed-2EA043?style=flat-square" alt="completed" /></td>
    <td valign="top"><small>PDDL and search algorithms (informed and uninformed).</small></td>
  </tr>
  <tr>
    <td valign="top">
      <b>Unsupervised Machine Learning</b>
      <ul>
        <li><sub><i>Coming soon</i></sub></li>
      </ul>
    </td>
    <td valign="top"><img src="https://img.shields.io/badge/in%20progress-D29922?style=flat-square" alt="in progress" /></td>
    <td valign="top"><small>K-Means, DBSCAN, t-SNE, MDS, ISOMAP, anomaly detection and reinforcement learning.</small></td>
  </tr>
  <tr>
    <td valign="top">
      <b>Neural Networks</b>
      <ul>
        <li><sub><i>Coming soon</i></sub></li>
      </ul>
    </td>
    <td valign="top"><img src="https://img.shields.io/badge/in%20progress-D29922?style=flat-square" alt="in progress" /></td>
    <td valign="top"><small>Keras, TensorFlow, GANs, CUDA/cuDNN; images, time series and cloud AI.</small></td>
  </tr>
</table>

<br>

<font color="#2196F3"><b>Advanced Program in Data Engineering courses</b></font>

<!-- ===========================================================
  HOW TO EDIT THE ACTIVITIES:
  Inside each course's <ul>, add or remove lines in HTML
  (it sits inside a table cell, so it is NOT markdown):
        <li><a href="https://github.com/greghgev/REPO-NAME">Activity name</a></li>
============================================================ -->

<table>
  <tr>
    <td valign="top", width="40%">
      <b>Engineering for Massive Data Processing</b>
      <ul>
        <li><a href="https://github.com/greghgev/master-ia-unir/tree/main/ingenieria-datos/walmart-sales-bigquery-eda">Walmart Sales EDA - Exploratory analysis with Google BigQuery and SQL</a></li>
        <li><a href="https://github.com/greghgev/master-ia-unir/tree/main/ingenieria-datos/flights-spark-streaming-kafka">Flights - Spark Structured Streaming + Kafka on Google Dataproc</a></li>
      </ul>
    </td>
    <td valign="top"><img src="https://img.shields.io/badge/completed-2EA043?style=flat-square" alt="completed" /></td>
    <td valign="top"><small>Large-scale ETL with Spark, relational warehouses on Hive and cloud services (GCP, Azure, AWS).</small></td>
  </tr>
  <tr>
    <td valign="top">
      <b>MLOps and AIOps: Deploying Models in Production Environments</b>
      <ul>
        <li><sub><i>Coming soon</i></sub></li>
      </ul>
    </td>
    <td valign="top"><img src="https://img.shields.io/badge/in%20progress-D29922?style=flat-square" alt="in progress" /></td>
    <td valign="top"><small>CI/CD for ML with MLflow, Docker, Google Vertex AI and orchestration in production.</small></td>
  </tr>
</table>

<br>


---

**Languages**

![Spanish](https://img.shields.io/badge/Spanish-native-2EA043?style=flat-square)
![Armenian](https://img.shields.io/badge/Armenian-native-2EA043?style=flat-square)
![Valencian](https://img.shields.io/badge/Valencian-C1-2196F3?style=flat-square)
![English](https://img.shields.io/badge/English-B2-2196F3?style=flat-square)

<br>

<!-- ===========================================================
  "GITHUB ACTIVITY" SECTION - HIDDEN.
  (If you re-enable it, you will again need the workflows from the .github
  folder that were deleted, because they generate metrics.svg and the output branch.)
  To show it, delete THIS opening comment line and the closing one.
============================================================

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/headers/actividad-dark.svg">
  <img src="assets/headers/actividad-light.svg" width="480" alt="GitHub Activity">
</picture>

<div align="center">

<img src="assets/metrics.svg" alt="GitHub metrics" width="100%">

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/greghgev/greghgev/output/snake-dark.svg">
  <img src="https://raw.githubusercontent.com/greghgev/greghgev/output/snake.svg" alt="Contributions animation" width="100%">
</picture>

</div>

<br>

============================ END OF HIDDEN SECTION ============================ -->

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/headers/cv-dark.svg">
  <img src="assets/headers/cv-light.svg" width="300" alt="CV">
</picture>

<div align="center">

<a href="assets/cv.pdf">
  <img src="assets/cv-preview.png" width="420" alt="CV preview - click to open the full PDF" />
</a>

<br>

<sub>Click the image to open the full PDF.</sub>

</div>

<br>

---

<div align="center">

### Available for hire

Open to **AI/ML Engineer** (Junior) positions and internships in Machine Learning, LLMs and Data Engineering teams.

<a href="https://www.linkedin.com/in/gregory-hgev">
  <img src="https://img.shields.io/badge/Let's%20talk-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="mailto:greg.hgev@gmail.com">
  <img src="https://img.shields.io/badge/Email%20me-1A1A1A?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>

</div>
