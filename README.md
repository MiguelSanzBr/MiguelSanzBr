<img align="center" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=gradient&section=header">

# Olá, sou o Miguel 👋

**Engenheiro de Software Back-end** em São Paulo: Go, PHP/Laravel e Python, com AWS em produção.

Construo APIs, mensageria e infraestrutura que aguentam carga e falha. Disponível para vaga back-end pleno (SP híbrido/presencial ou remoto).

### 🚀 Destaques profissionais
- 🛰️ **Gateway de mensageria em Go** (criador e arquiteto): outbox no Postgres com `SKIP LOCKED`, idempotência em 3 camadas. 900 msg/min por 10 min, 0% de falhas e p95 de 1,05 s em teste de carga na AWS
- 💰 **API de coleta de notícias** em PHP/Laravel + MongoDB, criada do zero: custo 99% menor (~R$ 107 mil/ano)
- ☁️ **Migração de produção do GCP para a AWS**, segredos no SSM via OIDC, observabilidade com Prometheus e Grafana
- 🧪 **Qualidade**: TDD, gates de 100% de cobertura, PHPStan de 1.770 erros para zero

> A maior parte do meu trabalho profissional está em repositórios privados (o gráfico abaixo inclui essas contribuições). Aqui ficam os projetos open source.

### 📌 Projetos open source

**Back-end em Go e Laravel.** Os padrões que uso no trabalho, reescritos do zero e abertos: DDD e arquitetura hexagonal com a regra de dependência travada por teste, TDD no histórico, 100% de cobertura com gate no CI e teste de mutação.

| Projeto | O que faz |
|---|---|
| **[outbox-gateway-demo](https://github.com/MiguelSanzBr/outbox-gateway-demo)** | Gateway de mensagens em Go com outbox no Postgres: `SKIP LOCKED`, lease com fencing token, ordem por destinatário, painel ao vivo via SSE, `/metrics` e números do k6, inclusive com `kill -9` |
| **[webhook-relay](https://github.com/MiguelSanzBr/webhook-relay)** | Recebe webhook, confere HMAC-SHA256 em tempo constante, barra replay e excesso por IP e repassa assinado, com retry. Só stdlib, `govulncheck` no CI |
| **[multitenant-invoicing](https://github.com/MiguelSanzBr/multitenant-invoicing)** | SaaS de cobrança multi-tenant em Laravel 13 + Inertia + React: isolamento por empresa garantido no banco e nos testes, lembrete idempotente que sai pelo outbox-gateway-demo |

**Periféricos no Linux.** Configuradores Linux para periféricos que só tinham software para Windows. Fiz a engenharia reversa do protocolo USB HID de cada app oficial (.NET, Electron e C++ nativo no Ghidra), validei cada byte no hardware real e publiquei CLI + GUI com testes contra um emulador do dispositivo.

| Projeto | O que faz | ⭐ |
|---|---|---|
| **[8bitdo-ultimate2-linux](https://github.com/MiguelSanzBr/8bitdo-ultimate2-linux)** | Remapeamento, sticks, gatilhos, giroscópio, LEDs e perfis do 8BitDo Ultimate 2 | 34 |
| **[gamesir-cyclone2-linux](https://github.com/MiguelSanzBr/gamesir-cyclone2-linux)** | Configurador do controle GameSir Cyclone 2 | 16 |
| **[attackshark-x11-linux](https://github.com/MiguelSanzBr/attackshark-x11-linux)** | DPI, polling, botões, iluminação e bateria do mouse ATTACK SHARK X11 | 7 |

Python + Tk direto no `/dev/hidraw`, sem daemon · 100% de cobertura · `.deb`, AppImage e [repositório Flatpak assinado](https://github.com/MiguelSanzBr/flatpak) · MIT

Versão web de cada um, direto no Chrome via WebHID: [8BitDo](https://miguelsanzbr.github.io/8bitdo-ultimate2-web/) · [GameSir](https://miguelsanzbr.github.io/gamesir-cyclone2-web/) · [ATTACK SHARK](https://miguelsanzbr.github.io/attackshark-x11-web/)

Também: **[Mini-CRM](https://github.com/MiguelSanzBr/teste-laravel-vue)** em Laravel + Inertia + Vue 3 com Docker · **[Portfólio](https://miguelsanzbr.github.io)**

### 🛠️ Stack
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=go,php,laravel,py,fastapi,postgres,redis,mongodb,docker,aws,githubactions,prometheus,grafana,linux"/>
  </a>
</p>

<hr>

## 📈 Atividade

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=miguelsanzbr&theme=react-dark" width="688">
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MiguelSanzBr/MiguelSanzBr/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/MiguelSanzBr/MiguelSanzBr/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/MiguelSanzBr/MiguelSanzBr/output/github-contribution-grid-snake.svg">
</picture>

<hr>

## 📞 Contato
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0F0F0F?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/miguel-sanz-boragan)
[![Gmail](https://img.shields.io/badge/Gmail-0F0F0F?style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:miguelsanzb.p@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-0F0F0F?style=for-the-badge&logo=telegram&logoColor=00CED1)](https://t.me/lkaizen)

<img align="center" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=gradient&section=footer">
