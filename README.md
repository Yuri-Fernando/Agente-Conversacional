# Agente Conversacional WhatsApp + Supabase + GPT-4o

Este projeto é um fluxo completo desenvolvido no **n8n**, que implementa um agente conversacional integrado ao WhatsApp, com gerenciamento de leads via **Supabase**, memória via **Redis**, e geração de respostas por **IA (GPT-4o-mini)**.

### Funcionalidades:
- Captura e cria leads automaticamente no Supabase
- Consulta e atualiza dados de leads com controle de interação
- Conta quantas vezes o usuário interagiu e ativa modo humano após X tentativas
- Responde apenas mensagens do usuário (ignora mensagens enviadas pelo bot)
- Filtra por tipo de mensagem (áudio, texto, imagem, figurinha, vídeo, etc.)
- Usa Redis para armazenar e comparar histórico recente da conversa
- Gera **respostas contextualizadas e com copy personalizada** com LLM (Gi Vautrin)
- Sempre inclui links estratégicos e provocativos para conversão
- Integra com API de envio de mensagens externas (Webhook EvolutionAPI)
- Cria logs de interação no Supabase para análise e histórico
- Integra com **Trello** para marcar leads com call agendada (modo SDR)

### Tecnologias:
- `n8n`
- `Supabase`
- `Redis`
- `LangChain / GPT-4o-mini`
- `Webhook/API REST`
- `Trello`
- `JavaScript Functions`

### Use Cases:
- Funil de vendas automatizado
- SDR com agente IA treinado
- Atendimento sexy, ousado ou persona provocativa (ex: OnlyFans/Hotmart/Beacons)
- Retenção e reativação por contexto
