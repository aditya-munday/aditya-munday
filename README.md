<!-- ═══════════════════ ANIMATED HEADER ═══════════════════ -->
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)"
          srcset="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=230&section=header&text=Aditya%20Munday&fontSize=68&fontColor=ffffff&animation=fadeIn&fontAlignY=34&desc=Quant%20%C2%B7%20Systems%20%C2%B7%20Backend%20Engineering&descAlignY=56&descSize=20"/>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,3,9&height=230&section=header&text=Aditya%20Munday&fontSize=68&fontColor=1b1f24&animation=fadeIn&fontAlignY=34&desc=Quant%20%C2%B7%20Systems%20%C2%B7%20Backend%20Engineering&descAlignY=56&descSize=20" width="100%" alt="Aditya Munday — animated header"/>
</picture>

<a href="https://github.com/aditya-munday">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=2500&pause=650&color=39D353&center=true&vCenter=true&width=820&height=46&lines=Quantitative+research+%26+financial+engineering;Low-latency+C%2B%2B+%7C+C+%7C+Rust;Backend+engineering+on+AWS+%26+Azure;Deep+systems%2C+memory+%26+performance" alt="Typing animation"/>
</a>

<a name="top"></a>

</div>

<!-- ═══════════════════ NAV (click to jump) ═══════════════════ -->
<div align="center">
<sub>

