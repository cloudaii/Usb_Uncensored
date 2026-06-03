# ⚡ Usb_Uncensored



**USB-Uncensored-LLM** is a fully air-gapped, plug-and-play Local AI system. Run large language models directly from your **local drive** or **USB/SSD**, with **no internet or complex installation** required. Compatible with **Windows, macOS, Linux, and Android**.

---

## 🚀 Features
- **Zero Setup:** Portable Python + isolated engine binaries, no admin rights required.  
- **Cross-Platform:** Download once, use on Windows, macOS, Linux.  
- **Censorship-Free:** Access uncensored, fine-tuned AI models.  
- **Network Access:** Serve AI UI locally and access from phones/tablets via WiFi.  
- **Hardware Optimized:** Supports AVX CPU, NVIDIA CUDA, or Apple Metal GPU for fast inference.  

---

## 💻 System Requirements
| Requirement | Minimum | Recommended |
|-------------|---------|-------------|
| Storage     | 8 GB    | 16 GB       |
| RAM         | 8 GB    | 16 GB       |
| CPU         | Any modern | AVX-enabled / GPU optional |

---

## 📂 Folder Structure
<details>
<summary>Click to expand</summary>

```text
[Portable Drive]
 ├── 📁 Android/      # Termux installers & scripts
 ├── 📁 Linux/        # Ubuntu/Debian offline execution scripts
 ├── 📁 Mac/          # macOS launcher tools
 ├── 📁 Windows/      # Windows automated batch menus
 └── 📁 Shared/       # Unified Core Files
      ├── 📁 bin/         # Cross-platform binaries (ollama, etc.)
      ├── 📁 chat_data/   # Persistent cross-platform chat history
      ├── 📁 models/      # Downloaded GGUF weights & mappings
      └── 📁 python/      # Isolated portable python runtime
```
</details>

---

## 🧠 Preloaded Models
| Model | Size | Notes |
|-------|------|-------|
| Gemma 2 2B Abliterated | ~1.6 GB | Fast & smart, safety purged |
| Gemma 4 E4B Ultra Heretic | ~5.34 GB | Fully uncensored |
| Qwen 3.5 9B Uncensored | ~5.2 GB | Large, precise reasoning |
| Custom | Any GGUF | Add `.gguf` weights to `Shared/models` |

---

## ⚙️ Quick Start

<details>
<summary>Click to expand</summary>

### 1️⃣ Initialize Engine
Run installer for your OS:
- **Windows:** `Windows/install.bat`  
- **macOS:** `Mac/install.command`  
- **Linux:** `bash Linux/install.sh`  
- **Android:** `bash Android/install.sh` (Termux)

### 2️⃣ Download Models
- Windows installer offers interactive model selection.  
- Or manually add `.gguf` files to `Shared/models`.

### 3️⃣ Launch
Run start script for your OS:
- **Windows:** `Windows/start-fast-chat.bat`  
- **macOS:** `Mac/start.command`  
- **Linux:** `bash Linux/start.sh`  
- **Android:** `bash Android/start.sh`  

Browser opens the local AI UI automatically.
</details>

---

## 📱 Android Setup (Termux)
<details>
<summary>Click to expand</summary>

**Requirements:** Termux (F-Droid), 6 GB+ RAM, ARM64, WiFi/data  

**Steps:**  
1. Copy USB-Uncensored-LLM folder to device  
2. Open Termux → navigate to project folder  
3. Run `bash Android/install.sh` → Select model  
4. Run `bash Android/start.sh`  

**Tips:**  
- `termux-wake-lock` to prevent process killing  
- Close background apps  
- Use 2B model for <12 GB RAM
</details>

---

## 🌐 LAN Mobile Access
<details>
<summary>Click to expand</summary>

- Ensure PC running AI and your phone are on same WiFi  
- Terminal displays a local IP (e.g., `http://192.168.1.15:3333`)  
- Open this in your mobile browser to access AI UI
</details>

---

## 🛠️ Troubleshooting
- **Script closes instantly (Windows):** Run via Command Prompt or "Run as Administrator"  
- **Engine not found:** Run OS installer first  
- **Slow performance:** Use smaller Gemma 2 2B model for low-RAM machines  

---

Disclaimer: USB-Uncensored-LLM is built for uncompromising computational freedom. By utilizing ablative models, the system will not moralize, lecture, or refuse your prompts. Please use responsibly.

*USB-Uncensored-LLM enables free, uncensored AI computing. Use responsibly.*

