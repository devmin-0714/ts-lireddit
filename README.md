# ts-tutorial

- [강의 링크](https://www.youtube.com/watch?v=I6ypD7qv3Z8)
- [Code](https://github.com/benawad/lireddit)

## Tech:
- React
- TypeScript
- GraphQL
- URQL/Apollo
- Node.js
- PostgreSQL
- MikroORM/TypeORM
- Redis
- Next.js
- TypeGraphQL
- Chakra

## Extensions
- Bracket Pair Colorizer 2
- Docker
- GraphQL for VSCode
- Prettier
- Vim

## Node/TypeScript Setup
### serve
$ npm init -y
$ node -v
$ yarn add -D @types/node typescript
$ yarn add -D ts-node
$ npx tsconfig.json -> node 선택
$ yarn add -D nodemon

```js
"scripts": {
    "watch": "tsc -w",
    "dev": "nodemon dist/index.js",
    "dev2": "nodemon --exec ts-node src/index.ts",
    "start": "node dist/index.js",
    "start2": "ts-node ssrc/index.tss"
}
```
- Terminal 1(Recompile Typescript File)
$ yarn watch
- Terminal 2 (Reexcecute JS File)
$ yarn dev



