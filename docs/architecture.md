# Arquitetura do TEACHERPRO 

## Componentes Principais
- **Frontend (Vanilla JS):** Interface no navegador que grava áudio e se comunica via HTTP com o backend local.
- **Backend (FastAPI):** Servidor local que orquestra as requisições e conecta os módulos.
- **Pipeline de Áudio:** Redução de ruído, normalização LUFS e remoção de silêncio.
- **Motor de Transcrição (Whisper):** Converte áudio em texto.
- **Análise de Pronúncia:** WavLM + Wav2Vec2 geram score e alinhamento.
- **Tutor IA (Qwen 2.5):** Gera feedback e conduz diálogos.
- **Banco de Dados (SQLite):** Armazena vocabulário, progresso, conquistas.
- **Motor de Contexto Híbrido:** Busca informações online opcionais sem expor dados do usuário.

## Fluxo de uma Análise de Pronúncia
1. O navegador grava o áudio e envia para `/api/analyze`.
2. O backend processa o áudio (noisereduce, pyloudnorm).
3. O Whisper transcreve a fala.
4. O WavLM extrai embeddings acústicos e calcula similaridade.
5. O Wav2Vec2 alinha fonemas no tempo.
6. O Scorer gera uma nota (0–100).
7. O Qwen 2.5 gera feedback personalizado.
8. O progresso é salvo no SQLite.
