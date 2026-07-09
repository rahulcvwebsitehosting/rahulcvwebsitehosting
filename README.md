<!--
  ╔══════════════════════════════════════════════════════════════╗
  ║                    RAHULOS v3.7 AI                           ║
  ║                    github.com/rahulcvwebsitehosting            ║
  ╚══════════════════════════════════════════════════════════════╝
-->

<br>

<!-- ═══════════ BOOT ═══════════ -->

```
RahulOS 3.7.0-ai (rahul-cv-01) │ tty1

[    0.000000] Booting system...
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
[    1.841006] Initramfs unpacking: Initializing userland...
[    2.101483] Freeing initrd memory: 32768K

─── SERVICE MANAGER INIT ────────────────────────────────

[  OK  ] Started gemini-adapter.service          — Multi-model routing
[  OK  ] Started vision-pipeline.service          — Computer Vision
[  OK  ] Started insightface-runtime.service      — Face Recognition
[  OK  ] Started ollama-bridge.service            — Local LLM runtime
[  OK  ] Started api-gateway.socket               — Next.js API routes
[  OK  ] Started dev-server.socket                — Vite dev server
[  OK  ] Started firebase-connector.service       — Firebase backend
[  OK  ] Started cloud-run-agent.service          — Cloud Run
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
│   │  Host      Windows 11 + WSL2                     │   │
│   │  Shell     /bin/zsh                              │   │
│   │  Editor    VS Code                               │   │
│   │  Cloud     Google Cloud                          │   │
│   │  Deploy    Vercel, Cloud Run                     │   │
│   │                                                  │   │
│   └──────────────────────────────────────────────────┘   │
│                                                          │
└──────────────────────────────────────────────────────────┘

Login successful.

```

<br>

<!-- ═══════════ SYSTEM INFORMATION ═══════════ -->

```
rahul@rahulos:~$ fastfetch

rahul@rahulos
--------------
OS: RahulOS 3.7.0-ai
Shell: zsh 5.9
Editor: VS Code
Languages: TypeScript, Python, JavaScript, C++
Stack: React, Next.js, Gemini, Firebase, Cloud Run, Vercel
Location: Chennai, India
Portfolio: rahulshyam-portfolio.vercel.app
GitHub: github.com/rahulcvwebsitehosting

```

<br>

<!-- ═══════════ AVAILABLE COMMANDS ═══════════ -->

```
rahul@rahulos:~$ help

Available commands
  fastfetch    System information
  ls           List files
  tree         Browse projects
  rahul-ai     Engine and service status
  man rahul    Developer manual
  fortune      Random note
  exit         End session

```

<br>

<!-- ═══════════ DESKTOP / FILE SYSTEM ═══════════ -->

```
╭───────────────────────── Terminal ─────────────────────────────╮
│                                                                  │
│   [ ~ ]  [ projects/ ]  [ services/ ]  [ .config/ ]  [ help ]   │
│                                                                  │
│   ┌──────────────────────────────────────────────────────────┐   │
│   │                                                          │   │
│   │       rahul@rahulos:~$ _                                 │   │
│   │                                                          │   │
│   └──────────────────────────────────────────────────────────┘   │
│                                                                  │
╰──────────────────────────────────────────────────────────────────╯

```

<br>

```
rahul@rahulos:~$ ls -la

total 72
drwxr-xr-x  10 rahul rahul  4096 Jul  9 00:42 .
drwxr-xr-x   3 root  root    4096 Jul  1 00:00 ..
drwxr-xr-x   7 rahul rahul  4096 Jul  9 00:42 projects/
drwxr-xr-x   3 rahul rahul  4096 Jul  9 00:42 services/
drwxr-xr-x   2 rahul rahul  4096 Jul  9 00:42 experience/
drwxr-xr-x   2 rahul rahul  4096 Jul  9 00:42 roadmap/
-rw-r--r--   1 rahul rahul   512 Jul  9 00:42 about.txt
-rw-r--r--   1 rahul rahul  1024 Jul  9 00:42 now.txt
drwx------   2 rahul rahul  4096 Jul  9 00:42 .config/
lrwxrwxrwx   1 rahul rahul    39 Jul  9 00:42 rahul.live -> https://rahulshyam-portfolio.vercel.app/

```

<br>

<!-- ═══════════ PROJECT TREE ═══════════ -->

```
rahul@rahulos:~$ tree projects/

projects/
├── LooksMax-AI/
│   ├── backend/
│   ├── frontend/
│   ├── models/
│   └── deploy/
├── CivilVision-AI/
│   ├── app/
│   ├── model/
│   └── research/
├── AutoBOM/
│   ├── parser/
│   ├── api/
│   └── deploy/
├── StudySense/
│   ├── web/
│   ├── api/
│   └── infra/
├── TypeArena/
│   ├── client/
│   ├── server/
│   └── public/
├── FallGuard/
│   ├── detection/
│   └── hardware/
├── Hostel-Planner/
│   ├── backend/
│   └── schema/

```

<br>

<!-- ═══════════ AI ENGINE STATUS ═══════════ -->

```
rahul@rahulos:~$ rahul-ai status

Router        ONLINE     Gemini 2.5 Pro (primary)
Vision        READY      InsightFace pipeline
Identity      READY      Face cache
Embeddings    ACTIVE     Dense vector store
Deployments   HEALTHY    Vercel · Cloud Run · Firebase

Fallback: Gemini Pro → Claude → DeepSeek

```

