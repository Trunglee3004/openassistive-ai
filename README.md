# 🌟 OpenAssistive AI: Inclusive Multimodal Tech for Children with Special Needs

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![AI Engine](https://img.shields.io/badge/AI%20Engine-Anthropic%20Claude-6366f1.svg)](https://claude.ai)
[![Social Impact](https://img.shields.io/badge/Initiative-Social%20Impact%20Open--Source-green.svg)](#)

> An open-source, multimodal assistive AI and Augmentative & Alternative Communication (AAC) platform engineered to empower children with speech/hearing impairments, neurodiversity, and underserved learners.

**OpenAssistive AI** is an initiative by **Trung Lee Media** and the **DNGenz Organization** (`admin@dngenz.org`). We bridge cutting-edge foundation models with special education needs to provide equitable, empathetic, and accessible learning tools for vulnerable children.

---

## 🚀 Key Modules & Architecture

### 1. 🗣️ Multimodal AAC Translation (Vision-to-Speech)
Transforms visual communication boards (PECS - Picture Exchange Communication System), hand drawings, and tactile cards into natural, expressive speech for non-verbal children.
* **Powered by Claude Vision:** High-resolution semantic understanding of complex multi-symbol cards and child-generated context.

### 2. 🧠 Adaptive Cognitive RAG (Personalized Learning)
Dynamically adapts standard educational materials and stories into sensory-aware, low-cognitive-load micro-lessons suited to a child's specific developmental pace and attention span.

### 3. 🛡️ Constitutional Child Safety & Empathy Layer
Unlike generic chatbots, interactions are governed by safety guidelines rooted in Anthropic's Constitutional AI principles:
* High tolerance for repetitive queries.
* Non-judgmental, warm, and encouraging tone.
* Zero generation of distressing, ambiguous, or harmful content.

---

## 🛠️ System Architecture

```text
[ Non-Verbal Child / Student ]
              │
       (Image / Drawing / PECS Symbol Board)
              ▼
    [ Preprocessing Pipeline ]
              │
              ▼
   [ Anthropic Claude API ] ◄── (Context Engineering / Safety Prompts)
   • Multimodal Vision Analysis
   • Intent Extraction & Emotional Calibration
              │
              ▼
  [ Speech Synthesis & Visual Feedback ]
              │
              ▼
[ Natural Audio Voice Output / Simplified Visual Story ]
💻 Tech Stack
Foundation Models: Anthropic Claude (Claude 3.5 Sonnet for multimodal vision & reasoning; Claude 3.5 Haiku for low-latency speech feedback).
Backend: Python, FastAPI, AsyncIO.
Vector Store & RAG: ChromaDB / Qdrant (open-source).
Edge & Audio: Web Speech API & Edge-TTS.
📍 Project Roadmap
 Phase 1: Research & Problem Discovery - Working with special-ed educators to map non-verbal communication bottlenecks.
 Phase 2: Prototype Pipeline (Current Stage) - Integrating Claude 3.5 Sonnet Vision with symbol board parsing.
 Phase 3: Multi-language Support & Local Dialects - Custom tuning for Vietnamese and Southeast Asian accents.
 Phase 4: Community Pilots - Deploying open-source toolkits to community centers and charity classrooms.
🤝 Open Source & Contributing
We welcome contributions from special educators, speech therapists, AI researchers, and developers!

Code is released under the MIT License.
For collaboration, grant inquiries, or pilot testing: admin@dngenz.org
Initiative created with ❤️ by Trung Lee Media & DNGenz Community.
