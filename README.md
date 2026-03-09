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
| Stric                                                                                | 122964.72 | 13217.70 | 149438.11 | 100%     |
| Bun                                                                                  | 122913.29 | 13223.28 | 147939.90 | 100%     |
| Hyper Express                                                                        | 108876.47 | 11988.66 | 144001.41 | 89%      |
| Elysia                                                                               | 92345.01  | 13269.29 | 135820.32 | 75%      |
| Deno                                                                                 | 85379.14  | 5312.71  | 110925.92 | 69%      |
| Vixeny (Deno)                                                                        | 83547.08  | 8530.37  | 112411.52 | 68%      |
| Fast                                                                                 | 80734.60  | 7759.16  | 109997.21 | 66%      |
| Fastro                                                                               | 78828.61  | 4055.88  | 97768.50  | 64%      |
| NHttp                                                                                | 78420.21  | 4248.48  | 95715.22  | 64%      |
| Hono                                                                                 | 76310.01  | 3846.48  | 93989.76  | 62%      |
| Megalo                                                                               | 71499.70  | 4472.60  | 104242.10 | 58%      |
| Deso                                                                                 | 70623.44  | 3513.36  | 82020.06  | 57%      |
| Alosaur                                                                              | 64852.82  | 3941.42  | 69457.42  | 53%      |
| Reno                                                                                 | 60816.20  | 3070.52  | 63822.09  | 49%      |
| Cheetah                                                                              | 57763.02  | 3460.25  | 61838.06  | 47%      |
| http                                                                                 | 51194.90  | 4941.11  | 56876.93  | 42%      |
| Router                                                                               | 48855.71  | 4813.18  | 79339.63  | 40%      |
| Danet V2 (Hono)                                                                      | 48064.70  | 3455.44  | 50625.84  | 39%      |
| Danet (Oak)                                                                          | 44573.73  | 4116.19  | 53907.06  | 36%      |
| Oak                                                                                  | 41165.79  | 3736.28  | 44321.85  | 33%      |
| Little                                                                               | 37402.65  | 4296.44  | 44026.90  | 30%      |
| Aqua                                                                                 | 36938.27  | 3953.20  | 42972.32  | 30%      |
| Node                                                                                 | 36485.48  | 3109.94  | 42943.30  | 30%      |
| Fastify                                                                              | 31857.93  | 3313.74  | 40477.29  | 26%      |
| Dinatra                                                                              | 22586.47  | 3646.42  | 27482.15  | 18%      |
| Abc                                                                                  | 19246.58  | 3012.71  | 25452.32  | 16%      |
| Express (Deno)                                                                       | 14516.49  | 2888.90  | 18384.82  | 12%      |
| Servest                                                                              | 9167.41   | 2332.66  | 15011.07  | 7%       |
| Express                                                                              | 8765.23   | 1531.31  | 11685.10  | 7%       |
| Acorn                                                                                | 0.00      | 0.00     | 0.00      | 0%       |
| Opine                                                                                | 0.00      | 0.00     | 0.00      | 0%       |
| Peko                                                                                 | 0.00      | 0.00     | 0.00      | 0%       |
| Vixeny (Bun)                                                                         | 0.00      | 0.00     | 0.00      | 0%       |
| ![Chart](https://quickchart.io/chart/render/zf-3711fba7-8b91-40c7-8683-77e951d2dd84) |           |          |           |          |

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
| 19246.58 | 3012.71 | 25452.32 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 15712.01 | 17271.80 | 20358.03 | 21129.24 | 21622.04 | 21981.65 | 22522.50 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 2ms      | 4ms      | 4ms      |

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
| 64852.82 | 3941.42 | 69457.42 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 63924.33 | 64842.88 | 65608.45 | 66201.01 | 66604.47 | 66867.59 | 67575.18 |
| **Latency** | 679µs    | 708µs    | 777µs    | 814µs    | 838µs    | 858µs    | 1ms      |

### [Aqua](#aqua)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 36938.27 | 3953.20 | 42972.32 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 34011.75 | 35616.76 | 38174.38 | 38852.01 | 39460.65 | 40114.49 | 41284.99 |
| **Latency** | 850µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Bun](#bun)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 122913.29 | 13223.28 | 147939.90 |     |

| **Stat**    | 10        | 25        | 50        | 75        | 90        | 95        | 99        |
| ----------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 104428.57 | 112951.82 | 123395.14 | 133608.40 | 140495.75 | 143106.45 | 146281.38 |
| **Latency** | 247µs     | 310µs     | 388µs     | 472µs     | 588µs     | 674µs     | 891µs     |

### [Cheetah](#cheetah)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 57763.02 | 3460.25 | 61838.06 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 57318.97 | 57720.04 | 58435.39 | 58842.33 | 59292.00 | 59512.49 | 59842.26 |
| **Latency** | 760µs    | 788µs    | 879µs    | 914µs    | 940µs    | 969µs    | 1ms      |

### [Danet (Oak)](#danet-oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 44573.73 | 4116.19 | 53907.06 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 42371.25 | 44037.02 | 44731.88 | 45738.45 | 48458.05 | 49769.33 | 52161.67 |
| **Latency** | 960µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Danet V2 (Hono)](#danet-v2-hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 48064.70 | 3455.44 | 50625.84 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 47430.37 | 48311.05 | 48792.38 | 49218.15 | 49622.85 | 49805.26 | 50121.34 |
| **Latency** | 906µs    | 936µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Deno](#deno)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 85379.14 | 5312.71 | 110925.92 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 81444.35 | 82907.23 | 84661.64 | 87416.76 | 90910.93 | 93662.26 | 102051.39 |
| **Latency** | 475µs    | 541µs    | 591µs    | 635µs    | 671µs    | 708µs    | 793µs     |

### [Deso](#deso)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 70623.44 | 3513.36 | 82020.06 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 69071.68 | 70118.99 | 71079.96 | 71954.78 | 72991.57 | 73521.27 | 75144.27 |
| **Latency** | 654µs    | 677µs    | 703µs    | 729µs    | 754µs    | 783µs    | 869µs    |

### [Dinatra](#dinatra)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 22586.47 | 3646.42 | 27482.15 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 18103.14 | 20543.43 | 24076.02 | 24819.39 | 25362.51 | 25880.51 | 26421.60 |
| **Latency** | 1ms      | 2ms      | 2ms      | 2ms      | 2ms      | 3ms      | 4ms      |

### [Elysia](#elysia)

| **Stat** | Mean     | Stddev    | Max |
| -------- | -------- | --------- | --- |
| 92345.01 | 13269.29 | 135820.32 |     |

| **Stat**    | 10       | 25       | 50       | 75        | 90        | 95        | 99        |
| ----------- | -------- | -------- | -------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 75648.53 | 82530.04 | 92078.08 | 101050.80 | 109656.31 | 115111.27 | 125149.38 |
| **Latency** | 316µs    | 419µs    | 521µs    | 610µs     | 764µs     | 938µs     | 1ms       |

### [Express](#express)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 8765.23  | 1531.31 | 11685.10 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90       | 95       | 99       |
| ----------- | ------- | ------- | ------- | ------- | -------- | -------- | -------- |
| **Req/Sec** | 6924.86 | 8354.74 | 8935.88 | 9165.74 | 10898.79 | 11341.03 | 11546.78 |
| **Latency** | 4ms     | 5ms     | 5ms     | 5ms     | 6ms      | 7ms      | 9ms      |

### [Express (Deno)](#express-deno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 14516.49 | 2888.90 | 18384.82 |     |

| **Stat**    | 10      | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | ------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 9635.40 | 12901.57 | 15885.15 | 16307.45 | 17203.26 | 17354.91 | 18132.51 |
| **Latency** | 2ms     | 2ms      | 3ms      | 3ms      | 4ms      | 5ms      | 6ms      |

### [Fast](#fast)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 80734.60 | 7759.16 | 109997.21 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 75403.81 | 77016.15 | 78992.71 | 84511.34 | 90153.31 | 93882.35 | 101403.19 |
| **Latency** | 458µs    | 565µs    | 629µs    | 682µs    | 717µs    | 748µs    | 849µs     |

### [Fastify](#fastify)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 31857.93 | 3313.74 | 40477.29 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 30351.66 | 31416.27 | 32505.49 | 33037.34 | 33448.67 | 33824.97 | 35863.99 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 3ms      |

### [Fastro](#fastro)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 78828.61 | 4055.88 | 97768.50 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 76635.03 | 77900.41 | 78851.83 | 80167.20 | 82034.88 | 83837.17 | 87701.53 |
| **Latency** | 550µs    | 589µs    | 638µs    | 677µs    | 704µs    | 728µs    | 814µs    |

### [Hono](#hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 76310.01 | 3846.48 | 93989.76 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 74472.54 | 75528.25 | 76456.92 | 77603.80 | 78816.22 | 80020.21 | 83439.83 |
| **Latency** | 572µs    | 607µs    | 658µs    | 696µs    | 724µs    | 749µs    | 827µs    |

### [http](#http)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 51194.90 | 4941.11 | 56876.93 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 45080.91 | 51428.15 | 52586.64 | 53506.41 | 54554.09 | 55219.37 | 56164.00 |
| **Latency** | 675µs    | 911µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Hyper Express](#hyper-express)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 108876.47 | 11988.66 | 144001.41 |     |

| **Stat**    | 10       | 25        | 50        | 75        | 90        | 95        | 99        |
| ----------- | -------- | --------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 95501.10 | 100395.85 | 107115.95 | 116289.76 | 125894.28 | 131018.09 | 139013.00 |
| **Latency** | 271µs    | 347µs     | 439µs     | 548µs     | 646µs     | 744µs     | 989µs     |

### [Little](#little)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 37402.65 | 4296.44 | 44026.90 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 34863.22 | 36615.16 | 38441.96 | 39368.64 | 40160.00 | 40903.14 | 41719.00 |
| **Latency** | 853µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Megalo](#megalo)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 71499.70 | 4472.60 | 104242.10 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 69642.37 | 70650.74 | 71588.66 | 72435.36 | 73437.52 | 77834.97 | 82751.06 |
| **Latency** | 613µs    | 648µs    | 705µs    | 744µs    | 771µs    | 792µs    | 902µs    |

### [NHttp](#nhttp)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 78420.21 | 4248.48 | 95715.22 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 76353.78 | 77336.41 | 78350.67 | 79321.63 | 81191.71 | 84600.27 | 90610.18 |
| **Latency** | 555µs    | 593µs    | 643µs    | 680µs    | 707µs    | 730µs    | 813µs    |

### [Node](#node)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 36485.48 | 3109.94 | 42943.30 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 35904.57 | 36334.91 | 36858.05 | 37401.32 | 37835.66 | 38054.79 | 38866.23 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Oak](#oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 41165.79 | 3736.28 | 44321.85 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 40211.67 | 41219.01 | 42174.31 | 42561.41 | 42944.52 | 43186.17 | 43524.44 |
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
| 60816.20 | 3070.52 | 63822.09 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 59916.44 | 60756.77 | 61344.98 | 61865.88 | 62262.91 | 62671.97 | 63166.28 |
| **Latency** | 724µs    | 753µs    | 834µs    | 870µs    | 895µs    | 915µs    | 1ms      |

### [Router](#router)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 48855.71 | 4813.18 | 79339.63 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 43827.29 | 48419.50 | 50222.38 | 51134.61 | 51881.87 | 52381.31 | 53574.38 |
| **Latency** | 697µs    | 964µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Stric](#stric)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 122964.72 | 13217.70 | 149438.11 |     |

| **Stat**    | 10        | 25        | 50        | 75        | 90        | 95        | 99        |
| ----------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 105119.45 | 112954.95 | 123108.61 | 133780.87 | 141122.95 | 143818.96 | 147005.07 |
| **Latency** | 246µs     | 309µs     | 387µs     | 472µs     | 589µs     | 675µs     | 887µs     |

### [Servest](#servest)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 9167.41  | 2332.66 | 15011.07 |     |

| **Stat**    | 10      | 25      | 50      | 75       | 90       | 95       | 99       |
| ----------- | ------- | ------- | ------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 6132.39 | 8351.11 | 9660.85 | 10400.79 | 11752.89 | 12324.62 | 12828.91 |
| **Latency** | 4ms     | 4ms     | 5ms     | 5ms      | 8ms      | 8ms      | 15ms     |

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
| 83547.08 | 8530.37 | 112411.52 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 76787.40 | 78207.06 | 81263.39 | 87939.64 | 95248.80 | 99586.77 | 107108.72 |
| **Latency** | 431µs    | 533µs    | 612µs    | 671µs    | 705µs    | 734µs    | 824µs     |

---

<p align="center">Generated 2026-03-09T00:39:46.550Z</p>
