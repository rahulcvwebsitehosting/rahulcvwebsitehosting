<!--
  ╔══════════════════════════════════════════════════════════════╗
  ║                    RAHULOS v3.7 AI                           ║
  ║                    AI Operating System                        ║
  ║                    github.com/rahulcvwebsitehosting            ║
  ╚══════════════════════════════════════════════════════════════╝
-->

<br>

<!-- ═══════════ BOOT ═══════════ -->

```
RahulOS 3.7.0-ai (rahul-cv-01) │ tty1

[    0.000000] Booting RahulOS 3.7.0-ai...
[    0.421913] Initializing AI inference subsystem
[    0.422008] Initializing vision processing unit
[    0.422105] Initializing multi-model router
[    0.813042] Mounting root filesystem...
[    1.104211] Mount-cache hash table entries: 2048 (order: 1)

┌──────────────────────────────────────────────────────────┐
│                                                          │
│    ██████╗     █████╗    ██╗  ██╗ ██╗   ██╗ ██╗          │
│    ██╔══██╗   ██╔══██╗   ██║  ██║ ██║   ██║ ██║          │
│    ██████╔╝   ███████║   ███████║ ██║   ██║ ██║          │
│    ██╔══██╗   ██╔══██║   ██╔══██║ ██║   ██║ ██║          │
│    ██║  ██║   ██║  ██║   ██║  ██║ ╚██████╔╝ ███████╗     │
│    ╚═╝  ╚═╝   ╚═╝  ╚═╝   ╚═╝  ╚═╝  ╚═════╝  ╚══════╝     │
│                                                          │
│         ██████╗     ███████╗                             │
│        ██╔═══██╗    ██╔════╝                             │
│        ██║   ██║    ███████╗                             │
│        ██║   ██║    ╚════██║                             │
│        ╚██████╔╝    ███████║                             │
│         ╚═════╝     ╚══════╝                             │
│                                                          │
└──────────────────────────────────────────────────────────┘

[    1.315290] PCI: Using ACPI for IRQ routing
[    1.315312] PCI: MMCONFIG at 0xe0000000 reserved
[    1.841006] Initramfs unpacking: Initializing AI userland...
[    2.101483] Freeing initrd memory: 32768K

─── SERVICE MANAGER INIT ────────────────────────────────

[  OK  ] Started gemini-adapter.service          — Multi-model routing
[  OK  ] Started vision-pipeline.service          — Computer Vision
[  OK  ] Started insightface-runtime.service      — Face Recognition
[  OK  ] Started ollama-bridge.service            — Local LLM runtime
[  OK  ] Started api-gateway.socket               — Next.js API routes
[  OK  ] Started dev-server.socket                — Vite dev server
[  OK  ] Started firebase-connector.service       — Firebase backend
[  OK  ] Started cloud-run-agent.service          — GCP deployment
[  OK  ] Started vercel-edge-agent.service        — Edge delivery

[  OK  ] Reached target session.target

```

<br>

<!-- ═══════════ LOGIN ═══════════ -->

```
rahul@rahulos login: rahul
Password: ********

Authenticating...

┌──────────────────────────────────────────────────────────┐
│                                                          │
│   User: rahul                                            │
│   UID: 1000    GID: 1000                                │
│   Groups: ai, builders, civil-engineering                │
│   Home: /home/rahul                                      │
│                                                          │
│   ┌── ENVIRONMENT ──────────────────────────────────┐   │
│   │                                                  │   │
│   │  Host OS  Windows 11 + WSL2                      │   │
│   │  Shell    /bin/zsh                               │   │
│   │  Editor   VS Code                                │   │
│   │  Cloud    Google Cloud                           │   │
│   │  Deploy   Vercel, Cloud Run                      │   │
│   │                                                  │   │
│   └──────────────────────────────────────────────────┘   │
│                                                          │
│   ┌── LOADING SESSION ─────────────────────────────┐    │
│   │                                                  │   │
│   │  Loading dotfiles             [############]  ✓   │   │
│   │  Initializing shell plugins   [############]  ✓   │   │
│   │  Connecting cloud services    [############]  ✓   │   │
│   │  Warming AI runtimes          [############]  ✓   │   │
│   │                                                  │   │
│   └──────────────────────────────────────────────────┘   │
│                                                          │
└──────────────────────────────────────────────────────────┘

Login successful. Welcome, rahul.

┌── MOTD ───────────────────────────────────────────────┐
│                                                       │
│   "Build AI that solves real problems.                 │
│    Not AI that impresses AI engineers."                 │
│                                                       │
└───────────────────────────────────────────────────────┘

```

<br>

