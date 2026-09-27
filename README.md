# Aula4-Computacao_em_nuvem

Nesta aula, foram apresentados conceitos básicos de **Docker e containers**, utilizando um ambiente Linux Ubuntu. Inicialmente, foi verificada a instalação e a versão do Docker por meio do comando `docker --version`.

Em seguida, foi executado o container `hello-world`, permitindo verificar o funcionamento correto do Docker e compreender o processo de obtenção de imagens a partir do Docker Hub, criação e execução de containers.

Posteriormente, foi criado um container utilizando a imagem **Nginx Alpine**, com o nome `web-aula4` e a porta `8080` do sistema vinculada à porta `80` do container. O funcionamento do servidor foi validado utilizando o comando `curl localhost:8080`.

Também foi realizada uma alteração no conteúdo da página inicial do Nginx diretamente dentro do container, utilizando o comando `docker exec`. Depois, foram consultados os recursos utilizados pelo container com `docker stats --no-stream`.

Por fim, o container foi parado e removido com os comandos `docker stop` e `docker rm`, e o comando `docker ps -a` foi utilizado para verificar os containers existentes no ambiente.

A atividade possibilitou praticar a criação, execução, gerenciamento e remoção de containers, além de compreender a utilização de imagens Docker e a publicação de um serviço web por meio do Nginx.
