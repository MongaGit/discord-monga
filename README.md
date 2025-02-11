# 🤖 Discord Monga Bots

Este repositório centraliza e orquestra bots especializados para o servidor Discord do Monga. Cada bot é desenvolvido com foco em containerização, manutenibilidade e resolução de problemas específicos.

## 🔗 Repositórios

[![mongaprops](https://img.shields.io/badge/mongaprops-181717?style=for-the-badge&logo=github)](https://github.com/mongagit/discord-mongaprops)
[![mongaboss](https://img.shields.io/badge/mongaboss-181717?style=for-the-badge&logo=github)](https://github.com/mongagit/discord-mongaboss)
[![mongadj](https://img.shields.io/badge/mongadj-181717?style=for-the-badge&logo=github)](https://github.com/mongagit/discord-mongadj)
[![mongahltv](https://img.shields.io/badge/mongahltv-181717?style=for-the-badge&logo=github)](https://github.com/mongagit/discord-mongahltv)


## 🎯 Bots

### discord-mongaprops
Bot para gerenciamento de mensagens automáticas e props diárias, enviando mensagens de "Bom dia" com imagens personalizadas em horários configuráveis.

### discord-mongaboss  
Bot de administração para gerenciamento de cargos e permissões, com suporte a roles temporárias e logs de auditoria.

### discord-mongadj
Bot de música integrado com SoundCloud, permitindo reprodução de músicas em canais de voz através de comandos simples.

### discord-mongahltv
Bot para acompanhamento de partidas de CS2, monitorando jogos da HLTV e criando eventos automáticos no Discord.



## 🛠️ Tecnologias

- Node.js (Discord.js)
- Python
- Docker / Docker Compose
- Git Submodules

## 📦 Deploy

Os bots podem ser executados individualmente ou em conjunto usando Docker Compose:

```bash
# Clone o repositório com submódulos
git clone --recursive https://github.com/MongaGit/discord-monga.git

# Configure as variáveis de ambiente
cp .env.exemple .env

# Inicie todos os bots
docker compose up -d
```

