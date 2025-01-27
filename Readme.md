# Discord ModMail Bot - Python

Este é um **bot ModMail** para Discord desenvolvido em Python. O bot permite que os membros do servidor entrem em contato com os moderadores de maneira privada e segura, sem que mensagens públicas sejam necessárias. Ele funciona como um sistema de correio, permitindo que os moderadores respondam aos usuários de forma organizada e eficiente.

## Funcionalidades

- **Criação de tickets privados**: Usuários podem abrir tickets privados para comunicar-se diretamente com os moderadores.
- **Respostas rápidas**: Moderadores podem responder a tickets através de mensagens privadas.
- **Gerenciamento de tickets**: Os moderadores podem fechar ou arquivar tickets após a resolução.
- **Notificações**: O bot notifica tanto os moderadores quanto os usuários quando um novo ticket é criado ou um ticket é fechado.
- **Armazenamento seguro**: As conversas são armazenadas de forma segura e privada.

## Tecnologias Usadas

- **Python** (3.x)
- **discord.py**: A biblioteca principal para interagir com a API do Discord.
- **SQLite** (ou outro banco de dados): Para armazenar informações dos tickets.
- **dotenv**: Para carregar variáveis de ambiente de forma segura.

## Instalação

### Requisitos

- **Python 3.8+** (recomendado)
- **Pip** (gerenciador de pacotes do Python)
- **Conta de Bot do Discord**: Você precisa de um bot no Discord e o **token** para configurar a autenticação.

### Passo a Passo

1. **Clone o repositório:**

   Abra seu terminal e execute o seguinte comando para clonar este repositório:

   ```bash
   git clone https://github.com/seu-usuario/discord-modmail-bot.git
   cd discord-modmail-bot
