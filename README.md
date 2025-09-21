# 📘 README - Jogo da Memória

## 🧩 Sobre o jogo

Este é um jogo da memória desenvolvido em **HTML, CSS e JavaScript puro**.
O objetivo é encontrar todos os pares de emojis idênticos no tabuleiro.
Quando todos os pares são encontrados, o jogador recebe uma mensagem de parabéns 🎉.

---

## 🚀 Tecnologias

* **HTML5** → Estrutura da página
* **CSS3** → Estilização e efeitos visuais (cartas virando, gradientes, responsividade)
* **JavaScript** → Lógica do jogo (embaralhamento, clique, verificação de pares)

---

## 📂 Estrutura do projeto

```
📁 memory-game
│── index.html        # Estrutura principal da página
│── src
│   ├── styles
│   │    └── main.css # Estilo visual do jogo
│   └── scripts
│        └── engine.js # Lógica principal do jogo
```

---

## 🎮 Como jogar

1. Abra o arquivo **index.html** em qualquer navegador moderno.
2. Clique em duas cartas para revelá-las.
3. Se forem iguais, elas permanecem abertas ✅.
4. Se forem diferentes, voltam a se fechar ❌.
5. Continue até encontrar todos os pares.
6. Ao final, uma janela de **parabéns** aparece 🏆.

---

## ⚙️ Lógica do jogo

* As cartas são representadas por **emojis**.
* Os emojis são **duplicados** (para formar pares) e embaralhados.
* Cada clique chama a função `handleClick()`.

  * Se duas cartas forem abertas, a função `checkMatch()` verifica se formam par.
  * Se sim → recebem a classe `boxMatch`.
  * Se não → voltam a ser fechadas após 0,5s.
* Quando todas as cartas tiverem a classe `boxMatch`, aparece o **popup de vitória**.

---

## 🛠️ Como executar localmente

1. Baixe ou clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/memory-game.git
   ```
2. Abra o arquivo `index.html` no navegador.
   (Não é necessário servidor, roda direto).

---

## ✨ Melhorias futuras

* ✅ Adicionar **níveis de dificuldade** (mais cartas).
* ✅ Cronômetro para medir tempo de conclusão.
* ✅ Sistema de pontuação.
* ✅ Ranking local com **localStorage**.
* ✅ Sons de acerto/erro.

---

## 📜 Licença

Este projeto é livre para estudo e pode ser utilizado para fins educacionais ou pessoais.
