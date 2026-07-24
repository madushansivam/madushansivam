<img width="100%" src="./assets/header.svg" alt="Madushan Samayasivam — DevOps Engineer"/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-f0883e?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/madushansivam)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-f0883e?style=flat-square&logo=safari&logoColor=white)](https://madushansivam.github.io/portfolio/)
[![Email](https://img.shields.io/badge/Email-Reach_Me-f0883e?style=flat-square&logo=gmail&logoColor=white)](mailto:madushansivam@gmail.com)
[![Followers](https://img.shields.io/github/followers/madushansivam?label=Followers&style=flat-square&color=f0883e)](https://github.com/madushansivam)
![Profile Views](https://komarev.com/ghpvc/?username=madushansivam&label=Profile+Views&color=f0883e&style=flat-square)

</div>

---

## 🧬 `$ cat /etc/madushan.yaml`

```yaml
# ─────────────────────────────────────────────────────────────
# /etc/madushan.yaml — DevOps Engineer Identity Config
# Last updated: 2026-07-23 | Version: 4.0.0 | Status: ACTIVE
# ─────────────────────────────────────────────────────────────

identity:
  name: Madushan Samayasivam
  role: DevOps Engineer
  location: Badulla, Sri Lanka
  email: madushansivam@gmail.com
  education: HNDIT @ SLIATE ATI Badulla (final year)
  studio: Nanmin Game Studio          # Founded — games are my creative lab

professional_stack:
  os:           Fedora Linux           # daily driver, not Ubuntu
  containers:   [ Docker, docker-compose ]
  ci_cd:        [ GitHub Actions, Jenkins ]
  cloud:        [ AWS, Azure ]
  scripting:    [ Bash, Python, Go, Rust ]
  monitoring:   [ learning: Prometheus, Grafana ]
  iac:          [ Terraform ]
  version_ctrl: [ Git ]
  web_server:   [ Nginx ]

currently_shipping:
  - infra-auditor-cli — Go concurrency + GitHub API auditing (Stage 1 of a 3-part trilogy)
  - AutoTest — autonomous LLM-driven web testing agent (final year project, shipped)
  - Kubernetes (k8s) — cluster fundamentals
  - German language (A1 to A2)

targets:
  short_term: DevOps internship (remote or on-site)
  long_term:  [ Germany, Sweden ]     # Europe — this is the mission

philosophy: "Automate the boring. Ship the meaningful. Build the unforgettable."
```

---

## ⚙️ `$ kubectl describe pipeline madushan-devops-workflow`

<img src="./assets/pipeline.svg" width="100%" alt="Animated CI/CD Pipeline: source, build, test, deploy, production"/>

---

## 🐳 `$ cat Dockerfile.madushan`

```dockerfile
# =====================================================
#  Madushan Samayasivam — DevOps Engineer Build Image
#  Base: Fedora 44 | Arch: multi-platform
#  Verified live from my own machine — not a template guess
# =====================================================

FROM fedora:44 AS base

LABEL maintainer="madushansivam@gmail.com" \
      role="DevOps Engineer" \
      location="Sri Lanka" \
      studio="Nanmin Game Studio"

RUN dnf install -y \
    docker git bash python3 nginx curl \
    golang rust cargo nodejs npm python3-pip

COPY .github/workflows/*.yml /workspace/pipelines/
ENV GITHUB_ACTIONS=true CI=true

ENV STUDIO="Nanmin Game Studio"
ENV GAME_STACK="Vanilla JS Canvas · Three.js · GSAP · WebGL"

EXPOSE 9090    # Prometheus
EXPOSE 3000    # Grafana
EXPOSE 8080    # Application

CMD ["automate", "--everything", "--ship", "--never-stop-learning"]

# Build: docker build -t madushan:devops .
# Run:   docker run --rm madushan:devops
```

---

## 🔍 `$ ./verify-system.sh`

```
--- SYSTEM DEV TOOLS (checked live, not templated) ---
✅ docker:    Docker version 29.6.0, build 1.fc44
✅ terraform: Terraform v1.15.8
✅ python3:   Python 3.14.6
✅ pip3:      pip 26.0.1 (python 3.14)
✅ git:       git version 2.55.0
✅ node:      v22.22.2
✅ npm:       10.9.7
✅ go:        go version go1.26.4 linux/amd64
✅ rustc:     rustc 1.97.1 (8bab26f4f 2026-07-14)

# Run this exact check on your own machine. The version
# numbers and .fc44 build tags are what my Fedora box
# reports TODAY. Copy the colors all you want — you can't
# copy a live system fingerprint without owning the system.
```

---

## 🚢 `$ docker ps -a`

```bash
CONTAINER NAME              IMAGE              STATUS          PORTS / LINKS
──────────────────────────────────────────────────────────────────────────────
autotest                    node:llm-agent     Up · shipped    → github.com/madushansivam/autotest
infra-auditor-cli           golang:1.26        Building...     → Stage 1/3 of Go trilogy
imagesync                   js:webworker       Up 4 months     → github.io/imagesync
the-quiet-protocol          html5:game         Up 9 months     → APOGEE GameJam 2026
helapidi                    js:canvas          Building...     → github.com/Nanmin-Game-Studio
portfolio-site              html:gsap          Up 7 months     → madushansivam.github.io
──────────────────────────────────────────────────────────────────────────────
6 containers — 4 running, 2 building
```

---

## 📊 `$ gh api /stats/madushan`

<div align="center">
<img height="175" src="https://github-readme-stats.vercel.app/api?username=madushansivam&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&title_color=f0883e&icon_color=ffa657&text_color=c9d1d9&bg_color=0d1117"/>
&nbsp;
<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=madushansivam&layout=compact&theme=github_dark&hide_border=true&title_color=f0883e&text_color=c9d1d9&bg_color=0d1117&langs_count=7"/>
</div>

<div align="center">
<img src="https://streak-stats.demolab.com?user=madushansivam&theme=github-dark-blue&hide_border=true&ring=f0883e&fire=ffa657&currStreakLabel=f0883e&sideLabels=8b949e&background=0d1117&dates=6e7681"/>
</div>

---

## 📈 `$ git log --graph --all`

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=madushansivam&theme=github-compact&hide_border=true&bg_color=0d1117&color=f0883e&line=ffa657&point=e6edf3&area=true&area_color=f0883e&radius=6"/>
</div>

---

## 🤝 `$ curl -X POST /connect`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-f0883e?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/madushansivam)
[![Portfolio](https://img.shields.io/badge/Portfolio-0d1117?style=for-the-badge&logo=safari&logoColor=f0883e)](https://madushansivam.github.io/portfolio/)
[![Email](https://img.shields.io/badge/Email-f0883e?style=for-the-badge&logo=gmail&logoColor=white)](mailto:madushansivam@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white)](https://github.com/madushansivam)

</div>

<div align="center">

*"Automate the boring. Ship the meaningful. Build the unforgettable."*

</div>
