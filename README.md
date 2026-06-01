**<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=00ADD8&center=true&vCenter=true&width=500&lines=Hey%2C+I'm+Shraman+%F0%9F%91%8B;Backend+Engineer+%7C+Go+%2B+C;Distributed+Systems+%7C+Storage+Engines;Building+ZENITH+from+first+principles" alt="Typing SVG" />
</div>

<br/>

<div align="center">

[![X](https://img.shields.io/badge/@shramanb113-000?style=flat-square&logo=x&logoColor=white)](https://x.com/shramanb113)&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/shraman-banerjee-385200303)&nbsp;
[![GitHub](https://img.shields.io/badge/github-shramanb113-181717?style=flat-square&logo=github)](https://github.com/shramanb113)

</div>

---

I build systems at the boundary of correctness and performance — storage engines, search infrastructure, distributed coordination. Third-year Mechanical Engineering undergrad at Jadavpur University, Kolkata — writing Go and C while everyone else does CAD.

My approach: read the codebase before touching it. Ship things I can explain from first principles.

---

## 🔭 Anchor Project — ZENITH

> A distributed hybrid search engine built entirely from scratch in Go. No Elasticsearch. No Lucene. Every layer is handwritten.

```
┌─────────────────────────────────────────────────────┐
│                    ZENITH                           │
│                                                     │
│  ┌──────────────┐    ┌──────────────────────────┐  │
│  │  Search Layer│    │     Storage Layer         │  │
│  │              │    │                           │  │
│  │  BM25 Hybrid │    │  LSM Tree + WAL           │  │
│  │  Inverted    │    │  SSTables + Bloom Filter  │  │
│  │  Index       │    │  Compaction Pipeline      │  │
│  │  BK-Tree     │    │                           │  │
│  │  Embeddings  │    └──────────────────────────┘  │
│  └──────────────┘                                   │
│                                                     │
│  ┌─────────────────────────────────────────────┐   │
│  │              Systems Layer                   │   │
│  │  gRPC + Protobuf  │  Raft Consensus          │   │
│  │  Prometheus (WIP) │  Distributed Coord       │   │
│  └─────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────┘
```

**Storage** — LSM tree with Write-Ahead Log, SSTables, Bloom filters for crash-safe persistence. Compaction pipeline to bound read amplification.

**Search** — Inverted index with Porter stemmer + N-gram tokenization. BK-Tree for edit-distance fuzzy matching. Sentence-transformer embeddings + cosine similarity for semantic search. BM25 hybrid ranking fusing lexical and vector scores.

**Systems** — gRPC transport, Raft consensus for distributed coordination, Prometheus instrumentation *(in progress)*.

> Ask me why BK-Trees over a trie, or why BM25 over pure TF-IDF.

---

## 🌱 Open Source Contributions

| Repo | Contribution | Type |
|------|-------------|------|
| [internetarchive/Zeno](https://github.com/internetarchive/Zeno) | Race condition fix + rate limiter improvement · [PR #578](https://github.com/internetarchive/Zeno/pull/578) | `Go` Bug Fix |
| [supabase-community/supabase-go](https://github.com/supabase-community/supabase-go) | SDK improvement · [PR #51](https://github.com/supabase-community/supabase-go/pull/51) | `Go` Enhancement |

**Active sprint:** Contributing to [Kyverno](https://github.com/kyverno/kyverno) across `kyverno`, `chainsaw`, `kyverno-json`, `policy-reporter`, and `website` — targeting 50+ PRs by October 2026 for **LFX Mentorship Term 3** application.

---

## 🗺️ What I'm Building Toward

```
Now          ████████░░  CKAD Certification          → July 2026
             ████░░░░░░  Kyverno OSS Sprint (50 PRs) → October 2026
Q3 2026      ░░░░░░░░░░  CKA Certification           → September 2026
Q4 2026      ░░░░░░░░░░  LFX Mentorship Term 3
2027         ░░░░░░░░░░  GSoC 2027 Application
2027         ░░░░░░░░░░  Internship · Product-focused company
```

Stack I'm going deep on: **Go · C · Kubernetes · distributed systems internals**

---

## 🛠️ Core Stack

```go
// What I actually bet on

languages := []string{"Go", "C", "Python", "Rust"}
infra      := []string{"Kubernetes", "Docker", "gRPC", "Kafka", "Redis"}
observe    := []string{"Prometheus", "Grafana"}
databases  := []string{"PostgreSQL", "Redis", "custom LSM (ZENITH)"}
tools      := []string{"Git", "GitHub Actions", "Linux"}
```

---

## 📊 GitHub Stats

<div align="center">

![Shraman's GitHub Stats](https://github-readme-stats.vercel.app/api?username=shramanb113&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=shramanb113&layout=compact&theme=tokyonight&hide_border=true&langs_count=6)

![GitHub Streak](https://nirzak-streak-stats.vercel.app/?user=shramanb113&theme=tokyonight&hide_border=true)

</div>

---

## ✍️ Writing

I write about what I build — storage engines, search internals, OSS contribution patterns. One post a month. No tutorials. Just implementation notes and design decisions.

Follow along on [X (@shramanb113)](https://x.com/shramanb113)

---

<div align="center">

**Open to backend infrastructure, distributed systems, and DevOps internships.**

*Jadavpur University · Mechanical Engineering · 2024–2028 · Kolkata, India*

</div>
**
