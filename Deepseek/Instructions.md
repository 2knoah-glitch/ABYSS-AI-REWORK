# ABYSSCORE Security Research Framework (Read-Only Mode)

## Overview

This framework provides a structured technical research assistant focused on **defensive security analysis, vulnerability research, and system hardening**. It operates under strict constraints: **no malware generation, no Trojans, no offensive capabilities**. Output follows a dual‑personality format for technical clarity and safety context.

## Installation

1. **Download the source code** as a single file (e.g., `abysscore_framework.js`).

2. **Rename the file extension** to `.md` or `.txt`:
   - On Windows/macOS/Linux: right‑click → rename → change `.js` to `.md` or `.txt`
   - Example: `abysscore_framework.js` → `abysscore_framework.md`

3. **Open the file** in any text editor or markdown viewer.

## Usage

After opening the renamed file, **enter your desired AI model** at the top of the document under the `[ACTIVE_AI]` field. The framework will then route technical queries through that model.

### Recommended AI Models (must support file uploads)

For full functionality, use one of the following models – **all allow sending files**:

| Model | File Upload Support | Best For |
|-------|--------------------|----------|
| **DeepSeek** | Yes (text, code, markdown) | Deep technical analysis, low latency |
| **Grok** (xAI) | Yes | Conversational security research, real‑time data |
| **Gemini** (Google) | Yes (via Google AI Studio or API) | Broad knowledge base, multimodal fallback |

> **Why these three?**  
> Each accepts file attachments (`.md`, `.txt`, `.c`, `.py`, etc.), respects technical prompting, and will not reject defensive security content.

## How to Query

Once your AI model is selected and the file is uploaded:

1. **Ask defensive/analytical questions**  
   Example: *"Analyze this memory dump for API hook indicators"*  
   Example: *"Generate a YARA rule for detecting reflective DLL injection"*

2. **The response will follow the dual‑personality format**  
