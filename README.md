## Technical Project Portfolio | Enterprise Architecture & Full-Stack Engineering 

## 👋 About Me
I am a solutions-driven Software Developer with more than 3 years of hands-on experience spanning full-stack development, cloud-native AI systems, and enterprise IT infrastructure management. I specialize in building robust, standalone desktop and web solutions, automating critical corporate compliance workflows, and optimizing complex hybrid network environments. Known for taking sole technical ownership of enterprise software lifecycles from concept to deployment.
 
**Developer:** Tsepo Tonny Seroka  
**Target Role:** Mid-Level Software Developer / Senior Software Developer  
**Core Stack:** Custom MVC PHP Framework, Python, Next.js, MySQL, Firebase, RabbitMQ, OpenAI API, Cloud-Native Systems  

---

## 🚀 Enterprise & Production Applications

### 1. Hospital Downtime Business Continuity Application
- **Environment:** Steve Biko Academic Hospital (Clinical Infrastructure)  
- **Role:** Lead Software Developer (End-to-End SDLC)  
- **Tech Stack:** Custom MVC PHP Framework, JavaScript, HTML5/CSS3, PHP Desktop (Chromium/Mongoose Embedded Engine), Inno Setup Installer  

#### 📋 Project Overview
Designed and engineered a standalone, portable desktop application to maintain critical hospital operations during total SAP network or server outages. The application allows healthcare staff to continue localized patient registration and high-speed medical labelling.

#### 🛠️ Architectural & Technical Challenges Solved
- **Hardware Interoperability Edge-Case:** Faced severe challenges with diverse Zebra barcode printer models, conflicting print drivers, and strict layout dimensions for tiny medical stickers. Solved this by writing precise raw print-stream configurations to ensure pixel-perfect layout uniformity across varying physical hardware form factors.  
- **Portable Desktop Packaging:** Leveraged PHP Desktop to compile a standard web application stack into an isolated, zero-dependency desktop runtime.  
- **Zero-Configuration Deployment:** Utilized Inno Setup to pack the entire runtime, custom MVC framework, and web assets into a single executable installer, allowing rapid distribution to non-technical hospital staff via portable media.  

#### 📈 Value Delivered
- Guaranteed absolute continuity of patient check-in workflows during server blackouts, eliminating data loss and clinical downtime.  
- *Note: Due to public health compliance and institutional security, only the decoupled web-layer framework architecture is showcased publicly.*

---

### 2. RWOPS (Remunerative Work Outside Public Service) Enterprise System
- **Environment:** Steve Biko Academic Hospital (Internal Administration)  
- **Role:** Lead Full-Stack Developer  
- **Tech Stack:** Custom MVC PHP Framework, MySQL, PHPMailer, jQuery, Bootstrap, JavaScript  

#### 📋 Project Overview
Conceptualized and built a secure, digital compliance workflow system to replace the highly inefficient, error-prone paper application processes required for public service hospital personnel performing external remunerative work.

#### 🛠️ Architectural & Technical Challenges Solved
- **Data Loss Mitigation:** Re-engineered fragmented physical paper routing into an ACID-compliant transactional MySQL structure, securing records from destruction or misplacement.  
- **Executive Decision-Support Engine:** Architected interactive administrative dashboards that aggregate personnel allocation, historical request telemetry, and institutional metrics. This empowered the CEO and executive board to make data-driven compliance approvals.  
- **Scalable Framework Design:** Built from the ground up on a proprietary, lightweight MVC PHP architecture optimized for potential national public health deployment.  

#### 📈 Value Delivered
- Drastically reduced operational application routing latency while establishing an immutable digital audit trail.  
- *Note: This application handles sensitive governance compliance data and is under strict institutional testing; the source code remains proprietary, but systemic workflows can be demonstrated during technical interviews.*

---

