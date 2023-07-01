# VideoLog e Keylogger - Módulos do Kernel do Linux

Este repositório contém dois módulos do kernel do Linux: VideoLog e Keylogger. Ambos os módulos utilizam comunicação por socket entre um cliente no Linux e um servidor em Python.


## Integrantes do grupo
Leonardo Hannas de Carvalho Santos 11800480

Carlos Henrique Hannas de Carvalho 11965988

Henrique Carobolante Parro 11917987


## Pré-requisitos

- Linux (kernel compatível com a compilação de módulos)
- Python 3.x

## Configuração

1. Clone este repositório em sua máquina local:

```
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

2. Compile o cliente usando o comando `make`. Se você precisar apagar o último build, execute `make clean` antes de compilar novamente. Isso se aplica tanto ao cliente do VideoLog quanto ao cliente do Keylogger.

3. Execute o servidor usando o script Python fornecido.

4. Certifique-se de usar o mesmo endereço IP e porta nos campos de rede/socket dos códigos do cliente e servidor.

## Utilização

1. Inicie o servidor executando o script Python do servidor:

```
python server.py
```


2. Compile e execute o cliente do VideoLog ou do Keylogger no Linux:

```
make
or
make clean
```

3. O cliente se conectará ao servidor usando o endereço IP e porta configurados anteriormente. Certifique-se de ter uma conexão de rede ativa.

## Contribuições

Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões de melhoria, sinta-se à vontade para abrir uma nova issue ou enviar um pull request.



## Licença

Este projeto é licenciado sob a [Licença MIT](LICENSE).

