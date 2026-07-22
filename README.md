<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4F46E5,100:7C3AED&height=220&section=header&text=Shraman%20Banerjee&fontSize=42&fontColor=ffffff&desc=AI%20Infrastructure%20Engineer&descAlignY=75&descSize=16" alt="header banner" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=7C3AED&center=true&vCenter=true&width=650&lines=Building+distributed+systems+from+first+principles;Now%3A+Kubernetes+%2B+agentic+AI+infrastructure;Contributing+to+the+Mastra+agent+framework+ecosystem" alt="Typing SVG" />

<br/>

<img src="https://img.shields.io/badge/Jadavpur_University-Mechanical_Engineering_%2724--%2728-4F46E5?style=for-the-badge" />
<img src="https://img.shields.io/badge/Kolkata%2C_India-8B5CF6?style=for-the-badge&logo=googlemaps&logoColor=white" />

<br/><br/>

<a href="https://linkedin.com/in/shramanb113" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-4F46E5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://x.com/shramanb113" target="_blank"><img src="https://img.shields.io/badge/X-1a1a2e?style=for-the-badge&logo=X&logoColor=white" /></a>
<a href="mailto:shramanbanerjee9@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/shramanb113" target="_blank"><img src="https://img.shields.io/badge/GitHub-1a1a2e?style=for-the-badge&logo=github&logoColor=white" /></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=shramanb113&color=7c3aed&style=for-the-badge&label=PROFILE+VIEWS" />
<img src="https://img.shields.io/github/followers/shramanb113?style=for-the-badge&color=4F46E5&labelColor=1a1a2e&label=FOLLOWERS" />

</div>

---

### 🧭 About

Third-year Mechanical Engineering student at Jadavpur University who taught himself backend and systems engineering — WAL, LSM trees, gRPC, compaction — because that's what it took to build ZENITH from scratch. Now moving deliberately into AI infrastructure: agent frameworks, retrieval systems, and Kubernetes-native observability, rather than generic AI-app work. Core member of the JU ACM Student Chapter (AI & Blockchain division). Builds in public.

**Open to:** remote AI-infrastructure engineering roles · backend / distributed-systems internships

---

### 🛠️ Toolbox

<p>
<img src="https://img.shields.io/badge/-Go-4F46E5?style=flat-square&logo=go&logoColor=white" />
<img src="https://img.shields.io/badge/-TypeScript-7C3AED?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/-Java-4F46E5?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/-C-7C3AED?style=flat-square&logo=c&logoColor=white" />
<img src="https://img.shields.io/badge/-Kubernetes-4F46E5?style=flat-square&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/-Docker-7C3AED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/-gRPC-4F46E5?style=flat-square&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/-PostgreSQL-7C3AED?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/-Prometheus-4F46E5?style=flat-square&logo=prometheus&logoColor=white" />
<img src="https://img.shields.io/badge/-GitHub_Actions-7C3AED?style=flat-square&logo=github-actions&logoColor=white" />
<img src="https://img.shields.io/badge/-Linux-4F46E5?style=flat-square&logo=linux&logoColor=white" />
<img src="https://img.shields.io/badge/-Git-7C3AED?style=flat-square&logo=git&logoColor=white" />
</p>

---

### 🤖 Where AI / agentic work shows up

| Area | Evidence |
|---|---|
| Semantic search & retrieval | ZENITH — ONNX embeddings fused with BM25 via weighted RRF, Recall@10 0.812 → 0.906 |
| Agentic frameworks | Building **Argus** on the **Mastra** framework (agent orchestration + RAG pipeline) |
| RAG systems | **Argus** *(in progress)* — incident root-cause agent mesh, Mastra + pgvector |
| GSoC track | Targeting **C2SI's b0bot** for GSoC 2027 |

---

### 🔭 Featured Projects

<details>
<summary><b>⚡ ZENITH</b> — embeddable hybrid search engine, written from scratch in Go</summary>
<br/>

Custom LSM storage engine (WAL → MemTable → SSTable → leveled compaction), inverted posting lists, BM25 lexical ranking fused with ONNX-based semantic retrieval via weighted Reciprocal Rank Fusion, served over gRPC with Prometheus instrumentation and a Cobra CLI.

