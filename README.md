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
| Bun                                                                                  | 118540.69 | 13354.75 | 148942.66 | 100%     |
| Stric                                                                                | 117402.06 | 15611.71 | 151247.36 | 99%      |
| Hyper Express                                                                        | 104815.85 | 11111.01 | 140783.69 | 88%      |
| Elysia                                                                               | 96717.96  | 9543.92  | 139443.72 | 82%      |
| Deno                                                                                 | 86278.98  | 4624.46  | 103965.75 | 73%      |
| Vixeny (Deno)                                                                        | 78964.32  | 3992.10  | 91382.92  | 67%      |
| NHttp                                                                                | 78731.87  | 4109.14  | 93015.42  | 66%      |
| Fast                                                                                 | 77911.33  | 4303.31  | 95804.00  | 66%      |
| Hono                                                                                 | 75931.95  | 4077.01  | 93462.00  | 64%      |
| Fastro                                                                               | 75534.60  | 6639.93  | 102354.99 | 64%      |
| Deso                                                                                 | 71852.23  | 3705.32  | 83303.46  | 61%      |
| Megalo                                                                               | 70774.09  | 4354.86  | 78233.41  | 60%      |
| Alosaur                                                                              | 64922.51  | 4308.70  | 71563.27  | 55%      |
| Reno                                                                                 | 61454.92  | 3832.57  | 64885.05  | 52%      |
| Cheetah                                                                              | 58293.10  | 3792.77  | 62199.77  | 49%      |
| http                                                                                 | 51333.95  | 5199.08  | 61996.84  | 43%      |
| Router                                                                               | 49171.47  | 5426.05  | 64119.52  | 41%      |
| Danet V2 (Hono)                                                                      | 48332.75  | 3951.82  | 57338.48  | 41%      |
| Danet (Oak)                                                                          | 43379.71  | 3436.08  | 46686.34  | 37%      |
| Oak                                                                                  | 40905.25  | 4428.16  | 44290.82  | 35%      |
| Node                                                                                 | 37192.98  | 3183.76  | 39714.63  | 31%      |
| Aqua                                                                                 | 35783.34  | 4214.98  | 42768.53  | 30%      |
| Little                                                                               | 35063.24  | 5465.57  | 46205.74  | 30%      |
| Fastify                                                                              | 34016.42  | 3566.77  | 36978.82  | 29%      |
| Dinatra                                                                              | 23072.45  | 4448.92  | 43368.07  | 19%      |
| Abc                                                                                  | 19086.83  | 3129.40  | 40744.82  | 16%      |
| Express (Deno)                                                                       | 14504.10  | 2827.08  | 18036.06  | 12%      |
| Express                                                                              | 8881.90   | 1659.12  | 11815.94  | 7%       |
| Servest                                                                              | 8189.84   | 2310.99  | 16596.07  | 7%       |
| Acorn                                                                                | 0.00      | 0.00     | 0.00      | 0%       |
| Opine                                                                                | 0.00      | 0.00     | 0.00      | 0%       |
| Peko                                                                                 | 0.00      | 0.00     | 0.00      | 0%       |
| Vixeny (Bun)                                                                         | 0.00      | 0.00     | 0.00      | 0%       |
| ![Chart](https://quickchart.io/chart/render/zf-1770972b-d3d4-46b9-9756-dc4681776d06) |           |          |           |          |

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
| 19086.83 | 3129.40 | 40744.82 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 15321.26 | 17020.89 | 20383.98 | 21015.77 | 21526.41 | 21908.88 | 22989.21 |
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
| 64922.51 | 4308.70 | 71563.27 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 62845.95 | 64711.45 | 65628.19 | 66593.95 | 67560.00 | 68125.80 | 69100.55 |
| **Latency** | 672µs    | 705µs    | 774µs    | 814µs    | 843µs    | 872µs    | 1ms      |

### [Aqua](#aqua)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 35783.34 | 4214.98 | 42768.53 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 32712.26 | 34509.46 | 36964.64 | 38001.97 | 38915.43 | 39782.01 | 40722.04 |
| **Latency** | 854µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Bun](#bun)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 118540.69 | 13354.75 | 148942.66 |     |

| **Stat**    | 10        | 25        | 50        | 75        | 90        | 95        | 99        |
| ----------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 101003.31 | 108024.08 | 118542.19 | 128634.96 | 136776.25 | 140530.88 | 144440.60 |
| **Latency** | 254µs     | 318µs     | 397µs     | 490µs     | 627µs     | 713µs     | 928µs     |

### [Cheetah](#cheetah)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 58293.10 | 3792.77 | 62199.77 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 57441.92 | 58414.55 | 58972.40 | 59641.02 | 60059.39 | 60426.27 | 60891.93 |
| **Latency** | 749µs    | 779µs    | 869µs    | 904µs    | 931µs    | 972µs    | 1ms      |

### [Danet (Oak)](#danet-oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 43379.71 | 3436.08 | 46686.34 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 42338.07 | 43309.17 | 44116.33 | 44636.79 | 45368.43 | 45647.79 | 46301.83 |
| **Latency** | 992µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Danet V2 (Hono)](#danet-v2-hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 48332.75 | 3951.82 | 57338.48 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 47706.71 | 48639.47 | 49109.73 | 49702.01 | 50081.43 | 50356.76 | 50873.27 |
| **Latency** | 896µs    | 926µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Deno](#deno)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 86278.98 | 4624.46 | 103965.75 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 82995.05 | 84724.61 | 86251.55 | 88090.87 | 90372.98 | 92064.47 | 95998.58 |
| **Latency** | 485µs    | 534µs    | 581µs    | 621µs    | 659µs    | 703µs    | 807µs    |

### [Deso](#deso)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 71852.23 | 3705.32 | 83303.46 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 70011.85 | 71243.31 | 72320.67 | 73311.74 | 74227.59 | 74808.09 | 76424.50 |
| **Latency** | 638µs    | 662µs    | 689µs    | 716µs    | 745µs    | 788µs    | 883µs    |

### [Dinatra](#dinatra)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 23072.45 | 4448.92 | 43368.07 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 16930.31 | 20368.05 | 25245.82 | 26016.71 | 26439.60 | 26711.41 | 27206.91 |
| **Latency** | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 3ms      | 4ms      |

### [Elysia](#elysia)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 96717.96 | 9543.92 | 139443.72 |     |

| **Stat**    | 10       | 25       | 50       | 75        | 90        | 95        | 99        |
| ----------- | -------- | -------- | -------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 86421.75 | 89720.40 | 95226.87 | 102599.02 | 109886.15 | 114453.36 | 122599.50 |
| **Latency** | 306µs    | 391µs    | 511µs    | 591µs     | 710µs     | 869µs     | 1ms       |

### [Express](#express)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 8881.90  | 1659.12 | 11815.94 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90       | 95       | 99       |
| ----------- | ------- | ------- | ------- | ------- | -------- | -------- | -------- |
| **Req/Sec** | 6623.18 | 8397.19 | 9146.91 | 9577.35 | 11030.43 | 11323.07 | 11642.97 |
| **Latency** | 4ms     | 5ms     | 5ms     | 5ms     | 7ms      | 7ms      | 9ms      |

### [Express (Deno)](#express-deno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 14504.10 | 2827.08 | 18036.06 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 10047.90 | 12702.71 | 15815.96 | 16631.34 | 16873.72 | 17029.70 | 17342.00 |
| **Latency** | 2ms      | 2ms      | 3ms      | 3ms      | 4ms      | 5ms      | 6ms      |

### [Fast](#fast)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 77911.33 | 4303.31 | 95804.00 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 75336.17 | 76852.66 | 78312.71 | 79700.76 | 81205.38 | 82153.75 | 84498.21 |
| **Latency** | 557µs    | 593µs    | 643µs    | 681µs    | 712µs    | 745µs    | 849µs    |

### [Fastify](#fastify)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 34016.42 | 3566.77 | 36978.82 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 33066.66 | 33849.91 | 34634.10 | 35295.58 | 35732.79 | 35975.35 | 36447.20 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Fastro](#fastro)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 75534.60 | 6639.93 | 102354.99 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 71918.69 | 73205.59 | 74663.16 | 76945.89 | 83616.43 | 87011.13 | 93255.55 |
| **Latency** | 544µs    | 614µs    | 671µs    | 716µs    | 745µs    | 769µs    | 884µs    |

### [Hono](#hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 75931.95 | 4077.01 | 93462.00 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 74094.66 | 75187.49 | 76350.39 | 77367.97 | 78470.66 | 79318.96 | 81171.98 |
| **Latency** | 575µs    | 608µs    | 660µs    | 696µs    | 725µs    | 759µs    | 861µs    |

### [http](#http)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 51333.95 | 5199.08 | 61996.84 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 45529.76 | 51317.28 | 52819.20 | 53904.95 | 55030.69 | 55536.19 | 56543.49 |
| **Latency** | 664µs    | 921µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Hyper Express](#hyper-express)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 104815.85 | 11111.01 | 140783.69 |     |

| **Stat**    | 10       | 25       | 50        | 75        | 90        | 95        | 99        |
| ----------- | -------- | -------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 92096.78 | 96510.52 | 103929.99 | 111774.58 | 120054.46 | 125085.95 | 133404.71 |
| **Latency** | 277µs    | 355µs    | 468µs     | 563µs     | 664µs     | 775µs     | 1ms       |

### [Little](#little)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 35063.24 | 5465.57 | 46205.74 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 31301.09 | 33400.75 | 36484.38 | 38253.20 | 39055.95 | 39855.24 | 41013.99 |
| **Latency** | 872µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      |

### [Megalo](#megalo)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 70774.09 | 4354.86 | 78233.41 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 68890.69 | 70146.76 | 71513.16 | 72706.25 | 73639.35 | 74045.26 | 74920.36 |
| **Latency** | 618µs    | 651µs    | 706µs    | 745µs    | 774µs    | 800µs    | 932µs    |

### [NHttp](#nhttp)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 78731.87 | 4109.14 | 93015.42 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 75994.48 | 77513.63 | 79212.07 | 80605.29 | 81981.78 | 83046.51 | 85851.34 |
| **Latency** | 546µs    | 586µs    | 636µs    | 675µs    | 711µs    | 750µs    | 850µs    |

### [Node](#node)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 37192.98 | 3183.76 | 39714.63 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 36220.23 | 36960.75 | 37647.27 | 38233.11 | 38719.64 | 39043.60 | 39462.22 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Oak](#oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 40905.25 | 4428.16 | 44290.82 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 40006.08 | 41119.87 | 42115.47 | 42503.79 | 43127.75 | 43385.85 | 43768.35 |
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
| 61454.92 | 3832.57 | 64885.05 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 59812.88 | 61230.02 | 62136.18 | 62982.40 | 63668.84 | 64026.64 | 64530.87 |
| **Latency** | 712µs    | 742µs    | 821µs    | 859µs    | 888µs    | 917µs    | 1ms      |

### [Router](#router)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 49171.47 | 5426.05 | 64119.52 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 43811.55 | 48423.66 | 50957.62 | 51923.60 | 52618.45 | 53162.70 | 54424.71 |
| **Latency** | 679µs    | 951µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Stric](#stric)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 117402.06 | 15611.71 | 151247.36 |     |

| **Stat**    | 10        | 25        | 50        | 75        | 90        | 95        | 99        |
| ----------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 100325.33 | 105418.16 | 115953.88 | 128735.32 | 138893.26 | 143608.80 | 148730.33 |
| **Latency** | 260µs     | 325µs     | 402µs     | 482µs     | 627µs     | 728µs     | 921µs     |

### [Servest](#servest)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 8189.84  | 2310.99 | 16596.07 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90       | 95       | 99       |
| ----------- | ------- | ------- | ------- | ------- | -------- | -------- | -------- |
| **Req/Sec** | 5312.17 | 6945.97 | 8514.99 | 9812.62 | 10657.08 | 11103.83 | 12625.93 |
| **Latency** | 4ms     | 5ms     | 5ms     | 6ms     | 8ms      | 9ms      | 15ms     |

### [Vixeny (Bun)](#vixeny-bun)

| **Stat** | Mean | Stddev | Max |
| -------- | ---- | ------ | --- |
| 0.00     | 0.00 | 0.00   |     |

| **Stat**    | 10   | 25   | 50   | 75   | 90   | 95   | 99   |
| ----------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| **Req/Sec** | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |
| **Latency** | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  |

### [Vixeny (Deno)](#vixeny-deno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 78964.32 | 3992.10 | 91382.92 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 76406.36 | 77715.72 | 79266.66 | 80815.23 | 82051.82 | 82883.38 | 87461.25 |
| **Latency** | 547µs    | 586µs    | 635µs    | 674µs    | 704µs    | 736µs    | 841µs    |

---

<p align="center">Generated 2025-12-19T00:34:01.999Z</p>
