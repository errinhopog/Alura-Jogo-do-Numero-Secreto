# Jogo de Adivinhar Números

Um simples jogo de adivinhação de números implementado em JavaScript.

## Descrição

Este é um jogo onde o jogador tenta adivinhar um número secreto gerado aleatoriamente pelo computador. O jogador recebe dicas se o número secreto é maior ou menor do que o número chutado até adivinhar corretamente. O objetivo é adivinhar o número com o menor número de tentativas possível.

## Funcionalidades

- Geração de um número secreto aleatório.
- Interface simples para inserir o chute.
- Feedback em tempo real se o chute é maior ou menor que o número secreto.
- Contagem de tentativas.
- Reinício do jogo após acerto.

## Como Jogar

1. Abra o jogo em seu navegador.
2. Leia a mensagem inicial e escolha um número entre 1 e 50.
3. Digite seu chute no campo de entrada e clique no botão para verificar.
4. Continue chutando até acertar o número secreto.
5. Após acertar, você pode reiniciar o jogo clicando no botão de reiniciar.

## Instalação

1. Clone este repositório em sua máquina local.
    ```sh
    git clone https://github.com/seu-usuario/jogo-de-adivinhar-numeros.git
    ```
2. Navegue até o diretório do projeto.
    ```sh
    cd jogo-de-adivinhar-numeros
    ```
3. Abra o arquivo `index.html` em seu navegador.

## Código

### Funções Principais

#### `exibirTextoNaTela(tag, texto)`

Exibe texto no elemento especificado e usa a função `responsiveVoice.speak` para falar o texto.

#### `exibirMensagemInicial()`

Exibe a mensagem inicial do jogo.

#### `verificarChute()`

Verifica se o chute do jogador está correto e exibe uma mensagem apropriada. Se o chute estiver incorreto, fornece uma dica.

#### `gerarNumeroAleatorio()`

Gera um número aleatório entre 1 e `numeroLimite`, garantindo que o número não tenha sido gerado anteriormente na mesma sessão.

#### `limparCampo()`

Limpa o campo de entrada do chute.

#### `reiniciarJogo()`

Reinicia o jogo gerando um novo número secreto e resetando o contador de tentativas.

## Tecnologias Utilizadas

- HTML
- CSS
- JavaScript

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
