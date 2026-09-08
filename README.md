# Bruno Nóbrega — Field Notes on Building with AI 🌿⚡

> **Diário de campo e portfólio de um professor da rede pública construindo produtos EdTech e ferramentas de pesquisa assistido por IA.**

[![Website](https://img.shields.io/badge/Website-bjnobrega.github.io%2Ffield--notes-0F1E1A?style=for-the-badge&logoColor=C9A227)](https://bjnobrega.github.io/field-notes/)
[![License: MIT](https://img.shields.io/badge/License-MIT-C9A227.svg?style=for-the-badge)](LICENSE)

---

## 📌 Sobre o Projeto

Vinte anos em salas de aula da rede pública em Magé, Rio de Janeiro. Sem formação formal em Ciência da Computação — o desenvolvimento é feito via **pair-programming com IA** (utilizando agentes de código como Antigravity/Google AI Studio, Claude Code e Qwen Code).

Este repositório contém o código-fonte do site [bjnobrega.github.io/field-notes](https://bjnobrega.github.io/field-notes/), concebido sob a metáfora visual de um **diário de campo biológico**. Cada projeto é catalogado como um "espécime", nascido de problemas reais vividos em sala de aula, na pesquisa de mestrado ou no comércio local da Baixada Fluminense.

---

## 📦 Coleção de Espécimes (Trabalhos Entregues)

1. **SPEC. 001 — sabedorIA / appwisdom** (`appsabedoria.com.br`)
   * *SaaS / EdTech*: Plataforma de geração de relatórios que auxilia professores a escrever avaliações de alunos alinhadas à BNCC. Possui banco de descritores em 8 categorias com interface de pontuação por chips.
   * *Stack*: Next.js, Firebase, Vercel.

2. **SPEC. 002 — Provinha** (`appsabedoria.com.br/provinha`)
   * *EdTech / Avaliação Adaptativa*: Motor autônomo que transforma matrizes curriculares geradas por IA em simuladores de exames leves, gamificados e 100% offline em uma única página HTML.
   * *Stack*: Vanilla JS, Tailwind CSS, LocalStorage.

3. **SPEC. 003 — barbearIA**
   * *SaaS / Comércio Local*: Plataforma de agendamento e retenção para barbearias e salões na Baixada Fluminense, com pagamentos Pix (webhooks) e automação via WhatsApp.
   * *Stack*: Next.js, Firestore, Evolution API (Oracle Cloud free-tier).

4. **SPEC. 004 — Pipeline Autônomo de Análise Estatística**
   * *Ferramenta de Pesquisa (M.Sc. UFRJ)*: Pipeline de análise quanti/quali para dados brutos de pesquisa (escala Likert adaptada do ROSE), aplicando testes de Wilcoxon, correlação bisserial e indicadores de alfabetização científica de Sasseron & Carvalho.
   * *Método*: Rigor estatístico validado com auxílio de IA na análise e escrita acadêmica.

5. **SPEC. 005 — Meninas na Robótica** (`bjnobrega.github.io/oficinas-robotica-microbit`)
   * *Robótica Educacional / Publicação*: Produto educacional da defesa de Mestrado na UFRJ. E-book pedagógico de 83 páginas e flipbook web com 5 oficinas práticas de BBC micro:bit para turmas femininas da rede pública.
   * *Formato*: Web Flipbook Interativo + PDF Open-source.

6. **SPEC. 006 — LoudText** (`github.com/bjnobrega/loud_text`)
   * *Acessibilidade & Produtividade*: Leitor minimalista de texto para voz (TTS) construído para vencer a exaustão cognitiva na leitura de artigos e documentos acadêmicos volumosos.
   * *Stack*: React, Vite, Web Speech API.

---

## 🛠️ O Kit de Campo (Stack & Ferramental)

* **Desenvolvimento Web**: HTML5 Semântico, CSS3 (Mobile-First), Vanilla JS, Next.js, React, TypeScript.
* **Backend & Infraestrutura**: Firebase / Firestore, Vercel, Oracle Cloud (Always Free Tier), Evolution API (WhatsApp).
* **Agentes & Orquestração de IA**:
  * **Antigravity (Google AI Studio)** — Agente primário de desenvolvimento de código.
  * **Claude Code & Qwen Code** — Arquitetura, refatoração e revisão de código.
  * **ChatGPT & Perplexity** — Pesquisa e síntese de informações.

---

## 🎨 Design & Arquitetura Web

- **Mobile-First**: Construído do menor para o maior dispositivo usando CSS nativo com `min-width` media queries.
- **Zero Dependências**: Desempenho máximo sem necessidade de compilação ou frameworks pesados de frontend no site principal.
- **Internacionalização**: Suporte nativo bilíngue (Português em `pt.html` e Inglês em `index.html`).
- **Acessibilidade**: Suporte a navegação por teclado (`:focus-visible`), alto contraste e `prefers-reduced-motion`.

---

## 🚀 Como Executar Localmente

Como o projeto é construído em HTML/CSS nativo, você não precisa instalar o Node.js nem gerenciar dependências.

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/bjnobrega/field-notes.git
   cd field-notes
   ```

2. **Abra no navegador**:
   - Dê um duplo clique no arquivo `index.html` (versão em inglês) ou `pt.html` (versão em português).
   - Ou utilize a extensão **Live Server** no VS Code / Antigravity IDE.
   - Ou via terminal com Python:
     ```bash
     python -m http.server 8000
     # Acesse http://localhost:8000
     ```

---

## 📩 Contato & Apoio

Sou um professor de escola pública no Brasil construindo com orçamento próprio. Busco parcerias, *grants* de pesquisa, créditos de API e acesso a modelos de fronteira para continuar testando o estresse da IA em ambientes de baixo recurso e distribuindo ferramentas gratuitas para professores.

* 🌐 **SaaS**: [appsabedoria.com.br](https://appsabedoria.com.br)
* 🐙 **GitHub**: [github.com/bjnobrega](https://github.com/bjnobrega)
* ✉️ **E-mail**: [bjnobrega@ufrj.br](mailto:bjnobrega@ufrj.br)

---

## 📜 Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
