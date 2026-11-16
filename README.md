<div align="center">

<!-- Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,50:414868,100:7aa2f7&height=180&section=header&text=Fernando%20Garcia&fontSize=42&fontColor=c0caf5&animation=fadeIn&fontAlignY=35&desc=Analista%20L%C3%ADder%20Fluig%20%E2%80%A2%20Desenvolvedor%20Full-stack&descSize=18&descAlignY=55" width="100%"/>

<!-- Typing intro -->
<a href="https://github.com/ferpgshy">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3500&pause=800&color=7AA2F7&center=true&vCenter=true&width=600&lines=Full+Stack+Developer+%F0%9F%9A%80;React+%E2%80%A2+TypeScript+%E2%80%A2+Node+%E2%80%A2+Python+%E2%80%A2+Go;Vis%C3%A3o+Computacional+%E2%80%A2+YOLOv8+%E2%80%A2+OpenCV;Analista+L%C3%ADder+TOTVS+Fluig+%E2%80%A2+BPM+%E2%80%A2+ECM+%E2%80%A2+WCM;Agentes+de+IA+com+Claude+Code;Rumo+a+Tech+Lead+%F0%9F%8E%AF" alt="Typing SVG" />
</a>

<br/>

<!-- Social badges -->
<a href="https://www.linkedin.com/in/fernando-portugal-garcia">
  <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Fernando%20Portugal%20Garcia-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
<a href="mailto:fernando.garcia2505@hotmail.com">
  <img alt="Email" src="https://img.shields.io/badge/Email-Contato-EA4335?style=for-the-badge&logo=gmail&logoColor=white">
</a>
<a href="https://github.com/ferpgshy">
  <img alt="GitHub followers" src="https://img.shields.io/github/followers/ferpgshy?style=for-the-badge&logo=github&logoColor=white&labelColor=1a1b27&color=7aa2f7">
</a>

</div>

<br/>

## 👋 Sobre mim

```typescript
const fernando = {
  localizacao: "Brasil 🇧🇷 (UTC-3)",
  atuacao: ["Desenvolvimento Web", "Analista Líder TOTVS Fluig", "Engenharia de processos (BPMN)", "Agentes de IA", "Visão Computacional", "Automações"],
  experiencia: "Produtos full-stack, levantamento de processos, especificação funcional, implantação de software e homologação",
  metodologia: ["Scrum", "estimativas & precificação", "documentação técnica"],
  objetivo: "Evoluir como Dev Web → Tech Lead 🎯",
  lema: "Entregas funcionais, testáveis e bem documentadas",
};
```

- 🔭 Atuo em **produtos full-stack de ponta a ponta**, do frontend React à infraestrutura com Docker e Terraform
- 🏢 Analista líder **TOTVS Fluig**: levantamento de processos, **BPMN**, especificação funcional (Pré-MIT e MIT098), formulários ECM, datasets, eventos e widgets WCM
- 👁️ Trabalho com **visão computacional** (YOLOv8, OpenCV) e **processamento de vídeo em tempo real**
- 🧩 Vivência em **estimativas, documentação funcional/técnica** e apresentações executivas
- 🤖 Construo **agentes de IA com Claude Code** para o dia a dia de consultoria: do levantamento ao BPMN, à MIT e aos formulários, com fonte para cada informação
- 🌱 Aprofundando **React/TypeScript** (patterns e testes) e arquitetura para liderar squads

<br/>

## 🧰 Stack & Ferramentas

<div align="center">

**Front-end**

<img src="https://skillicons.dev/icons?i=html,css,js,ts,react,vite,tailwind,astro&theme=dark" alt="Front-end" />

**Back-end, Dados & Automação**

<img src="https://skillicons.dev/icons?i=nodejs,express,python,go,lua,mongodb,redis&theme=dark" alt="Back-end" />

**DevOps & Ferramentas**

<img src="https://skillicons.dev/icons?i=docker,terraform,git,github,npm,vscode,powershell&theme=dark" alt="Tools" />

</div>

> Além disso: **TOTVS Fluig** (BPM, ECM, WCM, datasets, Fluig Studio) · **BPMN** e engenharia de processos · **agentes de IA** (Claude Code) · **ERPs** · **OCR** · userscripts (Tampermonkey) · **YOLOv8/OpenCV** (visão computacional) · streaming de vídeo (**RTMP/RTP, SRS, Redis Streams**) · fluxos com **IA generativa**

<br/>

## 💼 Projetos & Contribuições

### 🤝 B-Metric: análise de movimento e engajamento *(contribuidor)*

Sistema **multi-tenant** de análise de engajamento em ambientes educacionais, com visão computacional em tempo real. **Contribuo no ecossistema** (6 repositórios):

```
Câmeras ──▶ Ingest RTMP (Go + SRS) ──▶ Redis Streams ──▶ Consumer (Python + YOLOv8)
                                                              │
        Frontend (React + Vite + Tailwind) ◀── API (Node/Express + MongoDB) ◀──┘
                          │
              Infra: Docker · Terraform · runbooks        Site: Astro
```

- 📹 **Ingest de vídeo:** gateway RTMP em **Go**, decodificação de streams H.264 e publicação de frames via **Redis Streams**
- 🧠 **Processamento:** detecção de pessoas e análise de movimento com **YOLOv8** em Python
- ⚙️ **API REST:** Node.js/Express + Mongoose (MongoDB), arquitetura multi-tenant
- 🖥️ **Dashboard:** React + Vite + TypeScript + Tailwind, métricas em tempo real
- ☁️ **Infra:** Docker Compose, Terraform, configs de deploy e runbooks operacionais

