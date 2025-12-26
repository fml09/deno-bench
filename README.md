<div align="center">
  <h1><code>bench</code></h1>
  <p>
    <strong>📊 Daily benchmarks of deno & node & bun HTTP frameworks</strong>
  </p>
  <br>
  <p align="center">
    <a alt="Bench" href="https://github.com/denosaurs/bench/actions">
      <img src="https://img.shields.io/github/workflow/status/denosaurs/bench/bench" />
    </a>
  </p>
</div>

# Table of Contents

- [Overview](#overview)
  - [Hello, bench!](#hello-bench)
- [Frameworks](#frameworks)
  - [Abc](#abc)
  - [Acorn](#acorn)
  - [Alosaur](#alosaur)
  - [Aqua](#aqua)
  - [Bun](#bun)
  - [Cheetah](#cheetah)
  - [Danet (Oak)](#danet-oak)
  - [Danet V2 (Hono)](#danet-v2-hono)
  - [Deno](#deno)
  - [Deso](#deso)
  - [Dinatra](#dinatra)
  - [Elysia](#elysia)
  - [Express](#express)
  - [Express (Deno)](#express-deno)
  - [Fast](#fast)
  - [Fastify](#fastify)
  - [Fastro](#fastro)
  - [Hono](#hono)
  - [http](#http)
  - [Hyper Express](#hyper-express)
  - [Little](#little)
  - [Megalo](#megalo)
  - [NHttp](#nhttp)
  - [Node](#node)
  - [Oak](#oak)
  - [Opine](#opine)
  - [Peko](#peko)
  - [Reno](#reno)
  - [Router](#router)
  - [Stric](#stric)
  - [Servest](#servest)
  - [Vixeny (Bun)](#vixeny-bun)
  - [Vixeny (Deno)](#vixeny-deno)
- [Benchmarks](#benchmarks)
  - [Hello, bench!](#hello-bench-1)
    - [Abc](#abc-1)
    - [Acorn](#acorn-1)
    - [Alosaur](#alosaur-1)
    - [Aqua](#aqua-1)
    - [Bun](#bun-1)
    - [Cheetah](#cheetah-1)
    - [Danet (Oak)](#danet-oak-1)
    - [Danet V2 (Hono)](#danet-v2-hono-1)
    - [Deno](#deno-1)
    - [Deso](#deso-1)
    - [Dinatra](#dinatra-1)
    - [Elysia](#elysia-1)
    - [Express](#express-1)
    - [Express (Deno)](#express-deno-1)
    - [Fast](#fast-1)
    - [Fastify](#fastify-1)
    - [Fastro](#fastro-1)
    - [Hono](#hono-1)
    - [http](#http-1)
    - [Hyper Express](#hyper-express-1)
    - [Little](#little-1)
    - [Megalo](#megalo-1)
    - [NHttp](#nhttp-1)
    - [Node](#node-1)
    - [Oak](#oak-1)
    - [Opine](#opine-1)
    - [Peko](#peko-1)
    - [Reno](#reno-1)
    - [Router](#router-1)
    - [Stric](#stric-1)
    - [Servest](#servest-1)
    - [Vixeny (Bun)](#vixeny-bun-1)
    - [Vixeny (Deno)](#vixeny-deno-1)

# Overview

## Hello, bench!

> Requests per second

| Framework                                                                            | Mean      | Stddev   | Max       | Relative |
| ------------------------------------------------------------------------------------ | --------- | -------- | --------- | -------- |
| Stric                                                                                | 116381.13 | 13057.00 | 146816.49 | 100%     |
| Bun                                                                                  | 111697.42 | 13879.67 | 146108.59 | 96%      |
| Hyper Express                                                                        | 105682.18 | 11534.53 | 142252.52 | 91%      |
| Elysia                                                                               | 94997.32  | 10512.06 | 134913.50 | 82%      |
| Deno                                                                                 | 84664.86  | 4746.97  | 101912.47 | 73%      |
| Vixeny (Deno)                                                                        | 79128.73  | 4157.27  | 103001.05 | 68%      |
| Fastro                                                                               | 78548.97  | 10297.39 | 108348.95 | 67%      |
| NHttp                                                                                | 77684.60  | 4258.31  | 93704.18  | 67%      |
| Fast                                                                                 | 76553.60  | 4326.06  | 105121.73 | 66%      |
| Hono                                                                                 | 75599.74  | 4562.77  | 88389.20  | 65%      |
| Deso                                                                                 | 71384.10  | 4009.40  | 92412.73  | 61%      |
| Megalo                                                                               | 70396.97  | 4241.26  | 77918.34  | 60%      |
| Alosaur                                                                              | 64030.30  | 4341.70  | 92912.69  | 55%      |
| Reno                                                                                 | 60723.99  | 3942.45  | 65270.77  | 52%      |
| Cheetah                                                                              | 58054.29  | 3979.38  | 62610.81  | 50%      |
| http                                                                                 | 50487.94  | 6056.18  | 56836.30  | 43%      |
| Router                                                                               | 48834.66  | 5426.74  | 55847.26  | 42%      |
| Danet V2 (Hono)                                                                      | 48076.48  | 3866.94  | 56328.58  | 41%      |
| Danet (Oak)                                                                          | 42953.99  | 3696.86  | 46223.64  | 37%      |
| Oak                                                                                  | 40924.22  | 4317.04  | 44594.98  | 35%      |
| Node                                                                                 | 37788.85  | 3219.35  | 44573.11  | 32%      |
| Aqua                                                                                 | 35369.28  | 4107.95  | 42214.78  | 30%      |
| Little                                                                               | 34505.64  | 5388.34  | 41997.94  | 30%      |
| Fastify                                                                              | 33126.15  | 3361.84  | 37820.05  | 28%      |
| Dinatra                                                                              | 22065.63  | 4290.84  | 43786.24  | 19%      |
| Abc                                                                                  | 19194.16  | 3017.26  | 23362.65  | 16%      |
| Express (Deno)                                                                       | 14837.21  | 2203.66  | 17808.84  | 13%      |
| Express                                                                              | 8655.11   | 1593.77  | 11608.80  | 7%       |
| Servest                                                                              | 8120.42   | 2271.09  | 16403.10  | 7%       |
| Acorn                                                                                | 0.00      | 0.00     | 0.00      | 0%       |
| Opine                                                                                | 0.00      | 0.00     | 0.00      | 0%       |
| Peko                                                                                 | 0.00      | 0.00     | 0.00      | 0%       |
| Vixeny (Bun)                                                                         | 0.00      | 0.00     | 0.00      | 0%       |
| ![Chart](https://quickchart.io/chart/render/zf-9d07a7bb-43eb-4603-a873-a15139cc8acd) |           |          |           |          |

# Frameworks

## [Abc](https://deno.land/x/abc)

A better Deno framework to create web application

## [Acorn](https://deno.land/x/acorn)

A focused RESTful server framework for Deno 🌰🦕

## [Alosaur](https://deno.land/x/alosaur)

Deno web framework with many decorators

## [Aqua](https://deno.land/x/aqua)

A minimal and fast 🏃 web framework for Deno

## [Bun](https://bun.sh/)

Bun is a fast all-in-one JavaScript runtime

## [Cheetah](https://github.com/azurystudio/cheetah)

🐈 A blazing fast framework for the modern web.

## [Danet (Oak)](https://docs.danet.land/)

The most mature backend framework for Deno

## [Danet V2 (Hono)](https://danet.land/)

The most mature backend framework for Deno, V2 in Alpha

## [Deno](https://deno.land/)

A modern runtime for JavaScript and TypeScript

## [Deso](https://github.com/gothammm/deso)

A simple & fast HTTP web framework for Deno

## [Dinatra](https://github.com/syumai/dinatra)

Sinatra like light weight web app framework for deno.

## [Elysia](https://elysiajs.com/)

Ergonomic Framework for Humans

## [Express](https://expressjs.com/)

Fast, unopinionated, minimalist web framework for Node.js

## [Express (Deno)](https://expressjs.com/)

Fast, unopinionated, minimalist web framework for Node.js, run on Deno

## [Fast](https://deno.land/x/fast)

Small web framework with near-native performance.

## [Fastify](https://www.fastify.io/)

Fast and low overhead web framework, for Node.js

## [Fastro](https://fastro.dev)

Fast and simple web application framework for deno

## [Hono](https://github.com/honojs/hono)

Ultrafast web framework for Cloudflare Workers and Deno. Fast, but not only
fast.

## [http](https://deno.land/std/http)

The deno standard library http server

## [Hyper Express](https://github.com/kartikk221/hyper-express)

High performance Node.js webserver with a simple-to-use API powered by
uWebsockets.js under the hood.

## [Little](https://deno.land/x/little)

A minimalistic connect-like web framework. Automatically works out of the box
with Deno Deploy, Deno's Native HTTP and Deno's Standard HTTP server.

## [Megalo](https://github.com/tsar-boomba/megalo)

Deno HTTP server framework focused on speed

## [NHttp](https://github.com/nhttp/nhttp)

An Simple web-framework for Deno and Friends

## [Node](https://nodejs.org/)

Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine.

## [Oak](https://deno.land/x/oak)

A middleware framework for Deno's native HTTP server, Deno Deploy and Node.js
16.5 and later. It also includes a middleware router.

## [Opine](https://deno.land/x/opine)

Fast, minimalist web framework for Deno ported from ExpressJS.

## [Peko](https://peko.deno.dev)

Featherweight server/router framework + middleware and handler library 🐣

## [Reno](https://deno.land/x/reno)

A thin, testable routing library designed to sit on top of Deno's standard HTTP
module.

## [Router](https://crux.land/router@0.0.12)

The tiny, modern and fast router by the denosaurs for deno and deno deploy. Used
by projects like fresh

## [Stric](https://bun.sh/docs/ecosystem/stric)

Stric is a minimalist, fast web framework for Bun.

## [Servest](https://servestjs.org/)

🌾A progressive http server for Deno🌾

## [Vixeny (Bun)](https://vixeny.dev/)

A pure functional web framework

## [Vixeny (Deno)](https://vixeny.dev/)

A pure functional web framework

# Benchmarks

## Hello, bench!

A simple benchmark which expects a response simply containing the text
"`Hello, Bench!`"

### [Abc](#abc)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 19194.16 | 3017.26 | 23362.65 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 15463.91 | 17010.31 | 20539.19 | 21143.54 | 21548.77 | 21939.54 | 22775.80 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 3ms      | 3ms      | 4ms      |

### [Acorn](#acorn)

| **Stat** | Mean | Stddev | Max |
| -------- | ---- | ------ | --- |
| 0.00     | 0.00 | 0.00   |     |

| **Stat**    | 10   | 25   | 50   | 75   | 90   | 95   | 99   |
| ----------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| **Req/Sec** | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |
| **Latency** | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  |

### [Alosaur](#alosaur)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 64030.30 | 4341.70 | 92912.69 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 61897.88 | 63638.61 | 64722.58 | 65480.89 | 66258.38 | 66841.73 | 71436.66 |
| **Latency** | 682µs    | 717µs    | 785µs    | 826µs    | 857µs    | 888µs    | 1ms      |

### [Aqua](#aqua)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 35369.28 | 4107.95 | 42214.78 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 32199.86 | 34402.17 | 36493.94 | 37450.29 | 38471.36 | 39111.23 | 40049.33 |
| **Latency** | 882µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Bun](#bun)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 111697.42 | 13879.67 | 146108.59 |     |

| **Stat**    | 10       | 25        | 50        | 75        | 90        | 95        | 99        |
| ----------- | -------- | --------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 95307.22 | 100506.69 | 109617.17 | 122800.61 | 131335.33 | 136152.60 | 140851.45 |
| **Latency** | 272µs    | 339µs     | 423µs     | 510µs     | 666µs     | 766µs     | 968µs     |

### [Cheetah](#cheetah)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 58054.29 | 3979.38 | 62610.81 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 57273.36 | 58031.70 | 58772.92 | 59510.38 | 59974.14 | 60508.09 | 61051.23 |
| **Latency** | 750µs    | 783µs    | 869µs    | 908µs    | 940µs    | 999µs    | 1ms      |

### [Danet (Oak)](#danet-oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 42953.99 | 3696.86 | 46223.64 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 41934.52 | 42917.01 | 43721.86 | 44474.40 | 45148.88 | 45334.21 | 45783.56 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Danet V2 (Hono)](#danet-v2-hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 48076.48 | 3866.94 | 56328.58 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 47239.95 | 48358.30 | 48902.33 | 49535.10 | 49950.30 | 50123.92 | 50597.53 |
| **Latency** | 900µs    | 932µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Deno](#deno)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 84664.86 | 4746.97 | 101912.47 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 80906.50 | 82842.02 | 84623.75 | 86833.93 | 89551.13 | 91345.76 | 95371.40 |
| **Latency** | 484µs    | 541µs    | 591µs    | 635µs    | 686µs    | 737µs    | 834µs    |

### [Deso](#deso)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 71384.10 | 4009.40 | 92412.73 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 69307.70 | 70472.88 | 71742.56 | 72989.68 | 74309.14 | 75137.85 | 76518.33 |
| **Latency** | 638µs    | 665µs    | 693µs    | 722µs    | 758µs    | 806µs    | 900µs    |

### [Dinatra](#dinatra)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 22065.63 | 4290.84 | 43786.24 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 16746.74 | 19440.02 | 23566.53 | 24855.82 | 25622.99 | 25965.09 | 26751.24 |
| **Latency** | 1ms      | 1ms      | 2ms      | 2ms      | 2ms      | 3ms      | 4ms      |

### [Elysia](#elysia)

| **Stat** | Mean     | Stddev    | Max |
| -------- | -------- | --------- | --- |
| 94997.32 | 10512.06 | 134913.50 |     |

| **Stat**    | 10       | 25       | 50       | 75        | 90        | 95        | 99        |
| ----------- | -------- | -------- | -------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 82968.08 | 87119.55 | 93312.58 | 101242.53 | 110022.33 | 113107.57 | 125057.65 |
| **Latency** | 301µs    | 388µs    | 519µs    | 614µs     | 736µs     | 889µs     | 1ms       |

### [Express](#express)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 8655.11  | 1593.77 | 11608.80 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90       | 95       | 99       |
| ----------- | ------- | ------- | ------- | ------- | -------- | -------- | -------- |
| **Req/Sec** | 6409.21 | 8179.56 | 8885.87 | 9406.90 | 10775.94 | 11064.11 | 11336.05 |
| **Latency** | 4ms     | 5ms     | 5ms     | 5ms     | 7ms      | 8ms      | 9ms      |

### [Express (Deno)](#express-deno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 14837.21 | 2203.66 | 17808.84 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 11569.38 | 14421.31 | 15813.46 | 16117.00 | 16355.44 | 16644.49 | 17114.14 |
| **Latency** | 2ms      | 2ms      | 3ms      | 3ms      | 4ms      | 4ms      | 5ms      |

### [Fast](#fast)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 76553.60 | 4326.06 | 105121.73 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 73905.88 | 75327.16 | 76724.88 | 78311.42 | 79849.12 | 81179.61 | 85915.01 |
| **Latency** | 561µs    | 603µs    | 654µs    | 696µs    | 733µs    | 774µs    | 867µs    |

### [Fastify](#fastify)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 33126.15 | 3361.84 | 37820.05 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 32338.72 | 33103.27 | 33657.68 | 34208.53 | 34630.70 | 34924.18 | 35441.24 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Fastro](#fastro)

| **Stat** | Mean     | Stddev    | Max |
| -------- | -------- | --------- | --- |
| 78548.97 | 10297.39 | 108348.95 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 71023.39 | 72755.12 | 75317.28 | 83716.62 | 92958.78 | 98319.58 | 104555.89 |
| **Latency** | 451µs    | 547µs    | 652µs    | 719µs    | 758µs    | 794µs    | 917µs     |

### [Hono](#hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 75599.74 | 4562.77 | 88389.20 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 73229.01 | 74753.48 | 76121.06 | 77317.14 | 78606.81 | 79583.43 | 82437.74 |
| **Latency** | 572µs    | 609µs    | 662µs    | 701µs    | 734µs    | 774µs    | 874µs    |

### [http](#http)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 50487.94 | 6056.18 | 56836.30 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 43717.47 | 50907.34 | 52384.63 | 53360.70 | 54452.60 | 55154.64 | 56145.25 |
| **Latency** | 670µs    | 933µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Hyper Express](#hyper-express)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 105682.18 | 11534.53 | 142252.52 |     |

| **Stat**    | 10       | 25       | 50        | 75        | 90        | 95        | 99        |
| ----------- | -------- | -------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 92633.13 | 97219.72 | 104152.44 | 113511.89 | 121138.92 | 126879.06 | 135853.67 |
| **Latency** | 275µs    | 355µs    | 459µs     | 561µs     | 666µs     | 763µs     | 1ms       |

### [Little](#little)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 34505.64 | 5388.34 | 41997.94 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 30507.02 | 32862.12 | 36250.33 | 37457.94 | 38515.78 | 39054.19 | 40275.24 |
| **Latency** | 892µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      |

### [Megalo](#megalo)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 70396.97 | 4241.26 | 77918.34 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 68036.27 | 69508.69 | 71070.19 | 72362.64 | 73144.00 | 73909.42 | 75411.05 |
| **Latency** | 621µs    | 655µs    | 710µs    | 749µs    | 781µs    | 810µs    | 934µs    |

### [NHttp](#nhttp)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 77684.60 | 4258.31 | 93704.18 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 74878.97 | 76338.38 | 77855.67 | 79411.22 | 81388.32 | 82769.48 | 85833.93 |
| **Latency** | 550µs    | 594µs    | 645µs    | 686µs    | 723µs    | 766µs    | 860µs    |

### [Node](#node)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 37788.85 | 3219.35 | 44573.11 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 37184.95 | 37720.71 | 38207.42 | 38678.02 | 39080.91 | 39401.52 | 40103.59 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Oak](#oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 40924.22 | 4317.04 | 44594.98 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 39810.69 | 41106.87 | 42100.62 | 42540.76 | 43230.37 | 43512.83 | 44026.98 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Opine](#opine)

| **Stat** | Mean | Stddev | Max |
| -------- | ---- | ------ | --- |
| 0.00     | 0.00 | 0.00   |     |

| **Stat**    | 10   | 25   | 50   | 75   | 90   | 95   | 99   |
| ----------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| **Req/Sec** | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |
| **Latency** | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  |

### [Peko](#peko)

| **Stat** | Mean | Stddev | Max |
| -------- | ---- | ------ | --- |
| 0.00     | 0.00 | 0.00   |     |

| **Stat**    | 10   | 25   | 50   | 75   | 90   | 95   | 99   |
| ----------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| **Req/Sec** | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |
| **Latency** | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  |

### [Reno](#reno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 60723.99 | 3942.45 | 65270.77 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 58679.93 | 60006.49 | 61638.95 | 62581.47 | 63262.56 | 63705.86 | 64477.65 |
| **Latency** | 719µs    | 752µs    | 827µs    | 870µs    | 904µs    | 933µs    | 1ms      |

### [Router](#router)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 48834.66 | 5426.74 | 55847.26 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 43373.54 | 47842.21 | 50624.98 | 51789.94 | 52616.75 | 53014.16 | 53863.32 |
| **Latency** | 685µs    | 961µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Stric](#stric)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 116381.13 | 13057.00 | 146816.49 |     |

| **Stat**    | 10       | 25        | 50        | 75        | 90        | 95        | 99        |
| ----------- | -------- | --------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 98824.26 | 105892.15 | 115939.09 | 126668.44 | 133980.17 | 138603.16 | 143556.09 |
| **Latency** | 256µs    | 321µs     | 402µs     | 502µs     | 645µs     | 728µs     | 942µs     |

### [Servest](#servest)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 8120.42  | 2271.09 | 16403.10 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90       | 95       | 99       |
| ----------- | ------- | ------- | ------- | ------- | -------- | -------- | -------- |
| **Req/Sec** | 5317.91 | 6910.46 | 8427.90 | 9585.20 | 10568.75 | 11118.65 | 12845.92 |
| **Latency** | 4ms     | 5ms     | 5ms     | 6ms     | 8ms      | 9ms      | 16ms     |

### [Vixeny (Bun)](#vixeny-bun)

| **Stat** | Mean | Stddev | Max |
| -------- | ---- | ------ | --- |
| 0.00     | 0.00 | 0.00   |     |

| **Stat**    | 10   | 25   | 50   | 75   | 90   | 95   | 99   |
| ----------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| **Req/Sec** | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |
| **Latency** | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  |

### [Vixeny (Deno)](#vixeny-deno)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 79128.73 | 4157.27 | 103001.05 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 76501.49 | 78006.16 | 79367.29 | 80832.32 | 82245.48 | 83244.96 | 87839.70 |
| **Latency** | 542µs    | 583µs    | 633µs    | 673µs    | 708µs    | 746µs    | 843µs    |

---

<p align="center">Generated 2025-12-26T00:33:41.474Z</p>
