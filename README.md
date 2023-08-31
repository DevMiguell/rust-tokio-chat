# Projeto Rust com Tokio - Chat Simples

Este é um projeto Rust que utiliza a biblioteca Tokio para criar um servidor de chat TCP simples. Os usuários podem se conectar ao servidor via Telnet, entrando no mesmo canal para trocar mensagens entre si.

## Pré-requisitos

Certifique-se de ter o Rust instalado em sua máquina. Se você ainda não o possui, você pode instalá-lo por meio do [Rustup](https://rustup.rs/).

## Como Executar

1. Clone este repositório para o seu sistema.
2. Navegue até o diretório do projeto.
3. Rode o projeto com o comando cargo run
4. rode em dois terminais diferentes o comando telnet localhost 8080

Execute o seguinte comando no terminal:

```bash
cargo run
telnet localhost 8080
