# 💬 Chat IA — Standalone para Netlify

Versão completa do Campo Livre em um único arquivo HTML.
Sem servidor, sem banco de dados — funciona em qualquer hospedagem estática.

## Como publicar no Netlify (grátis, 1 minuto)

1. Acesse https://www.netlify.com e crie uma conta gratuita
2. Na dashboard, clique em **"Add new site" → "Deploy manually"**
3. Arraste a pasta do projeto (ou só o `index.html`) para a área indicada
4. Pronto! O site estará online em um link .netlify.app

## Funcionalidades
- ✅ Chat em tempo real com streaming
- ✅ Múltiplos provedores de IA (Groq, OpenAI, Gemini, OpenRouter, Perplexity)
- ✅ Detecção automática de provedor pela chave
- ✅ Múltiplas chaves salvas (localStorage)
- ✅ Voz: ditar mensagens por voz (pt-BR)
- ✅ TTS: IA lê as respostas em voz alta
- ✅ Exportar conversa como .txt
- ✅ Importar arquivo de texto (.txt, .md, .csv, .json)
- ✅ Blocos de código com botão Copiar
- ✅ Interface 100% em português
- ✅ PWA-ready (funciona offline após primeira visita)

## Provedores suportados (com CORS liberado)
| Prefixo da chave | Provedor | Gratuito? |
|---|---|---|
| gsk_ | Groq | ✅ Sim |
| sk- | OpenAI | 💳 Pago |
| AIza | Google Gemini | ✅ Sim (cota) |
| sk-or- | OpenRouter | ✅ Sim (cota) |
| pplx- | Perplexity | 💳 Pago |

## Obter chave Groq (gratuita, sem cartão)
1. Acesse https://console.groq.com
2. Crie uma conta
3. Vá em API Keys → Create API Key
4. Cole a chave (começa com gsk_) no campo ⚙️ do Chat IA
