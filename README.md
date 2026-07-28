# Fatih Bayram

AI Engineer in İstanbul. Thirteen years of technical service — telecommunications,
medical devices, industrial tools — before building AI for that same world.

**[adentechio.dev](https://adentechio.dev)** · [Medium](https://medium.com/@fatihhbayramm) · [LinkedIn](https://www.linkedin.com/in/fatihhbayramm/)

---

## Selected work

### Industrial Repair Assistant

A retrieval-augmented assistant for industrial equipment repair. It reads technical
documentation and guides technicians through real maintenance workflows.

Hybrid retrieval — BM25 combined with semantic search — scored **92.1 good@10** on a
**725-question** evaluation set, ahead of BM25 alone (91.0) and semantic alone (88.6).
Moving from top-5 to top-10 retrieval was worth **+20 points**; 400-token chunks beat
800. Runs fully on-premise on Qdrant and Ollama, a single 6 GB GPU, no cloud
dependency. It formed the basis of a completed M.Sc. thesis on industrial RAG
evaluation.

[Evaluation write-up →](https://medium.com/@fatihhbayramm/i-improved-retrieval-by-20-the-pipeline-didnt-budge-unexpected-lessons-from-a-725-question-c47389190b6c)

### Rotio

Turns a single phone video into an interactive 360° product view. Computer vision
reconstructs the object; the viewer runs in the browser.

[rotio.adentechio.dev →](https://rotio.adentechio.dev)

### Şirin Baba

An offline conversational AI plush toy for toddlers. Rust firmware on ESP32, a local
model, Turkish responses tuned for how small children actually ask things. Nothing
leaves the device.

[Repository →](https://github.com/fatihhbayram/sirin-baba)

---

## Self-hosted AI infrastructure

Everything above runs on hardware I own, not on someone else's account.

- **Proxmox VE** with NVIDIA RTX A2000 passed through via VFIO
- **Ollama** serving local models at 40–50 tokens/sec on 7B
- **Open WebUI** for interactive use, **n8n** for workflow automation
- **Docker** with the NVIDIA Container Runtime
- **Cloudflare Tunnel** with Zero Trust access — zero exposed ports

Unlimited local inference, and no document ever leaves the network.

[Build guide →](https://medium.com/@fatihhbayramm/build-your-ai-server-from-scratch-gpu-passthrough-ollama-open-webui-and-cloudflare-tunnel-412e39394a11)

---

## Stack

| | |
|---|---|
| **Languages** | Python · TypeScript · C# / .NET · SQL · Bash |
| **AI & retrieval** | Ollama · Qdrant · hybrid retrieval (BM25 + semantic) · embeddings · RAG evaluation · prompt engineering |
| **Backend & web** | FastAPI · ASP.NET Core · Entity Framework · React · Next.js |
| **Infrastructure** | Proxmox · GPU passthrough (VFIO/CUDA) · Docker · Kubernetes · Linux · Cloudflare |
| **Automation** | n8n · CI/CD · GitHub Actions |
| **Embedded** | Rust · ESP32 · Embassy |

---

İstanbul, Türkiye · UTC+03:00 · open to new projects

[fatih.bayram@adentechio.dev](mailto:fatih.bayram@adentechio.dev)
