<div align="center">

<a href="https://github.com/Bailensn">
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=30&pause=1400&color=58A6FF&center=true&vCenter=true&width=520&height=68&lines=Bailensn+%2F+%E5%BC%82%E6%88%96;Student+Developer;Open+Source+Enthusiast;Building+LianT"
    alt="Bailensn / 异或" />
</a>

**Bailensn** · 异或

`Student Developer` · `Open Source Enthusiast`

<sub>LensnTeam · 异山工作室</sub>

<br />

<sub>Building software, breaking software, and occasionally understanding why it works.</sub>

<br /><br />

<a href="https://github.com/Bailensn"><img src="https://img.shields.io/badge/GitHub-Bailensn-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
<a href="https://github.com/LensnTeam"><img src="https://img.shields.io/badge/LensnTeam-org-0B7285?style=flat-square&logo=github&logoColor=white" alt="LensnTeam" /></a>
<img src="https://img.shields.io/github/followers/Bailensn?label=Followers&style=flat-square&logo=github&color=0B7285" alt="Followers" />
<img src="https://img.shields.io/badge/Open%20Source-yes-3FB950?style=flat-square" alt="Open Source" />
<img src="https://img.shields.io/badge/Status-still%20learning-58A6FF?style=flat-square" alt="Status" />

</div>

---

## `/ about`

```console
$ whoami
Bailensn (异或)

$ cat role
Student Developer · Open Source Developer · Independent Builder

$ cat interests
linux, android, servers, self-hosting, open source,
low-level software, modern UI, new languages

$ cat workflow
small idea → rough prototype → rewrite → actual project
```

I'm a student developer who likes taking software apart and putting it back together.
Most of what I build starts as a tiny idea, then slowly turns into something real —
a bot manager, a roll-call tool, a small Android utility.

I like owning the stack: writing the code, running the server, deploying the service,
and fixing it when it breaks at 2 a.m.

---

## `/ currently building`

```text
→ LianT                  open-source, self-hosted Telegram Bot API manager
→ Modern Android UI      Jetpack Compose · Material 3 · animation
→ Go projects            services, tools, small experiments
→ Linux / server         self-hosted infra, networking, reverse proxy
→ Exploring Zig          a language I keep coming back to
→ Exploring desktop UI   Compose Multiplatform / SwiftUI
```

---

## `/ featured projects`

### LianT · 联T

**An open-source, self-hosted Telegram Bot API manager.**

> Making the Telegram Bot API feel less like a raw endpoint
> and more like a service you actually manage.

`Open Source` · `Self-hosted` · `Privacy-oriented` · `Multi-Service` · `Modern UI`

<p>
<a href="https://github.com/LensnTeam/LianT">
  <img src="https://img.shields.io/badge/LensnTeam%2FLianT-repository-58A6FF?style=flat-square&logo=github&logoColor=white" alt="LensnTeam/LianT" />
</a>
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/WSS-WebSocket-8957E5?style=flat-square" alt="WSS" />
</p>

<div align="center">

<a href="https://github.com/LensnTeam/LianT">
  <img
    src="https://github-readme-stats.vercel.app/api/pin/?username=LensnTeam&repo=LianT&theme=tokyonight&hide_border=true&show_owner=true"
    alt="LianT repository card" width="420" />
</a>

</div>

**Structure**

```text
LianT
├── Manager   → client apps, shared business logic
├── Service   → server side
└── Pages     → web / pages layer
```

`Service` is the server-side component: Telegram Bot API handling, bot relay,
temporary storage, sessions, authentication and network communication — written in **Go**,
deployed with **Docker**, self-hosted.

`Manager` is the client: Android first, then Desktop, iOS and HarmonyOS.

**Technical keywords**

`Go` · `Docker` · `Telegram Bot API` · `WSS` · `WebSocket` · `Session`
`Authentication` · `Challenge-Response` · `Temporary Token` · `Self-hosted`

**Security design (brief)**

Credential handling uses challenge-response with temporary credentials, and
`ChaCha20-Poly1305` for encrypted transport payloads. The full design lives in the repo —
this README stays a README.

---

### Dming

