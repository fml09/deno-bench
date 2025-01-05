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
| Stric                                                                                | 88587.93 | 10448.35 | 106508.08 | 100%     |
| Bun                                                                                  | 87068.45 | 9806.01  | 106272.01 | 98%      |
| Elysia                                                                               | 82687.47 | 12545.50 | 104421.92 | 93%      |
| Hyper Express                                                                        | 82176.27 | 12997.98 | 103319.50 | 93%      |
| Deno                                                                                 | 55898.33 | 4271.50  | 82906.60  | 63%      |
| Fastro                                                                               | 54195.99 | 6821.01  | 78430.48  | 61%      |
| NHttp                                                                                | 51995.57 | 3113.38  | 62484.27  | 59%      |
| Fast                                                                                 | 51743.74 | 3153.74  | 65900.53  | 58%      |
| Vixeny (Deno)                                                                        | 50902.20 | 2580.23  | 70256.40  | 57%      |
| Hono                                                                                 | 50577.36 | 3059.08  | 62523.09  | 57%      |
| Megalo                                                                               | 47573.40 | 2809.60  | 59745.08  | 54%      |
| Deso                                                                                 | 46655.23 | 2264.95  | 59525.92  | 53%      |
| Alosaur                                                                              | 44394.59 | 2791.14  | 56704.93  | 50%      |
| Reno                                                                                 | 41915.39 | 2519.82  | 51312.38  | 47%      |
| Cheetah                                                                              | 41323.16 | 2491.44  | 47829.01  | 47%      |
| http                                                                                 | 41121.89 | 3461.83  | 47651.43  | 46%      |
| Router                                                                               | 40243.04 | 3389.85  | 46567.86  | 45%      |
| Danet V2 (Hono)                                                                      | 36141.62 | 2593.65  | 40800.28  | 41%      |
| Danet (Oak)                                                                          | 34009.73 | 2369.60  | 37585.58  | 38%      |
| Little                                                                               | 31762.48 | 3120.60  | 36327.10  | 36%      |
| Aqua                                                                                 | 31379.58 | 3461.47  | 41439.02  | 35%      |
| Oak                                                                                  | 30469.63 | 2662.12  | 32670.32  | 34%      |
| Node                                                                                 | 19506.59 | 1807.35  | 22712.43  | 22%      |
| Fastify                                                                              | 18203.65 | 1852.23  | 21521.37  | 21%      |
| Dinatra                                                                              | 17081.72 | 1733.84  | 23001.56  | 19%      |
| Abc                                                                                  | 14222.75 | 1269.85  | 17839.11  | 16%      |
| Express (Deno)                                                                       | 10629.74 | 1365.77  | 12222.72  | 12%      |
| Servest                                                                              | 6530.74  | 1222.16  | 11581.03  | 7%       |
| Express                                                                              | 6392.29  | 924.16   | 8359.78   | 7%       |
| Acorn                                                                                | 0.00     | 0.00     | 0.00      | 0%       |
| Opine                                                                                | 0.00     | 0.00     | 0.00      | 0%       |
| Peko                                                                                 | 0.00     | 0.00     | 0.00      | 0%       |
| Vixeny (Bun)                                                                         | 0.00     | 0.00     | 0.00      | 0%       |
| ![Chart](https://quickchart.io/chart/render/sf-76d05f58-bc35-4ca4-8155-809db398cd3f) |          |          |           |          |

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
| 14222.75 | 1269.85 | 17839.11 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 13132.90 | 13747.87 | 14603.23 | 14928.29 | 15212.58 | 15408.70 | 15910.60 |
| **Latency** | 3ms      | 3ms      | 3ms      | 3ms      | 4ms      | 4ms      | 4ms      |

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
| 44394.59 | 2791.14 | 56704.93 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 42117.74 | 43866.30 | 44679.40 | 45513.56 | 46471.30 | 47249.97 | 50448.93 |
| **Latency** | 987µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Aqua](#aqua)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 31379.58 | 3461.47 | 41439.02 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 28307.05 | 30353.89 | 31995.94 | 33188.95 | 34265.36 | 35196.91 | 39119.62 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      |

### [Bun](#bun)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 87068.45 | 9806.01 | 106272.01 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95        | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | --------- | --------- |
| **Req/Sec** | 72766.63 | 83020.83 | 87930.16 | 93446.60 | 99238.41 | 101226.22 | 103622.49 |
| **Latency** | 364µs    | 448µs    | 518µs    | 655µs    | 876µs    | 990µs     | 1ms       |

### [Cheetah](#cheetah)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 41323.16 | 2491.44 | 47829.01 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 39704.66 | 41110.09 | 41833.53 | 42243.54 | 43004.73 | 43363.21 | 44375.71 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Danet (Oak)](#danet-oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 34009.73 | 2369.60 | 37585.58 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 33388.79 | 34133.05 | 34417.45 | 34709.39 | 35096.00 | 35248.39 | 35575.54 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Danet V2 (Hono)](#danet-v2-hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 36141.62 | 2593.65 | 40800.28 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 35501.18 | 36311.12 | 36573.61 | 36899.68 | 37274.47 | 37463.87 | 37744.02 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Deno](#deno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 55898.33 | 4271.50 | 82906.60 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 53083.42 | 53904.59 | 54808.02 | 56190.75 | 61346.07 | 64348.24 | 70950.29 |
| **Latency** | 723µs    | 831µs    | 908µs    | 972µs    | 1ms      | 1ms      | 1ms      |

### [Deso](#deso)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 46655.23 | 2264.95 | 59525.92 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 45348.34 | 46018.13 | 46515.77 | 47318.97 | 48480.64 | 49344.59 | 52026.04 |
| **Latency** | 986µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Dinatra](#dinatra)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 17081.72 | 1733.84 | 23001.56 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 15509.14 | 16335.33 | 17288.43 | 18143.66 | 18802.71 | 19088.55 | 19650.02 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 3ms      | 3ms      | 4ms      |

### [Elysia](#elysia)

| **Stat** | Mean     | Stddev    | Max |
| -------- | -------- | --------- | --- |
| 82687.47 | 12545.50 | 104421.92 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 62013.42 | 74439.94 | 85540.71 | 92300.54 | 97133.66 | 99344.45 | 102605.85 |
| **Latency** | 347µs    | 434µs    | 550µs    | 729µs    | 916µs    | 1ms      | 1ms       |

### [Express](#express)

| **Stat** | Mean   | Stddev  | Max |
| -------- | ------ | ------- | --- |
| 6392.29  | 924.16 | 8359.78 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 5082.28 | 6144.92 | 6686.29 | 6850.63 | 7021.24 | 7641.72 | 8237.13 |
| **Latency** | 6ms     | 7ms     | 7ms     | 7ms     | 8ms     | 9ms     | 11ms    |

### [Express (Deno)](#express-deno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 10629.74 | 1365.77 | 12222.72 |     |

| **Stat**    | 10      | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | ------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 9252.49 | 10528.95 | 11140.46 | 11268.93 | 11370.07 | 11428.03 | 11624.80 |
| **Latency** | 3ms     | 4ms      | 4ms      | 4ms      | 5ms      | 5ms      | 8ms      |

### [Fast](#fast)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 51743.74 | 3153.74 | 65900.53 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 49108.53 | 50055.07 | 51281.37 | 53328.80 | 55292.06 | 56645.38 | 60565.24 |
| **Latency** | 810µs    | 904µs    | 979µs    | 1ms      | 1ms      | 1ms      | 1ms      |

### [Fastify](#fastify)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 18203.65 | 1852.23 | 21521.37 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 17214.06 | 18010.05 | 18723.95 | 18955.19 | 19097.92 | 19206.15 | 19419.11 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 2ms      | 3ms      | 5ms      |

### [Fastro](#fastro)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 54195.99 | 6821.01 | 78430.48 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 48288.60 | 49573.10 | 52804.13 | 58321.57 | 62665.23 | 65827.84 | 70795.29 |
| **Latency** | 639µs    | 793µs    | 954µs    | 1ms      | 1ms      | 1ms      | 1ms      |

### [Hono](#hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 50577.36 | 3059.08 | 62523.09 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 48322.78 | 49194.83 | 50106.44 | 51820.04 | 53960.62 | 55737.58 | 59020.59 |
| **Latency** | 849µs    | 923µs    | 999µs    | 1ms      | 1ms      | 1ms      | 1ms      |

### [http](#http)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 41121.89 | 3461.83 | 47651.43 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 38052.39 | 39914.25 | 41904.04 | 43105.19 | 43975.86 | 44552.14 | 45718.13 |
| **Latency** | 909µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Hyper Express](#hyper-express)

| **Stat** | Mean     | Stddev    | Max |
| -------- | -------- | --------- | --- |
| 82176.27 | 12997.98 | 103319.50 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 61230.44 | 73504.37 | 85479.30 | 92206.06 | 96758.70 | 98697.83 | 101621.04 |
| **Latency** | 343µs    | 425µs    | 560µs    | 743µs    | 921µs    | 1ms      | 1ms       |

### [Little](#little)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 31762.48 | 3120.60 | 36327.10 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 29746.02 | 31154.81 | 32245.19 | 33343.24 | 34127.50 | 34709.53 | 35609.01 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      |

### [Megalo](#megalo)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 47573.40 | 2809.60 | 59745.08 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 45541.51 | 46566.36 | 47607.13 | 48801.39 | 50063.42 | 50912.57 | 53664.87 |
| **Latency** | 916µs    | 977µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [NHttp](#nhttp)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 51995.57 | 3113.38 | 62484.27 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 49156.40 | 50354.07 | 51716.28 | 53728.98 | 55669.22 | 57138.79 | 59734.08 |
| **Latency** | 798µs    | 899µs    | 975µs    | 1ms      | 1ms      | 1ms      | 1ms      |

### [Node](#node)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 19506.59 | 1807.35 | 22712.43 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 18125.81 | 19245.97 | 19859.62 | 20349.43 | 20685.93 | 20925.96 | 21330.40 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 2ms      | 2ms      | 4ms      |

### [Oak](#oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 30469.63 | 2662.12 | 32670.32 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 29710.93 | 30375.24 | 31105.40 | 31443.63 | 31835.16 | 32066.40 | 32302.87 |
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
| 41915.39 | 2519.82 | 51312.38 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 40599.73 | 41565.75 | 42227.60 | 43079.94 | 43809.81 | 44352.34 | 45436.52 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Router](#router)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 40243.04 | 3389.85 | 46567.86 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 37544.87 | 39228.84 | 40773.19 | 41988.90 | 43044.13 | 43691.67 | 45095.06 |
| **Latency** | 921µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Stric](#stric)

| **Stat** | Mean     | Stddev    | Max |
| -------- | -------- | --------- | --- |
| 88587.93 | 10448.35 | 106508.08 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90        | 95        | 99        |
| ----------- | -------- | -------- | -------- | -------- | --------- | --------- | --------- |
| **Req/Sec** | 72771.28 | 82197.50 | 90561.81 | 97013.83 | 100513.81 | 102284.56 | 104220.29 |
| **Latency** | 340µs    | 424µs    | 528µs    | 662µs    | 835µs     | 952µs     | 1ms       |

### [Servest](#servest)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 6530.74  | 1222.16 | 11581.03 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 5377.46 | 5759.29 | 6606.51 | 7175.35 | 7844.09 | 8361.37 | 9602.11 |
| **Latency** | 6ms     | 6ms     | 7ms     | 8ms     | 9ms     | 9ms     | 13ms    |

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
| 50902.20 | 2580.23 | 70256.40 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 49223.45 | 49828.07 | 50646.59 | 51636.43 | 53188.01 | 54429.33 | 59250.79 |
| **Latency** | 859µs    | 916µs    | 991µs    | 1ms      | 1ms      | 1ms      | 1ms      |

---

<p align="center">Generated 2025-01-05T00:31:56.914Z</p>
