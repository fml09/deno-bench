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

| Framework                                                                            | Mean     | Stddev   | Max       | Relative |
| ------------------------------------------------------------------------------------ | -------- | -------- | --------- | -------- |
| Stric                                                                                | 87157.59 | 10381.12 | 105032.22 | 100%     |
| Hyper Express                                                                        | 77611.97 | 12049.24 | 97786.91  | 89%      |
| Elysia                                                                               | 71476.25 | 11496.07 | 99012.71  | 82%      |
| Deno                                                                                 | 59052.08 | 6900.78  | 90854.96  | 68%      |
| Fastro                                                                               | 57570.65 | 8802.57  | 78040.55  | 66%      |
| NHttp                                                                                | 52702.92 | 3816.19  | 73541.78  | 60%      |
| Vixeny (Deno)                                                                        | 52053.94 | 3755.82  | 78747.10  | 60%      |
| Fast                                                                                 | 51027.96 | 2797.92  | 66309.81  | 59%      |
| Hono                                                                                 | 50698.27 | 3120.31  | 67633.20  | 58%      |
| Megalo                                                                               | 48518.74 | 2618.35  | 60977.93  | 56%      |
| Deso                                                                                 | 47701.94 | 2454.67  | 65246.37  | 55%      |
| http                                                                                 | 44756.33 | 5209.61  | 51290.51  | 51%      |
| Alosaur                                                                              | 44702.33 | 2746.01  | 54820.52  | 51%      |
| Router                                                                               | 42623.52 | 4612.14  | 51776.19  | 49%      |
| Cheetah                                                                              | 41291.15 | 2774.74  | 50018.49  | 47%      |
| Reno                                                                                 | 41028.09 | 2697.90  | 54901.18  | 47%      |
| Danet V2 (Hono)                                                                      | 36561.12 | 2381.14  | 39147.88  | 42%      |
| Danet (Oak)                                                                          | 34246.71 | 2427.88  | 38012.29  | 39%      |
| Little                                                                               | 33023.09 | 3875.51  | 37998.85  | 38%      |
| Aqua                                                                                 | 32282.52 | 3573.64  | 40300.54  | 37%      |
| Oak                                                                                  | 31261.17 | 2892.69  | 35600.95  | 36%      |
| Node                                                                                 | 19338.61 | 1863.93  | 22911.54  | 22%      |
| Fastify                                                                              | 17841.34 | 1887.95  | 19812.81  | 20%      |
| Dinatra                                                                              | 16264.95 | 2380.44  | 21049.42  | 19%      |
| Express (Deno)                                                                       | 14240.56 | 1975.53  | 16257.04  | 16%      |
| Abc                                                                                  | 14011.76 | 2142.89  | 23272.97  | 16%      |
| Express                                                                              | 6478.00  | 928.75   | 8268.41   | 7%       |
| Servest                                                                              | 6389.67  | 1591.95  | 11244.07  | 7%       |
| Acorn                                                                                | 0.00     | 0.00     | 0.00      | 0%       |
| Bun                                                                                  | 0.00     | 0.00     | 0.00      | 0%       |
| Opine                                                                                | 0.00     | 0.00     | 0.00      | 0%       |
| Peko                                                                                 | 0.00     | 0.00     | 0.00      | 0%       |
| Vixeny (Bun)                                                                         | 0.00     | 0.00     | 0.00      | 0%       |
| ![Chart](https://quickchart.io/chart/render/sf-f4d7661d-bbe7-4404-9d75-99f7e8fcb509) |          |          |           |          |

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
| 14011.76 | 2142.89 | 23272.97 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 12010.16 | 13341.91 | 14713.24 | 15175.25 | 15467.55 | 15659.07 | 16901.33 |
| **Latency** | 3ms      | 3ms      | 3ms      | 3ms      | 4ms      | 4ms      | 8ms      |

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
| 44702.33 | 2746.01 | 54820.52 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 42408.41 | 43945.23 | 45023.89 | 45991.55 | 47105.33 | 47642.13 | 49582.68 |
| **Latency** | 981µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Aqua](#aqua)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 32282.52 | 3573.64 | 40300.54 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 28160.40 | 31782.83 | 33176.60 | 34078.96 | 35052.61 | 35615.22 | 36402.89 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 3ms      |

### [Bun](#bun)

| **Stat** | Mean | Stddev | Max |
| -------- | ---- | ------ | --- |
| 0.00     | 0.00 | 0.00   |     |

| **Stat**    | 10   | 25   | 50   | 75   | 90   | 95   | 99   |
| ----------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| **Req/Sec** | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |
| **Latency** | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  |

### [Cheetah](#cheetah)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 41291.15 | 2774.74 | 50018.49 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 38753.24 | 40924.09 | 41837.45 | 42433.47 | 43394.94 | 43982.12 | 45444.40 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Danet (Oak)](#danet-oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 34246.71 | 2427.88 | 38012.29 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 33419.40 | 34227.34 | 34601.48 | 35155.30 | 35505.05 | 35701.80 | 36261.07 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Danet V2 (Hono)](#danet-v2-hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 36561.12 | 2381.14 | 39147.88 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 36079.63 | 36530.19 | 36850.27 | 37396.81 | 37698.07 | 37875.30 | 38272.74 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Deno](#deno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 59052.08 | 6900.78 | 90854.96 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 53526.50 | 54510.84 | 56339.60 | 62937.72 | 69387.09 | 73253.25 | 78636.05 |
| **Latency** | 583µs    | 745µs    | 871µs    | 955µs    | 1ms      | 1ms      | 1ms      |

### [Deso](#deso)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 47701.94 | 2454.67 | 65246.37 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 46191.37 | 46982.65 | 47632.37 | 48350.50 | 49337.96 | 50676.96 | 54971.86 |
| **Latency** | 964µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Dinatra](#dinatra)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 16264.95 | 2380.44 | 21049.42 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 13705.84 | 15905.30 | 16830.59 | 17560.10 | 18100.52 | 18316.69 | 19018.82 |
| **Latency** | 2ms      | 2ms      | 2ms      | 3ms      | 3ms      | 4ms      | 5ms      |

### [Elysia](#elysia)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 71476.25 | 11496.07 | 99012.71 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 56133.23 | 61454.88 | 72923.13 | 78938.14 | 87207.85 | 90634.47 | 94668.61 |
| **Latency** | 400µs    | 509µs    | 627µs    | 846µs    | 1ms      | 1ms      | 1ms      |

### [Express](#express)

| **Stat** | Mean   | Stddev  | Max |
| -------- | ------ | ------- | --- |
| 6478.00  | 928.75 | 8268.41 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 5073.17 | 6450.72 | 6737.36 | 6860.36 | 7181.34 | 7662.36 | 8195.33 |
| **Latency** | 6ms     | 7ms     | 7ms     | 7ms     | 8ms     | 9ms     | 11ms    |

### [Express (Deno)](#express-deno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 14240.56 | 1975.53 | 16257.04 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 12696.08 | 14313.43 | 14806.24 | 15053.71 | 15459.94 | 15667.36 | 16018.44 |
| **Latency** | 2ms      | 3ms      | 3ms      | 3ms      | 3ms      | 4ms      | 5ms      |

### [Fast](#fast)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 51027.96 | 2797.92 | 66309.81 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 49246.23 | 49967.44 | 50806.00 | 51736.65 | 53386.53 | 55716.32 | 59680.50 |
| **Latency** | 850µs    | 912µs    | 986µs    | 1ms      | 1ms      | 1ms      | 1ms      |

### [Fastify](#fastify)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 17841.34 | 1887.95 | 19812.81 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 16524.27 | 17524.82 | 18403.76 | 18708.91 | 18902.70 | 19020.35 | 19290.20 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 2ms      | 3ms      | 5ms      |

### [Fastro](#fastro)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 57570.65 | 8802.57 | 78040.55 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 48937.57 | 50104.77 | 55329.61 | 65140.92 | 70459.61 | 73037.70 | 75930.93 |
| **Latency** | 606µs    | 686µs    | 900µs    | 1ms      | 1ms      | 1ms      | 1ms      |

### [Hono](#hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 50698.27 | 3120.31 | 67633.20 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 48532.15 | 49362.75 | 50216.85 | 51415.36 | 53881.62 | 56227.69 | 60820.47 |
| **Latency** | 849µs    | 920µs    | 996µs    | 1ms      | 1ms      | 1ms      | 1ms      |

### [http](#http)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 44756.33 | 5209.61 | 51290.51 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 39805.49 | 44564.20 | 46110.65 | 47232.37 | 48413.87 | 49011.09 | 50228.55 |
| **Latency** | 841µs    | 992µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Hyper Express](#hyper-express)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 77611.97 | 12049.24 | 97786.91 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 58540.99 | 68869.17 | 80873.60 | 86918.24 | 91313.93 | 93203.47 | 95869.20 |
| **Latency** | 383µs    | 447µs    | 572µs    | 806µs    | 958µs    | 1ms      | 1ms      |

### [Little](#little)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 33023.09 | 3875.51 | 37998.85 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 29514.19 | 32434.16 | 34181.10 | 35144.82 | 35725.98 | 36126.69 | 36910.76 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Megalo](#megalo)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 48518.74 | 2618.35 | 60977.93 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 47107.19 | 47710.00 | 48582.90 | 49412.48 | 50577.12 | 51704.67 | 54321.01 |
| **Latency** | 906µs    | 958µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [NHttp](#nhttp)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 52702.92 | 3816.19 | 73541.78 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 49792.33 | 50704.79 | 51766.33 | 54146.56 | 57509.39 | 59935.70 | 64418.36 |
| **Latency** | 775µs    | 885µs    | 963µs    | 1ms      | 1ms      | 1ms      | 1ms      |

### [Node](#node)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 19338.61 | 1863.93 | 22911.54 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 17808.62 | 18756.86 | 19826.06 | 20326.93 | 20706.66 | 20884.77 | 21238.11 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 2ms      | 2ms      | 4ms      |

### [Oak](#oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 31261.17 | 2892.69 | 35600.95 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 30478.96 | 31315.08 | 32010.53 | 32363.02 | 32737.90 | 32970.17 | 33280.15 |
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
| 41028.09 | 2697.90 | 54901.18 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 37603.98 | 40050.55 | 41944.52 | 42526.97 | 43135.98 | 43356.67 | 44198.12 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Router](#router)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 42623.52 | 4612.14 | 51776.19 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 37000.84 | 42122.33 | 43828.96 | 45134.35 | 46122.73 | 46797.16 | 47985.93 |
| **Latency** | 870µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Stric](#stric)

| **Stat** | Mean     | Stddev    | Max |
| -------- | -------- | --------- | --- |
| 87157.59 | 10381.12 | 105032.22 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95        | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | --------- | --------- |
| **Req/Sec** | 72129.31 | 80135.12 | 89028.98 | 95163.74 | 99033.03 | 101098.70 | 103335.77 |
| **Latency** | 346µs    | 428µs    | 533µs    | 670µs    | 856µs    | 977µs     | 1ms       |

### [Servest](#servest)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 6389.67  | 1591.95 | 11244.07 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 5100.79 | 6030.63 | 6629.02 | 7137.13 | 7966.04 | 8436.22 | 9104.28 |
| **Latency** | 6ms     | 6ms     | 7ms     | 7ms     | 8ms     | 12ms    | 17ms    |

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
| 52053.94 | 3755.82 | 78747.10 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 49543.13 | 50379.00 | 51336.25 | 52723.86 | 56134.67 | 59103.14 | 64218.25 |
| **Latency** | 811µs    | 896µs    | 972µs    | 1ms      | 1ms      | 1ms      | 1ms      |

---

<p align="center">Generated 2025-03-07T00:28:44.890Z</p>
