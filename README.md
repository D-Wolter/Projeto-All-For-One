# <img src="https://user-images.githubusercontent.com/106452876/214559667-c9869f59-7e5b-42aa-8f77-06e45687edc1.png" width="30"/> Projeto All For One
Para praticarmos as queries de SQL que aprendemos nos foi proposto 27 desafios.

* Os oito primeiros desafios foram para o SELECT e criar dados;
* Os desafios de 9 a 19 foram para filtrar dados;
* E os desafios de 20 a 27 foram para manipular tabelas.

![Screenshot from 2023-01-25 10-13-57](https://user-images.githubusercontent.com/106452876/214572797-d8e36a93-7581-496a-9308-94f6fad708e7.png)

## Tecnologias usadas
Back-end:
> Desenvolvido usando: Docker, docker-compose, SQL, MySQL Workbench

## Instalando Dependências
### Com Docker
> Backend

* Primeiro instale os containers: 
```bash
docker-compose up -d
``` 

* Em seguida abra o terminal interativo do container: 
```bash
docker exec -it all_for_one bash
``` 

* Instale as dependências dentro do container: 
```bash
npm install
``` 
> Testes

* Dentro do terminal do container:
```bash
npm test
``` 

:warning: Atenção: O git dentro do container não vem configurado com suas credenciais;

### Sem Docker

* Instale as dependências [Caso existam]
```bash
npm install
``` 

:information_source: Para rodar o projeto desta forma, obrigatoriamente você deve ter o ```node``` instalado em seu computador e o avaliador espera que seja a versão 16.
