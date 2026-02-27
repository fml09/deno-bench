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
| Bun                                                                                  | 126394.27 | 13819.62 | 150723.62 | 100%     |
| Hyper Express                                                                        | 111944.59 | 14507.32 | 147479.82 | 89%      |
| Stric                                                                                | 111898.48 | 15717.46 | 148501.37 | 89%      |
| Elysia                                                                               | 102811.41 | 11447.38 | 141838.14 | 81%      |
| Deno                                                                                 | 87650.76  | 6033.71  | 115323.03 | 69%      |
| Fastro                                                                               | 80474.02  | 4350.20  | 94351.11  | 64%      |
| Vixeny (Deno)                                                                        | 79634.96  | 5730.85  | 101663.23 | 63%      |
| NHttp                                                                                | 79086.51  | 3928.82  | 90588.82  | 63%      |
| Fast                                                                                 | 78936.79  | 3803.39  | 92818.60  | 62%      |
| Hono                                                                                 | 76338.62  | 4020.41  | 89410.98  | 60%      |
| Deso                                                                                 | 76305.53  | 9295.94  | 111633.13 | 60%      |
| Megalo                                                                               | 71600.25  | 3653.90  | 85826.48  | 57%      |
| Alosaur                                                                              | 66289.47  | 3749.39  | 70565.58  | 52%      |
| Reno                                                                                 | 61929.68  | 3188.61  | 66320.98  | 49%      |
| Cheetah                                                                              | 59355.76  | 3735.25  | 65220.80  | 47%      |
| http                                                                                 | 52489.90  | 5423.52  | 58614.60  | 42%      |
| Router                                                                               | 49427.79  | 5150.82  | 55718.52  | 39%      |
| Danet V2 (Hono)                                                                      | 49172.87  | 3878.22  | 54655.22  | 39%      |
| Danet (Oak)                                                                          | 45327.14  | 3370.21  | 48008.88  | 36%      |
| Oak                                                                                  | 41755.33  | 3859.61  | 44743.83  | 33%      |
| Aqua                                                                                 | 37507.61  | 3698.77  | 42609.28  | 30%      |
| Little                                                                               | 37064.73  | 4119.77  | 42577.48  | 29%      |
| Node                                                                                 | 36841.20  | 3151.99  | 43269.12  | 29%      |
| Fastify                                                                              | 32342.86  | 3036.94  | 36610.40  | 26%      |
| Dinatra                                                                              | 23106.14  | 3629.65  | 29177.48  | 18%      |
| Abc                                                                                  | 19285.82  | 3591.82  | 30937.66  | 15%      |
| Express (Deno)                                                                       | 14693.57  | 2673.66  | 17972.78  | 12%      |
| Servest                                                                              | 8976.54   | 2498.61  | 17307.63  | 7%       |
| Express                                                                              | 8736.45   | 1461.45  | 11954.40  | 7%       |
| Acorn                                                                                | 0.00      | 0.00     | 0.00      | 0%       |
| Opine                                                                                | 0.00      | 0.00     | 0.00      | 0%       |
| Peko                                                                                 | 0.00      | 0.00     | 0.00      | 0%       |
| Vixeny (Bun)                                                                         | 0.00      | 0.00     | 0.00      | 0%       |
| ![Chart](https://quickchart.io/chart/render/zf-ab58855f-dee6-4d4d-ad8f-f3fdee3d2249) |           |          |           |          |

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
| 19285.82 | 3591.82 | 30937.66 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 15714.25 | 17647.09 | 20266.69 | 20885.12 | 21641.09 | 22125.32 | 29111.02 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 2ms      | 3ms      | 4ms      |

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
| 66289.47 | 3749.39 | 70565.58 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 65115.76 | 66163.68 | 67004.09 | 67672.54 | 68360.17 | 68624.72 | 69391.97 |
| **Latency** | 663µs    | 693µs    | 760µs    | 798µs    | 823µs    | 846µs    | 973µs    |

### [Aqua](#aqua)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 37507.61 | 3698.77 | 42609.28 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 34907.25 | 36209.53 | 38605.29 | 39280.41 | 40048.01 | 40920.16 | 41845.11 |
| **Latency** | 832µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Bun](#bun)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 126394.27 | 13819.62 | 150723.62 |     |

| **Stat**    | 10        | 25        | 50        | 75        | 90        | 95        | 99        |
| ----------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 107705.50 | 116629.07 | 127711.30 | 137756.16 | 144634.08 | 146722.52 | 148798.25 |
| **Latency** | 240µs     | 302µs     | 378µs     | 457µs     | 571µs     | 658µs     | 870µs     |

### [Cheetah](#cheetah)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 59355.76 | 3735.25 | 65220.80 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 58210.46 | 58970.17 | 60000.78 | 60796.20 | 61316.06 | 61621.67 | 62013.08 |
| **Latency** | 738µs    | 768µs    | 852µs    | 891µs    | 919µs    | 948µs    | 1ms      |

### [Danet (Oak)](#danet-oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 45327.14 | 3370.21 | 48008.88 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 44214.43 | 45378.88 | 46165.50 | 46602.93 | 46943.39 | 47217.39 | 47542.32 |
| **Latency** | 958µs    | 990µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Danet V2 (Hono)](#danet-v2-hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 49172.87 | 3878.22 | 54655.22 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 47829.70 | 49509.67 | 50014.45 | 50615.97 | 51016.52 | 51225.62 | 51785.04 |
| **Latency** | 884µs    | 915µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Deno](#deno)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 87650.76 | 6033.71 | 115323.03 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 83306.16 | 84758.87 | 86716.41 | 89668.35 | 94235.26 | 98800.56 | 105585.31 |
| **Latency** | 452µs    | 526µs    | 577µs    | 620µs    | 659µs    | 699µs    | 781µs     |

### [Deso](#deso)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 76305.53 | 9295.94 | 111633.13 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 69530.11 | 71414.12 | 73368.80 | 78812.54 | 89712.52 | 97026.84 | 106386.82 |
| **Latency** | 462µs    | 617µs    | 679µs    | 715µs    | 753µs    | 794µs    | 910µs     |

### [Dinatra](#dinatra)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 23106.14 | 3629.65 | 29177.48 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 18535.98 | 20442.28 | 24866.56 | 25406.60 | 25735.55 | 26002.86 | 26522.43 |
| **Latency** | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 3ms      | 4ms      |

### [Elysia](#elysia)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 102811.41 | 11447.38 | 141838.14 |     |

| **Stat**    | 10       | 25       | 50        | 75        | 90        | 95        | 99        |
| ----------- | -------- | -------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 89621.02 | 94537.18 | 101024.63 | 109426.50 | 120073.04 | 124697.53 | 133199.19 |
| **Latency** | 278µs    | 362µs    | 470µs     | 579µs     | 682µs     | 805µs     | 1ms       |

### [Express](#express)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 8736.45  | 1461.45 | 11954.40 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90       | 95       | 99       |
| ----------- | ------- | ------- | ------- | ------- | -------- | -------- | -------- |
| **Req/Sec** | 6866.51 | 8415.01 | 8976.21 | 9216.41 | 10365.62 | 11414.58 | 11698.15 |
| **Latency** | 4ms     | 5ms     | 5ms     | 5ms     | 6ms      | 7ms      | 9ms      |

### [Express (Deno)](#express-deno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 14693.57 | 2673.66 | 17972.78 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 10732.93 | 12786.26 | 15853.67 | 16824.37 | 16974.14 | 17053.64 | 17204.35 |
| **Latency** | 2ms      | 2ms      | 3ms      | 3ms      | 4ms      | 5ms      | 6ms      |

### [Fast](#fast)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 78936.79 | 3803.39 | 92818.60 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 77010.19 | 77917.08 | 78892.00 | 80308.41 | 81749.76 | 83644.83 | 87353.59 |
| **Latency** | 553µs    | 589µs    | 638µs    | 675µs    | 701µs    | 721µs    | 796µs    |

### [Fastify](#fastify)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 32342.86 | 3036.94 | 36610.40 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 31857.61 | 32356.65 | 32813.09 | 33205.93 | 33516.74 | 33670.52 | 34253.79 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Fastro](#fastro)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 80474.02 | 4350.20 | 94351.11 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 78359.81 | 79318.83 | 80400.60 | 81810.89 | 84187.63 | 86002.86 | 90206.83 |
| **Latency** | 538µs    | 577µs    | 626µs    | 664µs    | 690µs    | 714µs    | 791µs    |

### [Hono](#hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 76338.62 | 4020.41 | 89410.98 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 74906.52 | 75786.29 | 76627.09 | 77544.94 | 78535.49 | 79652.12 | 82111.06 |
| **Latency** | 576µs    | 607µs    | 658µs    | 693µs    | 718µs    | 740µs    | 819µs    |

### [http](#http)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 52489.90 | 5423.52 | 58614.60 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 46529.63 | 52144.11 | 54135.19 | 55260.41 | 55969.99 | 56536.14 | 57533.42 |
| **Latency** | 653µs    | 896µs    | 977µs    | 1ms      | 1ms      | 1ms      | 2ms      |

### [Hyper Express](#hyper-express)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 111944.59 | 14507.32 | 147479.82 |     |

| **Stat**    | 10       | 25        | 50        | 75        | 90        | 95        | 99        |
| ----------- | -------- | --------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 95179.34 | 100377.90 | 110141.88 | 122652.70 | 132594.90 | 137826.31 | 143400.17 |
| **Latency** | 261µs    | 332µs     | 423µs     | 541µs     | 632µs     | 720µs     | 983µs     |

### [Little](#little)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 37064.73 | 4119.77 | 42577.48 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 34697.60 | 36105.35 | 38126.14 | 39072.81 | 39715.73 | 40654.64 | 41797.57 |
| **Latency** | 855µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Megalo](#megalo)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 71600.25 | 3653.90 | 85826.48 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 69828.84 | 70985.98 | 71952.85 | 72877.10 | 73766.69 | 74454.72 | 76191.59 |
| **Latency** | 615µs    | 646µs    | 701µs    | 740µs    | 766µs    | 784µs    | 872µs    |

### [NHttp](#nhttp)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 79086.51 | 3928.82 | 90588.82 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 76830.90 | 77922.01 | 79217.51 | 80417.19 | 82062.27 | 83650.05 | 87213.11 |
| **Latency** | 551µs    | 587µs    | 636µs    | 674µs    | 699µs    | 720µs    | 795µs    |

### [Node](#node)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 36841.20 | 3151.99 | 43269.12 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 36065.43 | 36721.56 | 37260.10 | 37762.80 | 38261.16 | 38520.44 | 39236.26 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Oak](#oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 41755.33 | 3859.61 | 44743.83 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 40411.88 | 42003.97 | 42632.31 | 43253.06 | 43561.24 | 43791.75 | 44235.72 |
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
| 61929.68 | 3188.61 | 66320.98 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 61078.13 | 61834.90 | 62501.66 | 63015.66 | 63420.13 | 63785.30 | 64314.39 |
| **Latency** | 711µs    | 740µs    | 819µs    | 855µs    | 879µs    | 900µs    | 1ms      |

### [Router](#router)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 49427.79 | 5150.82 | 55718.52 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 44416.59 | 49424.76 | 51226.17 | 51953.29 | 52431.94 | 52775.49 | 53690.05 |
| **Latency** | 684µs    | 966µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Stric](#stric)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 111898.48 | 15717.46 | 148501.37 |     |

| **Stat**    | 10       | 25       | 50        | 75        | 90        | 95        | 99        |
| ----------- | -------- | -------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 92868.06 | 98508.57 | 111101.28 | 124133.80 | 134449.08 | 139117.75 | 144689.91 |
| **Latency** | 270µs    | 341µs    | 422µs     | 508µs     | 654µs     | 769µs     | 995µs     |

### [Servest](#servest)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 8976.54  | 2498.61 | 17307.63 |     |

| **Stat**    | 10      | 25      | 50      | 75       | 90       | 95       | 99       |
| ----------- | ------- | ------- | ------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 5905.10 | 7328.93 | 9470.17 | 10274.61 | 11867.52 | 12863.69 | 13575.62 |
| **Latency** | 3ms     | 4ms     | 5ms     | 6ms      | 7ms      | 8ms      | 13ms     |

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
| 79634.96 | 5730.85 | 101663.23 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 76019.15 | 77317.51 | 78619.65 | 81389.21 | 86102.13 | 90039.37 | 96504.45 |
| **Latency** | 512µs    | 583µs    | 636µs    | 681µs    | 710µs    | 737µs    | 831µs    |

---

<p align="center">Generated 2026-02-27T00:40:16.544Z</p>