<br>

<!-- ═══════════ EXPERIENCE ═══════════ -->

```
rahul@rahulos:~$ cat experience/work.txt

  ROLE               ORGANIZATION                  PERIOD
  ──────────────────────────────────────────────────────────
  Site Engineering   Tata Projects                 2024
  Intern             Chennai Underground Metro

  BIM Intern         Pinnacle Future Build         Jun–Jul 2026
                     Madurai

  Domain: Civil Engineering · AI · Software

```

<br>

<!-- ═══════════ SERVICE STATUS ═══════════ -->

```
rahul@rahulos:~$ rahul-ai services

Status     RUNNING
Focus      LooksMax AI — Computer Vision · Face Memory

Deploy targets
  Vercel       ONLINE
  Cloud Run    ACTIVE
  Firebase     ONLINE
  GH Actions   PASSING

Running services
  Prompt Router · Vision Engine · Face Memory
  LooksMax AI · CivilVision AI · StudySense
  TypeArena · AutoBOM

```

<br>

<!-- ═══════════ INSTALLED TOOLS ═══════════ -->

```
rahul@rahulos:~$ which node python docker git

/usr/bin/node
/usr/bin/python3
/usr/bin/docker
/usr/bin/git

```

<br>

```
rahul@rahulos:~$ which --list

node          /usr/bin/node          v22.0.0
python        /usr/bin/python3       v3.12.0
docker        /usr/bin/docker        v27.0.0
git           /usr/bin/git           v2.45.0
npm           /usr/bin/npm           v10.8.0
tsc           /usr/bin/tsc           v5.6.0

```

<br>

<!-- ═══════════ MANUAL ═══════════ -->

```
rahul@rahulos:~$ man rahul

NAME
     rahul — full-stack developer and AI engineer

SYNOPSIS
     rahul [--build project] [--deploy target] [--help]

DESCRIPTION
     Builds software from prototype to production.
     Focuses on computer vision, multimodal systems,
     full-stack web development, and AI applications
     for civil engineering.

     Ships on Vercel and Google Cloud Run.
     Uses Gemini and InsightFace for AI workloads.
     Writes TypeScript, Python, and React daily.

OPTIONS
     --build project     Build from concept to deployment.
     --deploy target     Ship to Vercel, Cloud Run, or Firebase.
     --help              Display this manual.

EXAMPLES
     rahul --build looksmax-ai
             Multi-model facial analysis platform.

     rahul --build civilvision-ai
             AI civil engineering helpbook.

     rahul --deploy cloud-run
             Deploy backend to Google Cloud Run.

FILES
     ~/projects/         Source code and assets.
     ~/services/         Running application configs.
     ~/experience/       Work history.

AUTHOR
     Rahul Shyam
     Chennai, India
     B.E. Civil Engineering, ESEC

SEE ALSO
     github.com/rahulcvwebsitehosting

```

<br>

<!-- ═══════════ FORTUNE ═══════════ -->

```
rahul@rahulos:~$ fortune

"The best code is the code you never had to write.
 Build things that make other builders faster."

```

<br>

<!-- ═══════════ SESSION LOG ═══════════ -->

```
rahul@rahulos:~$ cat /var/log/session

[00:42:13] session: User rahul authenticated — environment loaded
[00:42:14] router:  Gemini adapter connected — primary route ready
[00:42:15] vision:  InsightFace pipeline initialized
[00:42:16] storage: Firebase Firestore sync OK
[00:42:17] deploy:  Cloud Run agent reporting healthy
[00:42:18] system:  All services running — session ready
[00:42:20] kernel:  System ready
[00:42:21] shell:   Ready for input

```

<br>

<!-- ═══════════ ROADMAP ═══════════ -->

```
rahul@rahulos:~$ cat roadmap/tracker.txt

Stable   v3.7.0

  LooksMax AI         Multi-model facial analysis
  CivilVision AI      AI civil engineering helpbook
  AutoBOM             AI bill-of-materials from drawings
  StudySense          Study management platform
  TypeArena           Competitive typing
  RahulOS v3.7        Profile README

Next     v3.8.0 (Q1 2027)

  FallGuard           Fall detection — CV + sensors
  Hostel Planner      Room allocation + RDBMS

Research v4.0.0

  TunnelViz           3D tunnel construction viz
  OSB ETA             Delivery prediction

-- Building in public. Timelines are fluid.

```

<br>

<!-- ═══════════ CONTACT ═══════════ -->

```
rahul@rahulos:~$ cat .config/contact

Portfolio  rahulshyam-portfolio.vercel.app
GitHub     github.com/rahulcvwebsitehosting
LinkedIn   linkedin.com/in/rahulshyamcivil
X          x.com/RahulShyamCV
           threads.net/@rahulcvjps

Chennai, India
B.E. Civil Engineering, ESEC

```

<br>

<!-- ═══════════ SHUTDOWN ═══════════ -->

```
rahul@rahulos:~$ exit
logout

Saving session...

[  OK  ] Shell history written
[  OK  ] AI services stopped
[  OK  ] Filesystems unmounted

System halted.
```

<br>
<br>

<!--
  ╔══════════════════════════════════════════════════════════════╗
  ║  RahulOS v3.7 — github.com/rahulcvwebsitehosting            ║
  ╚══════════════════════════════════════════════════════════════╝
-->