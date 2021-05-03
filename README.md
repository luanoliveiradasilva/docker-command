# docker-command

## Infrastructure and Cloud Computing - MBA ES21

### Desafio 
> Subir dois contêineres, nginx e mysql, mapeando a porta 80 do nginx para acesso pelo host e permitir que o contêiner do nginx tenha comunicação de rede no contêiner mysql. 
> Enviar sequência de comandos na linha de comando ou o Docker-compose com os arquivos necessários para que a solução funcione.   

### Tecnologias utilizadas
* MySQL - Banco de dados.
* Nginx - Servidor web
* [Docker](https://www.docker.com/) - Ferramenta para container. 
* [Docker hub](https://hub.docker.com/) - Docker hub que será pego a aplicação.
* [Visual studio code](https://code.visualstudio.com/download) - utilizado para alterar o script e executar os comando no terminal, mais prático =).


### Criar o container
Passo 1. Clocar o projeto com o script do ```docker-compose.yml```<br />
Passo 2. Executar o comando ```docker-compose up -d```<br />
    Obs:Esse comando serve para executar o docker compose, permitindo baixar as imagens no docker e subir os container conforme definido do script.<br />
Passo 3. Após subir a aplicação, certifique-se que os container estejam iniciado, senão, inicie manualmente no próprio docker ou executando o comando ```docker-compose up nomedocontainer```.<br />

Passo 4. Para acessar o mysql do que está no docker tem que executar o comado ```docker exec -it nomedocontainerdobd bash```.<br />