<!-- ═══════════ WHOAMI ═══════════ -->

```
rahul@rahulos:~$ whoami

Rahul Shyam

AI Product Builder
Civil Engineering Student
Full-Stack Developer

Building practical AI products using
Computer Vision, LLMs, and Cloud Infrastructure.

```

<br>

<!-- ═══════════ DESKTOP ═══════════ -->

```
╭─────────────────────── RahulOS v3.7 AI ──────────────────────────╮
│                                                                  │
│   [ Desktop ]  [ Engine ]  [ Services ]  [ Modules ]  [ Log ]    │
│                                                                  │
│   ┌──────────────────────────────────────────────────────────┐   │
│   │                                                          │   │
│   │       AI OPERATING SYSTEM READY                          │   │
│   │                                                          │   │
│   │       rahul@rahulos:~$ _                                 │   │
│   │                                                          │   │
│   └──────────────────────────────────────────────────────────┘   │
│                                                                  │
╰──────────────────────────────────────────────────────────────────╯

```

<br>

```
rahul@rahulos:~$ ls -la /home/rahul/

total 80
drwxr-xr-x  12 rahul rahul  4096 Jul  9 00:42 .
drwxr-xr-x   3 root  root    4096 Jul  1 00:00 ..
drwxr-xr-x   7 rahul rahul  4096 Jul  9 00:42 projects/
drwxr-xr-x   3 rahul rahul  4096 Jul  9 00:42 services/
drwxr-xr-x   2 rahul rahul  4096 Jul  9 00:42 experience/
drwxr-xr-x   2 rahul rahul  4096 Jul  9 00:42 roadmap/
-rw-r--r--   1 rahul rahul   512 Jul  9 00:42 about.txt
-rw-r--r--   1 rahul rahul  1024 Jul  9 00:42 now.txt
-rw-r--r--   1 rahul rahul   256 Jul  9 00:42 contact.txt
drwx------   2 rahul rahul  4096 Jul  9 00:42 .config/
lrwxrwxrwx   1 rahul rahul    39 Jul  9 00:42 rahul.live -> https://rahulshyam-portfolio.vercel.app/

```

<br>

<!-- ═══════════ PROJECT EXPLORER ═══════════ -->

```
rahul@rahulos:~$ tree projects/

projects/
├── LooksMax AI/
│   ├── Gemini Vision
│   ├── InsightFace
│   └── Cloud Run
├── CivilVision AI/
│   ├── React
│   ├── Gemini API
│   └── Firebase
├── AutoBOM/
│   ├── OCR Pipeline
│   ├── AI Parsing
│   └── Supabase
├── StudySense/
│   ├── Next.js
│   ├── Firebase
│   └── Vercel
├── TypeArena/
│   ├── Next.js
│   ├── Tailwind CSS
│   └── Vercel
├── FallGuard/
│   ├── Computer Vision
│   └── Sensors
├── Hostel Planner/
│   ├── React
│   └── PostgreSQL

```

<br>

<!-- ═══════════ AI ENGINE PANEL ═══════════ -->

```
rahul@rahulos:~$ rahul-ai status

╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║  ── ROUTING ───────────────────────────────────────────────  ║
║                                                              ║
║  ROUTE        MODEL              STATUS           LATENCY    ║
║  ─────────────────────────────────────────────────────────── ║
║                                                              ║
║  Vision       Gemini Flash       ● ONLINE         340ms     ║
║  Reasoning    Gemini 2.5 Pro     ● ONLINE         820ms     ║
║  Code         DeepSeek Coder      ○ STANDBY        —        ║
║  Fallback     Claude Sonnet       ○ STANDBY        —        ║
║  Local        Ollama CodeLlama   ● ACTIVE         1.2s      ║
║                                                              ║
║  Fallback chain: Gemini Pro → Claude → DeepSeek             ║
║  Auto-failover: enabled    Failovers today: 0              ║
║                                                              ║
║  ── SUBSYSTEMS ────────────────────────────────────────────  ║
║                                                              ║
║  ┌──────────────────────┐ ┌──────────────────────────────┐   ║
║  │ Prompt Routing        │ │ Vision Analysis              │   ║
║  │ ● ACTIVE              │ │ ● RUNNING                    │   ║
║  │ Route: Reasoning      │ │ Pipeline: InsightFace        │   ║
║  │ Load: nominal         │ │ Queue depth: 0               │   ║
║  └──────────────────────┘ └──────────────────────────────┘   ║
║                                                              ║
║  ┌──────────────────────┐ ┌──────────────────────────────┐   ║
║  │ Identity Cache        │ │ Embedding Service            │   ║
║  │ ● READY               │ │ ● ACTIVE                     │   ║
║  │ Face database mounted │ │ Dimension: 512               │   ║
║  │ Ready for enrollment  │ │ Store: initialized           │   ║
║  └──────────────────────┘ └──────────────────────────────┘   ║
║                                                              ║
╚═══════════════════════════════════════════════════════════════╝

```