[<kbd>‎ whoami ‎</kbd>](#whoami) · [<kbd>‎ quant ‎</kbd>](#quant) · [<kbd>‎ systems ‎</kbd>](#systems) · [<kbd>‎ skills ‎</kbd>](#skills) · [<kbd>‎ work ‎</kbd>](#work) · [<kbd>‎ signals ‎</kbd>](#signals) · [<kbd>‎ console ‎</kbd>](#console) · [<kbd>‎ connect ‎</kbd>](#connect)

</sub>
</div>

<!-- ═══════════════════ QUANT HERO ═══════════════════ -->
<div align="center">
  <img src="./quant.gif" width="92%" alt="Animated price chart — quant research"/>
  <br/>
  <sub><i>Markets, models &amp; microstructure — rendered from first principles.</i></sub>
</div>

<br/>

<!-- ═══════════════════ BADGES ═══════════════════ -->
<div align="center">

<a href="https://github.com/aditya-munday?tab=followers"><img src="https://img.shields.io/github/followers/aditya-munday?label=Followers&style=for-the-badge&color=39d353&labelColor=0d1117" alt="followers"/></a>
<a href="https://github.com/aditya-munday?tab=repositories"><img src="https://img.shields.io/badge/Repositories-8-39d353?style=for-the-badge&labelColor=0d1117&logo=github" alt="repos"/></a>
<img src="https://visitor-badge.laobi.icu/badge?page_id=aditya-munday.readme&left_text=PROFILE%20VIEWS&left_color=0d1117&right_color=39d353" alt="profile views"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="100%" alt="divider"/>

<!-- ═══════════════════ ABOUT ═══════════════════ -->
<a name="whoami"></a>
## <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="24"/> `whoami`

<table>
<tr>
<td width="57%" valign="top">

```cpp
struct Aditya {
    const char* name      = "Aditya Munday";
    const char* domain    = "Quantitative science & backend engineering";
    const char* mission   = "Turn research into deterministic, auditable systems";
    const char* langs[]   = { "C++", "C", "Rust", "Python", "Julia", "R" };
    const char* cloud[]   = { "AWS", "Azure", "Docker", "Linux" };
    const char* values[]  = { "correctness", "latency", "reproducibility" };
};
```

I build at the intersection of **quantitative research**, **systems
engineering**, and **cloud-native backends** — pricing and simulation models in
C++/Rust, and the production services that serve them across AWS and Azure.

Every system I ship is designed to be **deterministic, capability-scoped, and
auditable**: the model you backtested is the model that runs in production.

</td>
<td width="43%" valign="top" align="center">

<img src="./stack.gif" width="100%" alt="Animated build &amp; deploy run"/>

*From `cargo build` to a green production deploy* —<br/>
deterministic · reproducible · auditable

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="100%" alt="divider"/>

<!-- ═══════════════════ QUANT ═══════════════════ -->
<a name="quant"></a>
## <img src="https://media.giphy.com/media/3o7btPCcdNniyf0ArS/giphy.gif" width="24"/> Quantitative science &amp; financial engineering

> *Research → model → backtest → production. No step skipped, no magic.*

<table>
<tr><th align="left">Domain</th><th align="left">What I work on</th></tr>
<tr><td><b>Derivatives &amp; pricing</b></td><td>Option pricing, Greeks, Monte-Carlo &amp; quasi-MC simulation, lattices, stochastic calculus (Itô, SDEs), volatility surfaces — performance-critical C++/Rust implementations.</td></tr>
<tr><td><b>Systematic strategies</b></td><td>Signal generation, alpha research, statistical arbitrage, factor / cross-sectional models, portfolio construction, risk &amp; attribution.</td></tr>
<tr><td><b>Stochastic modelling</b></td><td>GBM, Heston, jump-diffusion, mean-reverting processes, regime-switching; calibration to market quotes.</td></tr>
<tr><td><b>Market microstructure</b></td><td>Order-book modelling, LOB dynamics, execution algorithms (TWAP/VWAP/POV), slippage &amp; transaction-cost analysis.</td></tr>
<tr><td><b>Data &amp; analytics</b></td><td>Time-series econometrics, EWMA volatility, tail-risk (VaR/CVaR), backtesting engines with realistic fills.</td></tr>
<tr><td><b>Numerical methods</b></td><td>Linear algebra (LAPACK/BLAS, Eigen), Monte-Carlo, finite differences, optimisation, FFTs, SIMD &amp; cache-aware hot loops.</td></tr>
</table>

<details>
<summary><b>🤖 AI, ML &amp; model training</b> &nbsp;<sub>(click to expand)</sub></summary>
<br/>

<div align="center">

<img src="https://skillicons.dev/icons?i=tensorflow,pytorch&theme=dark" alt="AI &amp; ML stack"/>

<br/><br/>
<sub>Deep learning · model training · neural networks · scientific computing in Julia &amp; R</sub>

</div>
</details>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="100%" alt="divider"/>

<!-- ═══════════════════ SYSTEMS ═══════════════════ -->
<a name="systems"></a>
## <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="24"/> Systems, backend &amp; cloud

<table>
<tr>
<td width="50%" valign="top">

**Systems, low-level &amp; performance**
- C / C++17-20 — RAII, templates, SIMD, cache-aware design
- Rust — ownership, zero-cost abstractions, `no_std`
- Linux deep systems — syscalls, kernel interfaces, profiling (`perf`, flamegraphs)
- Memory &amp; low-level programming — allocators, layout, cache behaviour
- Performance engineering — hot-loop tuning, latency, benchmarking
- DSA — algorithmic design &amp; complexity analysis
- Cybersecurity — hardening, least privilege, threat modelling

</td>
<td width="50%" valign="top">

**Backend, cloud &amp; data**
- Docker — images, multi-stage builds, compose
- AWS &amp; Azure — compute, storage, IAM, managed data
- PostgreSQL &amp; MySQL — schema design, query tuning
- Backend testing — unit, integration, API contracts (Java)
- Shell — automation, tooling, POSIX pipelines
- Git &amp; GitHub — branching, reviews, CI

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="100%" alt="divider"/>

<!-- ═══════════════════ SKILLS ═══════════════════ -->
<a name="skills"></a>
## 🧭 Skills

<div align="center">

<img src="https://skillicons.dev/icons?i=c,cpp,rust,python,julia,r,postgres,mysql,linux&theme=dark" alt="languages &amp; data"/>
<br/>
<img src="https://skillicons.dev/icons?i=docker,aws,azure,bash,git,github,vscode,visualstudio,java,tensorflow,pytorch&theme=dark" alt="cloud, tooling &amp; ML"/>

<br/><br/>

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Julia](https://img.shields.io/badge/Julia-9558B2?style=for-the-badge&logo=julia&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white)

<br/>

![Performance](https://img.shields.io/badge/performance%20engineering-1f6feb?style=for-the-badge)
![Memory](https://img.shields.io/badge/low--level%20%26%20memory-1f6feb?style=for-the-badge)
![DSA](https://img.shields.io/badge/data%20structures%20%26%20algorithms-1f6feb?style=for-the-badge)
![Cybersecurity](https://img.shields.io/badge/cybersecurity-1f6feb?style=for-the-badge)
![Mathematics](https://img.shields.io/badge/mathematics-1f6feb?style=for-the-badge)
![Quant](https://img.shields.io/badge/quantitative%20finance-1f6feb?style=for-the-badge)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="100%" alt="divider"/>

<!-- ═══════════════════ WORK ═══════════════════ -->
<a name="work"></a>
## <img src="https://media.giphy.com/media/W5N6TjFK5kzB6/giphy.gif" width="24"/> Flagship work

<details open>
<summary><b>🧠 Directioner-OS</b> — the AI-native Fedora &nbsp;<sub>(click)</sub></summary>

> *"The differentiator is not that the OS can talk. It is that the OS employs an engineer."*

A Fedora-derived OS with a resident, multi-agent **AI Engineer** that plans,
implements, tests, reviews, ships, monitors and rolls back changes — preserving
determinism, transparency and user sovereignty.

`Fedora bootc` · `Rust workspace` · `SELinux` · `polkit` · `QEMU smoke tests`

</details>

<details>
<summary><b>🛰️ Aria · Aria-Electron</b> — native voice assistant &nbsp;<sub>(click)</sub></summary>

A background desktop assistant that wakes on a word or global shortcut and
surfaces a floating orb — never stealing focus. Typed `aria-core`/`aria-platform`
crates, a versioned desktop ⇄ backend contract, streaming and barge-in.

`Rust` · `TypeScript (Electron)` · `audio` · `wake-word`

</details>

<details>
<summary><b>⌨️ Directioner-CLI</b> — local-first AI coding agent &nbsp;<sub>(click)</sub></summary>

A bring-your-own-key terminal agent that inspects your repo, edits code, runs the
checks that matter, and reports what actually happened. Hardened against prompt
injection, filesystem and terminal abuse.

`TypeScript` · `BYOK` · `--doctor` · `hardened`

</details>

<details>
<summary><b>⚙️ Directioner-Platform-Backend</b> — platform backend &nbsp;<sub>(click)</sub></summary>

Shared identity, AI, data, task, entitlement and integration layer. Never executes
privileged ops itself — it requests them through an explicit allowlist.

`Node 24` · `Fastify 5` · `Zod` · `OpenAPI 3.1` · `Supabase` · `Vitest`

</details>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="100%" alt="divider"/>

<!-- ═══════════════════ SIGNALS ═══════════════════ -->
<a name="signals"></a>
## <img src="https://media.giphy.com/media/du3J3cXyzhj75IOgvA/giphy.gif" width="24"/> Signals

<div align="center">

<picture>
    <source media="(prefers-color-scheme: dark)"
            srcset="https://github-readme-stats.vercel.app/api?username=aditya-munday&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&bg_color=0d1117&title_color=39d353&icon_color=39d353&text_color=c9d1d9&ring_color=39d353"/>
    <img height="170em" src="https://github-readme-stats.vercel.app/api?username=aditya-munday&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&theme=default" alt="stats"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)"
            srcset="https://github-readme-streak-stats.herokuapp.com/?user=aditya-munday&hide_border=true&background=0d1117&stroke=39d353&ring=39d353&fire=39d353&currStreakLabel=c9d1d9&sideLabels=c9d1d9&dates=c9d1d9"/>
    <img height="170em" src="https://github-readme-streak-stats.herokuapp.com/?user=aditya-munday&hide_border=true&theme=default" alt="streak"/>
  </picture>

<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=aditya-munday&theme=github_dark" alt="repos per language"/>
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=aditya-munday&theme=github_dark" alt="profile summary"/>

<img width="98%" src="https://raw.githubusercontent.com/aditya-munday/aditya-munday/output/github-contribution-grid-snake-dark.svg" alt="snake contribution animation"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="100%" alt="divider"/>

<!-- ═══════════════════ CONSOLE (interactive) ═══════════════════ -->
<a name="console"></a>
## 🖥️ Console

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=1300&pause=350&color=39D353&center=true&vCenter=true&width=780&height=52&lines=%24+whoami;%3E+Aditya+Munday+%E2%80%94+quant+%C2%B7+systems+%C2%B7+backend;%24+cat+stack.txt;%3E+C%2B%2B+%7C+C+%7C+Rust+%7C+Python+%7C+Julia+%7C+R;%3E+Linux+deep+systems+%C2%B7+memory+%C2%B7+performance;%3E+AWS+%C2%B7+Azure+%C2%B7+Docker+%C2%B7+PostgreSQL+%C2%B7+MySQL;%24+./quant+run+--model+heston;%3E+calibrate+SVI+%C2%B7+simulate+10M+paths+%C2%B7+sharpe+2.14;%3E+deterministic+run+complete" alt="terminal console"/>

<br/>
<sub><i>A live terminal — type your own commands in the <a href="https://github.com/aditya-munday/aditya-munday/issues/new?title=console&body=%24%20">console issue</a>.</i></sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="100%" alt="divider"/>

<!-- ═══════════════════ CONNECT ═══════════════════ -->
<a name="connect"></a>
## <img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="24"/> Connect

<div align="center">

<a href="https://github.com/aditya-munday"><img src="https://img.shields.io/badge/GitHub-aditya--munday-39d353?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117" alt="GitHub"/></a>
<a href="https://www.linkedin.com/in/aditya-munday/"><img src="https://img.shields.io/badge/LinkedIn-aditya--munday-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117" alt="LinkedIn"/></a>
<a href="https://leetcode.com/u/aditya-munday/"><img src="https://img.shields.io/badge/LeetCode-aditya--munday-FFA116?style=for-the-badge&logo=leetcode&logoColor=white&labelColor=0d1117" alt="LeetCode"/></a>
<a href="https://www.geeksforgeeks.org/profile/adityamunday"><img src="https://img.shields.io/badge/GeeksforGeeks-adityamunday-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white&labelColor=0d1117" alt="GeeksforGeeks"/></a>
<a href="https://www.instagram.com/adi.vrse/"><img src="https://img.shields.io/badge/Instagram-@adi.vrse-E4405F?style=for-the-badge&logo=instagram&logoColor=white&labelColor=0d1117" alt="Instagram"/></a>
<a href="https://www.threads.net/@adi.vrse"><img src="https://img.shields.io/badge/Threads-@adi.vrse-000000?style=for-the-badge&logo=threads&logoColor=white&labelColor=0d1117" alt="Threads"/></a>
<a href="mailto:adityamunday@yahoo.com"><img src="https://img.shields.io/badge/Email-adityamunday@yahoo.com-6001D2?style=for-the-badge&logo=yahoo&logoColor=white&labelColor=0d1117" alt="Email"/></a>

<br/><br/>

<a href="#top"><kbd>‎ ↑ back to top ‎</kbd></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3" width="100%" alt="divider"/>

<!-- ═══════════════════ FOOTER ═══════════════════ -->
<div align="center">

<a href="https://github.com/aditya-munday">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3400&pause=1000&color=58A6FF&center=true&vCenter=true&width=760&lines=The+model+you+backtested+is+the+model+that+runs+in+production;Correctness+first%2C+then+latency%2C+then+everything+else;Build+things+that+outlive+the+demo" alt="closing typing"/>
</a>

<br/><br/>

**Quantitative research &amp; systems engineering — one deterministic commit at a time.**

<picture>
    <source media="(prefers-color-scheme: dark)"
            srcset="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=150&section=footer"/>
    <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,3,9&height=150&section=footer" width="100%" alt="footer"/>
  </picture>

</div>
