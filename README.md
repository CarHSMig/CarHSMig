<h1 align="center">Carlos Henrique dos Santos Migon</h1>

<p align="center">
  <b>Desenvolvedor Full-Stack</b> · Ruby on Rails · TypeScript · Python<br>
  <sub>SaaS multi-tenant · APIs REST · processamento assíncrono · integrações com IA</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/carlos-henrique-dos-santos-migon-46387b336/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="#projetos-em-destaque"><img src="https://img.shields.io/badge/Projetos-24292F?style=for-the-badge&logo=github&logoColor=white" alt="Projetos"></a>
  <img src="https://img.shields.io/badge/Brasil-009C3B?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Brasil">
</p>

---

## Sobre

Sou desenvolvedor full-stack com foco em **back-end Ruby on Rails** e experiência na construção de
produtos SaaS para o mercado financeiro. Trabalho em todas as camadas da aplicação, da modelagem do banco
de dados à interface, sempre com testes automatizados e atenção a desempenho, segurança e isolamento de dados.

Hoje atuo na **Proteo**, plataforma SaaS de compliance usada por instituições financeiras para prevenção à
lavagem de dinheiro e ao financiamento do terrorismo (PLD/FT).

## Experiência

**Desenvolvedor Full-Stack · Proteo**

- Desenvolvimento de uma aplicação **Rails multi-tenant**, com isolamento por schema no PostgreSQL.
- Processamento assíncrono e orquestração de rotinas com **Sidekiq** e Redis.
- Integrações com bureaus e fontes externas de dados para análise cadastral e de risco.
- Recursos de **IA** aplicados ao produto, como agentes e extração de documentos.
- Interfaces com **Hotwire** (Turbo + Stimulus), **ViewComponent** e Tailwind CSS.
- Testes com **RSpec**, revisão de código e documentação técnica.

## Formação

**Análise e Desenvolvimento de Sistemas** · UNIPAR

## Competências

| Área | Tecnologias |
|---|---|
| **Back-end** | Ruby, Ruby on Rails, Node.js, NestJS, Express, Python, FastAPI |
| **Front-end** | Hotwire (Turbo + Stimulus), ViewComponent, React, Next.js, TypeScript, Tailwind CSS |
| **Dados** | PostgreSQL, pgvector, Redis, modelagem relacional, SQL |
| **Infra e qualidade** | Docker, AWS, GitHub Actions, RSpec, Jest, RuboCop |
| **Outros** | Sidekiq, JWT, APIs REST, ActionCable, Swift / SwiftUI |

<p>
  <img src="https://skillicons.dev/icons?i=ruby,rails,postgres,redis,docker,aws,ts,nodejs,nestjs,nextjs,react,tailwind,py,fastapi,swift&theme=dark" alt="Ruby, Rails, PostgreSQL, Redis, Docker, AWS, TypeScript, Node.js, NestJS, Next.js, React, Tailwind, Python, FastAPI, Swift">
</p>

---

## Projetos em destaque

### Presence: controle de presença com geolocalização e reconhecimento facial

Sistema distribuído em três serviços. O aluno confirma a presença pelo celular, e a API só a registra quando
o horário do evento, a localização e o rosto conferem.

| Repositório | Stack | Responsabilidade |
|---|---|---|
| [**presence**](https://github.com/CarHSMig/presence) | Rails 8 · PostgreSQL + pgvector · JWT · Pundit · ActionCable · RSpec | API central e regras de negócio |
| [**Presence-FRONT**](https://github.com/CarHSMig/Presence-FRONT) | Next.js 16 · React 19 · Tailwind + shadcn/ui · TanStack | Painel administrativo e confirmação |
| [**Presence-face-recognition**](https://github.com/CarHSMig/Presence-face-recognition) | Python · FastAPI · InsightFace · pgvector · Docker | Embeddings e verificação facial |

### [claude-usage](https://github.com/CarHSMig/claude-usage)

Aplicativo nativo de macOS em **Swift 6 / SwiftUI** que monitora os limites de uso do Claude Code em várias
contas, indica a conta com mais capacidade disponível e registra horas de IA por projeto. Testado com XCTest.

### Encurtador de URLs

O mesmo domínio implementado com duas arquiteturas:

- [**short-url**](https://github.com/CarHSMig/short-url): Node.js, Express, Sequelize e PostgreSQL, com testes de request em Jest + Supertest.
- [**ts-short-url**](https://github.com/CarHSMig/ts-short-url): NestJS, TypeScript, TypeORM e Docker Compose.

### [APIbank](https://github.com/CarHSMig/APIbank)

API bancária em Rails com regras de negócio no domínio: abertura de conta com validação de documento e
idade, upload de documento com ActiveStorage e transações de débito e crédito com controle de saldo.

<details>
<summary><b>Outros repositórios</b></summary>
<br>

- [**education-page**](https://github.com/CarHSMig/education-page): página educativa de matemática para crianças, em Next.js + TypeScript.
- [**classes_unipar**](https://github.com/CarHSMig/classes_unipar): padrão de projeto State e jogo de labirinto em Ruby puro.

</details>

---

## Atividade no GitHub

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=CarHSMig&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&theme=tokyonight" alt="Estatísticas do GitHub">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs?username=CarHSMig&layout=compact&langs_count=8&hide_border=true&theme=tokyonight" alt="Linguagens mais usadas">
</p>

<p>
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=CarHSMig&theme=tokyo-night&hide_border=true&area=true" alt="Gráfico de contribuições">
</p>

---

<p align="center">
  Aberto a conversas sobre desenvolvimento web, Ruby on Rails e produtos SaaS.<br>
  Vamos nos conectar no <a href="https://www.linkedin.com/in/carlos-henrique-dos-santos-migon-46387b336/">LinkedIn</a>.
</p>
