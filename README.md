# Hi, I'm Silas 👋

**Systems thinker with ADHD** — I turn chaos into repeatable processes, whether it's construction governance, smart home automation, or cramming a Raspberry Pi into LEGO.

I hyperfocus on problems others ignore: "How do we audit 95.5% compliance in construction oversight?" or "Can this vintage LEGO set play actual Game Boy games?" Then I build systems that answer those questions.

---

## 🧠 ADHD as Architecture

My brain works differently, and I've learned to make it a strength:

**Pattern recognition** → I see connections between governance frameworks and Home Assistant automations  
**Hyperfocus loops** → 15-hour deep dives into mmWave sensors or systemd services  
**Zero tolerance for repetition** → If I do it twice, I automate it  
**Direct communication** → No corporate speak, just "here's the problem, here's the fix"  
**Documentation obsession** → Future-me will thank present-me for CLAUDE_CONTEXT.md

The projects below exist because ADHD doesn't let me leave problems half-solved.

---

## 🔧 What I Actually Build

### 🏗️ Governance Systems for Real-World Chaos

**Construction Oversight Framework** (Reserva do Pinhal Works Commission)  
- **Problem**: Homeowners association had no formal process for approving construction projects  
- **Solution**: Built end-to-end governance system with 7 document templates, 36 technical criteria, automated protocol workflows  
- **Result**: 95.5% compliance across multiple audit phases, 20-day SLA enforcement  
- **Tech**: Python automation, systematic documentation, legal framework integration  
- **Status**: Private (institutional governance), but ask me about process design

The hardest part wasn't the code — it was translating regulatory language into executable checklists.

---

### 🏠 Home Assistant Ecosystems

**Nabu Intelligence** - Voice assistant that doesn't wake my mom  
- Claude Sonnet 4 + Home Assistant Voice for natural language control  
- Context-aware TTS with automatic volume reduction (quiet hours: 23h-7h, or manual "sleep mode")  
- 30+ lights, 3 motorized curtains, A/C, 2 robot vacuums (named Caroline and Oswaldo)  
- Maintenance alerts, smart scheduling, emergency backup systems  
- **Tech**: ESPHome, YAML, Jinja2 templates, Anthropic API  
- **Repo**: `ha-nabu-intelligence-system` (ready to publish)

**Eldercare Monitoring** (for my 83-year-old mother)  
- **Challenge**: Monitor fall risk + CPAP compliance without cameras (privacy concerns)  
- **Stack**: mmWave presence detection (LD2450/Aqara FP2), thermal imaging (MLX90640), audio anomaly detection  
- **Intelligence**: Frigate + Hailo-8L AI for pose estimation (fall detection), contextual automation  
- **Privacy-first**: No video recording, local processing only, thermal "blobs" instead of images  
- **Status**: Active development, testing phase

