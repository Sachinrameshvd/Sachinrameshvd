<!--
  ============================================================
  README.md — GitHub Profile — VAGABOND / SUMI-E INK-WASH THEME
  Strictly monochrome: only black, white, and true (hue-free) grays are used.
  Every image, including third-party badges/icons whose source colors can't
  be edited via URL params, is forced to pure grayscale with a CSS filter,
  so nothing renders in color no matter what the underlying service returns.
  ============================================================
  SETUP:
  1. Repo name must EXACTLY match your GitHub username (e.g. "Sachinrameshvd")
     -> that's the only way GitHub renders this as your profile page.
  2. Replace every 🔧 REPLACE marker.
  3. To get the animated SNAKE contribution graph working,
     see "SNAKE SETUP" near the bottom — one GitHub Actions file, copy-paste ready.

  🖌️ IMAGE ASSET SLOTS (send these and I'll wire them in):
     [A] Hero divider — thin brush-stroke line under the header
     [B] Section-frame accent — small ink stamp / brush icon beside each heading
     [C] Optional silhouette — a lone swordsman standing in mist, back turned
     [D] Torn-paper / scroll-edge divider between major sections
     Until supplied, these use lightweight monochrome placeholders so nothing is broken.

  MONOCHROME PALETTE (true grays only — no hue, no saturation):
     Sumi black (ink):        #000000 / #0d0d0d
     Paper white:             #FFFFFF
     Ash gray (light):        #CFCFCF
     Ash gray (mid):          #9B9B9B
     Ash gray (dark):         #4A4A4A
  ============================================================
-->

<div align="center">

<sub>▌ VOLUME ONE ▐</sub>

<!-- Ink-wash gradient header — pure black-to-black, no color, wave = brush stroke -->
<img style="filter: grayscale(100%);" src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:1a1a1a,100:000000&height=260&section=header&text=SACHIN%20KUPPUSWAMY&fontSize=52&fontColor=FFFFFF&fontAlignY=36&animation=twinkling&desc=%3E%20AI%2FML%20Engineer%20_%20I%20ship%20models%20that%20survive%20production&descAlignY=58&descSize=18&descColor=CFCFCF" width="100%"/>

<!-- 🔧 REPLACE [C]: lone swordsman silhouette / brush-art image can sit here, centered, ~120px tall -->

<sub>一意専心 — one mind, one purpose. mastering the craft, one commit at a time</sub>

<!-- Terminal typing animation — ink palette only -->
<img style="filter: grayscale(100%);" src="https://readme-typing-svg.demolab.com?font=Bebas+Neue&weight=500&size=26&duration=2400&pause=800&color=FFFFFF,CFCFCF,9B9B9B&center=true&vCenter=true&multiline=true&width=800&height=100&lines=%24+whoami;multimodal-ml-engineer+%7C+mlops+%7C+backend;%24+cat+focus.txt;ONNX+%2B+FastAPI+%2B+Docker+%2B+RAG;%24+./deploy.sh+--prod;%E2%9C%94+shipped." alt="Typing SVG"/>

<br/>

<!-- Social badges — ink black, no accent color -->
<a href="mailto:sachinrameshvijayarani@gmail.com"><img style="filter: grayscale(100%);" src="https://img.shields.io/badge/-Email-000000?style=for-the-badge&logo=gmail&logoColor=FFFFFF&labelColor=000000"/></a>
<a href="https://linkedin.com/in/YOUR-LINKEDIN"><img style="filter: grayscale(100%);" src="https://img.shields.io/badge/-LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=FFFFFF&labelColor=000000"/></a>
<a href="https://YOUR-PORTFOLIO-LINK"><img style="filter: grayscale(100%);" src="https://img.shields.io/badge/-Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=FFFFFF&labelColor=000000"/></a>
<a href="https://github.com/Sachinrameshvd"><img style="filter: grayscale(100%);" src="https://img.shields.io/badge/-GitHub-000000?style=for-the-badge&logo=github&logoColor=FFFFFF&labelColor=000000"/></a>
<img style="filter: grayscale(100%);" src="https://komarev.com/ghpvc/?username=Sachinrameshvd&color=FFFFFF&style=for-the-badge&label=PROFILE+VIEWS&labelColor=000000"/>

<br/><br/>

<!-- 🔧 REPLACE [A]: swap this line for your brush-stroke divider image (thin, full-width) -->
<img style="filter: grayscale(100%);" src="https://capsule-render.vercel.app/api?type=transparent&color=0:FFFFFF,100:000000&height=6&section=header" width="100%"/>

<!-- Snake contribution animation — dark theme is already monochrome-safe, filter added as a guarantee -->
<img style="filter: grayscale(100%);" src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%"/>
<!-- ⬆ needs one-time setup — see "SNAKE SETUP" near the bottom -->

</div>

<br/>

```bash
┌─[sachin@production]─[~]
└──╼ $ ./boot.sh --whoami

[ OK ] Loading identity module.......... done
[ OK ] Mounting production mindset....... done
[ OK ] Killing 9-second inference time... done (now <1s)
[ OK ] Checking ego vs latency........... latency wins
[ OK ] Starting about_me.py

$ python3 about_me.py
```

```python
class Sachin:
    def __init__(self):
        self.role           = "AI/ML Engineer"
        self.based_in       = "India"
        self.studying       = "B.Tech CSE @ SRM IST"
        self.gpa            = "8.9 / 10  ████████████████████░░  89%"
        self.builds         = ["multimodal ML systems", "federated learning", "RAG pipelines"]
        self.obsessed_with  = "making models survive production, not just notebooks"
        self.status         = "online — probably debugging something at 2 AM"
        self.coffee_level   = "███████░░░  70%  (send help)"
        self.off_duty       = "playing football — best debugging tool I own"

    def currently(self):
        return [
            "shipping clinical-grade multimodal ML with explainability baked in",
            "going deeper on RAG architecture + LLM serving optimization",
            "open to healthcare-AI / federated-learning / MLOps OSS collabs",
            "every model I ship has to survive latency before ego",
        ]

    def __repr__(self):
        return f"<Sachin | {self.role} | shipping > sleeping>"


me = Sachin()
print(me)
```

```yaml
>>> <Sachin | AI/ML Engineer | shipping > sleeping>
>>> Process finished with exit code 0
```

<br/>

<!-- 🔧 REPLACE [D]: torn-paper / scroll-edge divider can go here -->
<div align="center">

<sub>○ ── ── ── ── ── ── ── ── ── ── ── ── ── ── ── ○</sub>

<img style="filter: grayscale(100%);" src="https://capsule-render.vercel.app/api?type=transparent&color=0:000000,50:FFFFFF,100:000000&height=3&section=header" width="60%"/>

</div>

<div align="center">

#### ▌ CHAPTER ONE ▐

## TECH ARSENAL

</div>

<table align="center">
<tr>
<td valign="top" width="50%">

**Languages**
<br/>
<img style="filter: grayscale(100%);" src="https://skillicons.dev/icons?i=python,java,mysql&theme=dark" />

**ML / Deep Learning**
<br/>
<img style="filter: grayscale(100%);" src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn&theme=dark" />
<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/ONNX-000000?style=flat-square&logo=onnx&logoColor=FFFFFF"/>
<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/Transformers-000000?style=flat-square&logo=huggingface&logoColor=FFFFFF"/>

**Generative AI / LLMs**
<br/>
<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/LangChain-000000?style=flat-square&logo=langchain&logoColor=FFFFFF"/>
<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/FAISS-000000?style=flat-square&logoColor=FFFFFF"/>
<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/HuggingFace-000000?style=flat-square&logo=huggingface&logoColor=FFFFFF"/>
<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/RAG_Pipelines-000000?style=flat-square&logoColor=FFFFFF"/>

</td>
<td valign="top" width="50%">

**MLOps & Deployment**
<br/>
<img style="filter: grayscale(100%);" src="https://skillicons.dev/icons?i=docker,aws,githubactions&theme=dark" />
<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/FastAPI-000000?style=flat-square&logo=fastapi&logoColor=FFFFFF"/>
<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=FFFFFF"/>
<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/MLflow-000000?style=flat-square&logo=mlflow&logoColor=FFFFFF"/>

**Computer Vision**
<br/>
<img style="filter: grayscale(100%);" src="https://skillicons.dev/icons?i=opencv&theme=dark" />
<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/YOLOv8-000000?style=flat-square&logoColor=FFFFFF"/>
<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/MediaPipe-000000?style=flat-square&logoColor=FFFFFF"/>

**Data & Infra**
<br/>
<img style="filter: grayscale(100%);" src="https://skillicons.dev/icons?i=postgres,redis,react&theme=dark" />
<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/Pandas-000000?style=flat-square&logo=pandas&logoColor=FFFFFF"/>
<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/Apache_Spark-000000?style=flat-square&logo=apachespark&logoColor=FFFFFF"/>
<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/Streamlit-000000?style=flat-square&logo=streamlit&logoColor=FFFFFF"/>

</td>
</tr>
</table>

<br/>

<div align="center">

<sub>○ ── ── ── ── ── ── ── ── ── ── ── ── ── ── ── ○</sub>

<img style="filter: grayscale(100%);" src="https://capsule-render.vercel.app/api?type=transparent&color=0:000000,50:FFFFFF,100:000000&height=3&section=header" width="60%"/>

</div>

<div align="center">

#### ▌ CHAPTER TWO ▐

## FEATURED BUILDS

<sub>a pin-board of the projects that actually shipped</sub>

</div>

<div align="center">

```
╔═══════════════════════════════════════════════════════════════╗
║  壱 ── OphthaRWE                                                 ║
║        Clinical Multimodal Eye-Disease Classifier               ║
╚═══════════════════════════════════════════════════════════════╝
```

<code>PyTorch · FastAPI · ONNX · SHAP · Docker</code>

<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/AUC-91%25-FFFFFF?style=flat-square&labelColor=000000"/> <img style="filter: grayscale(100%);" src="https://img.shields.io/badge/Inference-%3C1s-9B9B9B?style=flat-square&labelColor=000000"/> <img style="filter: grayscale(100%);" src="https://img.shields.io/badge/Encryption-AES--256-CFCFCF?style=flat-square&labelColor=000000"/>

</div>

<details open>
<summary><b>view details</b></summary>
<br/>

```diff
+ Fuses retinal-image CNN embeddings with structured patient data -> 91% AUC
+ Inference bottleneck: ~9s -> exported to ONNX + rebuilt serving -> <1s  (9x faster)
+ SHAP explanations shipped with every prediction (clinicians see the "why")
+ AES-256 encryption + RBAC on patient data, fully Dockerized
```

<!-- 🔧 REPLACE with real repo link -->
[`→ view repo`](https://github.com/Sachinrameshvd/your-repo)

</details>

<div align="center">

<sub>◆ ─── ─── ─── ─── ─── ─── ─── ─── ─── ─── ◆</sub>

</div>

<div align="center">

```
╔═══════════════════════════════════════════════════════════════╗
║  弐 ── Federated Food Freshness Detector                        ║
║        Privacy-Preserving Spoilage Classifier                   ║
╚═══════════════════════════════════════════════════════════════╝
```

<code>PyTorch · Flower · YOLOv8 · DoWhy</code>

<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/Accuracy-92.3%25-FFFFFF?style=flat-square&labelColor=000000"/> <img style="filter: grayscale(100%);" src="https://img.shields.io/badge/mAP@50-0.893-9B9B9B?style=flat-square&labelColor=000000"/> <img style="filter: grayscale(100%);" src="https://img.shields.io/badge/Privacy-No%20Raw%20Data%20Leaves%20Device-CFCFCF?style=flat-square&labelColor=000000"/>

</div>

<details>
<summary><b>view details</b></summary>
<br/>

```diff
+ Federated spoilage classifier across 5 nodes (Flower) -> 92.3% global acc
+ No raw images ever leave a device
+ YOLOv8 fine-tuned on 5k produce images -> 0.893 mAP@50
+ Added DoWhy causal inference to test if fridge placement CAUSES freshness
  changes, not just correlates -> up to 5.2 extra shelf-life days
```

[`→ view repo`](https://github.com/Sachinrameshvd/your-repo)

</details>

<div align="center">

<sub>◆ ─── ─── ─── ─── ─── ─── ─── ─── ─── ─── ◆</sub>

</div>

<div align="center">

```
╔═══════════════════════════════════════════════════════════════╗
║  参 ── AirAware                                                 ║
║        Air Quality Predictor & Route Planner                    ║
╚═══════════════════════════════════════════════════════════════╝
```

<code>XGBoost · Flask · REST API</code>

<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/Latency-%3C100ms-FFFFFF?style=flat-square&labelColor=000000"/> <img style="filter: grayscale(100%);" src="https://img.shields.io/badge/Latency%20Drop-70%25-9B9B9B?style=flat-square&labelColor=000000"/> <img style="filter: grayscale(100%);" src="https://img.shields.io/badge/Cities-6%20Indian%20Metros-CFCFCF?style=flat-square&labelColor=000000"/>

</div>

<details>
<summary align="center"><b>view details</b></summary>
<br/>

```diff
+ City-specific AQI models, 6 Indian metros, served <100ms via Flask
+ Upstream routing API kept failing on outages -> added retry + SQLite cache
+ Side effect: ~70% latency drop
+ Nightly retraining on ~250k live records, versioned artifacts
```

[`→ view repo`](https://github.com/Sachinrameshvd/your-repo)

</details>

<br/>

<div align="center">

<sub>○ ── ── ── ── ── ── ── ── ── ── ── ── ── ── ── ○</sub>

<img style="filter: grayscale(100%);" src="https://capsule-render.vercel.app/api?type=transparent&color=0:000000,50:FFFFFF,100:000000&height=3&section=header" width="60%"/>

</div>

<div align="center">

#### ▌ CHAPTER THREE ▐

## LIVE STATS

<!-- 🔧 REPLACE username in all URLs below -->
<img style="filter: grayscale(100%);" src="https://github-readme-stats.vercel.app/api?username=Sachinrameshvd&show_icons=true&hide_border=true&bg_color=00000000&icon_color=FFFFFF&title_color=FFFFFF&text_color=CFCFCF" height="165"/>
<img style="filter: grayscale(100%);" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sachinrameshvd&layout=compact&hide_border=true&bg_color=00000000&title_color=FFFFFF&text_color=CFCFCF" height="165"/>

<img style="filter: grayscale(100%);" src="https://github-readme-streak-stats.herokuapp.com/?user=Sachinrameshvd&theme=dark&hide_border=true&background=00000000&ring=FFFFFF&fire=9B9B9B&currStreakLabel=FFFFFF" />

<img style="filter: grayscale(100%);" src="https://github-readme-activity-graph.vercel.app/graph?username=Sachinrameshvd&theme=react-dark&hide_border=true&bg_color=00000000&color=FFFFFF&line=CFCFCF&point=9B9B9B" width="95%"/>

<img style="filter: grayscale(100%);" src="https://github-profile-trophy.vercel.app/?username=Sachinrameshvd&theme=darkhub&no-frame=true&column=7&margin-w=8&margin-h=8" />

</div>

<br/>

<div align="center">

<sub>○ ── ── ── ── ── ── ── ── ── ── ── ── ── ── ── ○</sub>

<img style="filter: grayscale(100%);" src="https://capsule-render.vercel.app/api?type=transparent&color=0:000000,50:FFFFFF,100:000000&height=3&section=header" width="60%"/>

</div>

<div align="center">

#### ▌ CHAPTER FOUR ▐

### CURRENTLY DEBUGGING IN MY HEAD

<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/-LLM_Serving_%E2%80%94_Quantization_%2B_Dynamic_Batching-FFFFFF?style=for-the-badge&labelColor=FFFFFF&color=FFFFFF"/>

<br/>

<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/-Production_RAG_%E2%80%94_Retrieval%2C_Chunking%2C_Real_Evals-9B9B9B?style=for-the-badge&labelColor=9B9B9B&color=9B9B9B"/>

<br/>

<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/-Distributed_Training_%E2%80%94_Scaling_Multimodal_Models-4A4A4A?style=for-the-badge&labelColor=4A4A4A&color=4A4A4A"/>

</div>

<br/>

<div align="center">

#### ▌ CHAPTER FIVE ▐

### COMMUNITY & IMPACT

<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/-Secretary%2C_CyberAnzen_Club-9B9B9B?style=for-the-badge&labelColor=9B9B9B&color=9B9B9B"/>
<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/-Peer_Mentor_%E2%80%94_10%2B_Juniors_Shipped-FFFFFF?style=for-the-badge&labelColor=FFFFFF&color=FFFFFF"/>

<br/>

<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/-CS50_AI_with_Python%2C_Harvard-4A4A4A?style=for-the-badge&labelColor=4A4A4A&color=4A4A4A"/>
<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/-Open_to_MLOps_%26_Healthcare_AI_OSS_Collabs-FFFFFF?style=for-the-badge&labelColor=FFFFFF&color=FFFFFF"/>

<br/><br/>

> **100+** students reached through workshops, hackathons & CTFs · **10+** juniors mentored into shipped projects

</div>

<br/>

<div align="center">

<sub>○ ── ── ── ── ── ── ── ── ── ── ── ── ── ── ── ○</sub>

<img style="filter: grayscale(100%);" src="https://capsule-render.vercel.app/api?type=transparent&color=0:000000,50:FFFFFF,100:000000&height=3&section=header" width="60%"/>

</div>

<div align="center">

<sub>▌ FINAL CHAPTER ▐</sub>

## THE WAY FORWARD

<img style="filter: grayscale(100%);" src="https://readme-typing-svg.demolab.com?font=Bebas+Neue&weight=500&size=22&duration=3000&pause=1200&color=FFFFFF,CFCFCF,9B9B9B&center=true&vCenter=true&width=750&lines=%22Ship+the+version+that+fits+inside%22;%22someone's+actual+workflow.%22" alt="Typing SVG"/>

<br/><br/>

<img style="filter: grayscale(100%);" src="https://img.shields.io/badge/-●_THE_END-000000?style=for-the-badge&labelColor=000000&color=FFFFFF"/>
<sub>&nbsp;&nbsp;end of volume one — more chapters in progress</sub>

<br/><br/>

<img style="filter: grayscale(100%);" src="https://komarev.com/ghpvc/?username=Sachinrameshvd&color=FFFFFF&style=for-the-badge&label=THANKS+FOR+VISITING&labelColor=000000"/>

<br/><br/>

<img style="filter: grayscale(100%);" src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:1a1a1a,100:000000&height=150&section=footer" width="100%"/>

</div>

<!--
============================================================
NOTE ON GITHUB RENDERING:
GitHub's markdown sanitizer strips the `style` attribute from raw <img> tags
in README files (it keeps src/width/height/align but drops inline CSS).
That means the grayscale(100%) filters above WILL work if you preview this
file in most local Markdown renderers / VS Code, but may be stripped when
GitHub actually renders your public profile page.

Because of that, treat the URL-level params (color=000000/FFFFFF/grays,
theme=dark, icon_color=FFFFFF, etc.) as the real source of truth for
monochrome on GitHub itself — those are already set to grays/black/white
above and will hold regardless of the style attribute.

Two spots GitHub's stat services can't be forced to true gray via URL
params alone: skillicons.dev icons (renders official multicolor brand
logos) and github-profile-trophy (renders rank-colored trophies). Options:
  1. Leave them — small flashes of color are common even on otherwise
     monochrome dev profiles and are usually accepted as "fine, it's icons."
  2. Swap skillicons for the shields.io badges already used elsewhere in
     this file (all forced to black/white/gray) and drop the trophy block
     entirely, or replace it with another github-readme-stats card.
Tell me which you'd prefer and I'll swap them in.
============================================================
SNAKE SETUP (one-time, ~2 minutes):
This makes the "snake eating your contribution graph" animation
near the top actually work with YOUR real contribution data.

1. In your profile repo, create: .github/workflows/snake.yml
2. Paste this content into it:

name: generate snake

on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch: {}
  push:
    branches: [ main ]

jobs:
  generate:
    permissions: contents: write
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: Platane/snk@v3
        id: snake-gif
        with:
          github_user_name: YOUR-GITHUB-USERNAME
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ '{{' }} secrets.GITHUB_TOKEN {{ '}}' }}

3. Commit, push, and manually run the workflow once (Actions tab -> Run workflow).
4. After it finishes, the image URL in this README will show YOUR real snake.

MONOCHROME PALETTE REFERENCE (for future edits — true grays only, no hue):
- Ink black (background):   #000000 / #0d0d0d
- Paper white (accent):     #FFFFFF
- Ash gray (light):         #CFCFCF
- Ash gray (mid):           #9B9B9B
- Ash gray (dark):          #4A4A4A

IMAGE ASSET SLOTS — once you send images, tell me which slot each one is for:
[A] Hero divider (currently a thin black/white gradient placeholder line)
[B] Section-frame accent icon beside headings (currently plain ▌ ▐ block brackets)
[C] Lone swordsman silhouette near the header
[D] Torn-paper / scroll-edge dividers between sections (currently thin gradient lines)
============================================================
-->
