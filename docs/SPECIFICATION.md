# Especificações Técnicas – TEACHERPRO v4.2

## Visão Geral
O TEACHERPRO é um tutor de inglês com IA que funciona de forma híbrida: 100% offline para aprendizado, com enriquecimento online opcional sem exposição de dados.

## Requisitos de Sistema
- Windows 10/11 (64 bits)
- Mínimo 4 GB de RAM (recomendado 8 GB)
- 5 GB de espaço livre
- Internet apenas na primeira instalação (para baixar modelos)

## Stack Tecnológica
- Backend: Python 3.11, FastAPI, Uvicorn, Ollama
- Frontend: Vanilla JavaScript, HTML5, CSS3
- Banco de Dados: SQLite (WAL mode, Repository Pattern)
- IA: PyTorch, Hugging Face Transformers, Whisper, Torchaudio
- Áudio: librosa, noisereduce, pyloudnorm, pydub
- Voz: gTTS / Edge TTS (cache offline)
- Empacotamento: PyInstaller, Inno Setup
- Segurança: PyArmor, assinatura digital

## Modelos de IA Integrados
1. **Whisper Tiny (OpenAI)** – Transcrição de fala, preservando erros do aluno.
2. **WavLM Base+ (Microsoft)** – Análise acústica e similaridade fonética.
3. **Wav2Vec2 Base (Meta)** – Alinhamento temporal forçado.
4. **Qwen 2.5 Coder 3B (Alibaba)** – Tutor conversacional.

## Funcionalidades
- Vocabulário com mais de 260 palavras em 13 categorias
- Diálogos interativos com personagens
- Conversação livre com tutor IA
- Módulo de números
- Análise de pronúncia (score 0–100)
- Rádio em inglês (streaming opcional)
- Gamificação com XP, níveis, conquistas e repetição espaçada
