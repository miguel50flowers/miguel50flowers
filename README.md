<a href="https://github.com/miguel50flowers">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,2,20,30&height=180&section=header&text=Miguel%20Angel%20Esparza&fontSize=42&fontAlignY=38&fontColor=ffffff&desc=Senior%20Full-Stack%20Engineer%20%C2%B7%20Shopify%20%C2%B7%20AWS%20%C2%B7%20Quito%2C%20Ecuador&descAlignY=58&descSize=15&animation=fadeIn" alt="Miguel Angel Esparza — Senior Full-Stack Engineer header" />
</a>

<p align="right">
  <img src="https://komarev.com/ghpvc/?username=miguel50flowers&style=flat-square&color=blueviolet&label=Profile+views" alt="Profile views counter" />
</p>

<p align="center">
  <a href="https://github.com/miguel50flowers">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=8B5CF6&center=true&vCenter=true&width=720&lines=Senior+Full-Stack+Engineer+%E2%80%A2+10%2B+years+shipping+production+software;Ingeniero+Full-Stack+Senior+%E2%80%A2+10%2B+a%C3%B1os+enviando+software+a+producci%C3%B3n;5+Shopify+embedded+apps+%C2%B7+9%2B+AWS+Lambdas+%C2%B7+11-service+B2B+platform;Image+pipelines+%C2%B7+serverless+%C2%B7+admin+APIs+%C2%B7+macOS+%26+ML+tooling;TypeScript+%C2%B7+Bun+%C2%B7+Hono+%C2%B7+Remix+%C2%B7+Next.js+%C2%B7+Python+%C2%B7+Swift+%C2%B7+PHP" alt="Typing intro: roles, scope, stack" />
  </a>
</p>

---

## About me / Sobre mí

<table>
<tr>
<td width="50%" valign="top">

### EN

I'm Miguel — a senior full-stack engineer based in **Quito, Ecuador**, with **10+ years** shipping production software across e-commerce, B2B platforms, AWS serverless, image pipelines, and macOS/ML tooling.