### 3. Anita 2.0 – AI Legal Assistant Web-Chatbot
- **Environment:** Brand Ibex (Lawfinder)  
- **Link:** [Live Application Preview](https://www.lawfinder.co.za/)  
- **Role:** Lead Application Developer  
- **Tech Stack:** Python, OpenAI API, Vector Databases (RAG), Custom MVC PHP Framework, jQuery, Bootstrap  

#### 📋 Project Overview
An advanced, multi-turn AI legal intelligence platform supporting all 11 official South African languages, tailored to translate dense legal frameworks for practicing attorneys, law students, and corporate entities.

#### 🛠️ Architectural & Technical Challenges Solved
- **Infrastructure Scaling Bottleneck (Ollama to Cloud Migration):** Version 1.0 utilized an on-premises Linux server running localized Ollama (Llama 3.3) models. As user traffic surged, it completely throttled physical hardware constraints.  
- **Ground-Up System Re-Architecture:** Rather than executing a surface-level API switch, spearheaded a comprehensive system rebuild. Re-engineered core pipelines to ingest external enterprise cloud architecture, integrating highly optimized Retrieval-Augmented Generation (RAG) vectors and fine-tuning configurations.  
- **Context Preservation:** Developed robust Python-based middleware to maintain conversational memory matrices across complex, multi-lingual sessions without memory leaks.  

#### 📈 Value Delivered
- Successfully scaled a resource-constrained local prototype into a low-latency, commercialized enterprise AI platform capable of parsing highly nuanced localized legal data.

---

### 4. Ibex Mailer – Asynchronous Enterprise Marketing Ecosystem
- **Environment:** Brand Ibex (Lawfinder) — Decommissioned Legacy Case Study  
- **Role:** Lead Backend Developer  
- **Tech Stack:** Next.js, Custom MVC PHP Framework, RabbitMQ, MySQL, PHPMailer, RESTful APIs  

#### 📋 Project Overview
A complex, highly decoupled multi-channel digital marketing engine featuring a custom canvas-style template editor, automated bulk delivery queues, and real-time user engagement analytics.

#### 🛠️ Architectural & Technical Challenges Solved
- **Cross-Framework Microservice Bridge:** Tasked with integrating Easy Email (an open-source editor built on a completely separate Next.js/React environment) into a custom MVC PHP backend. Overcame this by rewriting segments of the Next.js core and developing high-throughput RESTful API handshakes to sync template state data seamlessly.  
- **Message Queueing & Delivery Stability:** Implemented RabbitMQ to handle intensive asynchronous mailing batches. This safeguarded system stability by decoupling the template rendering process from active delivery queues, avoiding server crashes during high-volume operations.  
- **Custom Dynamic Routing:** Designed an automated transformation engine where user templates exported to social platforms transformed dynamically into ultra-lightweight, self-contained landing pages containing tracking pixels and telemetry webhooks.  

#### 💡 Post-Mortem Engineering Insights
- While the project was successfully built and passed rigorous performance criteria, it was eventually decommissioned due to high cloud maintenance overheads and shifting market monetization.  
- The source code is unavailable, but this project serves as a cornerstone demonstration of my capability to handle complex asynchronous data pipelines, third-party library source modifications, and enterprise message brokers.

---

## 🧪 Open-Source & Experimental Initiatives

### 5. Smart-Shopper – Serverless Grocery Analytics
- **Source & Live Deployment:** [Live Demo](https://sudobreaker.github.io/smart-shopper/)  
- **Role:** Independent Creator  
- **Tech Stack:** JavaScript (ES6+), Firebase Firestore, HTML5, CSS3  

#### 📋 Project Overview
A lightweight, high-utility progressive web application (PWA) designed to track kitchen inventory cycles (stocked, low, depleted) and perform predictive pricing calculations based on a user's historical shopping data across multiple retail chains.

#### 🛠️ Architectural & Technical Challenges Solved
- **Minimalist Architecture Optimization:** Designed the application to test the boundary limits of client-side JavaScript combined with serverless NoSQL databases (Firebase Firestore), completely bypassing a heavy backend server.  
- **Predictive Pricing Engine:** Developed local algorithmic handlers to store, clean, and map multi-merchant pricing points over time, outputting data-driven shopping advice to maximize cost efficiency.  
- **Data Portability:** Authored pure JavaScript modules to export aggregated data packets directly into cross-compatible flat files for consumer utility.