<br>

<!-- ═══════════ EXPERIENCE ═══════════ -->

```
rahul@rahulos:~$ cat /home/rahul/experience/work.txt

┌──────────────────────────────────────────────────────────┐
│                                                          │
│   ROLE               ORGANIZATION              PERIOD    │
│   ────────────────────────────────────────────────────   │
│                                                          │
│   Site Engineering   Tata Projects             2024      │
│   Intern             Chennai Underground Metro           │
│                                                          │
│   BIM Intern         Pinnacle Future Build     Jun–Jul   │
│                      Madurai                   2026      │
│                                                          │
│   Domain: Civil Engineering · AI · Software              │
│                                                          │
└──────────────────────────────────────────────────────────┘

```

<br>

<!-- ═══════════ SYSTEM STATUS ═══════════ -->

```
rahul@rahulos:~$ rahul-ai system

╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║  STATUS    : RUNNING                                         ║
║  MODE      : AI PRODUCT ENGINEERING                          ║
║  SESSION   : 0d 0h 12m (since boot)                         ║
║  FOCUS     : LooksMax AI — Computer Vision · Face Memory    ║
║                                                              ║
║  ┌─────────────────────────┐ ┌─────────────────────────────┐ ║
║  │ DEPLOY TARGETS          │ │ RUNNING SERVICES            │ ║
║  │                         │ │                             │ ║
║  │ Vercel           ONLINE │ │ Prompt Router      1148 ◉   │ ║
║  │ Cloud Run        ACTIVE │ │ Vision Engine      1152 ◉   │ ║
║  │ Firebase         ONLINE │ │ Face Memory         2184 ◉   │ ║
║  │ GH Actions      PASSING │ │ LooksMax AI         2191 ◉   │ ║
║  │                         │ │ CivilVision AI      2203 ◉   │ ║
║  │ ── BUILD HISTORY ──     │ │ StudySense          2230 ◉   │ ║
║  │ [22:14] Build #128 ✓    │ │ TypeArena           2241 ◉   │ ║
║  │ [21:55] Build #127 ✓    │ │ AutoBOM             2257 ◉   │ ║
║  │ [21:30] Build #126 ✓    │ │                     ───     │ ║
║  │                         │ │ 8 services running         │ ║
║  └─────────────────────────┘ └─────────────────────────────┘ ║
║                                                              ║
╚═══════════════════════════════════════════════════════════════╝

```

<br>

<!-- ═══════════ TOOLCHAIN ═══════════ -->

```
rahul@rahulos:~$ rahul-ai toolchain

╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║  AVAILABLE TOOLCHAIN                                        ║
║                                                              ║
║  TypeScript     React           Next.js          Python      ║
║  Gemini SDK     Firebase SDK    InsightFace       OpenCV     ║
║  Tailwind CSS   Supabase        Three.js          Google Cloud ║
║                                                              ║
║  12 tools — active toolchain                                 ║
║                                                              ║
╚═══════════════════════════════════════════════════════════════╝

```

<br>

<!-- ═══════════ MAN PAGE ═══════════ -->

```
rahul@rahulos:~$ man rahul

NAME
     rahul — AI product builder and full-stack engineer

SYNOPSIS
     rahul [--build]  [--deploy]  [--collaborate]

DESCRIPTION
     Builds AI-powered software from prototype to production.
     Focuses on computer vision, multimodal AI systems,
     full-stack web development, and AI applications for
     civil engineering.

     Ships on Vercel and Google Cloud Run.
     Uses Gemini and InsightFace for AI workloads.
     Writes TypeScript, Python, and React daily.

AREAS OF WORK

     Multi-model AI systems   Computer Vision / face recognition
     LLM-powered products     Prompt engineering / routing
     Cloud-native full-stack  Next.js / Firebase / Cloud Run
     Civil engineering AI     Construction tech / automation
     Developer tools          Type-safe frontends / design systems

SEE ALSO
     rahul.live(1)
     github.com/rahulcvwebsitehosting(7)

AUTHOR
     Rahul Shyam
     Chennai, India
     B.E. Civil Engineering, ESEC

```

<br>

<!-- ═══════════ SYSTEM STATS ═══════════ -->

