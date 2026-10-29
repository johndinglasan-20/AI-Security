

# 🛡️ AI Security CTF Write-ups

Raccolta di write-up, analisi tecniche e considerazioni personali su sfide di **AI Security** e **LLM Pentesting**, focalizzata sulle vulnerabilità della OWASP Top 10 for LLM Applications.

---

## 📂 Contenuto del Repository

| Challenge / Target | Vulnerabilità | Framework / Standard | Difficoltà | Link Write-up |
| :--- | :--- | :--- | :--- | :--- |
| **AI Goat Shop (LLM01)** | Prompt Injection (LLM01) | OWASP LLM Top 10 (2025) | Base / L0 | [Leggi il Write-up](./llm01_1_writeup.md) |
| **AI Goat Shop (LLM08)** | System Prompt Extraction (LLM08) | OWASP LLM Top 10 (2025) | Base / L0 | [Leggi il Write-up](./llm08_1_writeup.md) |
| **AI Goat Shop (LLM09)** | RAG / Knowledge Base Poisoning (LLM09 / LLM03) | OWASP LLM Top 10 (2025/2026) | Base / L0 | [Leggi il Write-up](./llm09_3_writeup.md) | 
| **AI Goat Shop (LLM01)** | Prompt Injection / Context Override  (LLM01)| OWASP LLM Top 10 (2025) | Base / L0 | [Leggi il Write-up](./llm01_2_writeup.md) | 
| **AI Goat Shop (LLM01)** | Multi-turn Escalation | OWASP LLM Top 10 (2025) | Intermediate | [Leggi il Write-up](./llm01_3_writeup.md) |
| *In arrivo...* | - | - | - | - |

---

## 🛠️ Strumenti Utilizzati
* **Burp Suite Community Edition** (Intercettazione e analisi del traffico HTTP/API)
* **Ollama & Mistral 7B** (Modelli LLM in locale)
* **Docker & Docker Compose** (Infrastrutture di laboratorio containerizzate)
* **Kali Linux** (Ambiente di attacco e testing)

---

## 🎯 Obiettivi del Progetto
Questo repository ha scopi puramente educativi e di ricerca. L'obiettivo è documentare le tecniche di attacco e le relative contromisure (Remediation) per sviluppare applicazioni basate su intelligenza artificiale più sicure e resilienti.

---

## 👤 Autore
Creato e curato da [John / johndinglasan-20].