### 🎱 PreviewBall (BilliardAssist): visão computacional em tempo real *(projeto próprio)*

Sistema de análise visual para sinuca: captura frames da tela em tempo real, **detecta bolas e mesa (OpenCV)**, calcula **trajetórias e previsão de tacadas** e renderiza overlay transparente. Inclui calibração HSV, modo debug e sistema de releases com licenças. `Python`

### 🏢 TOTVS Fluig: consultoria e produtos *(atuação profissional)*

Levanto processos com o cliente e transformo em **BPMN**, especificação funcional (Pré-MIT e MIT098) e formulário por etapa. No desenvolvimento, contribuo nos produtos **Kanban** e **Qualidade** para Fluig (widgets WCM): tela de integrantes do quadro, filtros, edição de ocorrências, visualização de anexos, exportação por dataset e modo escuro. `JavaScript` `TypeScript` `FreeMarker`

### 🧠 Fluig Agent Kit *(projeto próprio)*

**[fluig-agent-kit](https://github.com/ferpgshy/fluig-agent-kit)**: kit de trabalho para projetos TOTVS Fluig com agentes de IA. Transforma levantamento de processo em Pré-MIT, MIT098, BPMN, formulário ECM por etapa e especificação de campos, sem nenhuma informação sem fonte. `HTML` `Python` `Node`

### 🌐 Open source & projetos públicos *(projetos próprios)*

| Projeto | Descrição | Stack |
| --- | --- | --- |
| **[kontrollar-intranet](https://github.com/ferpgshy/kontrollar-intranet)** ⭐ | Dashboard/SPA com cards dinâmicos, avisos, chat em grupos, backlog e projetos. Persistência via `localStorage` e foco em UX consistente | `HTML` `CSS` `JS` |
| **[kontrollar-backend](https://github.com/ferpgshy/kontrollar-backend)** | API/back-end do ecossistema Kontrollar | `JavaScript` `Node` |
| **[streaming-anti-hijack](https://github.com/ferpgshy/streaming-anti-hijack)** | Defesa em camadas contra popup/popunder/click-hijack: userscript standalone, sem depender de adblock | `JavaScript` |
| **[d4forge](https://github.com/ferpgshy/d4forge)** | Assistente de encantamento para Diablo IV: lê as opções na tela por OCR e decide pelas suas regras | `Python` |
| **[filtro-de-vagas](https://github.com/ferpgshy/filtro-de-vagas)** | Userscript que lê a vaga aberta e sinaliza dealbreakers em LinkedIn, Catho, Gupy e outros | `JavaScript` |
| **[tadaaa](https://github.com/ferpgshy/tadaaa)** | Jogos de festa e desafios direto no navegador, sem login | `TypeScript` |
| **[fluig-board](https://github.com/ferpgshy/fluig-board)** | Board de gestão integrado ao Fluig (ECM/BPM) | `TypeScript` |
| **[vencord-focus-mode](https://github.com/ferpgshy/vencord-focus-mode)** | Plugin para Discord (Vencord): modo foco sem distrações | `TypeScript` |
| **[attack-shark-v4-R82HE](https://github.com/ferpgshy/attack-shark-v4-R82HE)** | Engenharia reversa + redesign visual do driver Attack Shark (Electron) com documentação de build | `HTML` `Electron` |

<details>
<summary>➕ <b>Mais projetos que desenvolvi</b> (privados/comerciais)</summary>
<br/>

- 🏆 **elevare-torneios**: plataforma de torneios `TypeScript`
- 🛒 **redalertmarket-v2** + **redalert.catalogo**: marketplace e catálogo `TypeScript`
- 🌆 **Sites para comunidades de jogos**: regras, formulários e organizações (múltiplos projetos `TypeScript`/`React`)
- 🤖 **automatizantion-rep4rep**: automação de API `JavaScript`
- 📦 **jynx-fechamento-automatizado**: automação de fechamento `TypeScript`
- 🔧 **shyhub**, **setup-share**, **repo-grabber**: ferramentas e utilitários `TypeScript`

</details>

<br/>

## 📊 Estatísticas

<div align="center">

<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ferpgshy&theme=tokyonight" alt="GitHub Stats" />
<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=ferpgshy&theme=tokyonight" alt="Linguagens" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=ferpgshy&theme=tokyonight&hide_border=true&background=1a1b27&locale=pt_BR" alt="GitHub Streak" />

<br/><br/>

<img src="https://github-trophies.vercel.app/?username=ferpgshy&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8" alt="GitHub Trophies" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ferpgshy&theme=tokyo-night&hide_border=true&bg_color=1a1b27&area=true" width="95%" alt="Contribution Graph" />

</div>

<br/>

## 📚 Como trabalho

- 🤝 **Colaboração & comunicação:** dailies, alinhamentos de escopo e feedback contínuo
- 🧪 **Qualidade:** componentização, estados previsíveis, validação de entradas e logs úteis
- 🚀 **Entrega:** MVP funcional, iteração rápida e métricas simples para guiar evolução
- 📐 **Nada sem fonte:** levantamento conferido, documentação com referência e validação antes de entregar

<br/>

## 🤝 Vamos conversar?

Sinta-se à vontade para abrir uma **issue**, enviar um **PR** ou me chamar no **[LinkedIn](https://www.linkedin.com/in/fernando-portugal-garcia)**.
Curto discutir soluções, revisar código e pensar produto com eficiência. 💬

<div align="center">

<img src="https://komarev.com/ghpvc/?username=ferpgshy&style=for-the-badge&color=7aa2f7&label=Visitas+ao+perfil" alt="Profile views" />

<!-- Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,50:414868,100:1a1b27&height=120&section=footer" width="100%"/>

</div>
