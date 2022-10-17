Docker-compose com a infraestrutura conteinerizada do Wordpress

```
Instruções:

1. Para utilizar localmente, adicionar o domínio no arquivo '/etc/hosts':

127.0.0.1 yourdomain.com

2. Editar a linha 5 arquivo '.docker/nginx/conf.d/wordpress.conf' com o nome do domínio que será utilizado:

server_name yourdomain.com;

3. Renomear o arquivo 'env-example' para '.env' e editar as variáveis:

$ mv env-example .env

4. Iniciar o projeto:

$ docker compose up

```