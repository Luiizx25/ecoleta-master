# Ecoleta

Aplicação criada com objetivo de cadastrar e localizar pontos de coleta de resíduos utilizando Node.js no Back-end, React no Front-end e React Native no Mobile.

## Baixando dependências

Após o clone ou download do repositório é necessário baixar as dependências do projeto executando npm install na raiz de cada projeto
1.  server
2.  web
3.  mobile

### Pré requisitos

1. Node.js
2. Expo

### Iniciando o back-end

1. npm run knex:migrate (Cria as tabelas do projeto)
2. npm run knex:seed (Popula as categorias de resíduos)
3. npm run dev
```
Para verificar se o back-end está ok => http://localhost:3333/items
```

### Iniciando o front-end

1. npm start
```
Para verificar se o front-end está ok => http://localhost:3000
```

### Iniciando o mobile

1. npm start
```
Após esse comando instalando o App Expo no celular é possível ler o QRCode e iniciar a mobile pelo celular
```

## Agradecimento

Agradecimento em especial a rocketseat pois o projeto foi desenvolvido pela conquista da certificação deles.