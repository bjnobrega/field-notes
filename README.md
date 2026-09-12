# Bruno Nóbrega — Field Notes on Building with AI 🌿⚡

> **Diário de campo e portfólio de um professor da rede pública construindo produtos EdTech e ferramentas de pesquisa assistido por IA.**

[![Website](https://img.shields.io/badge/Website-bjnobrega.github.io%2Ffield--notes-0F1E1A?style=for-the-badge&logoColor=C9A227)](https://bjnobrega.github.io/field-notes/)
[![License: MIT](https://img.shields.io/badge/License-MIT-C9A227.svg?style=for-the-badge)](LICENSE)

---

## 📌 Sobre o Projeto

Vinte anos em salas de aula da rede pública no Rio de Janeiro. Minha formação acadêmica é em **Biologia e Educação**, não em Ciência da Computação, e o desenvolvimento é feito por **pair-programming assistido por IA**, utilizando agentes de código como Antigravity/Google AI Studio, Claude Code e Qwen Code.

Este repositório contém o código-fonte do site [bjnobrega.github.io/field-notes](https://bjnobrega.github.io/field-notes/), concebido sob a metáfora visual de um **diário de campo biológico**. Cada projeto é catalogado como um "espécime", nascido de problemas reais vividos na educação pública, na pesquisa de mestrado ou no comércio local da Baixada Fluminense.

---

## 📦 Coleção de Espécimes

1. **SPEC. 001 — sabedorIA / appwisdom** — [Ao vivo](https://appsabedoria.com.br)
   * *SaaS / EdTech*: plataforma de geração de relatórios que auxilia professores a escrever avaliações de alunos alinhadas à BNCC, com banco de descritores em 8 categorias e interface de pontuação por chips.
   * *Stack*: Next.js, Firebase, Vercel.

2. **SPEC. 002 — Provinha** — [Ao vivo](https://appsabedoria.com.br/provinha)
   * *EdTech / Avaliação*: motor que transforma matrizes curriculares geradas por IA em simuladores leves, gamificados e 100% offline em uma única página HTML.
   * *Stack*: Vanilla JS, Tailwind CSS, LocalStorage.

3. **SPEC. 003 — barbearIA**
   * *SaaS / Comércio Local*: plataforma em desenvolvimento para agendamento e retenção de clientes em pequenos negócios da Baixada Fluminense, com Pix via webhook e automações de WhatsApp.
   * *Stack*: Next.js, Firestore, Evolution API / Oracle Cloud.

4. **SPEC. 004 — Pipeline de análise de pesquisa assistido por IA**
   * *Ferramenta de Pesquisa (M.Sc. UFRJ)*: fluxo quanti/quali para dados de pesquisa, com testes de Wilcoxon, correlação bisserial e codificação com indicadores de alfabetização científica de Sasseron & Carvalho.
   * *Método*: IA auxilia análise e escrita, com testes estatísticos explícitos e revisão humana.

5. **SPEC. 005 — Meninas na Robótica** — [Projeto](https://bjnobrega.github.io/oficinas-robotica-microbit/) · [GitHub](https://github.com/bjnobrega/oficinas-robotica-microbit)
   * *Robótica Educacional / Publicação*: produto educacional desenvolvido como parte da dissertação de Mestrado na UFRJ. E-book pedagógico de 83 páginas e flipbook web com 5 oficinas práticas de BBC micro:bit, com foco na participação de meninas em STEM.
   * *Status*: publicado como parte da pesquisa de Mestrado; defesa ainda em andamento no PPG ProfiCiências / UFRJ.

6. **SPEC. 006 — LoudText** — [GitHub](https://github.com/bjnobrega/loud_text)
   * *Acessibilidade & Produtividade*: leitor minimalista de texto para voz criado para reduzir fadiga visual e cognitiva em leituras acadêmicas longas.
   * *Stack*: React, TypeScript, Vite, Web Speech API.
   * *Status*: ferramenta pessoal ativa, com código publicamente visível no GitHub.

---

## 🛠️ O Kit de Campo

* **Desenvolvimento Web**: HTML5, CSS3, Vanilla JS, Next.js, React, TypeScript.
* **Backend & Infraestrutura**: Firebase / Firestore, Vercel, Oracle Cloud, Evolution API.
* **Agentes & IA**:
  * **Antigravity / Google AI Studio** — desenvolvimento assistido por IA.
  * **Claude Code & Qwen Code** — arquitetura, implementação, refatoração e revisão.
  * **ChatGPT & Perplexity** — pesquisa e síntese de informações.

---

## 🎨 Design & Arquitetura Web

- **Mobile-first**: CSS nativo com layout responsivo.
- **Site principal sem framework**: HTML/CSS leve, sem etapa de build.
- **Bilíngue**: Português em `pt.html` e Inglês em `index.html`.
- **Acessibilidade**: navegação por teclado, alto contraste e `prefers-reduced-motion`.

---

## 🚀 Como Executar Localmente

```bash
git clone https://github.com/bjnobrega/field-notes.git
cd field-notes
python -m http.server 8000
```

Ou abra diretamente `index.html` / `pt.html` no navegador.

---

## 📩 Contato & Apoio

Sou um professor de escola pública no Brasil construindo com orçamento próprio. Busco parcerias, *grants* de pesquisa, créditos de API, suporte de infraestrutura e acesso a modelos para continuar testando IA em contextos reais de baixo recurso e desenvolvendo ferramentas úteis para educação.

* 🌐 **SaaS**: [appsabedoria.com.br](https://appsabedoria.com.br)
* 🐙 **GitHub**: [github.com/bjnobrega](https://github.com/bjnobrega)
* ✉️ **E-mail**: [bjnobrega@ufrj.br](mailto:bjnobrega@ufrj.br)

---

## 📜 Licença

Este site está licenciado sob a [Licença MIT](LICENSE).
