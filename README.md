# 🚀 Portal do Calouro - UNIVESP

> Um ecossistema digital completo projetado para guiar, integrar e facilitar a jornada dos novos estudantes no Ambiente Virtual de Aprendizagem (AVA) e na estrutura do curso.

---

## 🌐 Sobre o Projeto

O **Portal do Calouro** nasceu para resolver uma dor real: a sobrecarga de informações que os novos alunos enfrentam ao ingressar na universidade. Em vez de manuais longos e confusos, este projeto oferece uma experiência interativa, fluida e acessível de qualquer dispositivo.

O projeto é composto por um ecossistema com duas pontes de navegação integradas:
1. **O Portal Web (Online):** Interface interativa contendo cronogramas, FAQs dinâmicos e um assistente virtual inteligente.
2. **O Manual de Impressão (Offline/PDF):** Um layout HTML alternativo, otimizado especificamente para geração de PDF via navegador (sem bordas indesejadas e com aproveitamento total de página), permitindo o estudo offline.

---

## ⚡ Funcionalidades Principais

*   **🤖 Chatbot IA Integrado:** Um assistente virtual inteligente baseado no modelo *stateless* (estilo NotebookLM). Ele processa as dúvidas dos calouros em tempo real usando como base os documentos oficiais do curso.
    *   *Privacidade Garantida:* As conversas são tratadas de forma isolada por sessão do navegador, garantindo que nenhum usuário veja o histórico do outro e eliminando a necessidade de logins complexos.
*   **📄 Design Otimizado para Impressão:** O arquivo `versao-impressao.html` utiliza CSS `@media print` customizado para zerar margens e forçar a renderização de fundos, permitindo que o usuário gere um PDF impecável com `Ctrl + P`.
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