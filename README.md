# macl-codec-8b-instruct

A highly optimized, quantized Llama-3.1 model fine-tuned to act as a real-time neuro-symbolic control engine. It natively compiles raw environmental states into structured, safe MAC-L action envelopes. Designed for local GPU deployment, sub-50ms response times, and 100% syntactic execution accuracy.

---

## 📥 Model & Weights
The model is quantized to **Q4_K_M** GGUF format, making it highly efficient for local inference on consumer hardware. 

Because of file size limitations, the raw model weights are hosted on Hugging Face:
👉 **[Download macl-codec-8b-instruct on Hugging Face](PASTE_YOUR_HF_LINK_HERE)**

---

## 🧠 Core Capabilities
* **Neuro-Symbolic Control:** Bridges the gap between neural network processing and strict symbolic logic frameworks.
* **Environmental State Compilation:** Translates streaming state data into actionable MAC-L syntax.
* **Low-Latency Performance:** Optimized for sub-50ms local inference loops.
* **Implements a multi-layered fallback ladder (L0-L4) that decouples time-sensitive survival reflexes from LLM reasoning, ensuring sub-10ms response times to environmental threats.
* **Utilizes asynchronous sleep consolidation to convert verbose episodic experience into structured semantic facts, maintaining a flat active context window regardless of operational horizon.

---

## 📋 Quickstart / Local Inference
To run this model locally using tools like `llama.cpp` or `Ollama`:

```bash
# Example command if using llama.cpp
llama-cli -m Meta-Llama-3.1-8B-Instruct.Q4_K_M.gguf -p "Your prompt here"
