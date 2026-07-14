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

## 🛠️ Tecnologias Utilizadas

*   **HTML5 & CSS3:** Estruturação semântica e estilização moderna com variáveis de cores personalizadas e efeitos de brilho em caixas de diálogo.
*   **Design Responsivo:** Adaptado para telas de celulares, tablets e computadores.
*   **Engenharia de Prompt / RAG:** Integração do assistente com foco em documentos específicos da instituição.

---

## 📂 Estrutura do Repositório

```text
├── index.html              # Código principal do Portal Web
├── versao-impressao.html   # HTML especial otimizado para gerar o PDF
└── README.md               # Documentação do projeto (este arquivo)