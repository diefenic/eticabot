# Rasa EticaBot
<!-- badges -->

## Tutorial para configurar todo o projeto

### Pré requisitos

Para rodar o projeto em sua máquina é necessário ter instalado:
- Docker
- Docker compose

### Primeiros passos

Primeiramente, clone o repositório para sua máquina local usando o comando:

```sh
git clone <Link para o repositório>
```

Para ter seu chatbot Rasa funcionando, certifique-se de estar dentro da pasta do projeto e então execute no terminal o seguinte comando:

```sh
make first-run
```

⚠️ **Atenção**: Caso ocorra algum erro de permissão, executar o comando `sudo make first-run`.


Esse comando irá construir a infraestrutura necessária (subir containers com as dependências, treinar o chatbot, etc) para possibilitar a interação com o chatbot.

Tudo está dockerizado então você não deve ter problemas de instalação do ambiente.

Depois que tudo for instalado, você verá a seguinte mensagem e pode começar a interagir com o bot

```sh
Bot loaded. Type a message and press enter (use '/stop' to exit):
Your input ->
```

Para fechar a interação com o bot é só dar `ctrl+c`.


Para conferir se os contêineres foram construídos corretamente, execute o comando:

```sh
docker ps
```

Para iniciar uma conversa com o chatbot, execute o comando `make run-shell`.


## Introdução

Um projeto feito em Rasa com configurações necessárias para a construção de um projeto grande de chatbot.

Este projeto teve como base o projeto [Tais](http://github.com/lappis-unb/tais) e o projeto [Rasa_Boilerplate](http://github.com/lappis-unb/rasa-boilerplate).

