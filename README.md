# Docker Todo List

O projeto Docker Todo List visava testar os conhecimentos básicos de docker aprendidos durante a primeira seção do módulo de back-end do curso da Trybe.

Os requisitos envolviam a conteinerização de aplicações, criação de imagens customizadas com Dockerfile, gerenciamento e orquestração de múltiplos containers com docker-compose. Tudo tanto através da linha de comanto quanto dos arquivos Dockerfile e docker-compose.yml.

## A estrutura do projeto

O projeto possuí diversos requisitos, que são resolvidos com um comando docker ou docker-compose e alguns, adicionalmente, com a definição de um aquivo Dockerfile ou .yaml.
- Cada comando que resolve o requisito foi colocado em um arquivo `command<número do requisito>.dc` no diretório `docker/docker-commands`.
- Cada Dockerfile está localizado no diretório de cada aplicação dentro de `docker/todo-app`.
- E o arquivo .yml está na raiz da pasta `docker`.

## Tecnologias utilizadas
- Docker
- Docker Compose
