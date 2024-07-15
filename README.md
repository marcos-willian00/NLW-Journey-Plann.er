## Plann.er

Backend do **Plann.er**

O Plann.er é um aplicação voltada ao gerenciamento de viagens.

## Linguagem e ferramentas utilizadas:

- TypeScript
  
- NodeJs
- Fastify
- Prisma
- Zod
- Nodemailer

## Execução do Plann.er

### 1. Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

- Clone o repositório:
  ```
  https://github.com/marcos-willian00/NLW-Journey-Plann.er.git
  ```

- Você instalou a versão mais recente do NodeJS?
  - Se sim, pode prosseguir
  - Se não, visite o site do [NodeJS](https://nodejs.org/en) e faça a instalação!

- Instalação das dependências do projeto
  - Antes de realizar os proximos comandos instale as dependências do projeto, isso vai garantir que ele funcione!
  - Este comando vai instalar todas as dependências de uma só vez!

  ```
  npm install
  ```

### 3. Executar em modo de desenvolvimento

```
npm run dev
```

### 4. Executar em modo de produção

- Para converter a aplicação TypeScript e gerar a aplicação JavaScript:
  ```
  npm run build
  ```
- Para rodar a aplicação JavaScript:
  ```
  npm start
  ```

### 5. Executar migrations

```
npx prisma migrate dev
```

### 6. Executar o Prisma Studio

```
npx prisma studio
```
