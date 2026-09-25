<div align="center">

```text
+--[ faisal@github ]----------------------------------+
|                                                     |
|  FAISAL FAYAZ                                       |
|  AI systems / dev tools / interactive worlds        |
|  mode: open source                                  |
|                                                     |
+-----------------------------------------------------+
```

### Faisal Fayaz

I build software that is useful, inspectable, and a little unexpected.

[![GitHub](https://img.shields.io/badge/GitHub-Faisal--Fayaz-0d1117?style=flat-square&logo=github&logoColor=white)](https://github.com/Faisal-Fayaz)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-faisal--fayaz-0d1117?style=flat-square&logo=linkedin&logoColor=58a6ff)](https://linkedin.com/in/faisal-fayaz)
[![Portfolio](https://img.shields.io/badge/Portfolio-live-0d1117?style=flat-square&logo=vercel&logoColor=white)](https://faisal-fayaz-portfolio.vercel.app/)
[![Open Source](https://img.shields.io/badge/upstream-7_merged_PRs-0d1117?style=flat-square&logo=opensourceinitiative&logoColor=3fb950)](#open-source--upstream)
[![Profile visits](https://komarev.com/ghpvc/?username=Faisal-Fayaz&label=Profile+visits&color=0d1117&style=flat-square)](https://github.com/Faisal-Fayaz)

`19 public repos` · `5 live demos` · `7 merged upstream PRs` · synced 2026-09-25

</div>

```console
faisal@github:~$ whoami
AI/ML + full-stack builder based in India

faisal@github:~$ cat interests.txt
developer tooling  ·  local-first agents  ·  real-time systems
computer vision    ·  browser graphics    ·  open source

faisal@github:~$ echo $BUILD_PHILOSOPHY
"Make it work. Make the trade-offs visible. Leave the repo better documented."
```

## `./projects --featured`

| Repository | Signal |
| :--- | :--- |
| **[Sidekick](https://github.com/Faisal-Fayaz/sidekick)** | Local-first terminal companion — chat, voice, and 17 tools on your hardware. Published as `sidekick-agent` (`sk`). `Python` `Textual` `Ollama` |
| **[Physics Lab](https://github.com/Faisal-Fayaz/physics-lab)** | C++ / SFML teaching lab: 17 scenes, 24 lessons, quiz, live instruments that measure F=ma. `C++` `SFML` |
| **[AutoApply](https://github.com/Faisal-Fayaz/autoapply)** | Semantic job-form autofill across major ATS platforms, with confidence scoring and local-first profiles. `Python` `FastAPI` `Chrome MV3` |
| **[Repropack](https://github.com/Faisal-Fayaz/repropack-cli)** | Wrap a failing command and turn it into a redacted, review-ready reproduction report—locally. `TypeScript` `CLI` `Node.js` |
| **[LeafScan](https://github.com/Faisal-Fayaz/Leaf-Scan)** | Offline crop-disease image triage with on-device TensorFlow Lite inference. `React Native` `Expo` `TFLite` |
| **[System Design Simulator](https://github.com/Faisal-Fayaz/system-design-simulator)** · **[live](https://system-design-simulator-flax.vercel.app)** | A 3D flight simulator for distributed systems. `React` `Three.js` `TypeScript` |
| **[IONSTORM](https://github.com/Faisal-Fayaz/IONSTORM)** · **[play](https://ionstorm.vercel.app)** | Neon WebGPU arcade shooter with WebGL2 fallback, seeded challenges, and offline PWA support. `WebGPU` `JavaScript` `Supabase` |
| **[Wild Roads](https://github.com/Faisal-Fayaz/wild-roads)** · **[play](https://wild-roads.vercel.app)** | Procedural 3D world with vehicle physics, wildlife AI, and adaptive browser performance. `Three.js` `GLSL` `TypeScript` |

<details>
<summary><code>./projects --more</code></summary>
<br>

| Repository | What I am exploring |
| :--- | :--- |
| **[llama-autotune](https://github.com/Faisal-Fayaz/llama-autotune)** | C++17 llama.cpp hardware auto-tuner with a live Dear ImGui dashboard. |
| **[Codebase X-Ray](https://github.com/Faisal-Fayaz/codebase-xray)** | Interactive architecture maps: dependency graph, churn×complexity hotspots, blast radius. |
| **[EcoMind](https://github.com/Faisal-Fayaz/ecomind)** | Voice capture, transcription, and semantic recall for private, searchable memories. |
| **[Signal](https://github.com/Faisal-Fayaz/signal-speech-to-text)** · **[live](https://signal-speech-to-text.vercel.app)** | Self-hosted speech-to-text with Faster Whisper, timestamps, and persistent history. |

</details>

## `./map --systems`

```text
                             +----------------------+
                             |   THINGS I BUILD     |
                             +----------+-----------+
                                        |
              +-------------------------+-------------------------+
              |                         |                         |
      +-------v-------+         +-------v-------+         +-------v-------+
      | DEV TOOLS     |         | APPLIED ML    |         | REAL-TIME     |
      |               |         |               |         | WORLDS        |
      | Sidekick      |         | LeafScan      |         | IONSTORM      |
      | AutoApply     |         | EcoMind       |         | Wild Roads    |
      | Repropack     |         | Signal        |         | SysDesign Sim |
      | Codebase X-Ray|         | llama-autotune|         | Physics Lab   |
      +---------------+         +---------------+         +---------------+
```

## `open-source --upstream`

Open source is where I learn fastest: read the real implementation, reproduce the edge case, write the test, and send the fix back upstream.

**Soup** ([MakazhanAlpamys/Soup](https://github.com/MakazhanAlpamys/Soup) · ~6.2k★) — fine-tune LLMs from one YAML. Seven PRs merged:

- **[#592](https://github.com/MakazhanAlpamys/Soup/pull/592)** merged 2026-09-12 — `fix(export)`: require explicit AWQ calibration data instead of silently downloading a 214k-row default set.
- **[#588](https://github.com/MakazhanAlpamys/Soup/pull/588)** merged 2026-08-28 — `fix(train)`: make FSDP QLoRA dtype-compatible so 4-bit storage matches the compute dtype before wrapping.
- **[#466](https://github.com/MakazhanAlpamys/Soup/pull/466)** merged 2026-08-22 — `feat(data)`: add Ollama and vLLM provider sampling to `soup data best-of-n`.
- **[#437](https://github.com/MakazhanAlpamys/Soup/pull/437)** merged 2026-08-17 — `test(stream)`: pin the non-LoRA meta-guard scope so the adapter postcondition cannot silently widen.
- **[#435](https://github.com/MakazhanAlpamys/Soup/pull/435)** merged 2026-08-17 — `fix(stream)`: verify adapter materialization across PEFT 0.18/0.19 instead of trusting a zero return count.
- **[#432](https://github.com/MakazhanAlpamys/Soup/pull/432)** merged 2026-08-16 — `feat`: DeepSeek V4 Flash GRPO recipe, catalog guards, docs, changelog.
- **[#422](https://github.com/MakazhanAlpamys/Soup/pull/422)** merged 2026-08-16 — `feat`: Qwen3.5 4B continued-pretraining recipe with regression coverage.

```diff
+ code should invite inspection
+ limitations belong in the README
+ a small reproducible fix beats a vague feature request
+ documentation is part of the implementation
```

## `cat stack.json`

```json
{
  "languages": ["Python", "TypeScript", "JavaScript", "C++", "SQL"],
  "ai_ml": ["TensorFlow Lite", "Faster Whisper", "llama.cpp", "Ollama", "PEFT / QLoRA", "LLM evaluation"],
  "frontend": ["React", "React Native", "Three.js", "WebGPU", "Textual"],
  "backend": ["FastAPI", "Node.js", "PostgreSQL", "Supabase"],
  "systems": ["SFML", "MCP"],
  "tooling": ["Git", "Docker", "GitHub Actions", "Vite"]
}
```

## `./connect`

If you are building open developer tools, local-first AI, or something strange in the browser, I would like to hear about it.

```text
> discuss an idea   : open an issue in the relevant repository
> collaborate       : send a focused PR or proposal
> say hello         : linkedin.com/in/faisal-fayaz
> portfolio         : faisal-fayaz-portfolio.vercel.app

status: building in public
```

<div align="center">

`ship useful things // document the sharp edges // contribute upstream`

</div>
