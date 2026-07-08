 🎧 TEACHERPRO v4.2 — AI-Powered English Tutor (Offline & Hybrid)

**Status:**  Production Ready | **INPI Registered** | **Full Source Code Available for Acquisition**

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.109.0-009688?logo=fastapi)](https://fastapi.tiangolo.com)
[![License](https://img.shields.io/badge/License-Proprietary-red)](LICENSE)
[![INPI](https://img.shields.io/badge/INPI-Registered-green)](https://www.gov.br/inpi)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-lightgrey?logo=windows)](https://www.microsoft.com/windows)
[![AI Models](https://img.shields.io/badge/AI_Models-4-orange?logo=openai)](https://github.com/openai/whisper)
[![Tests](https://img.shields.io/badge/Tests-47%20passed-brightgreen)](tests/)
[![Security](https://img.shields.io/badge/Security-Bandit%20Audited-success)](docs/security/bandit_report.html)

---

## Visão Geral

**TEACHERPRO** é um tutor de inglês completo que integra **quatro modelos de inteligência artificial** e opera de forma **híbrida**: 100% offline para aprendizado, com enriquecimento online opcional que jamais expõe os dados do usuário. O software foi projetado para ser uma solução educacional privada, escalável e juridicamente protegida.

>  **Diferencial estratégico:** Adquira um ativo tecnológico maduro e elimine meses de desenvolvimento. O TEACHERPRO está pronto para ser comercializado sob sua marca, como SaaS, white-label ou licenciamento.

---

##  Por que Adquirir este Ativo

| Benefício | Descrição |
|:---|:---|
|  **Time-to-Market Zero** | O produto já está funcional, testado e documentado. |
|  **Economia de Custos** | Desenvolver uma plataforma equivalente exigiria um investimento significativo e uma equipe multidisciplinar. |
|  **Segurança Jurídica** | Registro no INPI com direitos de titularidade transferíveis. |
|  **Tecnologia de Ponta** | Integração de 4 modelos de IA locais, pipeline de áudio profissional e arquitetura híbrida. |
|  **Pacote Completo** | Código-fonte, executável, documentação técnica e relatório de segurança incluídos. |

---

##  Arquitetura Híbrida

O TEACHERPRO opera em dois modos que se complementam, garantindo experiência ininterrupta e total privacidade:
┌─────────────────────────────────────────────────────────────┐
│ MODO OFFLINE (PADRÃO) │
│ │
│ Reconhecimento de Fala (Whisper) │
│ Análise de Pronúncia (WavLM + Wav2Vec2) │
│ Diálogos com Personagens (Qwen 2.5) │
│ Conversação Livre (Qwen 2.5) │
│ Vocabulário e Gamificação │
│ Progresso do Aluno (SQLite) │
│ │
│ NENHUM DADO SAI DO DISPOSITIVO │
└─────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────┐
│ MODO ONLINE (OPCIONAL) │
│ │
│  Clima / Cultura / Cotação (APIs públicas) │
│  Rádio em Inglês (streaming) │
│  Voz Neural de Alta Qualidade (TTS) │
│ │
│ CONSULTAS COM PARÂMETROS GENÉRICOS │
│  SE A INTERNET FALHAR, O SISTEMA CONTINUA OFFLINE │
└─────────────────────────────────────────────────────────────┘

text

---

##  Pipeline de Inteligência Artificial

Quatro modelos trabalham em sequência para transformar a fala do aluno em feedback personalizado:
Microfone
│
▼
Processamento de Áudio (Redução de Ruído + Normalização LUFS)
│
▼
Reconhecimento de Fala (Whisper · OpenAI)
│
▼
Análise Acústica (WavLM · Microsoft) + Alinhamento Temporal (Wav2Vec2 · Meta)
│
▼
Cálculo do Score (Scorer)
│
▼
Tutor Conversacional (Qwen 2.5 · Alibaba)
│
▼
Feedback ao Aluno (Texto + Áudio + Gamificação)

text

---

##  Segurança e Propriedade Intelectual

- **Privacidade por Design:** voz, transcrições e progresso armazenados localmente (SQLite), sem transmissão externa.
- **Auditoria de Código:** relatório Bandit incluso na documentação (nenhuma vulnerabilidade crítica encontrada).
- **Registro no INPI:** Pedido **BR 51 2026 003960 6** — autoria comprovada e direitos de titularidade **transferíveis**.
- **Código Protegido:** ofuscação com PyArmor e possibilidade de assinatura digital do executável.

---

## Stack Tecnológica

| Camada | Tecnologias |
|:---|:---|
| **Backend** | Python 3.11, FastAPI, Uvicorn, Ollama |
| **Frontend** | Vanilla JavaScript, HTML5, CSS3 (sem frameworks pesados) |
| **Banco de Dados** | SQLite (WAL mode), Repository Pattern |
| **IA / Machine Learning** | PyTorch, Hugging Face Transformers, Whisper, Torchaudio |
| **Processamento de Áudio** | librosa, noisereduce, pyloudnorm, pydub |
| **Síntese de Voz** | gTTS / Edge TTS (cache local para offline) |
| **Empacotamento** | PyInstaller, Inno Setup (instalador profissional) |
| **Segurança do Código** | PyArmor, assinatura digital (signtool) |

---

##  Funcionalidades

| Módulo | Descrição |
|:---|:---|
|  **Vocabulário** | Mais de 260 palavras em 13 categorias com pronúncia, tradução e pontuação. |
|  **Diálogos com IA** | Conversas realistas com personagens (garçom, recepcionista, médico). |
|  **Conversa Livre** | Chat aberto com tutor IA sobre qualquer tema. |
|  **Números** | Cardinais, ordinais, horas, preços e medidas. |
|  **Pronúncia** | Frases completas com análise fonética detalhada e score 0–100. |
|  **Rádio em Inglês** | Streaming opcional de estações dos EUA/UK para treino auditivo. |
|  **Gamificação** | XP, níveis, conquistas, repetição espaçada (SRS). |

---

##  Oportunidades de Comercialização

O TEACHERPRO pode ser explorado em múltiplos modelos de negócio:

-  **White-label** (sua marca)
-  **SaaS** (assinatura recorrente)
-  **Desktop App** (licença vitalícia)
-  **Licenciamento para Escolas**
-  **Treinamento Corporativo (T&D)**
-  **Programas Governamentais de Educação**

---

##  O Que Está Incluído na Aquisição

| Item | Status |
|:---|:---|
| Código-fonte completo (Python / Vanilla JS) | |
| Executável .exe para Windows |  |
| Instalador profissional (Inno Setup) |  |
| Banco de dados pré-preenchido (260+ palavras, 80+ diálogos, 18 conquistas) | |
| Documentação de Arquitetura |  |
| Relatório de Auditoria de Segurança (Bandit) |  |
| Registro no INPI (direitos transferíveis) |  |
| Pipeline de IA integrado e testado |  |
| Sistema de Gamificação com SRS |  |

---

##  Demonstração

 [Assista à demonstração em vídeo](#) https://youtu.be/ZR_pklHKgB4

![Tela de Pronúncia](docs/screenshots/pronunciation.png)
![Tela de Diálogo](docs/screenshots/dialog.png)
![Tela de Progresso](docs/screenshots/progress.png)

---

##  Documentação Adicional

- [Especificação Técnica Completa](docs/SPECIFICATION.md)
- [Relatório de Segurança (Bandit)](docs/security/bandit_report.html)
- [Arquitetura Detalhada](docs/architecture.md)

---

##  Contato para Aquisição

Interessado em adquirir este ativo ou solicitar uma demonstração ao vivo?

 **E-mail:** [expeditoanderson08@gmail.com](mailto:expeditoanderson08@gmail.com)

> *Conversas confidenciais. Documentação completa disponível sob NDA.*