**ESP32 Irrigation System** ("Lady Gaga")  
- Standalone operation (doesn't depend on Home Assistant connectivity)  
- Capacitive soil sensor (CS12) with pulse logic (25s ON / 120s OFF for deep watering)  
- OLED display for local status, relay control with AC-rated protection  
- Fallback safety: If HA dies, system continues autonomously  
- **Tech**: ESP32-C3, ESPHome, fail-safe relay design

**Home Energy Monitor**  
- Real-time power consumption tracking per circuit  
- UPS monitoring with automatic alerts on power failure  
- Integration with LoRa mesh for construction site monitoring  

All projects follow the same philosophy: **self-hosted, privacy-first, fail-safe defaults**.

---

### 🎮 Retro Computing & Hardware Hacks

**LEGO Game Boy Emulator** (rpi-game-boy-lego)  
- Converted LEGO set 72046 into functional Game Boy emulator  
- Raspberry Pi Zero 2W + 2" LCD (ST7789), I2S audio (MAX98357A), 9 tactile buttons  
- **Challenge solved**: PAM8403 amplifier burned out in <10s → migrated to I2S digital audio  
- Systemd auto-start, safe shutdown via GPIO, 60 FPS GB/GBC emulation  
- **Status**: 70% complete (display ✅, audio migration ⏳)  
- **Cost**: R$462-631 (~$90-120 USD)  
- **Repo**: Ready to publish with full build guide

**Lessons learned**: Always read datasheets before connecting components. PWM audio ≠ clean amplifier input.

**Raspberry Pi Mini Console**  
- RetroPie multi-emulator with custom case design  
- Focus on polish: boot animations, controller configs, kid-friendly UI

**Tasmota Firmware Projects**  
- Flashing Sonoff devices for local control (no cloud dependencies)  
- Custom MQTT integrations for X10 protocol smart home (for my brother)

---

### 🛠️ IoT & Electronics

**Hardware Validation Methodology**  
- Rigorous component verification before soldering (datasheet-first approach)  
- PCB design review, thermal calculations, failure mode analysis  
- **Why**: Because I've burned enough components to know better

**M5Stack Exploration**  
- Testing M5StickC Plus2, Cardputer, C6L for LoRa mesh networks  
- Goal: Construction site monitoring + emergency backup comms  
- Meshtastic community integration

**Snapcast Multi-Room Audio**  
- Synchronized playback across Alexa devices  
- Low-latency streaming with custom buffer tuning

---

## 🛠️ Technical Stack

**Languages**: Python 3.11+, JavaScript/TypeScript, YAML, Bash, C++ (ESP32)  
**Hardware**: ESP32, Raspberry Pi, M5Stack, LoRa devices, mmWave sensors  
**Platforms**: Home Assistant, ESPHome, RetroPie, Docker  
**Automation**: Systemd services, MQTT, fail-safe state machines  
**AI/ML**: Claude API integration, Frigate NVR, Hailo-8L accelerator  
**Docs**: Markdown, technical writing, ADHD-friendly structure (lists > paragraphs)

**Philosophy**: Self-hosted where possible, cloud when necessary, always with local fallback.

---

## 📚 How I Work

**Project Documentation**  
Every project gets:  
- `CLAUDE_CONTEXT.md` - Full technical context for AI collaboration  
- `CHANGELOG.md` - Semantic versioning (MAJOR.MINOR.PATCH)  
- `README.md` - Human-readable quick start  
- Incremental git commits (no batch commits at end)

**ADHD-Adapted Workflow**  
1. **Explore** → Understand requirements, read existing code/docs  
2. **Plan** → Architecture BEFORE implementation (avoid over-engineering)  
3. **Execute** → TODO lists, commit incrementally, document decisions  
4. **Validate** → Test edge cases, verify against spec

**Critical rule**: When in doubt, ask > assume and break things later.

---

## 🌐 Contributions & Collaboration

**What I'm good at**:  
- Translating vague requirements into structured systems  
- Hardware validation (datasheets, schematics, "will this actually work?")  
- ADHD-friendly documentation (concise, scannable, example-driven)  
- Portuguese ↔ English technical translation  
- Process design (governance, compliance, automation)

**What I'm learning**:  
- AI/ML inference optimization (Hailo accelerators, TensorFlow Lite)  
- LoRa mesh networking (Meshtastic protocol)  
- Advanced ESPHome (custom components, lambda functions)

**Languages**: Portuguese (native), English (technical proficiency, still improving)

---

## 📂 Featured Repositories

### 🎮 rpi-game-boy-lego
LEGO 72046 converted to functional Game Boy emulator. Complete build guide with component datasheets, troubleshooting, systemd integration.

### 🏠 ha-nabu-intelligence-system  
Claude-powered voice assistant for Home Assistant. Context-aware responses, quiet hours automation, Portuguese BR support.

### 🌱 ha-irrigation-esp32
Autonomous irrigation system with fail-safe defaults. Works standalone if Home Assistant fails.

### 🏗️ project-docs-methodology *(skill)*
Universal documentation framework for technical projects. ADHD-optimized structure.

---

## 💬 Connect

**Location**: São Paulo, Brazil  
**Interests**: Governance automation, eldercare tech, retro computing, mesh networks, privacy-first IoT  
**Open to**: Collaborations on Home Assistant integrations, hardware validation reviews, process automation

---

## ⚠️ Disclaimer

Not all projects are public yet:  
- **Governance work** is institutional (privacy/legal constraints)  
- **Eldercare monitoring** involves personal health data  
- **Some IoT projects** are still in "prove it works" phase

I publish when systems are stable, documented, and genuinely useful to others — not just "it compiled once."

---

**If you're building**:  
- Smart home systems that need to work when the internet dies  
- Hardware projects where datasheets matter  
- Governance frameworks for chaotic organizations  
- Anything requiring ADHD-level attention to edge cases  

**Let's talk.**

---

*Built with hyperfocus in São Paulo 🇧🇷*
