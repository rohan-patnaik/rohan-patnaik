### Hi there, I'm Rohan! <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="20">

<blockquote>
I'm a ML engineer from India, and Python/Go are my languages of choice.<br>
I'm a big fan of ML projects and always up for collaborating on cool ideas.
</blockquote>

[Portfolio](https://rohan-patnaik.github.io)&nbsp;&nbsp;&nbsp;&nbsp;[LinkedIn](https://www.linkedin.com/in/rohan-patnaik-88929b159)

Connect with me -> [here!](https://rohan-patnaik.github.io/#contact)

Thanks for visiting here. Follow for more open-source and AI work I'm part of.

---

## Popular OSS work

*20+ merged PRs across Google, Meta, Microsoft, Grafana Labs, T3 and more (290k★ combined).*

| Company | Merged PRs | Projects |
|:--|:--:|:--|
| <img src="https://github.com/google.png?size=40" width="20" height="20" align="absmiddle"> **Google** | 6 | [go-containerregistry](https://github.com/google/go-containerregistry), [cel-go](https://github.com/cel-expr/cel-go), [osv-scanner](https://github.com/google/osv-scanner) |
| <img src="https://github.com/facebook.png?size=40" width="20" height="20" align="absmiddle"> **Meta** | 6 | [Lexical](https://github.com/facebook/lexical), [BoTorch](https://github.com/meta-pytorch/botorch), [Docusaurus](https://github.com/facebook/docusaurus), [TorchFT](https://github.com/meta-pytorch/torchft) |
| <img src="https://github.com/microsoft.png?size=40" width="20" height="20" align="absmiddle"> **Microsoft** | 3 | [ONNX Runtime](https://github.com/microsoft/onnxruntime), [Playwright for Python](https://github.com/microsoft/playwright-python), [Azure CLI](https://github.com/Azure/azure-cli) |
| <img src="https://github.com/grafana.png?size=40" width="20" height="20" align="absmiddle"> **Grafana Labs** | 3 | [k6](https://github.com/grafana/k6) |
| <img src="https://github.com/pingdotgg.png?size=40" width="20" height="20" align="absmiddle"> **T3** | 2 | [T3 Code](https://github.com/pingdotgg/t3code) |
| <img src="https://github.com/openclaw.png?size=40" width="20" height="20" align="absmiddle"> **OpenClaw** | 2 | [gogcli](https://github.com/openclaw/gogcli) |
| <img src="https://github.com/aaif-goose.png?size=40" width="20" height="20" align="absmiddle"> **Agentic AI Foundation** | 1 | [goose](https://github.com/aaif-goose/goose) |
| <img src="https://github.com/Unstructured-IO.png?size=40" width="20" height="20" align="absmiddle"> **Unstructured** | 1 | [Unstructured](https://github.com/Unstructured-IO/unstructured) |

<details open>
<summary><b>What each PR did</b></summary>

### Google

#### <img src="https://github.com/google.png?size=32" width="24" height="24" align="absmiddle"> [google/go-containerregistry](https://github.com/google/go-containerregistry) (4k★)

- [PR #2314](https://github.com/google/go-containerregistry/pull/2314) - Ensured only true loopback hosts get plain-HTTP registry access.
- [PR #2315](https://github.com/google/go-containerregistry/pull/2315) - Let push-only workflows skip Kubernetes pull secrets.
- [PR #2316](https://github.com/google/go-containerregistry/pull/2316) - Kept `localhost/...` image references pointing at the local registry.

#### <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/go/go-original.svg" width="24" height="24" align="absmiddle" alt="Go"> [cel-expr/cel-go](https://github.com/cel-expr/cel-go) (3k★)

- [PR #1340](https://github.com/cel-expr/cel-go/pull/1340) - Added a JSON encoder to CEL’s standard extensions.
- [PR #1327](https://github.com/cel-expr/cel-go/pull/1327) - Allowed container aliases for simple names, with validation still strict.

#### <img src="https://github.com/google.png?size=32" width="24" height="24" align="absmiddle"> [google/osv-scanner](https://github.com/google/osv-scanner) (11k★)

- [PR #2808](https://github.com/google/osv-scanner/pull/2808) - Removed duplicate vulnerability queries in bulk scans, keeping result order.

### Meta

#### <img src="https://github.com/facebook.png?size=32" width="24" height="24" align="absmiddle"> [facebook/lexical](https://lexical.dev/) (24k★)

- [PR #8539](https://github.com/facebook/lexical/pull/8539) - Fixed collapsible blocks breaking on empty or inline-only content.
- [PR #8541](https://github.com/facebook/lexical/pull/8541) - Added markdown round-trip tests for bold-italic text.

#### <img src="https://github.com/meta-pytorch.png?size=32" width="24" height="24" align="absmiddle"> [meta-pytorch/botorch](https://github.com/meta-pytorch/botorch) (3.6k★)

- [PR #3370](https://github.com/meta-pytorch/botorch/pull/3370) - Fixed sampling from batched truncated normal distributions, which used to reject batched constraints.
- [PR #3372](https://github.com/meta-pytorch/botorch/pull/3372) - Let nonlinear-constrained optimization start from infeasible points, since SLSQP can repair them.

#### <img src="https://docusaurus.io/img/docusaurus.svg" width="22" height="22" align="absmiddle"> [facebook/docusaurus](https://docusaurus.io/) (67k★)

- [PR #12054](https://github.com/facebook/docusaurus/pull/12054) - Fixed localized sites publishing wrong URLs in metadata and sitemaps.

#### <img src="https://github.com/meta-pytorch.png?size=32" width="24" height="24" align="absmiddle"> [meta-pytorch/torchft](https://github.com/meta-pytorch/torchft) (552★)

- [PR #356](https://github.com/meta-pytorch/torchft/pull/356) - Made checkpoint transfers honour the transport's configured timeout by default.

### Microsoft

#### <img src="https://github.com/microsoft.png?size=32" width="24" height="24" align="absmiddle"> [microsoft/onnxruntime](https://github.com/microsoft/onnxruntime) (22k★)

- [PR #32846](https://github.com/microsoft/onnxruntime/pull/32846) - Enabled int8 and uint32 support in the CPU `Where` operator.

#### <img src="https://github.com/microsoft.png?size=32" width="24" height="24" align="absmiddle"> [microsoft/playwright-python](https://playwright.dev/python/) (15k★)

- [PR #3084](https://github.com/microsoft/playwright-python/pull/3084) - Fixed handlers with keyword-only parameters getting the wrong arguments.

#### <img src="https://github.com/Azure.png?size=32" width="24" height="24" align="absmiddle"> [Azure/azure-cli](https://github.com/Azure/azure-cli) (4.6k★)

- [PR #33429](https://github.com/Azure/azure-cli/pull/33429) - Kept `az vm image list` working when the remote alias file is malformed.

### Grafana Labs

#### <img src="https://github.com/grafana.png?size=32" width="24" height="24" align="absmiddle"> [grafana/k6](https://github.com/grafana/k6) (32k★)

- [PR #6071](https://github.com/grafana/k6/pull/6071) - Added static labels so Prometheus metrics from parallel k6 runs stay distinguishable.
- [PR #6070](https://github.com/grafana/k6/pull/6070) - Stopped recent console logs getting lost by flushing file logs during runs.
- [PR #6002](https://github.com/grafana/k6/pull/6002) - Added `single()` to grab the first matching element in k6/html.

### T3

#### <img src="https://github.com/pingdotgg.png?size=32" width="24" height="24" align="absmiddle"> [pingdotgg/t3code](https://github.com/pingdotgg/t3code) (31k★)

- [PR #19923](https://github.com/pingdotgg/t3code/pull/19923) - Stopped large image attachments stalling the chat timeline by decoding them asynchronously.
- [PR #12768](https://github.com/pingdotgg/t3code/pull/12768) - Made desktop builds report one consistent version across the client, server and package.

### OpenClaw

#### 🦞 [openclaw/gogcli](https://gogcli.sh) (8.5k★)

- [PR #554](https://github.com/openclaw/gogcli/pull/554) - Added read-only Drive reports: tree views, folder summaries and inspection.
- [PR #555](https://github.com/openclaw/gogcli/pull/555) - Added a safe preview for finding duplicate Google Contacts.
- [PR #116](https://github.com/openclaw/gogcli/pull/116) - Introduced the original Drive reporting, Drive sync, and contacts dedupe contribution.

### Agentic AI Foundation

#### <img src="https://github.com/aaif-goose.png?size=32" width="24" height="24" align="absmiddle"> [aaif-goose/goose](https://github.com/aaif-goose/goose) (56k★)

- [PR #12516](https://github.com/aaif-goose/goose/pull/12516) - Kept session context alive across the agent's reply lifecycle, including ACP delegation and resumes.

### Unstructured

#### <img src="https://github.com/Unstructured-IO.png?size=32" width="24" height="24" align="absmiddle"> [Unstructured-IO/unstructured](https://github.com/Unstructured-IO/unstructured) (16k★)

- [PR #4504](https://github.com/Unstructured-IO/unstructured/pull/4504) - Kept element IDs and source metadata intact when reloading Unstructured's own JSON output.

</details>

## Current Projects


- <img src="assets/codebloom-logo.png" width="18" height="18" alt="Codebloom" align="absmiddle"> [Codebloom](https://github.com/rohan-patnaik/codebloom) : See any codebase bloom into a mind map, with call arrows across files. On VS Code, Open VSX & JetBrains.
- 🔌 [subpool](https://github.com/rohan-patnaik/subpool) : Your Claude, ChatGPT and Gemini subscriptions as one fast API: a single Rust binary with a built-in dashboard.
- 📅 [OpenCalendly](https://opencalendly.com) : Open-source Calendly: share a link, take 1:1 or team bookings, synced to your calendar.
- 📄 [ZenPDF](https://thezenpdf.vercel.app) : Clean, open-source PDF workbench with practical tools and transparent usage limits.
- <img src="assets/gogcli-plus-google-g.png" width="18" height="18" alt="Google G" align="absmiddle"> [gogcli-plus](https://github.com/rohan-patnaik/gogcli-plus) : Supercharge gogcli with Drive reports, local↔Drive sync and contact deduplication.
- 📘 [Paperloop](https://mypaperloop.vercel.app) : Explore Ilya Sutskever’s must-read AI papers in a Minecraft-style mini world.
- ඞ [Pasture Imposters](https://pasture-imposters-web.pages.dev) : Among Us on a Pokémon-style farm: make your avatar and catch the imposter.
- Ⓩ [ZenPDF for Omarchy](https://omarchyplugins.com/plugin.html?id=io.github.rohan-patnaik.zenpdf) : An offline-first Acrobat alternative for Omarchy and Arch Linux, in the works.
- 🃏 [Solitaire](https://omarchyplugins.com/plugin.html?id=io.github.rohan-patnaik.solitaire) : Five classic solitaire games, offline and ad-free, for Omarchy.
- ◎ [Orbit](https://omarchyplugins.com/plugin.html?id=io.github.rohan-patnaik.window-switcher) : A better Alt+Tab for Omarchy: macOS icons, Windows 7 stacks or a Windows 11 grid.
- 🎨 [Chromarchy](https://github.com/rohan-patnaik/Chromarchy) : A local-first Photoshop alternative for Omarchy and Arch Linux, in the works.

### 🛠 Tech Stack

Some of the tools and tech I’ve been working with recently:

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-111111?style=flat)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=amazon-dynamodb&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Kubeflow Pipelines](https://img.shields.io/badge/Kubeflow%20Pipelines-4285F4?style=flat&logo=kubeflow&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---