I currently lead backend and image-pipeline work for **[Farm Exports](https://farmexports.com)** (B2B floral wholesale on Shopify, migrating from Komet Sales to a custom internal platform — *Bloom Brain*), and have shipped **5 Shopify embedded apps**, **9+ AWS Lambdas**, **11+ event-driven services**, and **6 Liquid themes** — most of it within the **[@fifty-git](https://github.com/fifty-git)** organization (Farm Exports, **FlowerFix** / theflowerfix.myshopify.com, and related brands).

On the side I publish small open-source utilities for problems I personally hit, and explore game dev (Godot, Pygame), AI tooling (ComfyUI pipelines, local LLMs) and ML/NLP (CV classification, watermark detection).

I care about **well-typed, well-logged, well-tested software that ships**.

</td>
<td width="50%" valign="top">

### ES

Soy Miguel — ingeniero full-stack senior en **Quito, Ecuador**, con **10+ años** entregando software a producción en e-commerce, plataformas B2B, AWS serverless, pipelines de imagen y herramientas macOS/ML.

Actualmente lidero backend y pipelines de imagen para **[Farm Exports](https://farmexports.com)** (B2B floral wholesale sobre Shopify, migrando de Komet Sales a una plataforma propia — *Bloom Brain*). He entregado **5 Shopify embedded apps**, **9+ AWS Lambdas**, **11+ servicios event-driven** y **6 themes Liquid** — la mayoría dentro de la organización **[@fifty-git](https://github.com/fifty-git)** (Farm Exports, **FlowerFix** / theflowerfix.myshopify.com y marcas relacionadas).

En paralelo publico pequeñas utilidades open-source para problemas que yo mismo encuentro, y exploro game dev (Godot, Pygame), AI tooling (pipelines ComfyUI, LLMs locales) y ML/NLP (clasificación de CVs, detección de watermarks).

Creo en **software bien tipado, bien logueado, bien probado, que se entrega**.

</td>
</tr>
</table>

---

## Currently building / Trabajando actualmente en

- **Bloom Brain platform** — modern internal PIM/OMS replacing Komet Sales for Farm Exports. **Bun · Hono · Prisma · PostgreSQL · Redis · BullMQ** — 30+ admin endpoints, 5 background queues, multi-tenant.
- **Image sync pipeline** — 3000+ products with **template-matching + Tesseract OCR + Ollama GLM-OCR** watermark detection, **ComfyUI Flux2 Klein** AI logo removal on dual-GPU, EXIF correction, S3 + Shopify CDN sync (Pillow · ThreadPoolExecutor with 8 workers · Sharp).
- **ML product matching engine** — 4-component hybrid scoring (TF-IDF + 56 category mappings + 38 color synonyms + grid-search-calibrated weights across 2,401 combinations) mapping 80+ farm SKUs to 1,200+ catalog SKUs (`scikit-learn` · `pandas`).
- **Open-source macOS utilities** — [`fe-image-transform-lite`](https://github.com/miguel50flowers/fe-image-transform-lite) (batch image transforms with live preview) and [`openvpn-mac-fix`](https://github.com/miguel50flowers/openvpn-mac-fix) (auto-restore internet after disconnecting from any of 17 VPN clients).

---

## Tech stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,react,remix,nextjs,nodejs,bun,python,swift,php,laravel,ruby,rust&perline=12" alt="Languages and frameworks: TypeScript, React, Remix, Next.js, Node.js, Bun, Python, Swift, PHP, Laravel, Ruby, Rust" />
  </a>
  <br />
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=docker,aws,azure,postgres,mysql,redis,prisma,graphql,tailwind,vite,git,githubactions&perline=12" alt="Infra and tooling: Docker, AWS, Azure, PostgreSQL, MySQL, Redis, Prisma, GraphQL, Tailwind, Vite, Git, GitHub Actions" />
  </a>
</p>

<p align="center"><sub>

Plus: **Shopify** (GraphQL · REST · Liquid · Functions · Checkout & Customer Account Extensions · App Proxy · App Bridge · Polaris · Theme App Extensions) · Hono · Drizzle ORM · Express · AWS **SAM** / **Serverless Framework** · Lambda · SES · S3 · SQS · Secrets Manager · DynamoDB · Pillow · OpenCV · PyTorch · Sharp · Playwright · ComfyUI · Ollama · BullMQ · Twilio · Avalara · HubSpot · QuickBooks · GitHub Actions

</sub></p>

---

## Open source / Proyectos open-source

<table>
<tr>
<td width="50%" valign="top">

### `openvpn-mac-fix`
[![openvpn-mac-fix repo card](https://github-readme-stats.vercel.app/api/pin/?username=miguel50flowers&repo=openvpn-mac-fix&hide_border=true&theme=tokyonight)](https://github.com/miguel50flowers/openvpn-mac-fix)

[![Stars](https://img.shields.io/github/stars/miguel50flowers/openvpn-mac-fix?style=flat-square&color=8B5CF6)](https://github.com/miguel50flowers/openvpn-mac-fix/stargazers)
[![Swift](https://img.shields.io/badge/Swift-macOS%2013%2B-orange?style=flat-square&logo=swift&logoColor=white)](https://github.com/miguel50flowers/openvpn-mac-fix)

SwiftUI menu-bar app + privileged helper that **auto-restores internet** after disconnecting from any of **17 supported VPN clients** (OpenVPN · WireGuard · NordVPN · Cisco AnyConnect · Zscaler · …). XPC architecture, DNS/DHCP/firewall cleanup, real-time status, in-app log viewer, Sparkle auto-updates. Distributed via DMG, .pkg and Homebrew.

</td>
<td width="50%" valign="top">

### `fe-image-transform-lite`
[![fe-image-transform-lite repo card](https://github-readme-stats.vercel.app/api/pin/?username=miguel50flowers&repo=fe-image-transform-lite&hide_border=true&theme=tokyonight)](https://github.com/miguel50flowers/fe-image-transform-lite)

[![Stars](https://img.shields.io/github/stars/miguel50flowers/fe-image-transform-lite?style=flat-square&color=8B5CF6)](https://github.com/miguel50flowers/fe-image-transform-lite/stargazers)
[![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/miguel50flowers/fe-image-transform-lite)

macOS desktop app for **batch image transforms with live preview** — flip · rotate · safe square crop · resize % · brightness/contrast/sharpness · drag-and-drop ordering · presets/recipes (JSON import-export) · recursive folders · WebP/JPEG/PNG/TIFF output · auto-update via GitHub Releases. Built on Pillow + pywebview, ~32MB PyInstaller bundle.

</td>
</tr>
</table>

---

## Selected work / Trabajo destacado

<table>
<tr>
<td width="50%" valign="top">

### Shopify embedded apps · 5 in production

**bundles** · **checkout** (payment-method gating) · **dynamic fees** · **B2B quote-to-order** · **pro directory** with public App Proxy API.

Built on **Remix / React Router 7** · **Polaris (incl. Web Components)** · **Prisma** · **Shopify Functions (Rust → WASM)** · **Checkout/Customer Account Extensions** · **App Proxy** · **Admin GraphQL** · multi-environment Docker deploys (dev/stage/prod) with health checks and runtime secret injection (AWS Secrets Manager).

Surfaces: Functions · Checkout UI Ext · Customer Account Ext · Admin Ext · App Proxy · Theme App Ext · Webhooks · Billing API · Metafields · Metaobjects.

</td>
<td width="50%" valign="top">

### AWS serverless · 9+ Lambdas

Order ingestion (HMAC-verified Shopify webhooks) · **fraud risk-tagging with exponential-backoff retries** · carrier shipping-rate callbacks · fulfillment sync (FedEx/UPS) · presigned-URL upload service · receipt event-date sync · SES email infra · 23-function monorepo orchestrating Shopify ↔ MySQL ↔ DynamoDB ↔ Secrets Manager.

Stack: **Node 22.x** · **AWS SAM** + **Serverless Framework** · **API Gateway** · **SQS** · **EventBridge** · **CloudWatch** · `serverless-mysql` · GraphQL-Request · async-retry.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Bloom Brain B2B platform · 11 services

Event-driven microservices for B2B order fulfillment & claims:

- 5 backend APIs (operations · webhooks · user-management with multi-protocol auth · content-manager · event-orchestrator)
- 1 Remix BFF web platform with **XState** state machines + **TipTap** rich-text
- 2 React micro-frontends (multi-instance product-availability calendar widget · claims SPA with reCAPTCHA + direct S3 upload)
- 1 shared TypeScript library (18 subpath exports, multi-tenant schemas)
- CLI sync tool (oclif + Sharp)

Stack: **Bun** · **Hono** · **Drizzle ORM** · **MySQL + Redis** · **DDD/Clean Architecture** · **Zod** · **JWT** · `oxlint`/`oxfmt`.

</td>
<td width="50%" valign="top">

### Image pipeline · end-to-end

CLI batch processor (Pillow · 8-worker ThreadPoolExecutor) → Lambda presigned-URL uploads → multi-strategy detection (template **NCC** + Tesseract OCR + **Ollama GLM-OCR**) → AI logo removal (**ComfyUI Flux2 Klein** on dual-GPU with primary/secondary host failover) → **RealESRGAN** 4x upscale → WebP @ q90 → Shopify CDN sync.

Plus an **ML product-matching engine** (`scikit-learn` TF-IDF + 56 category mappings + 38 color synonyms + grid-search across 2,401 weight combinations) mapping 80+ farm SKUs to 1,200+ catalog SKUs.

Languages: **Python · TypeScript · Node**. Cloud: **S3 · Lambda · CloudWatch**.

</td>
</tr>
</table>

> The bulk of my day-to-day work lives in private repos under [@fifty-git](https://github.com/fifty-git) (Shopify integrations, ETLs against QuickBooks/Komet/BackyardBrands, 6 Liquid themes including Farm Export & TheFlowerCEO with WCAG 2.1 AA + Theme Check 0 offenses, internal admin tooling). Happy to walk through architecture and code on request.

---

## Beyond the e-commerce stack / Más allá del día a día

<table>
<tr>
<td width="33%" valign="top">

### Game dev

- **`indie-g-dd`** — Godot framework with test suite (GDScript)
- **`fistoftheindgame`** — 2D Metroidvania platformer in **Pygame** with procedural assets and gacha mechanics
- **`Artiflexly`** — async Python pipeline that orchestrates **ComfyUI** to auto-generate game assets and import them into Godot

</td>
<td width="33%" valign="top">

### AI / ML

- **CV classifier** — OCR + NLP + geolocalization extracting names · emails · skills from PDFs (3.3% → 100% extraction success)
- **Watermark detection** — template NCC + Tesseract + Ollama GLM-OCR cascade
- **Logo removal & 4x upscale** — ComfyUI diffusion + RealESRGAN

</td>
<td width="33%" valign="top">

### Productivity & infra

- **`summary-yearly-dailies`** — analyzes Slack daily standups with **Ollama qwen3** (local LLM), exports monthly/yearly PDFs
- **`azure-notifications`** — Azure Logic Apps + Managed Identity scheduling VM start/stop with email alerts
- **`ProsReviewScript`** — Next.js admin recovering 100+ customers' lost discount tags with audit trail

</td>
</tr>
</table>

---

## GitHub stats

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=miguel50flowers&show_icons=true&hide_border=true&theme=tokyonight&rank_icon=github&include_all_commits=true&count_private=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=miguel50flowers&show_icons=true&hide_border=true&rank_icon=github&include_all_commits=true&count_private=true" />
    <img src="https://github-readme-stats.vercel.app/api?username=miguel50flowers&show_icons=true&hide_border=true&theme=tokyonight&rank_icon=github&include_all_commits=true&count_private=true" alt="GitHub stats card" height="170" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=miguel50flowers&layout=compact&hide_border=true&theme=tokyonight&langs_count=10&hide=html,css,scss" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=miguel50flowers&layout=compact&hide_border=true&langs_count=10&hide=html,css,scss" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=miguel50flowers&layout=compact&hide_border=true&theme=tokyonight&langs_count=10&hide=html,css,scss" alt="Top languages card" height="170" />
  </picture>
</p>

---

## Contribution graph

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/miguel50flowers/miguel50flowers/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/miguel50flowers/miguel50flowers/output/github-snake.svg" />
    <img src="https://raw.githubusercontent.com/miguel50flowers/miguel50flowers/output/github-snake.svg" alt="Snake-style animation eating GitHub contributions" />
  </picture>
</p>

---

## Reach me / Contacto

<p align="center">
  <a href="https://www.maecly.com/"><img src="https://img.shields.io/badge/Portfolio-maecly.com-8B5CF6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio: maecly.com" /></a>
  <a href="mailto:migueltuxd@gmail.com"><img src="https://img.shields.io/badge/Email-migueltuxd%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email contact" /></a>
  <a href="https://www.linkedin.com/in/miguel-angel-esparza-calero-88ba49142/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn profile" /></a>
  <a href="https://x.com/MigelAngel_ec"><img src="https://img.shields.io/badge/Twitter-%40MigelAngel__ec-000000?style=for-the-badge&logo=x&logoColor=white" alt="Twitter / X profile" /></a>
</p>

<p align="center"><sub>More links (Instagram, YouTube, Facebook, GitHub <code>@MigelAngelEC</code>) on <a href="https://www.maecly.com/">maecly.com</a>.</sub></p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,2,20,30&height=80&section=footer" alt="Decorative footer wave" />