| Stack | Scale | Performance | Repository |
|---|---|---|---|
| Go, gRPC, ONNX, Prometheus | ~120 commits · 29 stars · MS MARCO 100k passages | Recall@10 0.812→0.906 · BM25 latency 284ms→177ms | [ZENITH](https://github.com/shramanb113/ZENITH) |

</details>

<details>
<summary><b>🔍 Argus</b> — incident root-cause agent mesh <i>(in progress)</i></summary>
<br/>

Standalone project (not built on ZENITH). Committed to a Mastra/TypeScript end-to-end stack with plain vector RAG via Mastra's built-in pipeline and pgvector as the vector store.

| Stack | Status |
|---|---|
| Mastra, TypeScript, pgvector | Architecture decided — build in progress |

</details>

---

### 🌱 Open Source

<table>
  <thead align="center">
    <tr><td><b>📦 Repo</b></td><td><b>🔧 What I did</b></td></tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/internetarchive/Zeno"><b>internetarchive/Zeno</b></a></td>
      <td>Race condition fix · <a href="https://github.com/internetarchive/Zeno/pull/578">PR #578 merged</a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/supabase-community/supabase-go"><b>supabase-community/supabase-go</b></a></td>
      <td>SDK improvement · <a href="https://github.com/supabase-community/supabase-go/pull/51">PR #51 merged</a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/kyverno/kyverno"><b>kyverno/kyverno</b></a> <i>(active)</i></td>
      <td>Kubernetes policy engine (CNCF)</td>
    </tr>
  </tbody>
</table>

---

### 🏆 Recognition

<div align="center">

| Recognition | Details |
|---|---|
| IEEE JUSB — DoubleSlash Hackathon | Finalist, 750+ participant field |

</div>

---

### 🗺️ Roadmap

```yaml
current_focus:
  learning:
    - Agentic AI architectures via Mastra
    - Kubernetes-native observability patterns
  building:
    - Argus — incident root-cause agent mesh (Mastra + pgvector)
    - Kubernetes SRE copilot template (Mastra ecosystem)
  exploring:
    - GSoC 2027 with C2SI (b0bot)
  open_to:
    - Remote AI infrastructure engineering roles
    - Backend / distributed systems internships
```

```
Now  →  Q3 2026   Mastra Kubernetes SRE copilot — merge + Argus build-out
        Q3 2026   CKAD certification
        Q3 2026   CKA certification
        Q4 2026   LFX Mentorship Term 3 application
        2027      GSoC 2027 — targeting C2SI (b0bot)
        2027      Remote AI-infrastructure engineering role
```

---

### 📈 GitHub Analytics

<p align="center">
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=shramanb113&theme=tokyonight" alt="profile summary" />
</p>
<p align="center">
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=shramanb113&theme=tokyonight" alt="languages" />
</p>
<p align="center">
<img src="https://streak-stats.demolab.com?user=shramanb113&theme=dark&hide_border=true&background=0D1117&ring=7C3AED&fire=8B5CF6&currStreakLabel=7C3AED" alt="streak stats" />
</p>

<p align="center">
<img src="https://github-profile-trophy.vercel.app/?username=shramanb113&theme=discord&no-frame=true&row=1&column=4" alt="trophies" />
</p>

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=shramanb113&theme=react-dark&hide_border=true&bg_color=0D1117&color=8B5CF6&line=7C3AED&point=C4B5FD" alt="activity graph" />
</p>

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/shramanb113/shramanb113/output/github-contribution-grid-snake-dark.svg" />
  <img alt="snake" src="https://raw.githubusercontent.com/shramanb113/shramanb113/output/github-contribution-grid-snake.svg" />
</picture>
</p>

---

### ✍️ Writing

Implementation notes on storage engines, search algorithms, and OSS contribution patterns — one post a month, no tutorials. Follow along on [X (@shramanb113)](https://x.com/shramanb113).

---

### 📫 Connect

<p align="center">
<a href="mailto:shramanbanerjee9@gmail.com"><img src="https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://linkedin.com/in/shramanb113"><img src="https://img.shields.io/badge/LinkedIn-4F46E5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/shramanb113"><img src="https://img.shields.io/badge/GitHub-1a1a2e?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<div align="center">
<sub><i>Systems I can explain from first principles, not frameworks I can't open up.</i></sub>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,100:4F46E5&height=100&section=footer" />
