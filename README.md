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
| Stric                                                                                | 119403.08 | 12341.72 | 148501.58 | 100%     |
| Bun                                                                                  | 117403.26 | 11912.16 | 146421.22 | 98%      |
| Hyper Express                                                                        | 106634.46 | 12826.14 | 137926.05 | 89%      |
| Elysia                                                                               | 100219.12 | 11409.38 | 137803.78 | 84%      |
| Deno                                                                                 | 86776.43  | 6590.73  | 118783.31 | 73%      |
| NHttp                                                                                | 80179.20  | 5291.84  | 99577.60  | 67%      |
| Vixeny (Deno)                                                                        | 78519.74  | 5159.79  | 98482.78  | 66%      |
| Fast                                                                                 | 78460.69  | 5678.63  | 104248.53 | 66%      |
| Fastro                                                                               | 77326.09  | 10100.24 | 107854.44 | 65%      |
| Hono                                                                                 | 76195.19  | 5182.46  | 97801.41  | 64%      |
| Deso                                                                                 | 71329.95  | 4181.05  | 90055.31  | 60%      |
| Megalo                                                                               | 71297.58  | 4311.50  | 85014.41  | 60%      |
| Alosaur                                                                              | 62173.13  | 4360.83  | 68390.17  | 52%      |
| Reno                                                                                 | 59675.74  | 3356.62  | 63482.67  | 50%      |
| Cheetah                                                                              | 57924.78  | 3855.73  | 62144.34  | 49%      |
| http                                                                                 | 50071.98  | 6116.17  | 59503.63  | 42%      |
| Router                                                                               | 47948.42  | 5499.99  | 56488.80  | 40%      |
| Danet V2 (Hono)                                                                      | 46199.40  | 3558.30  | 49583.94  | 39%      |
| Danet (Oak)                                                                          | 41422.92  | 3446.71  | 44397.27  | 35%      |
| Oak                                                                                  | 38814.00  | 4196.40  | 44145.45  | 33%      |
| Node                                                                                 | 37182.03  | 3252.36  | 41840.13  | 31%      |
| Aqua                                                                                 | 34338.72  | 4555.88  | 43354.10  | 29%      |
| Little                                                                               | 33538.92  | 5591.87  | 41090.11  | 28%      |
| Fastify                                                                              | 32728.25  | 3509.14  | 40977.61  | 27%      |
| Dinatra                                                                              | 20934.09  | 3958.03  | 27671.82  | 18%      |
| Abc                                                                                  | 18391.66  | 2819.80  | 28434.37  | 15%      |
| Express (Deno)                                                                       | 14515.26  | 2505.05  | 17755.98  | 12%      |
| Express                                                                              | 8992.71   | 1687.42  | 11701.96  | 8%       |
| Servest                                                                              | 7827.54   | 2175.00  | 15275.15  | 7%       |
| Acorn                                                                                | 0.00      | 0.00     | 0.00      | 0%       |
| Opine                                                                                | 0.00      | 0.00     | 0.00      | 0%       |
| Peko                                                                                 | 0.00      | 0.00     | 0.00      | 0%       |
| Vixeny (Bun)                                                                         | 0.00      | 0.00     | 0.00      | 0%       |
| ![Chart](https://quickchart.io/chart/render/zf-b69798ad-d8c9-4816-b3e7-9a4d2ca5f68a) |           |          |           |          |

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
| 18391.66 | 2819.80 | 28434.37 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 15119.86 | 16603.04 | 19561.66 | 20162.90 | 20629.78 | 20944.73 | 21541.04 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 3ms      | 4ms      | 4ms      |

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
| 62173.13 | 4360.83 | 68390.17 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 60403.17 | 61769.11 | 62952.46 | 63931.14 | 64670.79 | 65119.78 | 65944.95 |
| **Latency** | 702µs    | 737µs    | 807µs    | 849µs    | 879µs    | 908µs    | 1ms      |

### [Aqua](#aqua)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 34338.72 | 4555.88 | 43354.10 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 29549.23 | 32610.81 | 35771.23 | 36592.21 | 37873.58 | 39119.55 | 41621.61 |
| **Latency** | 920µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Bun](#bun)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 117403.26 | 11912.16 | 146421.22 |     |

| **Stat**    | 10        | 25        | 50        | 75        | 90        | 95        | 99        |
| ----------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 101337.25 | 108128.44 | 118026.25 | 126936.13 | 132835.95 | 135509.91 | 138308.98 |
| **Latency** | 256µs     | 322µs     | 404µs     | 492µs     | 630µs     | 714µs     | 924µs     |

### [Cheetah](#cheetah)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 57924.78 | 3855.73 | 62144.34 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 57243.70 | 57808.66 | 58587.24 | 59412.51 | 59860.47 | 60115.67 | 60733.47 |
| **Latency** | 752µs    | 783µs    | 874µs    | 910µs    | 939µs    | 992µs    | 1ms      |

### [Danet (Oak)](#danet-oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 41422.92 | 3446.71 | 44397.27 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 40703.59 | 41417.00 | 42178.54 | 42718.19 | 43254.52 | 43451.87 | 43932.06 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Danet V2 (Hono)](#danet-v2-hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 46199.40 | 3558.30 | 49583.94 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 45159.98 | 46271.57 | 46914.72 | 47602.41 | 48018.06 | 48311.85 | 48802.84 |
| **Latency** | 935µs    | 968µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Deno](#deno)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 86776.43 | 6590.73 | 118783.31 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 81423.45 | 83518.07 | 85930.57 | 89343.83 | 93981.17 | 98479.60 | 106684.56 |
| **Latency** | 440µs    | 524µs    | 581µs    | 629µs    | 676µs    | 729µs    | 841µs     |

### [Deso](#deso)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 71329.95 | 4181.05 | 90055.31 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 69414.76 | 70345.78 | 71460.43 | 72713.45 | 73988.64 | 75031.48 | 81549.55 |
| **Latency** | 644µs    | 668µs    | 694µs    | 720µs    | 748µs    | 796µs    | 918µs    |

### [Dinatra](#dinatra)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 20934.09 | 3958.03 | 27671.82 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 15700.03 | 19121.62 | 22021.16 | 23527.50 | 24613.68 | 25078.16 | 25746.40 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 3ms      | 3ms      | 4ms      |

### [Elysia](#elysia)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 100219.12 | 11409.38 | 137803.78 |     |

| **Stat**    | 10       | 25       | 50       | 75        | 90        | 95        | 99        |
| ----------- | -------- | -------- | -------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 88416.01 | 91822.83 | 97543.55 | 106771.85 | 117301.88 | 122713.29 | 131701.91 |
| **Latency** | 302µs    | 384µs    | 479µs    | 573µs     | 705µs     | 851µs     | 1ms       |

### [Express](#express)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 8992.71  | 1687.42 | 11701.96 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90       | 95       | 99       |
| ----------- | ------- | ------- | ------- | ------- | -------- | -------- | -------- |
| **Req/Sec** | 6460.00 | 8515.94 | 9262.10 | 9888.15 | 11051.16 | 11394.38 | 11583.12 |
| **Latency** | 4ms     | 4ms     | 5ms     | 5ms     | 7ms      | 8ms      | 9ms      |

### [Express (Deno)](#express-deno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 14515.26 | 2505.05 | 17755.98 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 10652.67 | 13410.02 | 15637.71 | 16174.33 | 16583.84 | 16782.62 | 17218.42 |
| **Latency** | 2ms      | 2ms      | 3ms      | 3ms      | 4ms      | 5ms      | 6ms      |

### [Fast](#fast)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 78460.69 | 5678.63 | 104248.53 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 74829.09 | 76224.57 | 77860.65 | 80108.49 | 84547.08 | 87918.27 | 94131.84 |
| **Latency** | 530µs    | 591µs    | 644µs    | 686µs    | 717µs    | 748µs    | 879µs    |

### [Fastify](#fastify)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 32728.25 | 3509.14 | 40977.61 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 31224.50 | 32304.47 | 33255.26 | 33931.37 | 34394.03 | 34726.21 | 38606.43 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Fastro](#fastro)

| **Stat** | Mean     | Stddev    | Max |
| -------- | -------- | --------- | --- |
| 77326.09 | 10100.24 | 107854.44 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 70172.90 | 72686.81 | 75180.69 | 82362.54 | 89047.03 | 94847.83 | 104049.87 |
| **Latency** | 460µs    | 572µs    | 658µs    | 720µs    | 757µs    | 795µs    | 945µs     |

### [Hono](#hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 76195.19 | 5182.46 | 97801.41 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 73285.23 | 74750.57 | 76125.65 | 77510.15 | 80514.56 | 84058.48 | 89332.52 |
| **Latency** | 563µs    | 606µs    | 659µs    | 699µs    | 732µs    | 775µs    | 895µs    |

### [http](#http)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 50071.98 | 6116.17 | 59503.63 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 41926.19 | 50670.86 | 52143.26 | 52960.03 | 53955.85 | 54579.26 | 55787.91 |
| **Latency** | 674µs    | 933µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Hyper Express](#hyper-express)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 106634.46 | 12826.14 | 137926.05 |     |

| **Stat**    | 10       | 25       | 50        | 75        | 90        | 95        | 99        |
| ----------- | -------- | -------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 91648.41 | 96702.19 | 105549.76 | 115217.26 | 125026.17 | 130430.59 | 135282.33 |
| **Latency** | 282µs    | 355µs    | 443µs     | 556µs     | 670µs     | 774µs     | 1ms       |

### [Little](#little)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 33538.92 | 5591.87 | 41090.11 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 29119.61 | 30925.61 | 35732.53 | 36734.50 | 37791.35 | 38550.93 | 39750.83 |
| **Latency** | 897µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      |

### [Megalo](#megalo)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 71297.58 | 4311.50 | 85014.41 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 69552.25 | 70595.01 | 71698.09 | 72771.18 | 73885.22 | 75000.06 | 78500.22 |
| **Latency** | 614µs    | 647µs    | 702µs    | 743µs    | 768µs    | 792µs    | 946µs    |

### [NHttp](#nhttp)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 80179.20 | 5291.84 | 99577.60 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 76699.91 | 77992.34 | 79612.64 | 82097.29 | 85652.86 | 88805.11 | 93515.53 |
| **Latency** | 515µs    | 577µs    | 629µs    | 672µs    | 705µs    | 740µs    | 861µs    |

### [Node](#node)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 37182.03 | 3252.36 | 41840.13 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 36303.11 | 37045.62 | 37644.51 | 38237.53 | 38662.17 | 38955.05 | 39818.74 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Oak](#oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 38814.00 | 4196.40 | 44145.45 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 37325.80 | 38781.47 | 40076.03 | 40549.68 | 41163.16 | 41369.02 | 41853.64 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

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
| 59675.74 | 3356.62 | 63482.67 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 58526.81 | 59608.59 | 60334.17 | 60926.61 | 61399.31 | 61722.78 | 62253.39 |
| **Latency** | 735µs    | 765µs    | 849µs    | 885µs    | 911µs    | 942µs    | 1ms      |

### [Router](#router)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 47948.42 | 5499.99 | 56488.80 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 42036.46 | 47803.78 | 49728.27 | 50641.05 | 51555.50 | 51978.59 | 52853.13 |
| **Latency** | 692µs    | 990µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Stric](#stric)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 119403.08 | 12341.72 | 148501.58 |     |

| **Stat**    | 10        | 25        | 50        | 75        | 90        | 95        | 99        |
| ----------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 103332.65 | 109753.45 | 119242.75 | 128722.82 | 135867.50 | 139691.86 | 144907.30 |
| **Latency** | 250µs     | 315µs     | 396µs     | 486µs     | 623µs     | 706µs     | 916µs     |

### [Servest](#servest)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 7827.54  | 2175.00 | 15275.15 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90       | 95       | 99       |
| ----------- | ------- | ------- | ------- | ------- | -------- | -------- | -------- |
| **Req/Sec** | 5084.65 | 6641.36 | 8162.75 | 9318.93 | 10086.31 | 10511.62 | 11824.55 |
| **Latency** | 5ms     | 5ms     | 6ms     | 6ms     | 9ms      | 10ms     | 17ms     |

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
| 78519.74 | 5159.79 | 98482.78 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 75433.41 | 76929.42 | 78460.37 | 80143.08 | 83046.34 | 85535.01 | 90433.03 |
| **Latency** | 546µs    | 589µs    | 639µs    | 679µs    | 709µs    | 741µs    | 870µs    |

---

<p align="center">Generated 2026-01-05T00:36:36.180Z</p>
