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
| Stric                                                                                | 99950.32 | 11624.62 | 124614.14 | 100%     |
| Elysia                                                                               | 86915.91 | 11927.45 | 118613.36 | 87%      |
| Deno                                                                                 | 85833.50 | 8727.30  | 107235.11 | 86%      |
| Bun                                                                                  | 85694.15 | 8509.84  | 107217.71 | 86%      |
| Hyper Express                                                                        | 80514.38 | 13689.35 | 106814.98 | 81%      |
| Vixeny (Deno)                                                                        | 80513.34 | 12865.21 | 117901.10 | 81%      |
| Fast                                                                                 | 80008.44 | 10199.44 | 116011.59 | 80%      |
| NHttp                                                                                | 78829.32 | 8697.34  | 110218.50 | 79%      |
| Fastro                                                                               | 76897.87 | 10436.55 | 108106.27 | 77%      |
| Hono                                                                                 | 69335.97 | 9097.60  | 106558.74 | 69%      |
| Megalo                                                                               | 66596.94 | 8106.42  | 101113.94 | 67%      |
| Deso                                                                                 | 63479.16 | 9859.35  | 95217.49  | 64%      |
| Reno                                                                                 | 54818.73 | 6735.51  | 65172.99  | 55%      |
| Cheetah                                                                              | 54541.31 | 5982.17  | 72179.82  | 55%      |
| Alosaur                                                                              | 49383.77 | 7530.30  | 69082.02  | 49%      |
| Router                                                                               | 47883.32 | 5951.68  | 56267.96  | 48%      |
| http                                                                                 | 47328.75 | 7342.30  | 57536.80  | 47%      |
| Danet V2 (Hono)                                                                      | 43963.05 | 5355.84  | 50258.85  | 44%      |
| Danet (Oak)                                                                          | 42882.56 | 4322.58  | 53376.00  | 43%      |
| Oak                                                                                  | 39732.46 | 4552.59  | 44561.60  | 40%      |
| Node                                                                                 | 32211.75 | 4847.13  | 43566.59  | 32%      |
| Fastify                                                                              | 29274.59 | 3673.23  | 43818.03  | 29%      |
| Aqua                                                                                 | 27549.18 | 4942.63  | 37637.01  | 28%      |
| Little                                                                               | 26748.31 | 6327.42  | 38809.83  | 27%      |
| Dinatra                                                                              | 19458.11 | 4543.82  | 39629.51  | 19%      |
| Abc                                                                                  | 17101.81 | 2961.25  | 22013.54  | 17%      |
| Express (Deno)                                                                       | 10960.94 | 2811.32  | 16064.70  | 11%      |
| Express                                                                              | 7517.47  | 1654.91  | 11342.51  | 8%       |
| Servest                                                                              | 5959.36  | 2102.33  | 15509.40  | 6%       |
| Acorn                                                                                | 0.00     | 0.00     | 0.00      | 0%       |
| Opine                                                                                | 0.00     | 0.00     | 0.00      | 0%       |
| Peko                                                                                 | 0.00     | 0.00     | 0.00      | 0%       |
| Vixeny (Bun)                                                                         | 0.00     | 0.00     | 0.00      | 0%       |
| ![Chart](https://quickchart.io/chart/render/zf-ed934ce9-488d-4f77-a215-1df10daf2477) |          |          |           |          |

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
| 17101.81 | 2961.25 | 22013.54 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 13535.28 | 15469.98 | 17702.43 | 19342.39 | 20208.10 | 20655.12 | 21228.75 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 3ms      | 4ms      | 5ms      |

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
| 49383.77 | 7530.30 | 69082.02 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 40853.36 | 46205.30 | 50530.68 | 54090.52 | 57151.90 | 58953.95 | 62422.76 |
| **Latency** | 797µs    | 881µs    | 975µs    | 1ms      | 1ms      | 1ms      | 1ms      |

### [Aqua](#aqua)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 27549.18 | 4942.63 | 37637.01 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 21429.61 | 25227.32 | 28518.20 | 30868.78 | 32770.48 | 33664.86 | 35104.43 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 4ms      |

### [Bun](#bun)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 85694.15 | 8509.84 | 107217.71 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 76013.33 | 81214.41 | 86220.44 | 90929.38 | 95515.62 | 98140.56 | 102285.05 |
| **Latency** | 340µs    | 447µs    | 561µs    | 680µs    | 840µs    | 956µs    | 1ms       |

### [Cheetah](#cheetah)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 54541.31 | 5982.17 | 72179.82 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 49207.52 | 52822.38 | 55236.96 | 57505.04 | 59816.00 | 61683.75 | 65505.16 |
| **Latency** | 762µs    | 820µs    | 907µs    | 974µs    | 1ms      | 1ms      | 1ms      |

### [Danet (Oak)](#danet-oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 42882.56 | 4322.58 | 53376.00 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 38512.31 | 41755.45 | 44090.17 | 45045.69 | 46029.60 | 47006.83 | 49802.71 |
| **Latency** | 984µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Danet V2 (Hono)](#danet-v2-hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 43963.05 | 5355.84 | 50258.85 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 38003.69 | 41978.73 | 45029.34 | 47755.09 | 48837.85 | 49205.79 | 49661.49 |
| **Latency** | 935µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Deno](#deno)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 85833.50 | 8727.30 | 107235.11 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 78016.42 | 81952.20 | 86293.56 | 91182.77 | 95140.80 | 97541.44 | 102710.57 |
| **Latency** | 416µs    | 501µs    | 584µs    | 649µs    | 722µs    | 783µs    | 937µs     |

### [Deso](#deso)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 63479.16 | 9859.35 | 95217.49 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 53857.55 | 58541.63 | 62721.53 | 68928.04 | 74916.04 | 79632.76 | 89237.42 |
| **Latency** | 533µs    | 646µs    | 800µs    | 881µs    | 971µs    | 1ms      | 1ms      |

### [Dinatra](#dinatra)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 19458.11 | 4543.82 | 39629.51 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 13612.27 | 16218.17 | 20255.18 | 23221.05 | 24420.12 | 24914.90 | 25959.54 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 3ms      | 4ms      | 5ms      |

### [Elysia](#elysia)

| **Stat** | Mean     | Stddev    | Max |
| -------- | -------- | --------- | --- |
| 86915.91 | 11927.45 | 118613.36 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90        | 95        | 99        |
| ----------- | -------- | -------- | -------- | -------- | --------- | --------- | --------- |
| **Req/Sec** | 73210.51 | 80579.89 | 87210.53 | 94992.08 | 101533.03 | 104112.86 | 109213.26 |
| **Latency** | 342µs    | 428µs    | 531µs    | 667µs    | 840µs     | 988µs     | 1ms       |

### [Express](#express)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 7517.47  | 1654.91 | 11342.51 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99       |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | -------- |
| **Req/Sec** | 5002.61 | 6870.05 | 7675.48 | 8592.79 | 9425.44 | 9964.59 | 11045.62 |
| **Latency** | 5ms     | 5ms     | 6ms     | 6ms     | 8ms     | 9ms     | 12ms     |

### [Express (Deno)](#express-deno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 10960.94 | 2811.32 | 16064.70 |     |

| **Stat**    | 10      | 25      | 50       | 75       | 90       | 95       | 99       |
| ----------- | ------- | ------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 6703.56 | 9130.89 | 11477.99 | 13002.69 | 14382.73 | 14842.06 | 15701.58 |
| **Latency** | 3ms     | 3ms     | 4ms      | 4ms      | 6ms      | 7ms      | 9ms      |

### [Fast](#fast)

| **Stat** | Mean     | Stddev    | Max |
| -------- | -------- | --------- | --- |
| 80008.44 | 10199.44 | 116011.59 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 71053.13 | 75610.98 | 78539.33 | 85445.93 | 92261.41 | 97255.07 | 105291.97 |
| **Latency** | 443µs    | 548µs    | 636µs    | 696µs    | 753µs    | 813µs    | 959µs     |

### [Fastify](#fastify)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 29274.59 | 3673.23 | 43818.03 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 26261.30 | 27959.47 | 29864.17 | 31468.50 | 32295.14 | 32741.76 | 33818.52 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      |

### [Fastro](#fastro)

| **Stat** | Mean     | Stddev    | Max |
| -------- | -------- | --------- | --- |
| 76897.87 | 10436.55 | 108106.27 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 64910.19 | 71301.87 | 77590.75 | 83196.30 | 89129.07 | 92661.49 | 100276.67 |
| **Latency** | 457µs    | 559µs    | 650µs    | 722µs    | 811µs    | 874µs    | 1ms       |

### [Hono](#hono)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 69335.97 | 9097.60 | 106558.74 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 59763.71 | 64940.18 | 69882.34 | 73819.83 | 78864.91 | 83433.08 | 92134.56 |
| **Latency** | 524µs    | 635µs    | 717µs    | 791µs    | 876µs    | 944µs    | 1ms      |

### [http](#http)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 47328.75 | 7342.30 | 57536.80 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 38821.20 | 45478.96 | 49336.70 | 52012.70 | 53407.54 | 54297.32 | 55510.39 |
| **Latency** | 722µs    | 931µs    | 1ms      | 1ms      | 1ms      | 1ms      | 3ms      |

### [Hyper Express](#hyper-express)

| **Stat** | Mean     | Stddev    | Max |
| -------- | -------- | --------- | --- |
| 80514.38 | 13689.35 | 106814.98 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 64183.79 | 74978.86 | 83019.32 | 89466.10 | 94325.23 | 97901.25 | 103518.53 |
| **Latency** | 349µs    | 456µs    | 573µs    | 710µs    | 897µs    | 1ms      | 1ms       |

### [Little](#little)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 26748.31 | 6327.42 | 38809.83 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 17242.73 | 22814.98 | 28403.88 | 31621.17 | 33561.16 | 34302.85 | 36314.65 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      | 5ms      |

### [Megalo](#megalo)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 66596.94 | 8106.42 | 101113.94 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 58788.14 | 64025.06 | 67304.27 | 70022.76 | 73424.47 | 77889.82 | 90157.12 |
| **Latency** | 607µs    | 678µs    | 746µs    | 804µs    | 873µs    | 935µs    | 1ms      |

### [NHttp](#nhttp)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 78829.32 | 8697.34 | 110218.50 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 70330.48 | 73819.55 | 77808.94 | 83813.15 | 89795.66 | 94023.52 | 101037.85 |
| **Latency** | 450µs    | 553µs    | 646µs    | 709µs    | 769µs    | 819µs    | 958µs     |

### [Node](#node)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 32211.75 | 4847.13 | 43566.59 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 26862.90 | 31124.50 | 33645.36 | 35031.59 | 35882.68 | 36333.96 | 37612.81 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      |

### [Oak](#oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 39732.46 | 4552.59 | 44561.60 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 35479.97 | 38796.17 | 41066.71 | 42429.87 | 43031.71 | 43257.79 | 43644.20 |
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
| 54818.73 | 6735.51 | 65172.99 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 47702.30 | 51337.31 | 56316.39 | 59844.15 | 60956.42 | 61464.94 | 62282.69 |
| **Latency** | 756µs    | 813µs    | 886µs    | 966µs    | 1ms      | 1ms      | 1ms      |

### [Router](#router)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 47883.32 | 5951.68 | 56267.96 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 40808.46 | 45849.50 | 49629.54 | 51806.48 | 52872.80 | 53429.48 | 54656.22 |
| **Latency** | 715µs    | 938µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Stric](#stric)

| **Stat** | Mean     | Stddev    | Max |
| -------- | -------- | --------- | --- |
| 99950.32 | 11624.62 | 124614.14 |     |

| **Stat**    | 10       | 25       | 50        | 75        | 90        | 95        | 99        |
| ----------- | -------- | -------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 87012.49 | 94951.20 | 101604.50 | 107457.04 | 111742.12 | 113530.06 | 116610.38 |
| **Latency** | 310µs    | 389µs    | 473µs     | 572µs     | 725µs     | 816µs     | 1ms       |

### [Servest](#servest)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 5959.36  | 2102.33 | 15509.40 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99       |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | -------- |
| **Req/Sec** | 3124.06 | 5316.58 | 6106.04 | 6952.86 | 8024.14 | 9034.38 | 11498.35 |
| **Latency** | 6ms     | 7ms     | 8ms     | 9ms     | 11ms    | 13ms    | 18ms     |

### [Vixeny (Bun)](#vixeny-bun)

| **Stat** | Mean | Stddev | Max |
| -------- | ---- | ------ | --- |
| 0.00     | 0.00 | 0.00   |     |

| **Stat**    | 10   | 25   | 50   | 75   | 90   | 95   | 99   |
| ----------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| **Req/Sec** | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 | 0.00 |
| **Latency** | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  | 0ms  |

### [Vixeny (Deno)](#vixeny-deno)

| **Stat** | Mean     | Stddev    | Max |
| -------- | -------- | --------- | --- |
| 80513.34 | 12865.21 | 117901.10 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95        | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | --------- | --------- |
| **Req/Sec** | 66628.74 | 74136.50 | 79113.85 | 87375.01 | 97526.94 | 103248.10 | 112284.98 |
| **Latency** | 416µs    | 500µs    | 621µs    | 710µs    | 798µs    | 865µs     | 1ms       |

---

<p align="center">Generated 2026-04-01T00:47:28.207Z</p>
