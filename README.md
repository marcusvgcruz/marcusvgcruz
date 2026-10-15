<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=24&pause=1200&color=FF7A00&center=true&vCenter=true&width=700&lines=Ol%C3%A1%2C+eu+sou+o+Marcus+Cruz+%F0%9F%91%8B;Desenvolvedor+Python+%7C+APIs+%7C+Automa%C3%A7%C3%A3o;Construindo+com+Intelig%C3%AAncia+Artificial" alt="Marcus Cruz" />

**Desenvolvedor Python · APIs REST · Automação · Inteligência Artificial**

São José dos Campos, SP 🇧🇷

[![LinkedIn](https://img.shields.io/badge/LinkedIn-marcusvgcruz-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcusvgcruz)
[![GitHub](https://img.shields.io/badge/GitHub-marcusvgcruz-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/marcusvgcruz)
[![Gmail](https://img.shields.io/badge/E--mail-marcusvgcruz23%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:marcusvgcruz23@gmail.com)

[![Português](https://img.shields.io/badge/PT-Portugu%C3%AAs-009C3B?style=for-the-badge)](#)
[![English](https://img.shields.io/badge/EN-English-1F6FEB?style=for-the-badge)](README.en.md)

</div>

---

## 👨‍💻 Sobre mim

Sou desenvolvedor **Python** com 7 anos de experiência em tecnologia, construída na
operação — sustentação de sistemas, análise funcional e investigação de incidentes.
Esse caminho me deu algo que levo para o código: leio logs, escrevo SQL para
entender o dado de verdade e traduzo a necessidade do negócio em algo que o time
consegue implementar.

Hoje construo aplicações web com **Django**, **APIs REST**, automações e integrações
com **Inteligência Artificial**. Gosto de problema real, de código legível e de
entrega verificada.

---

## 🎯 No que estou trabalhando

- 🐍 **Backend com Python e Django** — arquitetura em apps por domínio, ORM, autenticação e autorização
- 🔌 **APIs REST** — Django REST Framework, autenticação JWT, permissões e serialização
- 🤖 **IA aplicada** — integração com LLMs, RAG, agentes, automações e orquestração de contexto
- 🔎 **Dados e observabilidade** — SQL, análise de logs, métricas e monitoramento
- ✅ **Qualidade** — testes automatizados, refatoração segura e documentação técnica

---

## 🧰 Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=for-the-badge&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![REST](https://img.shields.io/badge/REST%20APIs-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![LLMs](https://img.shields.io/badge/LLMs%20%26%20RAG-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini%20API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)

</div>

---

## 📌 Projetos em destaque

### 🎓 Inglês Smart — portal escolar completo
Sistema web que substituiu planilhas e processos manuais de uma escola de idiomas:
turmas e horários, presenças e reposições, avaliações por competência, financeiro,
gamificação com ranking e feed de conteúdo — com portal do aluno em PWA.

Depois da entrega, o projeto passou por uma **refatoração completa**: os 30 models
que viviam em um único app foram separados em **8 apps por domínio** com migrations
que preservam o schema (sem risco para os dados), a segurança foi endurecida (chave
por variável de ambiente, sanitização de HTML contra XSS, ações de escrita com
POST + CSRF) e todas as telas foram redesenhadas.

`Django` `PostgreSQL` `PWA` `Chart.js` `CKEditor 5` `nh3`
**[→ ver o projeto](https://github.com/marcusvgcruz/ingles_smart)**

### 🚗 Carros — inventário de veículos com IA
Inventário de veículos com **automação reativa via Django Signals**: a descrição
técnica do carro é gerada por **IA (Gemini)** no momento do cadastro, e o estoque
— com valor patrimonial acumulado — é recalculado a cada movimentação, com histórico.

`Python` `Django` `Django Signals` `Gemini API` `Pillow`
**[→ ver o projeto](https://github.com/marcusvgcruz/carros)**

### 🎬 Flix API — API REST de catálogo de filmes
API REST com autenticação **JWT** e CRUD completo de atores, gêneros, filmes e
avaliações. O destaque é a **permissão customizada** que traduz o método HTTP na
permissão de model do Django (`view_`, `add_`, `change_`, `delete_`) — o controle
de acesso acompanha o modelo de dados sem código repetido — além de um endpoint de
**estatísticas agregadas**.

`Python` `Django REST Framework` `SimpleJWT` `SQLite`
**[→ ver o projeto](https://github.com/marcusvgcruz/flix_api)**

---

## 🧭 Como eu trabalho

- **Verifico antes de dizer que está pronto** — teste automatizado e evidência real, não "deve funcionar"
- **Código que outra pessoa consegue ler** — nomes claros, responsabilidade única, sem mágica desnecessária
- **Refatoração com rede de segurança** — mudar a estrutura sem quebrar o que já funciona
- **Documento o que faço** — README que explica o *porquê*, não só o *como*
- **Entendo o problema antes da solução** — a vivência em suporte e análise de sistemas ajuda nisso

---

<div align="center">

**Aberto a oportunidades em desenvolvimento Python, APIs e automação com IA.**

Vamos conversar? [LinkedIn](https://www.linkedin.com/in/marcusvgcruz) · [marcusvgcruz23@gmail.com](mailto:marcusvgcruz23@gmail.com)

</div>
