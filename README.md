# Hi! I'm Jacintha Walters
**Cybersecurity & AI Professional**

Hands-on IT professional with a strong academic background (MSc & BSc Cum Laude) and a few years of experience with security architecture, risk assessments, LLM/RAG models and secure NLP/ML pipelines. Known for bridging the gap between technical implementation, compliance frameworks, and stakeholder communication.

---

## 🛠️ Technical Expertise
Network Security | Governance | Data Processing | Generative AI | Machine Learning | Deep Learning | Computer Vision | Natural Language Processing (NLP) | Large Language Model (LLM) Vulnerabilities |AI Security | Responsible AI |  Internet of Things (IoT) | AWS Cloud Architecture | Containerization | NIST Framework | Incident Response | Risk Assessment | Identity & Access Management (IAM) | API Architecture | Multi Factor Authentication (MFA) | JavaScript | Java | Git | Python | C++ | SQL

---

## 🚀 Featured Engineering Projects & Case Studies

### 1. RAG-Grounded Regulatory Compliance Assistant: EU AI Act Compliance Checker
Full-stack self-serve web app that helps organizations to classify an AI system's risk tier under the EU AI Act, by scoring high-risk AI model against a 50-question compliance assessment. The app contains a chatbot that allows the user to discuss the results of the questionnaire and give specific advise on mitigation. This tool builds on and extends my own 2023 peer-reviewed research (50+ citations).
* **Core Tech:** Python, FastAPI, React (Vite), Pydantic, sentence-transformers, Google Gemini API, RAG.
* **RAG & Evaluation:** Built a full retrieval-augmented generation pipeline from scratch — local embedding of primary legal source text, similarity retrieval, and prompt grounding using both retrieved articles and the user's own structured assessment data, to keep LLM output citation-accurate rather than generic.
* **Security & Cost Controls:** Per-IP rate limiting (slowapi) and Pydantic-enforced input length constraints on the LLM-facing endpoint to prevent abuse and control API spend; scoped CORS allowlisting between deployed frontend and backend.
* **Why it matters:** Demonstrates the ability to take original academic research from theory to a deployed, RAG-grounded production tool — spanning data modeling, API design, retrieval architecture, and applied LLM evaluation, not just prompting.
* 🔗 **[Live demo!](https://euaiact-chat.vercel.app/)**
* 🔗 **[View Repository & Source Code](https://github.com/jacintha-walters/euaiact-chat)**

---

### 2. Production-Ready NLP Pipeline: Adaptive Text Complexity Engine (Linguall)
Containerised microservice automating dynamic linguistic text profiling, designed to serve as a core component for language learning platforms.

* **Core Tech:** Python, FastAPI, Docker, SpaCy, Pydantic, Textstat.
* **Security & DevSecOps Controls:** Implemented automated input sanitization via optimized regex filters; enforced fail-secure header-based API key validation, and mitigated Denial of Service (DoS/CPU exhaustion) risks through payload constraints.
* **Why it matters:** Demonstrates the ability to build clean, maintainable, and containerised microservices that bridge advanced Natural Language Processing (NLP) with secure, production-grade API architecture.
* 🔗 **[View Repository & Source Code](https://github.com/jacintha-walters/adaptive-text-complexity-engine)**

---

### 3. Peer-Reviewed Publication: Enterprise AI Governance Framework (EU AI Act)
*First-Author research translating emerging European Union Artificial Intelligence Act regulations into actionable organizational maturity assessments.*
* **Core Focus:** AI Governance, Regulatory Compliance, Data Safety, Responsible AI, Risk Management
* **Publication Details:** J. Walters, D. Dey, D. Bhaumik, S. Horsman (Amsterdam University of Applied Sciences). Published 14-07-2023. Self-published and later indexed in **Springer’s "Artificial Intelligence: ECAI 2023 International Workshops"**.
* **Impact:** Selected by the university for multiple international conference keynotes (including ECAI 2023 in Krakow). **Cited 42 times** by global researchers.
* 🔗 **[View Scientific Paper on arXiv](https://arxiv.org/abs/2307.10458)**

#### 💡 Abstract and Engineering Methodology
Organisations adopting Artificial Intelligence face massive challenges aligning deep learning models with data privacy laws and compliance frameworks. My master's research aimed at bridging this gap by focusing on how organisations can assess and improve their readiness for compliance with the AIA:
* **Maturity Modeling:** Translated abstract regulatory requirements into practical, structured auditing frameworks that evaluate AI transparency, accountability, and mitigation of algorithmic bias, resulting in a **compliancy score**.
* **Risk Auditing & Data Analysis:** Processed and analysed quantitative and qualitative research data to identify patterns and evaluate challenges related to AI governance.
* **Proof-of-Concept LLM Development:** Engineered a Large Language Model (LLM) chatbot to allow smaller organisations to interactively explore the new legislation and their current weaknesses.
---


## 4. Predictive Machine Learning Framework (Dutch National Police)
*Applied specialized Machine Learning and Data Engineering pipelines to optimize automated anomaly detection and national safety monitoring.*

* **Core Tech:** Python, Scikit-Learn, Feature Vectorization, Pandas, NumPy, Machine Learning Pipelines.
* **Classification:** Classified Government Ecosystem *(Specific operational details and data implementations are strictly confidential)*.

### 💡 Architectural Focus and Methodology
Working within a high-security government environment for the Dutch National Police, I developed a proof-of-concept predictive framework to improve data-driven safety monitoring:
* **Data Engineering:** Designed robust preprocessing loops to securely ingest, clean, and structure high-volume intelligence data using large-scale open-source datasets comprising ~700,000 records.
* **Advanced Feature Engineering:** Implemented high-dimensional vectorization techniques to transform unstructured data inputs into standardized numerical features for model ingestion.
* **Model Optimization & Feature Selection:** Benchmarked and compared **four distinct machine learning architectures** against a 50% baseline accuracy. Developed an iterative feature selection framework, systematically isolating the **top 230 highest-impact predictive features**. 
* **Performance Breakthrough:** Successfully refined the pipeline through exhaustive train-test-evaluate iterations, **driving model performance from the 50% baseline up to a 90% classification accuracy**.

<table width="100%">
  <tr>
    <td width="50%" align="center" valign="top">
      <p><b>3. Research Flow</b></p>
      <img src="research-flow-DutchPolice.png" width="350" style="max-width: 350px; height: auto; alt="Dutch Police Research Structure" />
      <p><i>Note: Original documentation delivered to the Dutch National Police (Translation: Research Phase → Experimenting Phase → Development Phase → Refinement Phase).</i></p>
    </td>
  </tr>
</table>

---

### 5. Deep Packet Inspection & Custom Intrusion Detection (IDS) Lab
*Low-level network security protocol parser designed from scratch to enforce zero-trust filtering and secure subnet boundaries.*
* **Core Focus:** Python, Socket Programming, IAM, Relational Databases, Network Monitoring

#### 💡 Engineering Implementation
To gain a foundational, bit-level understanding of network routing and security boundaries without relying on high-level abstraction libraries, I engineered a custom network monitoring processor simulated for an e-commerce infrastructure environment:
* **Bit-Stream Parsing:** Utilized Python's `struct.unpack` framework to map raw network packets, programmatically unpacking layered network headers directly from the binary payload stream to search for URLs and map this against white-listed URLs kept in a database.
* **Access Control & Threat Detection:** Implemented multi-factor validation logic to verify connection attempts based on destination URL, network location, and authorized MAC/device addresses, automating real-time administrator security alerts upon detection.
<table width="100%">
  <tr>
    <td width="50%" align="center" valign="top">
      <p><b>4. Deep Packet Inspection </b></p>
      <img src="deep-packet-inspection.png" width="350" style="max-width: 350px; height: auto; alt="Architecture of the system." />
            <p><i>Architectural overview of the packet inspection system.</i></p>
    </td>
  </tr>
</table>

---

## ☕ More About Me
When I am not analysing for vulnerabilities or training AI pipelines, you can usually find me:
* 🍳 **Cooking traditional European dishes** and sourcing fresh, seasonal ingredients directly from local organic farmers. I am already looking forward to exploring New Zealand's local markets!
* ☕ **Working on my YouTube channel!** I have a channel with currently **15,000+ subscribers and 900,000+ views** where I share videos about my travel experiences and day-to-day life!
* 🇪🇺 **Polyglot in training:** Native in Dutch, fluent in English (C2), and currently maintaining an intermediate (B1) level in German. 

