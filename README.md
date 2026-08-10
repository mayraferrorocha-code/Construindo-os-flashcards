# 🧠 Flashcards de Estudo Interativos

Projeto web simples, moderno e responsivo desenvolvido com **HTML5** e **CSS3** para auxiliar na fixação de conteúdos de estudo utilizando cartões com animação 3D de giro (*flip*).

---

## 🚀 Funcionalidades

- **Animação 3D em CSS:** Cartões que giram ao passar o mouse ou tocar na tela.
- **Design Responsivo:** Funciona perfeitamente em computadores, tablets e celulares.
- **Organização por Matérias:** Tags coloridas para identificar diferentes disciplinas (Biologia, História, Química, etc.).
- **Navegação Acessível:** Funciona também com foco de teclado (`tabindex`).

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica do conteúdo.
- **CSS3:** Estilização, layout em Grid e efeitos de transição/transformação 3D (`perspective`, `transform`, `backface-visibility`).

---

## 📂 Como Executar o Projeto

1. Baixe ou clone os arquivos do projeto para o seu computador.
2. Certifique-se de que os arquivos `index.html` e `style.css` estejam na mesma pasta.
3. Dê um duplo clique no arquivo **`index.html`** para abri-lo em qualquer navegador web (Chrome, Edge, Firefox, etc.).

---

## ✏️ Como Adicionar Novos Flashcards

Para criar uma nova carta, abra o arquivo `index.html` e adicione o bloco abaixo dentro da `<main class="container">`:

```html
<div class="flashcard" tabindex="0">
  <div class="flashcard-inner">
    <div class="flashcard-front">
      <span class="tag biologia">Sua Matéria</span>
      <h2>Sua Pergunta Aqui?</h2>
    </div>
    <div class="flashcard-back">
      <p>Sua Resposta Aqui.</p>
    </div>
  </div>
</div>
