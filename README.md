# Challenge DevOps Alura

Primeira semana do desafio DevOps da Alura! #alurachallengedevops1.

A imagem Docker criada se chama gapaulo/chall-1 na versão 1.0 e já está no Docker Hub.

Para rodar:

    sudo docker-compose up -d

Para criar o super usuário:
  
    sudo docker exec -it aluraflix python manage.py createsuperuser
    

Obs: Infelizmente não consegui separar o banco de dados para rodar em seu próprio container. Fora isso, a aplicação está rodando normalmente, acredito eu haha.
