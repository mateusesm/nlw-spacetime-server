### NLW Spacetime - Server
API Rest desenvolvida durante NLW (Next Level Week) da Rocketseat que tem como objetivo ser o back-end de aplicação Web e Mobile, também desenvolvidas durante a semana. 

A aplicação consiste em um sistema que funciona como Cápsula do Tempo para guardar memórias de usuários (Texto, imagens, etc.) O sistema dispõe de autenticação com JWT (Json Web Token) logando o usuário com sua conta do GitHub e CRUD de memórias em banco de dados SQLite utilizando o Prisma como ORM.

O back-end foi desenvolvido utilizando o framework Fastify junto ao Node.js e tecnologias como; Typescript e Zod.

Lembrando que para autenticação funcionar, é necessário criar um arquivo .env na raiz do projeto e nele registrar duas variáveis de ambiente; uma para o GITHUB_CLIENT_ID, e uma para GITHUB_CLIENT_SECRET. Lembrando que, em produção, será necessário criar duas de cada, para o ambiente Web e para o Mobile. Ambas, ID e SECRET podem ser criadas e encontradas na própria conta do GitHub em Settings >>> Developer settings.

### Para executar a API basta seguir as instruções abaixo

Antes de tudo, verifique se há alguma versão do Node instalada rodando o comando:

```bash
node --version
```
O comando deverá retornar a versão do Node instalada. Se não houver, baixe-a

Caso o Node esteja instalado, entre na pasta do projeto e rode o seguinte comando para instalar todas as dependências:

```bash
npm install
```
Em seguida, rode o seguinte comando para rodar o projeto:

```bash
npm run dev
```
Uma mensagem será exibida no terminal informando a URL do servidor e a porta na qual está rodando.



