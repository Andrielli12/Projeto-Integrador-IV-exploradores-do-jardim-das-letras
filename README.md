# 🌿 Exploradores do Jardim das Letras

**Projeto Integrado IV – UNIVESP - 2026** *Licenciatura em Pedagogia*

---

## 📖 Sobre o Jogo

O **Exploradores do Jardim das Letras** é um jogo educativo desenvolvido para crianças em fase de alfabetização (aproximadamente 7 anos). Ele combina o aprendizado de palavras com a conscientização ambiental.

No jogo, a criança encontra um jardim encantado com **9 palavras** relacionadas à natureza. Cada palavra tem uma dica e a criança deve digitar as letras corretas nos quadradinhos. Ao acertar, o card correspondente ganha um ✅. Quando todas as palavras são descobertas, uma medalha especial aparece como prêmio.

---

## 🎮 Como Jogar

### 1. Tela Inicial (Jardim Encantado)
- Cenário animado com árvores, flores, nuvens, pássaros e borboletas.
- **JOGAR** → inicia o jogo e vai para a tela dos cards.
- **LIMPAR** → apaga todo o progresso salvo e recomeça do zero.

### 2. Tela dos Cards
- 9 cards numerados (1 a 9), cada um com uma cor de borda diferente.
- Cards já resolvidos exibem um ✅.
- Clique em um card para abrir a palavra correspondente.
- Quando todas as palavras forem completadas, aparece um botão de prêmio:  
  **🎉 PARABÉNS! VOCÊ COMPLETOU TODAS AS PALAVRAS! CLIQUE PARA RECEBER SEU PRÊMIO.**

### 3. Tela da Palavra
- **Dica**: texto com pistas sobre a palavra.
- **Quadradinhos**: um para cada letra da palavra.
- **Digitação**:
  - Ao digitar uma letra, o cursor avança para o próximo quadrado.
  - Tecla **Backspace** apaga a letra e, se o campo estiver vazio, volta ao quadrado anterior.
- **Botões**:
  - **REVELAR IMAGEM** → mostra um emoji que ajuda a identificar a palavra.
  - **VERIFICAR** → confere se a palavra está correta.
  - **TENTAR NOVAMENTE** → limpa todos os quadrados.
  - **VOLTAR AS CARTAS** → retorna à tela dos cards.
- **Feedback**:
  - **Acerto**: quadrados ficam verdes e mensagem de parabéns.
  - **Erro**: quadrados ficam vermelhos e mensagem de tentar novamente.

### 4. Tela do Prêmio
- Aparece ao clicar no botão de prêmio após completar todas as palavras.
- Imagem de uma medalha (pode ser substituída).
- Mensagem de congratulação.
- Botão **VOLTAR AO JARDIM** para recomeçar.
- Fundo animado com pássaros e borboletas voando em direções diferentes.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** – Estrutura das telas.
- **CSS3** – Estilos, animações e responsividade.
- **JavaScript (ES6)** – Lógica do jogo, validações e salvamento.
- **Google Fonts** – Fonte amigável para crianças.
- **LocalStorage** – Salva o progresso no navegador.

---

## ✅ Status do Projeto

**Versão final** – todas as funcionalidades estão implementadas e testadas.

- [x] Tela inicial animada
- [x] 9 cards numerados com cores
- [x] Tela da palavra com dica e suporte a Backspace
- [x] Botão "revelar imagem"
- [x] Validação e feedback visual
- [x] Salvamento automático (LocalStorage)
- [x] Botão de prêmio na tela de cards
- [x] Tela de prêmio com medalha e animações
- [x] Design responsivo (celular, tablet, PC)
- [x] Textos em maiúsculas para facilitar a leitura

---

## 📂 Estrutura do Projeto

```text
/
├── index.html                 # Arquivo principal (HTML + CSS + JS)
├── medalha.jpg                # Imagem da medalha (pode ser trocada)
└── fundo da tela inicial.jpg  # Imagem de fundo da tela inicial
```


**Observações sobre imagens:** - O jogo utiliza as imagens `medalha.jpg` e `fundo da tela inicial.jpg`.  
- Você pode substituí-las por outros arquivos locais ou até mesmo usar links externos, ajustando os caminhos no código.

---

## 🚀 Como Executar

1. **Baixe os arquivos** do repositório para uma pasta no seu computador.
2. Abra o arquivo `index.html` em qualquer navegador moderno (Chrome, Edge, Firefox, Safari).
3. Ou acesse diretamente a versão online:  
   🔗 [https://andrielli12.github.io/Projeto-Integrador-IV-exploradores-do-jardim-das-letras/](https://andrielli12.github.io/Projeto-Integrador-IV-exploradores-do-jardim-das-letras/)

---

## 👩‍🏫 Uso em Sala de Aula

- **Alfabetização** – as crianças leem as dicas e escrevem as palavras.
- **Educação ambiental** – palavras como ar, água, árvore e reciclar geram conversas sobre o meio ambiente.
- **Trabalho em duplas** – um lê a dica, o outro digita.
- **Adaptação** – é possível trocar as palavras editando o array `palavras` no JavaScript.

---

## 📝 Licença

Este projeto é um **Recurso Educacional Aberto (REA)**. Você pode usar, copiar, modificar e compartilhar livremente para fins educacionais, desde que cite a autoria original (UNIVESP – Projeto Integrado IV).

---

**Desenvolvido por:** Alexandra Cristina Alves dos Santos, Ana Paula Miranda Moreira de Lima, Andrielli Aengie Galvão de França Libanoro, Erica Andreza Coelho Bowersox, Gisele Nascimento Antonio, Lilian Maria de Souza, Samara Aparecida Jordão da Silva e Thaina da Silva Campos Correa  
**Orientação:** Natália Santos  
**Ano:** 2026
