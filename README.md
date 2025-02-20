<p align="center">
  <img src="art.png" />
  <br>
  <span>A curated list of <a href="https://kysely.dev" target="_blank">Kysely</a> resources, tools, utilities and applications.</span>
</p>

<br>

## Contents

- [Adapters](#adapters)
- [Addons](#addons)
- [Articles](#articles)
- [CLIs](#clis)
- [Dialects](#dialects)
- [ORMs](#orms)
- [Templates](#templates)
- [Tools](#tools)
- [Type Generators](#type-generators)
- [Videos](#videos)

## Adapters

- [nestjs-kysely](https://github.com/kazu728/nestjs-kysely) - [Kysely](https://kysely.dev) module for [NestJS](https://nestjs.com/). ![npm](https://img.shields.io/npm/dw/nestjs-kysely?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/kazu728/nestjs-kysely?style=flat-square) ![NPM](https://img.shields.io/npm/l/nestjs-kysely?style=flat-square)

## Addons

- [kysely-params](https://github.com/jtlapp/kysely-params) - A utility for parameterizing compiled [Kysely](https://kysely.dev) queries. ![npm](https://img.shields.io/npm/dw/kysely-params?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/jtlapp/kysely-params?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-params?style=flat-square)
- [kysely-paginate](https://github.com/charlie-hadden/kysely-paginate) - Pagination helpers for use with [Kysely](https://kysely.dev). ![npm](https://img.shields.io/npm/dw/kysely-paginate?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/charlie-hadden/kysely-paginate?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-paginate?style=flat-square)

## Articles

- [Kysely - A type-safe SQL query builder for typescript](https://www.jakso.me/blog/kysely-a-type-safe-sql-query-builder-for-typescript) - A blog post by [koskimas](https://github.com/koskimas), the creator of [Kysely](https://kysely.dev). Letting the world know, way back in 2021, what is [Kysely](https://kysely.dev), its inspiration, design principles, etc.
- [Typesafe Database Queries on the Edge](https://www.nexxel.dev/blog/typesafe-database) - The groundbreaking blog post by [nexxel](https://twitter.com/nexxeln) that set the stage for the [Prisma](https://www.prisma.io) + [Kysely](https://kysely.dev) + [Planetscale](https://planetscale.com)'s DatabaseJS serverless driver usage pattern. Inspired the [prisma-kysely](https://github.com/valtyr/prisma-kysely) adapter.
- [Building a PageSpeed Monitoring Service Using Remix, Kysely and Litestream](https://www.joseferben.com/posts/a-pagespeed-monitoring-service-using-remix-kysely-and-litestream) - A great blog post by [Josef Erben](https://twitter.com/joseferben) that provides a high-level overview of an architechture combining [Kysely](https://kysely.dev) and [Remix](https://remix.run), and shows trade-offs of design decisions made.
- [Build TypeSafe Node API using tRPC, Fastify, Kysely and Atlas CLI](https://dev.to/franciscomendes10866/build-typesafe-node-api-using-trpc-fastify-kysely-and-atlas-cli-580c) - A blog post by [Francisco Mendes](https://github.com/FranciscoMendes10866) on combining [Kysely](https://kysely.dev), [tRPC](https://trpc.io), [Fastify](https://www.fastify.io) and [Atlas](https://atlasgo.io/) to build a robust, type-safe CRUD API.
- [Crafting the Perfect T3 Stack: My Journey with Kysely, Atlas, and Clerk](https://eliasson.me/articles/crafting-the-perfect-t3-stack-my-journey-with-kysely-atlas-and-clerk) - A blog post by [Johan Eliasson](https://twitter.com/elitasson) on how he built his [T3](https://create.t3.gg) inspired stack with [Kysely](https://kysely.dev), [Atlas](https://atlasgo.io/) and [Clerk](https://clerk.dev).
- [Kysely dialect for PlanetScale](https://depot.dev/blog/kysely-dialect-planetscale) - A blog post by [Jacob Gillespie](https://twitter.com/jacobwgillespie) on how [Depot](https://depot.dev) adopted [Kysely](https://kysely.dev) and [PlanetScale](https://planetscale.com/) and created the [Planetscale dialect](https://github.com/depot/kysely-planetscale).
- [Running Vercel Postgres Locally](https://gal.hagever.com/posts/running-vercel-postgres-locally) - A blog post by [Gal Schlezinger](https://twitter.com/galstar) on how he utilizes [neon](https://neon.tech)'s WebSockets proxy [docker](https://www.docker.com/) image and [Kysely](https://kysely.dev) to run his postgres queries locally and ship fast without breaking anything.
- [Simple CQRS in NodeJS with Typescript](https://itnext.io/simple-cqrs-in-nodejs-with-typescript-6da6d3e8a420) - A blog post by Illija on how to implement a simple CQRS pattern with query models using [Kysely](https://kysely.dev).
- [Kysely and CockroachDB](https://morgans-blog.deno.dev/kysely-crdb) - A blog post by [Morgan Winslow](https://github.com/mowinslow2) on [Kysely](https://kysely.dev) and how to use it with [CockroachDB](https://www.cockroachlabs.com).
- [Type-safe S3 Select queries with Kysely](https://dev.to/kumo/type-safe-s3-select-queries-with-kysely-4ge0) - A blog post by [Thomas Aribart](https://twitter.com/aribartt) on how to query [AWS S3](https://aws.amazon.com/s3) buckets, and how to do it in a type-safe manner with [Kysely](https://kysely.dev). Inspired the [S3 Select dialect](https://github.com/igalklebanov/kysely-s3-select).
- [Typescript で SQL を叩く方法を整理する](https://zenn.dev/moekidev/articles/d3db4dc362b93d) - A blog post by [moekidev](https://twitter.com/moekidev) about trying out [Kysely](https://kysely.dev) with [Prisma](https://www.prisma.io) and [Vercel Postgres](https://vercel.com/postgres).
- [現状Cloudflare WorkersでGraphQLサーバを構築するならコレ](https://zenn.dev/chimame/articles/3e7f0f0f7e783d) - A blog post by [chimame](https://twitter.com/chimame_rt) about combining [GraphQL](https://graphql.org/), [Prisma](https://www.prisma.io) and [Kysely](https://kysely.dev) on [Cloudflare Workers](https://workers.cloudflare.com).

## CLIs

- [kysely-migration-cli](https://github.com/acro5piano/kysely-migration-cli) - Thin migration cli library for [Kysely](https://kysely.dev). ![npm](https://img.shields.io/npm/dw/kysely-migration-cli?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/acro5piano/kysely-migration-cli?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-migration-cli?style=flat-square)

## Dialects

- [kysely-data-api](https://github.com/serverless-stack/kysely-data-api) - This library adds [AWS RDS Data Api](https://docs.aws.amazon.com/rdsdataservice/latest/APIReference/Welcome.html) support for [Kysely](https://kysely.dev). It has support for both [MySQL](https://www.mysql.com) and [Postgres](https://www.postgresql.org). ![npm](https://img.shields.io/npm/dw/kysely-data-api?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/serverless-stack/kysely-data-api?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-data-api?style=flat-square)
- [kysely-planetscale](https://github.com/depot/kysely-planetscale) - A [Kysely](https://kysely.dev) dialect for [PlanetScale](https://planetscale.com), using the [PlanetScale](https://planetscale.com) serverless driver for JavaScript. ![npm](https://img.shields.io/npm/dw/kysely-planetscale?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/depot/kysely-planetscale?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-planetscale?style=flat-square)
- [kysely-d1](https://github.com/aidenwallis/kysely-d1) - [Kysely](https://kysely.dev) dialect for [Cloudflare D1](https://developers.cloudflare.com/d1). ![npm](https://img.shields.io/npm/dw/kysely-d1?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/aidenwallis/kysely-d1?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-d1?style=flat-square)
- [@vercel/postgres-kysely](https://github.com/vercel/storage/tree/main/packages/postgres-kysely) - A [@vercel/postgres](https://github.com/vercel/storage/tree/main/packages/postgres) wrapper for the [Kysely](https://kysely.dev) query builder. ![npm](https://img.shields.io/npm/dw/@vercel/postgres-kysely?style=flat-square) ![NPM](https://img.shields.io/npm/l/@vercel/postgres-kysely?style=flat-square)
- [kysely-surrealdb](https://github.com/igalklebanov/kysely-surrealdb) - [Kysely](https://kysely.dev) dialects, plugins and other goodies for [SurrealDB](https://surrealdb.com). SurrealQL is based on SQL, so why not? :trollface: ![npm](https://img.shields.io/npm/dw/kysely-surrealdb?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/igalklebanov/kysely-surrealdb?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-surrealdb?style=flat-square)
- [kysely-neon](https://github.com/seveibar/kysely-neon) - [Kysely](https://kysely.dev) dialect for [Neon](https://neon.tech) serverless [Postgres](https://www.postgresql.org). ![npm](https://img.shields.io/npm/dw/kysely-neon?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/seveibar/kysely-neon?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-neon?style=flat-square)
- [kysely-singlestore](https://github.com/igalklebanov/kysely-singlestore) - [Kysely](https://kysely.dev) dialects, plugins and other goodies for [SingleStore](https://www.singlestore.com) (formerly MemSQL). ![npm](https://img.shields.io/npm/dw/kysely-singlestore?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/igalklebanov/kysely-singlestore?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-singlestore?style=flat-square)
- [kysely-postgres-js](https://github.com/igalklebanov/kysely-postgres-js) - [Kysely](https://kysely.dev) dialect for [PostgreSQL](https://www.postgresql.org) using the [Postgres.js](https://github.com/porsager/postgres) client library under the hood. This dialect should not be confused with [Kysely](https://kysely.dev)'s built-in [PostgreSQL](https://www.postgresql.org) dialect, which uses the [pg](https://github.com/brianc/node-postgres) client library instead. ![npm](https://img.shields.io/npm/dw/kysely-postgres-js?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/igalklebanov/kysely-postgres-js?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-postgres-js?style=flat-square)
- [@libsql/kysely-libsql](https://github.com/libsql/kysely-libsql) - A [Kysely](https://kysely.dev) dialect for [libSQL/sqld](https://github.com/libsql/sqld), using the Hrana protocol over a WebSocket. ![npm](https://img.shields.io/npm/dw/@libsql/kysely-libsql?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/libsql/kysely-libsql?style=flat-square) ![NPM](https://img.shields.io/npm/l/@libsql/kysely-libsql?style=flat-square)
- [@andersgee/kysely-fetch-driver](https://github.com/Andersgee/kysely-fetch-driver) - Edge compatible fetch driver for [Kysely](https://kysely.dev). ![npm](https://img.shields.io/npm/dw/@andersgee/kysely-fetch-driver?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/Andersgee/kysely-fetch-driver?style=flat-square) ![NPM](https://img.shields.io/npm/l/@andersgee/kysely-fetch-driver?style=flat-square)
- [kysely-s3-select](https://github.com/igalklebanov/kysely-s3-select) - [Kysely](https://kysely.dev) dialects, plugins and other goodies for [Amazon S3 Select](https://docs.aws.amazon.com/AmazonS3/latest/userguide/selecting-content-from-objects.html). ![npm](https://img.shields.io/npm/dw/kysely-s3-select?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/igalklebanov/kysely-s3-select?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-s3-select?style=flat-square)

## ORMs

- [kysely-orm](https://github.com/seeden/kysely-orm) - TypeSafe ORM for [Kysely](https://kysely.dev) library. ![npm](https://img.shields.io/npm/dw/kysely-orm?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/seeden/kysely-orm?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-orm?style=flat-square)
- [kysely-mapper](https://github.com/jtlapp/kysely-mapper) - Flexible [Kysely](https://kysely.dev)-based utility for mapping between tables and objects. ![npm](https://img.shields.io/npm/dw/kysely-mapper?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/jtlapp/kysely-mapper?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-mapper?style=flat-square)

## Templates

- [Acme Corp](https://acme-corp.jumr.dev) - Your all-in-one, enterprise ready starting point. Full-stack Typesafety with [tRPC](https://trpc.io/), [Next.js](https://nextjs.org), and [React](https://react.dev) Server Components. Typesafe database access using [Kysely](https://kysely.dev) as query builder, and [Prisma](https://www.prisma.io) for schema management. ![GitHub stars](https://img.shields.io/github/stars/juliusmarminge/acme-corp?style=flat-square)
- [Vercel Postgres + Kysely Next.js Starter](https://vercel.com/templates/next.js/postgres-kysely) - Simple [Next.js](https://nextjs.org) template that uses [Vercel Postgres](https://vercel.com/postgres) as the database and [Kysely](https://kysely.dev) as the query builder.

## Tools

- [kysely-playground](https://kyse.link) - Playground for [Kysely](https://kysely.dev). Provides vscode-like experiences including type checking and auto suggestions. Supports built-in dialects ([Postgres](https://postgresql.org), [MySQL](https://www.mysql.com), [SQLite](https://sqlite.org)), last 20 [Kysely](https://kysely.dev) versions. You can test stuffs quickly, create issues with reproducing with playground. ![GitHub stars](https://img.shields.io/github/stars/wirekang/kysely-playground?style=flat-square)

## Type Generators

- [kysely-codegen](https://github.com/RobinBlomberg/kysely-codegen) - Generate [Kysely](https://kysely.dev) type definitions from your database. ![npm](https://img.shields.io/npm/dw/kysely-codegen?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/RobinBlomberg/kysely-codegen?style=flat-square) ![NPM](https://img.shields.io/npm/l/kysely-codegen?style=flat-square)
- [prisma-kysely](https://github.com/valtyr/prisma-kysely) - Generate [Kysely](https://kysely.dev) types directly from your [Prisma](https://www.prisma.io) schema. ![npm](https://img.shields.io/npm/dw/prisma-kysely?style=flat-square) ![GitHub stars](https://img.shields.io/github/stars/valtyr/prisma-kysely?style=flat-square) ![NPM](https://img.shields.io/npm/l/prisma-kysely?style=flat-square)

## Videos

- [I tried 8 different Postgres ORMs](https://youtu.be/4QN1BzxF8wM) - [Fireship](https://twitter.com/fireship_dev) breaks down some popular [PostgreSQL](https://www.postgresql.org) libraries in the [Node.js](https://nodejs.org) ecosystem. Starting from client libraries, going through query builders ([Kysely](https://kysely.dev) is mentioned starting at the [5:20](https://youtu.be/4QN1BzxF8wM?t=320) mark) and then finishing with ORMs.
- [We need to talk about Prisma](https://youtu.be/J2j1XwZRi30) - [Mehul Mohan](https://twitter.com/mehulmpt) talks about what [codedamn](https://codedamn.com) went through while migrating from [MongoDB](https://mongodb.com) to [Prisma](https://prisma.io) and [Planetscale](https://planetscale.com), and their eventual re-re-write to [AWS Aurora](https://aws.amazon.com/rds/aurora) and [Kysely](https://kysely.dev) for type-safety and performance (starts at the [14:37](https://youtu.be/J2j1XwZRi30?t=877) mark).
- [Let's Talk About Database Performance](https://youtu.be/3P7jnolWfHw) - [Theo Browne aka t3.gg](https://twitter.com/t3dotgg) talks about database performance, [Prisma](https://www.prisma.io), serverless and edge functions, [PlanetScale](https://planetscale.com), their Data API offering and type-safety via [Kysely](https://kysely.dev) (starts at the [15:57](https://youtu.be/3P7jnolWfHw?t=957) mark).
- [Type-Safe SQL on the Edge with Kysely](https://youtu.be/zd9a_Lk3jAc) - [Supabase](https://supabase.com) Edge Functions can connect directly to your [Postgres](https://www.postgresql.org) database to execute SQL Queries. [Kysely](https://kysely.dev) is a type-safe and autocompletion-friendly typescript SQL query builder. Combining [Kysely](https://kysely.dev) with [Deno Postgres](https://deno-postgres.com) provides a neat developer experience for interacting directly with your [Postgres](https://www.postgresql.org) database.
- [2022-08-12 - Fresh Spots - Deno + Fresh Part 4 - Kysely DB Setup / Replacement](https://www.youtube.com/watch?v=C14LWU6zJvA) - Watch [Coding Garden](https://twitter.com/coding_garden) as he combines [Kysely](https://kysely.dev) (starts at the [12:09](https://www.youtube.com/watch?v=C14LWU6zJvA&t=729s) mark), [Deno](https://deno.com/runtime) and [Fresh](https://fresh.deno.dev) on his stream.
