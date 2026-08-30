<h1 align="center">hey, I'm Ankitha 👋</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/ankitha-gangavarapu/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=flat&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://ankithadeviportfolio.netlify.app/">
    <img src="https://img.shields.io/badge/Portfolio-Visit-1D9E75?style=flat&logo=netlify&logoColor=white" />
  </a>
  &nbsp;
  <a href="mailto:ankithadevig@gmail.com">
    <img src="https://img.shields.io/badge/Email-ankithadevig@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" />
  </a>
</p>

---

**Part one:** B.Tech CS @ SRM India. learned to code, fell into ML, didn't look back.

**Part two:** MS Computer Science @ **Arizona State University** 🌵 — GPA 3.7, specializing in ML systems and cloud infrastructure. the problems got harder. I got better.

I don't just train models. I deploy them, benchmark them, and make sure they survive contact with real traffic.
And I'd rather spend a week understanding a system deeply than ship something I can't explain.

---

## 🛠️ what I work with

```python
ankitha = {
  "ML / AI"   : ["PyTorch", "HuggingFace", "PEFT/LoRA", "RLHF", "TRL", "MONAI", "Scikit-learn", "W&B", "Langchain"],
  "backend"   : ["FastAPI", "WebSockets", "REST", "GraphQL", "gRPC"],
  "cloud"     : ["AWS Lambda", "EC2", "S3", "SQS", "DynamoDB", "API Gateway", "CloudWatch"],
  "data"      : ["PostgreSQL", "MySQL", "Redis", "Pandas", "NumPy"],
  "infra"     : ["Docker", "Kubernetes", "Linux", "Git"],
  "languages" : ["Python", "Java", "JavaScript", "SQL", "C"],
}
```

---

## 🚀 things I've actually built 

### 🧠 LLM Fine-Tuning Pipeline — LoRA + RLHF
Fine-tuned a 7B-parameter LLM from scratch. Not a wrapper. Not a tutorial.
Full pipeline: SFT → reward model on preference pairs → PPO optimization with KL penalty.
LoRA cut trainable parameters by **~99%** without hurting task performance.
Wrapped it in a FastAPI inference server. Benchmarked at FP16, INT8, INT4.

`PyTorch` `HuggingFace` `PEFT` `TRL` `W&B` `FastAPI` → [View repo](https://github.com/Ankitha101003/LLM-Fine-Tuning)

---

### 🔬 Vision Transformer — Medical Image Segmentation
Swin-UNet for multi-class organ segmentation. **92% Dice coefficient** on Medical Segmentation Decathlon, within a 16GB GPU budget.
Full augmentation pipeline. Evaluated on Dice, Hausdorff distance, and per-class IoU — because one metric is never enough.

`PyTorch` `MONAI` `HuggingFace` `Swin-Transformer` → [View repo](https://github.com/Ankitha101003/Vision-Transformer-for-Medical-Image-Segmentation)

---

### ⚡ Distributed Rate Limiter Service
Three algorithms (Token Bucket, Sliding Window Log, Fixed Window Counter) in one service.
Redis atomic Lua scripts for race-condition-free counters — **sub-millisecond p99 latency, 10K+ req/s per node**.
Deployed on EC2 behind an ALB. Load tested with Locust until it stopped being interesting.

`Python` `FastAPI` `Redis` `Docker` `AWS EC2` → *(repo coming soon)*

---

### 🔗 URL Shortener with Real-Time Analytics
5,000+ redirects/minute under load. Read-through Redis cache with stampede prevention — **90% drop in database reads**.
Live WebSocket analytics dashboard. Click logs archived to S3, Athena-queryable Parquet partitions.
Built the base-62 encoding and collision-resistant ID scheme myself. Yes, there are tests.

`Python` `FastAPI` `PostgreSQL` `Redis` `AWS S3` `WebSockets` → *(repo coming soon)*

---

### 💬 Real-Time Serverless Chat App
React + AWS serverless (API Gateway WebSockets, Lambda, DynamoDB). Built during my internship at Augusta Hitech, shipped to production.
Exponential backoff. Idempotent handlers. Custom CloudWatch metrics.
The kind of details that matter when things break at 2am.

`React` `AWS Lambda` `DynamoDB` `API Gateway` `CloudWatch` → [View repo](https://github.com/Ankitha101003/ReactChatApp)

---

## 🎲 a few things that make me, me

🇯🇵 **currently learning Japanese** — because picking up a new language is the fastest way I know to rewire how you think. already deep in the grammar rabbit hole and mildly obsessed with the culture. 

🏋️ **sports & fitness are my reset button** — when I need to stop using my brain, I go move my body. no spreadsheet, no optimization, just effort. it's the one part of my life I deliberately keep unanalyzed.

🎬 **I binge movies and series** — I binge watch a lott, can't help it. horror is my genre of choice (yes, I will always suggest the horror movie). I'm great at horror movie nights.

🎲 friends & mindless fun are mandatory — I don't care what we're doing as long as it's fun and nobody's overthinking it. no itinerary, no plan, just show up and figure it out. best kind of hangout.

---

## 📬 let's talk

Open to conversations about interesting problems.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ankitha--gangavarapu-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ankitha-gangavarapu/)
[![Portfolio](https://img.shields.io/badge/Portfolio-ankithadeviportfolio.netlify.app-1D9E75?style=flat-square)](https://ankithadeviportfolio.netlify.app/)
[![Email](https://img.shields.io/badge/Email-ankithadevig@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ankithadevig@gmail.com)

*scroll down — the repos are right there* 👇
