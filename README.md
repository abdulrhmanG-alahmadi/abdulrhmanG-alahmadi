<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.png">
  <img alt="Abdulrhman Alahmadi — Practical AI. Useful software. AI / Data / Web." src="assets/banner.png" width="1200">
</picture>

<div align="center">

**I build practical tools across AI, data, and the web.**  
Jeddah, Saudi Arabia · From a useful idea to working software.

[Explore projects](#selected-work) · [Project demos](#project-demos) · [Portfolio ↗](https://alahmadi.me/)

</div>

## Selected work

### 01 / TriageKit

<a href="https://github.com/abdulrhmanG-alahmadi/triagekit-oss">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/triagekit-cover.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/triagekit-cover-light.svg">
  <img alt="TriageKit — reliable LLM workflows. TypeScript, Bun and PostgreSQL." src="assets/triagekit-cover.svg" width="1200">
</picture>
</a>

**A support ticket goes in. A validated classification comes back.**

**Problem:** Slow or unavailable model providers should not lose accepted tickets.  
**Approach:** Persist work in PostgreSQL; classify in a separate worker with validation, bounded retries, and recovery.  
**Evidence:** Runnable offline demo, integration tests, and reclassification history. The demo uses a deterministic fake provider; it is not a live-model accuracy benchmark.

[Source ↗](https://github.com/abdulrhmanG-alahmadi/triagekit-oss) · [Run the demo](https://github.com/abdulrhmanG-alahmadi/triagekit-oss#start-offline) · [Design decisions](https://github.com/abdulrhmanG-alahmadi/triagekit-oss/blob/HEAD/docs/design.md)

### 02 / Leadline

<a href="https://github.com/abdulrhmanG-alahmadi/leadline">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/leadline-cover.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/leadline-cover-light.svg">
  <img alt="Leadline — local business discovery. Bun, Elysia and Vite." src="assets/leadline-cover.svg" width="1200">
</picture>
</a>

**Find businesses. Filter the results. Export a useful list.**

**Problem:** Repeated searches and manual contact collection slow down prospecting.  
**Approach:** A local dashboard combines Google Places searches, contact filters, and CSV export.  
**Evidence:** Existing dashboard preview and runnable source for Jeddah, Khobar, and Riyadh. Local setup requires a Google Places API key.

[Source ↗](https://github.com/abdulrhmanG-alahmadi/leadline) · [Dashboard preview](#leadline-dashboard) · [Run locally](https://github.com/abdulrhmanG-alahmadi/leadline#the-easy-way-macos)

### 03 / EduVision

<a href="https://github.com/abdulrhmanG-alahmadi/AI-Classroom-Engagement-Analysis">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/eduvision-cover.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/eduvision-cover-light.svg">
  <img alt="EduVision — classroom video exploration. Python, PyTorch and MediaPipe." src="assets/eduvision-cover.svg" width="1200">
</picture>
</a>

**Explore visible patterns in video with computer vision.**

**Problem:** Long recordings are difficult to review frame by frame.  
**Approach:** Detect and crop people, estimate head pose and raised hands, detect phones, and summarize saved outputs.  
**Evidence:** Python pipeline, desktop launcher, and body-pose notebook. This is a research prototype; visible activity is not a validated measure of attention or learning.

[Source ↗](https://github.com/abdulrhmanG-alahmadi/AI-Classroom-Engagement-Analysis) · [Pipeline](#eduvision-pipeline) · [Notebook](https://github.com/abdulrhmanG-alahmadi/AI-Classroom-Engagement-Analysis/blob/HEAD/Body%20Pose%20Train%20and%20Data.ipynb)

## Project demos

### TriageKit offline run

![Recorded TriageKit API demo using synthetic input and the fake provider](assets/triagekit-demo.svg)

[Read the captured request and response](assets/triagekit-demo.json) · [Reproduce locally](https://github.com/abdulrhmanG-alahmadi/triagekit-oss#start-offline)

### Leadline dashboard

<details>
<summary>Open the existing dashboard screenshot</summary>

<a href="https://github.com/abdulrhmanG-alahmadi/leadline/blob/HEAD/docs/leadline-dashboard.png"><img src="https://raw.githubusercontent.com/abdulrhmanG-alahmadi/leadline/HEAD/docs/leadline-dashboard.png" alt="Leadline dashboard showing city and business filters, contact results, and Export CSV." width="760"></a>

Existing screenshot from the project repository. This is a static product preview; no live search runs on this profile.

</details>

### EduVision pipeline

![EduVision architecture: video frames, person detection, pose and phone analysis, visual summaries](assets/eduvision-pipeline.svg)

Architecture illustration. A detection recording is not included because the repository has no bundled sample footage.

## Skills, with evidence

| Focus | Tools used | See the work |
| :--- | :--- | :--- |
| Reliable AI workflows | TypeScript · Bun · Elysia · PostgreSQL · Docker | [TriageKit](https://github.com/abdulrhmanG-alahmadi/triagekit-oss#architecture) |
| Useful web tools | Bun · Vite · Google Places API | [Leadline](https://github.com/abdulrhmanG-alahmadi/leadline#architecture) |
| Computer vision | Python · PyTorch · MediaPipe · OpenCV | [EduVision](https://github.com/abdulrhmanG-alahmadi/AI-Classroom-Engagement-Analysis#architecture) |
| Data exploration | pandas · Seaborn · Jupyter | [Prosper Loan Analysis](https://github.com/abdulrhmanG-alahmadi/Communicate-Data-Findings) |

## More work

- **[Prosper Loan Analysis](https://github.com/abdulrhmanG-alahmadi/Communicate-Data-Findings)** — explore 113,937 loans through statistical visualizations.
- **[Mashoorah](https://github.com/abdulrhmanG-alahmadi/Mashoorah-Saudichatgpt-hackathon)** — an Arabic investing-education hackathon concept, with Figma designs and a presentation.
- **[Airline Pilot Manager](https://github.com/abdulrhmanG-alahmadi/Airline-Pilot-Management-System)** — a Java console exercise in inheritance, interfaces, and collections.

---

<div align="center">

**Practical AI. Useful software.**  
[Portfolio ↗](https://alahmadi.me/) · [X / Twitter](https://x.com/abdulrhman_ai) · [All repositories](https://github.com/abdulrhmanG-alahmadi?tab=repositories)

</div>
