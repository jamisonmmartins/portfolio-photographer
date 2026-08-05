# 📸 Rachel Green — Portfolio & Web Design

> Projeto de desenvolvimento Front-End focado na recriação e refatoração de um layout tradicional (inspiração W3Schools) para os padrões modernos de **Acessibilidade (A11y/WCAG)**, **SEO Otimizado** e **Desenvolvimento Semântico Mobile-First**.

---

## 🎯 Sobre o Projeto

Este projeto consiste na construção do site institucional/portfólio para a persona **Rachel Green** (Fotografia e Web Design). 

Diferente de um código básico de aprendizado, a proposta principal deste repositório é **aplicar engenharia de software de alta qualidade no Front-End**:
- Subtituição de layouts genéricos em `<div>` por **HTML5 Semântico**.
- Implementação de técnicas avançadas de acessibilidade **WCAG (Níveis AA/AAA)**.
- Eliminação de redundâncias visuais (ex: correção do grid original da galeria, mantendo 6 fotos exclusivas em vez de duplicatas).
- Estruturação de componentes responsivos usando **CSS Grid e Flexbox com abordagem Mobile-First**.

---

## 🛠️ Tecnologias e Ferramentas

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

- **HTML5 Semântico:** Landmarks (`header`, `nav`, `main`, `section`), hierarquia correta de headings (`h1` ao `h3`).
- **CSS3 Moderno:** Mobile-First, Flexbox, CSS Grid e animações sutis.
- **JavaScript Vanilla:** Manipulação limpa do DOM e gerenciamento de estados de acessibilidade (`aria-expanded`).
- **Padrões de Commit:** Convenção [Conventional Commits](https://www.conventionalcommits.org/).

---

## ♿ Acessibilidade (A11y) & WCAG

A acessibilidade não foi tratada como um detalhe no final, mas como um **requisito arquitetural**:

- ⌨️ **Navegação por Teclado (Skip Link):** Atalho funcional de teclado como primeiro elemento do DOM (`WCAG 2.4.1`) apontando para `<main tabindex="-1">`.
- 🔊 **Compatibilidade com Leitores de Tela:** Atributos ARIA aplicados de forma consciente (`aria-expanded`, `aria-controls`, `aria-label`, `aria-hidden` em SVGs decorativos).
- 🧭 **Marcos de Navegação (Landmarks):** Suporte nativo ao modo de leitor do iOS (VoiceOver) e Android (TalkBack).
- 👁️ **Contraste Mínimo & Foco Visível:** Elementos focáveis preparados para conformidade de contraste e indicação visual.

---

## 🔍 SEO & Desempenho

- **Meta Tags Estruturadas:** `charset`, `viewport` responsivo sem bloqueio de zoom (`user-scalable`), `description` focada.
- **Open Graph (OG Tags):** Configurado para pré-visualização otimizada em redes sociais e apps de mensagem.
- **Otimização de Conteúdo:** Galeria sem repetição desnecessária de assets e atributo `alt` descritivo nas imagens.

---

## 🗺️ Estrutura das Seções

1. **Header & Navigation:** Marca (`h1`), botão de menu acessível e navegação principal (`nav`).
2. **Galeria Portfolio (`h2`):** Grid responsivo com 6 projetos selecionados.
3. **Sobre Mim (`h2`):** Apresentação, seção de *Technical Skills* com barras de progresso e *Cards de Preços/Serviços*.
4. **Contato (`h2`):** Formulário acessível para envio de mensagens.

---

## 🚀 Como executar o projeto localmente

```bash
# Clone o repositório
git clone [https://github.com/jamisonmmartins/portfolio-photographer.git](https://github.com/jamisonmmartins/portfolio-photographer.git)

# Abra o arquivo index.html no seu navegador ou via extensão Live Server no VS Code
