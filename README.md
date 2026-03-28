🌿 Exploradores do Jardim das Letras
Projeto Integrado IV – UNIVESP - 2026
Licenciatura em Pedagogia

📖 Sobre o Projeto
O Exploradores do Jardim das Letras é um jogo educativo desenvolvido como parte do Projeto Integrado IV da UNIVESP. O objetivo é auxiliar crianças em fase de alfabetização (aproximadamente 7 anos) a reconhecer palavras e associá-las a elementos da natureza, estimulando a leitura, a escrita e a consciência ambiental.

O jogo apresenta um jardim encantado com nove palavras relacionadas ao meio ambiente. A criança deve ler a dica de cada palavra e preencher os quadradinhos com as letras corretas. Ao acertar, ganha um ✅ no card e, ao completar todas, recebe uma medalha especial.

🎮 Funcionalidades
Tela inicial (Jardim Encantado)
Fundo com imagem de jardim e elementos animados (árvores, flores, nuvens, pássaros, borboletas)

Mensagem de boas‑vindas: BEM‑VINDOS AO JOGO JARDIM DAS LETRAS

Botões:

JOGAR → acessa a tela de cards

LIMPAR → apaga todo o progresso salvo e reinicia a partida

Rodapé com créditos institucionais (REA, UNIVESP, 2026)

Tela de cards
Grade com 9 cards numerados (1 a 9)

Cada card tem uma cor de borda específica (ex.: AR = azul claro, SOL = amarelo, ÁGUA = azul, FLOR = rosa etc.)

Cards já resolvidos mostram um ✅ no canto superior direito

Ao clicar em um card, a tela da palavra é aberta

Quando todas as palavras forem completadas, um botão de prêmio aparece abaixo da grade:
🎉 PARABÉNS! VOCÊ COMPLETOU TODAS AS PALAVRAS! CLIQUE PARA RECEBER SEU PRÊMIO. 🎉

Tela da palavra
Cenário: inicialmente um placeholder ❓ IMAGEM SECRETA.
A criança pode clicar no botão REVELAR IMAGEM a qualquer momento para ver um emoji relacionado à palavra (auxílio visual).

Texto com a dica da palavra, em letras maiúsculas

Quadrados para digitar cada letra (a quantidade varia conforme a palavra)

Digitação:

Ao digitar uma letra, o cursor avança automaticamente para o próximo quadrado.

Tecla Backspace apaga a letra atual e, se o campo estiver vazio, retorna ao quadrado anterior.

Botões:

REVELAR IMAGEM – mostra o emoji correspondente

VERIFICAR – confere se a palavra digitada está correta

TENTAR NOVAMENTE – limpa todos os campos de letra

VOLTAR AS CARTAS – retorna à tela dos cards

Feedback visual:

Acerto: quadrados ficam verdes, mensagem de parabéns aparece, o card correspondente é marcado com ✅

Erro: quadrados ficam vermelhos e a mensagem “TENTE NOVAMENTE” é exibida; após 1 segundo as bordas voltam ao normal

Progresso salvo automaticamente no navegador (LocalStorage)

Tela do prêmio
Exibida após clicar no botão de prêmio da tela de cards

Contém uma imagem de medalha (medalha.jpg – pode ser substituída por outra)

Mensagem de congratulação:

PARABÉNS! VOCÊ ENCONTROU TODAS AS PALAVRAS DO NOSSO JARDIM E APRENDEU MAIS SOBRE O MEIO AMBIENTE. AGORA VOCÊ É UM GRANDE EXPLORADOR DO JARDIM DAS LETRAS!

Botão VOLTAR AO JARDIM que leva de volta à tela inicial

Fundo com animações:

Pássaros voando da direita para a esquerda

Borboletas voando da esquerda para a direita (efeitos suaves e alternados)

🛠️ Tecnologias Utilizadas
HTML5 – Estrutura das telas e elementos

CSS3 – Estilização, animações (balançar, voar, mover nuvens) e design responsivo (adaptado para celulares)

JavaScript (ES6) – Lógica do jogo, controle de estado, validação de palavras, armazenamento local e manipulação do DOM

Google Fonts – Fonte infantil Comic Neue (torna a leitura mais agradável)

LocalStorage – Persistência do progresso do jogador entre sessões

🧪 Status do Projeto
✅ Versão final – todas as funcionalidades planejadas foram implementadas e testadas:

Tela inicial com animações e botões

9 cards numerados com cores personalizadas

Tela de palavra com dica, quadrados de letra e suporte a Backspace

Botão “revelar imagem” para auxílio visual

Validação de palavra com feedback visual

Salvamento automático do progresso (LocalStorage)

Botão de prêmio na tela de cards ao completar todas as palavras

Tela de prêmio com medalha, mensagem e animações de pássaros/borboletas

Design responsivo (funciona em computadores, tablets e smartphones)

Textos em maiúsculas para facilitar a leitura de crianças em alfabetização

📂 Estrutura do Projeto
text
/
├── index.html          # Página principal com todo o código (HTML, CSS, JS)
├── medalha.jpg         # Imagem da medalha (deve estar na mesma pasta)
└── fundo da tela inicial.jpg  # Imagem de fundo da primeira tela (opcional)
Nota: O jogo utiliza imagens de fundo e medalha que podem ser substituídas por arquivos locais ou links externos.

🚀 Como Executar

link: https://andrielli12.github.io/Projeto-Integrador-IV-exploradores-do-jardim-das-letras/

Divirta-se!

👩‍🏫 Possibilidades de Uso em Sala de Aula
Atividade de alfabetização – as crianças leem as dicas e escrevem as palavras.

Educação ambiental – as palavras escolhidas (ar, água, árvore, reciclar etc.) abrem espaço para conversas sobre preservação.

Trabalho em duplas – um aluno lê a dica e o outro digita as letras.

Adaptação – o professor pode modificar a lista de palavras e as dicas editando o array palavras no JavaScript, permitindo novos temas (animais, frutas, etc.).

📝 Licença
Este projeto é um Recurso Educacional Aberto (REA) e pode ser livremente utilizado, copiado, modificado e compartilhado para fins educacionais, desde que citada a autoria original (UNIVESP – Projeto Integrado IV).

Desenvolvido por: [Seu Nome ou Grupo]
Orientação: [Nome do orientador, se houver]
Ano: 2026