**An attendance / roll-call application.**

One very small idea, rewritten until it became a full software project:

```text
V1  Bash
V2  Bash + student mapping
V3  HTML
V4  Native app
V5  FluxUI + backend
```

No repository card here — the code isn't public yet.

---

### 异山工具箱

**An Android utility collection.**

Small tools that do one thing each, built with `Kotlin` + `Jetpack Compose`.
Secondary project, still growing.

---

## `/ lian t architecture`

```mermaid
flowchart LR
    T["Telegram"] <--> S["LianT Service (Go)"]
    S <-->|WSS| M["LianT Manager"]
    M --> A["Android · Compose"]
    M --> D["Desktop"]
    M --> I["iOS · SwiftUI"]
    M --> H["HarmonyOS · Native UI"]
```

**Same business. Different experience.**

```text
                 LianT
                   │
            Common Business Logic
                   │
       ┌───────────┼───────────┐
       │           │           │
    Android     Desktop    iOS / Harmony
       │           │           │
    Compose    Desktop UI   Native UI
```

One product doesn't have to look the same on every platform.
The business logic stays as consistent as possible; the UI is designed per platform.

---

## `/ tech stack`

**Currently working with**

<p>
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C" />
</p>

**Exploring**

<p>
<img src="https://img.shields.io/badge/Zig-F7A41D?style=flat-square&logo=zig&logoColor=black" alt="Zig" />
<img src="https://img.shields.io/badge/System%20Programming-000000?style=flat-square" alt="System Programming" />
</p>

`Zig` · `Compose Multiplatform` · `SwiftUI` · `system programming` · `networking` ·
`self-hosted infrastructure` · `modern UI`

**Android**

<p>
<img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android" />
<img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white" alt="Jetpack Compose" />
<img src="https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white" alt="Gradle" />
</p>

`Kotlin` · `Android SDK` · `Material 3` · `KernelSU` · `Termux` · `Termux:X11` —
I care about modern, component-based and responsive UI: animation, Material 3,
and layouts that behave on any screen.

**Linux / Server**

<p>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

`Debian` · `Ubuntu` · `CentOS` · `Apache` · `SSH` · `IPv6` · `reverse proxy` ·
`git server / bare repository` · `self-hosted`

I like owning the whole thing: deploy it, configure it, compile it, patch it, keep it running.
Self-hosted, open source, free software — control and hackability over convenience.

No percentage bars, no fake proficiency levels — just things I use, things I'm learning,
and things I'd like to understand better.

---

## `/ github activity`

<div align="center">

<img
  src="https://github-readme-stats.vercel.app/api?username=Bailensn&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true"
  alt="GitHub stats" width="48%" />
<img
  src="https://streak-stats.demolab.com?user=Bailensn&theme=tokyonight&hide_border=true"
  alt="GitHub streak" width="48%" />

<br /><br />

<img
  src="https://github-readme-stats.vercel.app/api/top-langs/?username=Bailensn&layout=compact&langs_count=8&theme=tokyonight&hide_border=true"
  alt="Top languages" width="420" />

</div>

<div align="center"><sub>Top languages reflect what I write most, not how good I am at it.</sub></div>

---

## `/ contributions`

<div align="center">

<img
  src="https://raw.githubusercontent.com/Bailensn/Bailensn/output/github-contribution-grid-snake-dark.svg"
  alt="Contribution snake" />

<br /><br />

<img
  src="https://github-readme-activity-graph.vercel.app/graph?username=Bailensn&theme=tokyo-night&hide_border=true&area=true"
  alt="Activity graph" width="100%" />

</div>

---

## `/ development philosophy`

```text
Build first.
Understand later.

Rewrite when necessary.

Open source when possible.
Self-host when practical.

Same business.
Different experience.

Still learning.
Still building.
```

---

## `/ links`

- GitHub — [@Bailensn](https://github.com/Bailensn)
- Organization — [LensnTeam](https://github.com/LensnTeam)
- Main project — [LensnTeam/LianT](https://github.com/LensnTeam/LianT)

<div align="center">
<br />
<sub>异或 · Bailensn — still learning, still building.</sub>
</div>
