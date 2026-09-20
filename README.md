<div align="center">

# Hi, I'm Pranay 👋

**Building intelligent systems that move from research to real-world deployment.**

`Autonomous Agents` &nbsp;•&nbsp; `Edge Computer Vision` &nbsp;•&nbsp; `LLM Evals` &nbsp;•&nbsp; `Systems`

<a href="https://linkedin.com/in/pranaysb"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" height="22" alt="LinkedIn" /></a>
<a href="mailto:pranaysb2006@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat&logo=gmail&logoColor=white" height="22" alt="Gmail" /></a>

</div>

---
- Leading **Optisense AI** — vision-sensing prototype  for production
- Researched at the **Visual Intelligence and Learning Lab, IIT Hyderabad**
- Shipping fixes upstream to **NVIDIA**, **OpenTelemetry**, **Roboflow**, **Voxel51**, **Kornia** and **MTEB**

## 🌍 Open Source

<div align="center">

![Merged PRs](https://img.shields.io/badge/merged_PRs-18-2ea44f?style=for-the-badge&logo=git&logoColor=white)
![Repositories](https://img.shields.io/badge/repositories-7-8957e5?style=for-the-badge&logo=github&logoColor=white)
![Lines added](https://img.shields.io/badge/lines_added-%2B1,621-238636?style=for-the-badge)
![Lines removed](https://img.shields.io/badge/lines_removed-%E2%88%92197-da3633?style=for-the-badge)

</div>

18 merged pull requests across 7 widely-used projects — memory leaks, crash fixes, correctness bugs and reliability gaps in production frameworks. Every entry links to the real merged PR.

| Project | Merged | Focus |
| :-- | :-: | :-- |
| [**NVIDIA/NeMo-Agent-Toolkit**](https://github.com/NVIDIA/NeMo-Agent-Toolkit) | 4 | OAuth2 flow isolation, `lru_cache` memory leaks, finetuning CLI overrides |
| [**embeddings-benchmark/mteb**](https://github.com/embeddings-benchmark/mteb) | 4 | Score aggregation across splits, Pydantic 2.11 deprecation, Ruff rules, citation fixes |
| [**voxel51/fiftyone**](https://github.com/voxel51/fiftyone) | 3 | Cityscapes annotations, field-name validation, info-dict serialization |
| [**open-telemetry/opentelemetry-python**](https://github.com/open-telemetry/opentelemetry-python) | 2 | `Context` immutability bypass, `os.fork()` TypeError for GC'd processors |
| [**roboflow/trackers**](https://github.com/roboflow/trackers) | 2 | `cv2.resize` crash on tiny images, zero-division in box converter |
| [**roboflow/supervision**](https://github.com/roboflow/supervision) | 2 | float64 / arbitrary dtypes in polygon utils, integer overflow in `scale_boxes` |
| [**kornia/kornia**](https://github.com/kornia/kornia) | 1 | `drop_path` typo in DeDoDe transformer block |

<details>
<summary><b>All 18 merged pull requests</b></summary>

<br/>

| # | Repository | Pull request | Diff |
| :-: | :-- | :-- | :-- |
| 1 | NVIDIA/NeMo-Agent-Toolkit | [#2165 — isolate OAuth2 client per flow in console/MCP auth handler](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2165) | +134 −1 |
| 2 | NVIDIA/NeMo-Agent-Toolkit | [#2103 — apply CLI config overrides in finetuning runtime](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2103) | +137 −13 |
| 3 | NVIDIA/NeMo-Agent-Toolkit | [#2105 — fix memory leak lru cache](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2105) | +107 −72 |
| 4 | NVIDIA/NeMo-Agent-Toolkit | [#2118 — resolve lru_cache memory retention in DiscoveryMetadata](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2118) | +43 −7 |
| 5 | voxel51/fiftyone | [#8163 — visible bbox and visibility ratio in Cityscapes person annotations](https://github.com/voxel51/fiftyone/pull/8163) | +105 −1 |
| 6 | voxel51/fiftyone | [#8145 — warn `pk` as an invalid field name](https://github.com/voxel51/fiftyone/pull/8145) | +79 −1 |
| 7 | voxel51/fiftyone | [#8379 — serialize untyped info dict values properly](https://github.com/voxel51/fiftyone/pull/8379) | +68 −0 |
| 8 | open-telemetry/opentelemetry-python | [#5399 — fix Context in-place mutability bypass via inherited dict methods](https://github.com/open-telemetry/opentelemetry-python/pull/5399) | +38 −2 |
| 9 | open-telemetry/opentelemetry-python | [#5453 — fix TypeError in `os.fork()` for garbage-collected processors](https://github.com/open-telemetry/opentelemetry-python/pull/5453) | +135 −5 |
| 10 | roboflow/trackers | [#488 — prevent `cv2.resize` crash on tiny downscaled images](https://github.com/roboflow/trackers/pull/488) | +132 −8 |
| 11 | roboflow/trackers | [#485 — prevent zero division in `xcycsr_to_xyxy` converter](https://github.com/roboflow/trackers/pull/485) | +103 −54 |
| 12 | roboflow/supervision | [#2542 — support float64 and arbitrary dtypes in polygon utilities](https://github.com/roboflow/supervision/pull/2542) | +140 −4 |
| 13 | roboflow/supervision | [#2541 — prevent integer overflow in `scale_boxes`](https://github.com/roboflow/supervision/pull/2541) | +179 −8 |
| 14 | kornia/kornia | [#3781 — resolve `drop_path` typo in DeDoDe transformer block](https://github.com/kornia/kornia/pull/3781) | +1 −1 |
| 15 | embeddings-benchmark/mteb | [#4897 — isolate splits when aggregating scores in aggregated tasks](https://github.com/embeddings-benchmark/mteb/pull/4897) | +208 −9 |
| 16 | embeddings-benchmark/mteb | [#4893 — fix Pydantic 2.11 deprecation warning](https://github.com/embeddings-benchmark/mteb/pull/4893) | +1 −1 |
| 17 | embeddings-benchmark/mteb | [#4890 — add missing arXiv ID and publication year for mFollowIR citations](https://github.com/embeddings-benchmark/mteb/pull/4890) | +4 −4 |
| 18 | embeddings-benchmark/mteb | [#5380 — enable ANN205 (missing-return-type-static-method) Ruff rule](https://github.com/embeddings-benchmark/mteb/pull/5380) | +7 −6 |

</details>

## 🛠️ Selected projects

| Project | What it is | Stack |
| :-- | :-- | :-- |
| [**API Forge AI**](https://github.com/pranaysb/API-Forge-AI) | Agentic SDK generation platform | FastAPI · Next.js · PostgreSQL · Docker · LangGraph |
| [**AgencyOS AI**](https://github.com/pranaysb/agencyOS-ai) | AI-powered influencer agency workflow | n8n · Supabase · Next.js · Groq |
| [**Autonomous Driving VQA**](https://github.com/pranaysb/VQA-Blip-model) | Fine-tuning BLIP on driving scenes with semantic evaluation | Python · PyTorch · BLIP · BERTScore |
| [**IPL Verse**](https://github.com/ujwal209/iplverse) | Full-stack daily IPL gaming platform | Next.js · Supabase · PostgreSQL · Groq |

## 📊 GitHub activity

<div align="center">
  <img src="./assets/github-stats.svg" alt="GitHub Analytics" width="100%" />
</div>
