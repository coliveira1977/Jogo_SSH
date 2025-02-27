Jogo do Número Secreto

Este é um jogo simples de adivinhação onde o jogador deve acertar um número secreto gerado aleatoriamente dentro de um limite definido.

Funcionalidades

O jogador chuta um número dentro do intervalo especificado.

O jogo informa se o número secreto é maior ou menor que o chute.

Quando o jogador acerta, o jogo exibe a quantidade de tentativas utilizadas.

O jogador pode reiniciar o jogo para tentar novamente.

Feedback de voz com a biblioteca responsiveVoice.

Como Executar

Clone o repositório:

git clone https://github.com/coliveira1977/Jogo_SSH.git

Abra o arquivo index.html em um navegador.

Digite um número e tente adivinhar!

Tecnologias Utilizadas

JavaScript: Lógica do jogo e manipulação do DOM.

HTML: Estrutura da interface.

CSS: Estilização básica.

responsiveVoice: Biblioteca de síntese de voz para feedback auditivo.

Estrutura do Código

exibirTextoNaTela(tag, texto): Exibe mensagens na tela e faz leitura em voz alta.

verificarChute(): Verifica se o chute do jogador está correto.

gerarNumeroAleatorio(): Gera um número aleatório sem repetição até atingir o limite.

limparCampo(): Limpa o campo de entrada do usuário.

reiniciarJogo(): Reinicia o jogo com um novo número secreto.

Melhorias Futuras

Adicionar uma interface mais interativa e responsiva.

Permitir que o jogador escolha o intervalo de números.

Implementar um histórico de tentativas.

Contribuição

Sinta-se à vontade para contribuir! Faça um fork do repositório, implemente melhorias e abra um pull request.

Feito com ❤️ para aprendizado e diversão!
