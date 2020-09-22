**IMPORTANTE: os arquivos de configuração de containers, são apenas exemplos. É sempre importante lembrar que nem todos se aplicam para casos de ambiente de produção e sim para subir localmente para desenvolvimento, até porque quando se utiliza algo em produção, por questões de segurança e claro visando o uso em uma infra automatizada e funcional, quando é utilizada uma imagem de terceiros, é necessário informar a versão para evitar problemas desncessários e inesperados.**

**Outra boa prática é definir limites de cpu e memória.**

Para utilizar qualquer arquivo compose, existe n parâmetros que podem ser utilizados.
Costumo usar:

```
docker-compose up 
```

Ou 

```
docker-compose up -d
```

Indico usar a segunda opção, pois poderá fechar a janela onde foi executado o comando sem problemas. Teste e entenda.
