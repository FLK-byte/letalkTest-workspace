### Como rodar o projeto
 *Inicialmente clone o projeto ```git clone --recurse-submodules https://github.com/FLK-byte/letalkTest-workspace.git```*

## <Span id="withDocker">Com Docker</Span>
 - Tenha o [docker](https://www.docker.com/) instalado no seu ambiente
 - Rode ```docker compose up``` no terminal dentro da pasta do workspace

## <Span id="withoutDocker">Sem Docker</Span>
 - As instruções para rodar sem docker está dentro de cada readme de cada repositorio

 ## Entregáveis:
 #### [Link para aplicação](https://letalktest-front.onrender.com): https://letalktest-front.onrender.com (obs: pode demorar de 1 a 2min para o primeiro carregamento pois a maquina que hospeda o site fica desligada ate haver uma requisição)

 #### [Endpoint para Acessar os Empréstimos Efetivados](https://letalktest-back.onrender.com/loans): https://letalktest-back.onrender.com/loans (obs: pode demorar de 1 a 2min para o primeiro carregamento pois a maquina que hospeda a pi fica desligada ate haver uma requisição)

 #### Tempo Gasto na Execução do Teste: 9h 27min
 ##### Como o tempo foi gasto:
```
 - 1hr de planejamento
 - 1h 27min de desenvolvimento e configuracao do back
 - 3h de desenvolvimento e configuracao do front
 - 3h de tentivas de deploy do workspace (com docker) na aws usando o plano gratuito,
 mesmo nao conseguindo dar deploy com o docker tentei fazer o deploy separado no ec2
 consegui fazer mas na hora de configurar pro ssh remoto rodar o servico para o servidor nao fechar
 a maquina crashava por conta de recursos entao optei por outra ferramenta para o deploy
 - 1h de testes apos finalizar o deploy, isso inclui clonagem do projeto e o fluxo geral
```
