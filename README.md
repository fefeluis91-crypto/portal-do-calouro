# 🚀 Portal do Calouro - UNIVESP

> Um ecossistema digital completo projetado para guiar, integrar e facilitar a jornada dos novos estudantes no Ambiente Virtual de Aprendizagem (AVA) e na estrutura do curso.

---

## 🌐 Contexto Acadêmico & Sobre o Projeto

Este projeto foi desenvolvido como parte de um **Projeto Acadêmico para a UNIVESP (Universidade Virtual do Estado de São Paulo)**. 

O objetivo principal é aplicar conceitos práticos de Engenharia de Software, UX/UI e Inteligência Artificial para resolver uma dor real da comunidade acadêmica: a sobrecarga de informações que os novos alunos enfrentam ao ingressar no ensino a distância (EAD). 

Em vez de manuais estáticos, longos e de difícil navegação, criamos:
1. **O Portal Web (Online):** Interface interativa contendo cronogramas, FAQs dinâmicos e um assistente virtual inteligente.

---

## ⚡ Funcionalidades Principais

*   **🤖 Chatbot IA Integrado:** Um assistente virtual inteligente baseado no modelo *stateless* (estilo NotebookLM). Ele processa as dúvidas dos calouros em tempo real usando como base os documentos oficiais do curso.
    *   *Privacidade Garantida:* As conversas são tratadas de forma isolada por sessão do navegador, garantindo que nenhum usuário veja o histórico do outro e eliminando a necessidade de logins complexos.
*   **🔄 Navegação Cíclica (UX/UI):** O portal web leva ao gerador de PDF e o PDF possui elementos gráficos interativos (como botões neon com indicadores visuais "👉") que trazem o usuário de volta para o ambiente online.

---

## 🛠️ Tecnologias & Metodologia de Desenvolvimento

*   **HTML5 & CSS3:** Estruturação semântica e estilização moderna com variáveis de cores personalizadas, efeitos de brilho neon e responsividade para dispositivos móveis.
*   **CSS @media print:** Engenharia de estilo dedicada para conversão limpa de HTML para PDF direto no navegador.
*   **Vibe Coding (Metodologia de Co-criação):** O projeto foi desenvolvido utilizando a metodologia de *Vibe Coding*, unindo a visão de produto, design e curadoria humana com a velocidade de desenvolvimento e refinamento de código de uma Inteligência Artificial parceira (Gemini). Essa sinergia permitiu prototipar, ajustar estilos em tempo real, testar e publicar a solução com máxima agilidade.

---

## 📂 Estrutura do Repositório

```text
├── index.html              # Código principal do Portal Web
├── versao-impressao.html   # HTML especial otimizado para gerar o PDF
└── README.md               # Documentação do projeto (este arquivo)

---

## 👥 Equipe e Co-criação

*   **[Luis/GitHub]** — Idealizador, Designer UX/UI, Piloto de Desenvolvimento e Engenharia de Prompt (Vibe Coding).
*   **Gabi** — Produção de Conteúdo, Curadoria dos Textos e Estruturação do FAQ.
*   **Gemini (IA)** — Copiloto de Código, responsável por gerar os componentes HTML/CSS sob demanda, auxiliar na lógica de navegação e formatação de impressão.
