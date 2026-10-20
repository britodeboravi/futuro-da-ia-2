# 🤖 Jornada IA: Escolha os Caminhos da Tecnologia

Aplicação interativa desenvolvida no curso de programação web (**FIAP / Alura**), projetada para provocar reflexões sobre como a Inteligência Artificial molda o nosso cotidiano e o nosso futuro.

---

## 🎯 Visão Geral

O **Jornada IA** é um jogo de escolhas em formato de narrativa dinâmica. Cada decisão tomada pelo jogador altera a sequência dos acontecimentos e constrói um desfecho exclusivo para a sua experiência.

### ⚡ Destaques do Projeto:
- **Boas-vindas Interativas:** Tela inicial com introdução ao tema e botão de partida para engajar o usuário antes do desafio.
- **Protagonista Dinâmico:** Sorteio automático de nomes que personaliza os enunciados e a mensagem de encerramento.
- **Navegação Ramificada:** Estrutura baseada em fluxograma em que cada resposta determina a etapa seguinte.
- **Conclusão Exclusiva:** Combinação de frases sorteadas a partir das decisões do usuário para criar uma síntese final única.
- **Reinício Rápido:** Botão "Jogar Novamente" que restaura a aplicação instantaneamente sem precisar recarregar a página.

---

## 💻 Tecnologias Aplicadas

- **HTML5:** Marcação estruturada e semântica.
- **CSS3:** Estilização moderna com variáveis (`:root`), Flexbox, tipografia do Google Fonts (`Chakra Petch` e `Inter`) e controle de telas.
- **JavaScript ES6+:** Arquitetura em módulos (`import`/`export`), manipulação de elementos do DOM, expressões regulares e controle de fluxo.

---

## 📁 Organização dos Arquivos

```text
MISSÃO-IA/
├── index.html        # Estrutura principal da interface
├── style.css         # Estilos visuais e regras de exibição
└── js/
    ├── aleatorio.js  # Módulo responsável pelos sorteios aleatórios
    ├── perguntas.js  # Módulo com o banco de perguntas e rotas do jogo
    └── script.js     # Módulo central de lógica e controle do sistema