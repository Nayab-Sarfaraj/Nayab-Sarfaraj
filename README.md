<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=58A6FF&center=true&vCenter=true&width=500&lines=Still+debugging...;prompt+in+%E2%86%92+short+out;agents+that+actually+ship;React+Native+%2B+Next.js+%2B+FastAPI" alt="typing" />
</p>

<h1 align="center">yo, i'm nayab</h1>

<p align="center">
  Software Engineer @ <b>Byldd</b> · I build agentic video + research pipelines that survive production<br/>
  <a href="https://portfolio-self-chi-m6v05x2bws.vercel.app/">portfolio</a> ·
  <a href="https://linkedin.com/in/nayab-sarfaraj-856a70258/">linkedin</a> ·
  <a href="https://x.com/NayabSarfaraj">x</a> ·
  <a href="mailto:nayabsarfaraj@gmail.com">email</a>
</p>

```js
const nayab = {
  role: "Software Engineer @ Byldd",
  ships: ["AutoAI Shorts (Play Store live)", "Instacap (live)", "Pixl AI"],
  obsession: "prompt -> pipeline -> production",
  hates: ["credit-based pricing", "static polylines", "unindexed mongo queries"],
  status: "still debugging"
};
```

### what i actually do

i don't do demo-ware. i do `text in → video out`, `query in → cited report out`, `photo in → clean edit out` — with queues, retries, caching and billing attached.

currently:
- building medical + vibe-coding review platforms in Next.js at Byldd
- shipping React Native navigation that replaced a static polyline map with real turn-by-turn (Swift bridging, delivered 4 days early)
- running BullMQ + Redis workers for AI video / transcription at scale

### flagship agentic builds

**1. AutoAI Shorts — prompt to viral short, on your phone**
[`backend`](https://github.com/Nayab-Sarfaraj/ai-youtube-shorts-backend) · [`android app`](https://play.google.com/store/apps/details?id=com.alishanbyldd.AutoAIShorts)
> Gemini writes the script → ElevenLabs voices it → Replicate / Stable Diffusion draws it → AssemblyAI + Remotion Lambda captions + renders it. Orchestrated with Inngest. Born in a hackathon, now live on Play Store.

**2. Instacap / caption-generator — word-level captions that don't suck**
[`live`](https://getinstacap.com/) · [`repo`](https://github.com/Nayab-Sarfaraj/caption-generator)
> Next.js + Remotion components as captions (not burned overlays), Deepgram Nova-2 word timestamps, BullMQ + Redis workers, 32 styles, Clerk auth, Polar billing. Flat pricing. No credit-system scam.

**3. research-copilot-server — async research agent with receipts**
[`repo`](https://github.com/Nayab-Sarfaraj/research-copilot-server)
> LangGraph + Inngest + pgvector + Groq. Takes natural-language query + PDFs + live web search → streams back a cited report. Real RAG, not a wrapper.

**4. resume-customizer — ATS-aware, LaTeX-safe**
[`repo`](https://github.com/Nayab-Sarfaraj/resume-customizer)
> Python + LangChain + Groq pipeline that parses LaTeX, rewrites for the job description, keeps it compilable. Boring problem, ruthless execution.

<details>
<summary><b>systems side-quests (click)</b></summary>

- [`discord-bot`](https://github.com/Nayab-Sarfaraj/discord-bot) — prod Discord bot + realtime admin dashboard, auth, background jobs, Slack routing, AI issue triage.
- [`Geofencing`](https://github.com/Nayab-Sarfaraj/Geofencing) — realtime vehicle tracking, custom map zones, WebSocket boundary alerts.
- [`PixlAI`](https://github.com/Nayab-Sarfaraj/PixlAI) — Expo photo editor, instant background removal, Supabase storage + history.
- [`shop-sync`](https://github.com/Nayab-Sarfaraj/shop-sync) — Puppeteer scraping engine that beat anti-bot, Razorpay + vendor alerts.

</details>

### how i build agents

```
ingest (web / pdf / prompt)
  → queue it (Inngest / BullMQ + Redis)
  → reason it (Gemini / Groq / LangGraph)
  → voice/see it (ElevenLabs / Deepgram / Replicate)
  → render it (Remotion / Lambda / R2 / S3)
  → cache the hell out of it
```

opinionated toolbox, not a badge wall:
`React Native · Next.js · Node · FastAPI · TypeScript · MongoDB · Postgres + pgvector · Redis · BullMQ · Inngest · LangGraph · Docker`

### receipts, not adjectives

- `123.8ms → 1.7ms` avg API latency with Redis caching (~73x, p95 290ms → 1ms, Artillery 1000 reqs @ 50 rps)
- `~40%` faster Mongo queries via indexing + schema rework
- `500+` DAU on GPT chat features (forked CometChat SDK, @all mentions + push)
- `~10 hrs/week` saved via Reddit-lead scraper → Anthropic drafts → Slack approval
- live in stores: [`Automojo Specialist (iOS)`](https://apps.apple.com/in/app/automojo-specialist/id1609288961), `AutoAI Shorts (Android)`, [`White Coat Romance`](https://www.whitecoatromance.com)

### stats but make it honest

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Nayab-Sarfaraj&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" height="160" />
  <img src="https://streak-stats.demolab.com?user=Nayab-Sarfaraj&theme=tokyonight&hide_border=true" height="160" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nayab-Sarfaraj&layout=compact&theme=tokyonight&hide_border=true" height="120" />
</p>

### ping me if

- you're building AI video / voice / RAG and your queue keeps dying
- your React Native bridge is fighting you (Swift-side, I've been there)
- you break one of my demos — seriously, open an issue, I fix fast

```
$ npx nayab --hire
> installing common sense... done
> installing shipping... done
> status: still debugging, but shipping anyway
```

<p align="center">
  <a href="mailto:nayabsarfaraj@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://linkedin.com/in/nayab-sarfaraj-856a70258/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://portfolio-self-chi-m6v05x2bws.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-58A6FF?style=for-the-badge&logo=vercel&logoColor=white" /></a>
</p>

<!-- TODO: sleep -->