```
rahul@rahulos:~$ rahul-ai stats

╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║  Focus areas                                                ║
║    LooksMax AI     Computer Vision · Face Memory            ║
║    CivilVision     AI for civil engineering                 ║
║    StudySense      Full-stack · Firebase                    ║
║    TypeArena       Competitive typing · Next.js             ║
║    AutoBOM         Document parsing · Gemini Vision         ║
║                                                              ║
║  Languages: TypeScript, Python, JavaScript, C++             ║
║  Deploy targets: Vercel, Cloud Run, Firebase, Supabase       ║
║                                                              ║
╚═══════════════════════════════════════════════════════════════╝

```

<br>

<!-- ═══════════ SESSION LOG ═══════════ -->

```
rahul@rahulos:~$ cat /var/log/session

[00:42:13] session: User rahul authenticated — environment loaded
[00:42:14] router:  Gemini adapter connected — primary route ready
[00:42:15] vision:  InsightFace pipeline initialized
[00:42:16] storage: Firebase Firestore sync OK
[00:42:16] deploy:  Cloud Run agent reporting healthy
[00:42:17] deploy:  Vercel edge functions — 0 errors
[00:42:18] system:  All 8 services running — session ready
[00:42:20] kernel:  RahulOS 3.7.0 — AI operating mode
[00:42:21] shell:   Ready for input

```

<br>

<!-- ═══════════ ROADMAP ═══════════ -->

```
rahul@rahulos:~$ cat /home/rahul/roadmap/tracker.txt

╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   Stable  : v3.7.0                                           ║
║   Next    : v3.8.0 (Q1 2027)                                 ║
║   Research: v4.0.0                                           ║
║                                                              ║
║   ── v3.7.0 — SHIPPED ─────────────────────────────────      ║
║                                                              ║
║     LooksMax AI         Multi-model facial analysis          ║
║     CivilVision AI      AI civil engineering helpbook        ║
║     AutoBOM             AI bill-of-materials from drawings   ║
║     StudySense          Study management platform            ║
║     TypeArena           Competitive typing                   ║
║     RahulOS v3.7        AI OS profile README                ║
║                                                              ║
║   ── v3.8.0 — BUILDING ──────────────────────────────────    ║
║                                                              ║
║     FallGuard           Fall detection — CV + sensors        ║
║     Hostel Planner      Room allocation + RDBMS              ║
║                                                              ║
║   ── v4.0.0 — EXPLORING ─────────────────────────────────    ║
║                                                              ║
║     TunnelViz           3D tunnel construction viz           ║
║     OSB ETA             OSB delivery prediction              ║
║                                                              ║
║   NOTE: Building in public. Timelines are fluid.             ║
║                                                              ║
╚═══════════════════════════════════════════════════════════════╝

```

<br>

<!-- ═══════════ CONTACT ═══════════ -->

```
rahul@rahulos:~$ cat /home/rahul/contact.txt

┌──────────────────────────────────────────────────────────┐
│                                                          │
│  Portfolio   rahulshyam-portfolio.vercel.app    ONLINE   │
│  GitHub      github.com/rahulcvwebsitehosting  ACTIVE    │
│  LinkedIn    linkedin.com/in/rahulshyamcivil   AVAILABLE │
│  X           x.com/RahulShyamCV                IDLE      │
│  Threads     threads.net/@rahulcvjps           IDLE      │
│                                                          │
│  Chennai, India · B.E. Civil Engineering @ ESEC         │
│  Active hours: 0600–2300 IST                             │
│                                                          │
└──────────────────────────────────────────────────────────┘

```

<br>

<!-- ═══════════ SHUTDOWN ═══════════ -->

```
rahul@rahulos:~$ exit
logout

═══════════════════════════════════════════════════════════

Broadcast message from rahul@rahulos (Thu Jul  9 2026):

┌──────────────────────────────────────────────────────────┐
│                                                          │
│   /etc/motd:                                             │
│                                                          │
│   "The system will now shut down.                         │
│    All AI models have been persisted to disk.             │
│                                                          │
│    Build things that matter.                              │
│    Ship AI that solves real problems.                     │
│                                                          │
│    — RahulOS v3.7.0 AI                                    │
│                                                          │
└──────────────────────────────────────────────────────────┘

Connection to github.com/rahulcvwebsitehosting closed.

```

<br>
<br>
<br>

```
System halted.

[ power down complete ]
```

<br>
<br>

<!--
  ╔══════════════════════════════════════════════════════════════╗
  ║  RahulOS v3.7.0 AI — Built with real products.              ║
  ║  github.com/rahulcvwebsitehosting                             ║
  ╚══════════════════════════════════════════════════════════════╝
-->