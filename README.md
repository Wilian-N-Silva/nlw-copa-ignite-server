definir que o projeto usa JS
```console
npm init -y
```

instalar o typescript
```console
npm i typescript -D
```

configurar o typescript
```console
npx tsc --init
```

instalar o fastify
```console
npm i fastify
```

instalar o tsx
```console
npm i tsx -D
```

configuração tsx - package.json
```json
  "scripts": {
    "dev": "tsx watch src/server.ts"
  },
```

executar o server
```console
npm run dev
```

instala o prisma
```console
npm i prisma -D
```

instala o prisma/client (conecta com o banco de dados)
```console
npm i @prisma/client
```

inicializa o prisma com SQLite
```console
npx prisma init --datasource-provider SQLite
```

criar migration
npx prisma migrate dev

ver bd
npx prisma studio


instalar prisma-erd + mermaid
npm i prisma-erd-generator @mermaid-js/mermaid-cli  -D

gerar erd
npx prisma generate

fastify cors
npm i @fastify/cors