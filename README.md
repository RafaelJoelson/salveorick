# Jogo da Forca - Salve o Professor!

Um jogo da forca temático e interativo, onde o objetivo é salvar o Professor Ricardo. Desafie seus amigos ou sua audiência com palavras secretas e divirta-se com este clássico jogo em uma roupagem moderna e pixelada!

## 🚀 Funcionalidades

- **Palavra Secreta**: Insira uma palavra personalizada para desafiar os jogadores.
- **Ciframento**: A palavra secreta é cifrada em Base64, garantindo que ela não fique visível na URL.
- **Cronômetro**: Tempo limitado para salvar o professor.
- **Áudio e Animações**: Sons de fundo, efeitos sonoros e animações dinâmicas tornam o jogo mais imersivo.
- **Destaque para Letras Especiais**: Suporte a acentuações e equivalência de letras (ex.: "A" e "Á" são tratadas como iguais).

## 📂 Estrutura do Projeto

```plaintext
.
├── index.html          # Página inicial para inserir a palavra secreta
├── inicio.html         # Página intermediária com botão "Começar Jogo"
├── jogo.html           # Página do jogo
├── vitoria.html        # Tela de vitória
├── img/                # Imagens da forca e do fundo
├── audio/              # Arquivos de áudio do jogo
├── styles/             # (Opcional) Diretório para folhas de estilo adicionais
└── README.md           # Documentação do projeto

Aqui está um exemplo simples de um `README.md` pronto para o seu projeto:

```markdown
# Jogo da Forca - Salve o Professor! 🪓

Este é um projeto de um jogo da forca divertido e estilizado, onde o objetivo é salvar o professor Ricardo! Inspirado no clássico jogo da forca, ele conta com uma interface pixelada retrô e animações temáticas.

## 🛠️ Funcionalidades

- **Inserção de palavra secreta:** A palavra é cifrada em Base64 para garantir que não fique visível na URL.
- **Animações temáticas:** Transições dinâmicas e divertidas a cada erro.
- **Timer de desafio:** O jogador tem 3 minutos para adivinhar a palavra secreta.
- **Suporte a caracteres especiais:** Aceita letras com acentos e cedilha (ex.: "Á", "Ç", etc.).
- **Áudios personalizados:** Som de acerto, erro e música de fundo.

## 🚀 Tecnologias Utilizadas

- **HTML5:** Estrutura das páginas.
- **CSS3:** Estilização com design pixelado e retrô.
- **JavaScript:** Lógica do jogo, manipulação de elementos, e cifragem da palavra.

## 📂 Estrutura do Projeto

```plaintext
.
├── index.html         # Página inicial para inserir a palavra secreta
├── inicio.html        # Página intermediária com o botão para começar o jogo
├── jogo.html          # Tela principal do jogo
├── vitoria.html       # Tela de vitória
├── css/
│   └── style.css      # (Opcional) Arquivo centralizado de estilos
├── img/               # Pasta com imagens do jogo
│   ├── ricardo1.gif
│   ├── ricardo2.gif
│   └── ...
├── audio/             # Pasta com os arquivos de som
│   ├── backgroundmusic.mp3
│   ├── acerto.mp3
│   └── ...
└── README.md          # Documentação do projeto
```

## 🎮 Como Jogar?

1. **Defina a palavra secreta:** Na página inicial (`index.html`), insira a palavra secreta e clique para prosseguir.
2. **Comece o jogo:** Na página intermediária (`inicio.html`), clique em "Começar Jogo".
3. **Adivinhe as letras:** Use as letras disponíveis para tentar adivinhar a palavra.
4. **Salve o professor:** Adivinhe antes de cometer 6 erros ou perder o tempo disponível.

## 🖼️ Prévia

https://salveorick.vercel.app/

## 🧩 Próximas Melhorias

- Implementar um sistema de pontuação.
- Adicionar mais palavras predefinidas como opção para o jogador.
- Melhorar a responsividade para dispositivos móveis.

## 📝 Licença

Este projeto foi desenvolvido para fins educacionais e é livre para uso. 🚀
```