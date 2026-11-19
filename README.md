# 🎮 English Quest — Gamified Quiz

Aplicação web educativa e interativa desenvolvida para apoiar a prática de vocabulário, *phrasal verbs*, falsos cognatos (*false friends*), expressões idiomáticas e compreensão em Língua Inglesa durante sessões de mentoria e estudo.

> Projeto desenvolvido no âmbito da **Atividade Extensionista (Jogos Digitais)** — **FMU**.

---

## ✨ Funcionalidades

* **Quiz interativo de 8 questões** divididas em categorias como *Phrasal Verbs*, *False Friends*, *Everyday Idioms*, *Grammar & Context*, *Workplace & Tech English* e *Vocabulary*.
* **Sistema de pontuação e *streak* (sequência de acertos):** cada acerto vale `100` pontos base e sequências consecutivas (`streak > 1`) concedem bônus extra (`streak * 10`).
* **Feedback imediato e explicativo:** ao responder, o jogador visualiza se acertou ou errou, vê a alternativa correta destacada e lê uma explicação contextualizada em português.
* **Barra de progresso e tela de resultado final:** acompanhamento visual do avanço no desafio e mensagem final personalizada conforme o desempenho.
* **Interface responsiva e temática:** layout escuro (*dark mode*) construído em arquivo único, sem necessidade de dependências externas ou build.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5** — Estrutura semântica das telas inicial, de jogo e de resultados.
* **CSS3** — Estilização, variáveis CSS (`:root`), *flexbox*, transições e design responsivo.
* **JavaScript (Vanilla JS)** — Lógica do quiz, controle de estado (`score`, `streak`, `currentIndex`), manipulação do DOM e renderização dinâmica das perguntas.

---

## 🚀 Como Executar Localmente

Como o projeto está em um único arquivo HTML, não é necessário instalar pacotes ou configurar servidores:

1. Faça o download ou clone este repositório:
   ```bash
   git clone [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)
