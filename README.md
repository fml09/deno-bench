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
| Bun                                                                                  | 123492.54 | 13437.63 | 151148.38 | 100%     |
| Stric                                                                                | 123347.85 | 12806.76 | 151563.79 | 100%     |
| Hyper Express                                                                        | 106080.19 | 11936.95 | 142107.69 | 86%      |
| Elysia                                                                               | 103280.89 | 11444.95 | 145781.58 | 84%      |
| Deno                                                                                 | 85361.40  | 4812.54  | 101048.85 | 69%      |
| Fastro                                                                               | 80177.67  | 10331.28 | 111704.27 | 65%      |
| NHttp                                                                                | 79720.75  | 4162.71  | 95728.49  | 65%      |
| Vixeny (Deno)                                                                        | 79654.86  | 4182.51  | 104857.77 | 65%      |
| Fast                                                                                 | 78860.06  | 4555.78  | 122027.84 | 64%      |
| Hono                                                                                 | 77174.38  | 4135.29  | 92518.36  | 62%      |
| Deso                                                                                 | 71509.39  | 4302.21  | 97037.92  | 58%      |
| Megalo                                                                               | 71406.18  | 4352.36  | 82921.67  | 58%      |
| Alosaur                                                                              | 66608.33  | 4110.57  | 72165.85  | 54%      |
| Reno                                                                                 | 62129.49  | 3533.67  | 66470.20  | 50%      |
| Cheetah                                                                              | 58813.68  | 3824.56  | 61981.80  | 48%      |
| http                                                                                 | 50916.45  | 5908.41  | 60331.65  | 41%      |
| Router                                                                               | 48673.96  | 4877.15  | 63604.31  | 39%      |
| Danet V2 (Hono)                                                                      | 48233.12  | 4363.42  | 51321.87  | 39%      |
| Danet (Oak)                                                                          | 43172.15  | 3546.79  | 46332.16  | 35%      |
| Oak                                                                                  | 40897.65  | 4323.79  | 44213.00  | 33%      |
| Aqua                                                                                 | 36329.40  | 3972.78  | 42050.50  | 29%      |
| Node                                                                                 | 36086.93  | 3065.67  | 43360.01  | 29%      |
| Little                                                                               | 35036.35  | 5259.04  | 41736.62  | 28%      |
| Fastify                                                                              | 32176.49  | 3201.96  | 35065.84  | 26%      |
| Dinatra                                                                              | 22132.12  | 4018.60  | 36751.19  | 18%      |
| Abc                                                                                  | 18664.32  | 3544.35  | 29770.34  | 15%      |
| Express (Deno)                                                                       | 15983.73  | 1831.82  | 17786.32  | 13%      |
| Express                                                                              | 9010.07   | 1674.14  | 12050.64  | 7%       |
| Servest                                                                              | 8724.01   | 2437.94  | 13578.87  | 7%       |
| Acorn                                                                                | 0.00      | 0.00     | 0.00      | 0%       |
| Opine                                                                                | 0.00      | 0.00     | 0.00      | 0%       |
| Peko                                                                                 | 0.00      | 0.00     | 0.00      | 0%       |
| Vixeny (Bun)                                                                         | 0.00      | 0.00     | 0.00      | 0%       |
| ![Chart](https://quickchart.io/chart/render/zf-7c80a398-97ee-453a-9feb-2afd0cd37ad5) |           |          |           |          |

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
| 18664.32 | 3544.35 | 29770.34 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 15074.71 | 16613.95 | 19885.67 | 20721.85 | 21205.25 | 21501.54 | 27307.10 |
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
| 66608.33 | 4110.57 | 72165.85 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 65375.81 | 66409.16 | 67302.96 | 68176.06 | 68825.71 | 69337.49 | 70092.46 |
| **Latency** | 660µs    | 689µs    | 755µs    | 793µs    | 818µs    | 839µs    | 976µs    |

### [Aqua](#aqua)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 36329.40 | 3972.78 | 42050.50 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 33240.17 | 34920.63 | 37499.90 | 38546.52 | 39222.49 | 39840.53 | 40880.91 |
| **Latency** | 855µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Bun](#bun)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 123492.54 | 13437.63 | 151148.38 |     |

| **Stat**    | 10        | 25        | 50        | 75        | 90        | 95        | 99        |
| ----------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 105317.27 | 112933.10 | 124007.81 | 133949.40 | 141353.74 | 144909.33 | 148085.17 |
| **Latency** | 246µs     | 309µs     | 388µs     | 464µs     | 589µs     | 675µs     | 876µs     |

### [Cheetah](#cheetah)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 58813.68 | 3824.56 | 61981.80 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 58418.33 | 58832.56 | 59556.45 | 60037.67 | 60565.33 | 60804.63 | 61505.63 |
| **Latency** | 742µs    | 773µs    | 861µs    | 897µs    | 925µs    | 971µs    | 1ms      |

### [Danet (Oak)](#danet-oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 43172.15 | 3546.79 | 46332.16 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 42324.05 | 43384.57 | 44031.69 | 44455.69 | 44853.76 | 45055.99 | 45511.87 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Danet V2 (Hono)](#danet-v2-hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 48233.12 | 4363.42 | 51321.87 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 46842.74 | 48640.63 | 49214.41 | 49898.51 | 50303.14 | 50606.42 | 51003.80 |
| **Latency** | 894µs    | 925µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Deno](#deno)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 85361.40 | 4812.54 | 101048.85 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 81887.45 | 83547.18 | 85200.71 | 87212.55 | 90217.47 | 92121.59 | 98023.53 |
| **Latency** | 481µs    | 538µs    | 588µs    | 630µs    | 675µs    | 723µs    | 822µs    |

### [Deso](#deso)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 71509.39 | 4302.21 | 97037.92 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 69685.73 | 71017.34 | 72010.69 | 73037.94 | 73910.59 | 74735.15 | 80082.19 |
| **Latency** | 642µs    | 666µs    | 692µs    | 719µs    | 748µs    | 804µs    | 903µs    |

### [Dinatra](#dinatra)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 22132.12 | 4018.60 | 36751.19 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 16855.31 | 19602.85 | 23579.88 | 24804.28 | 25485.82 | 26105.62 | 26810.71 |
| **Latency** | 1ms      | 2ms      | 2ms      | 2ms      | 2ms      | 3ms      | 4ms      |

### [Elysia](#elysia)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 103280.89 | 11444.95 | 145781.58 |     |

| **Stat**    | 10       | 25       | 50        | 75        | 90        | 95        | 99        |
| ----------- | -------- | -------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 90811.40 | 94896.41 | 101338.90 | 110017.76 | 118801.58 | 124819.59 | 136472.45 |
| **Latency** | 277µs    | 358µs    | 466µs     | 570µs     | 696µs     | 825µs     | 1ms       |

### [Express](#express)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 9010.07  | 1674.14 | 12050.64 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90       | 95       | 99       |
| ----------- | ------- | ------- | ------- | ------- | -------- | -------- | -------- |
| **Req/Sec** | 6808.85 | 8407.60 | 9126.66 | 9610.93 | 11427.57 | 11691.35 | 11947.20 |
| **Latency** | 4ms     | 4ms     | 5ms     | 5ms     | 6ms      | 7ms      | 9ms      |

### [Express (Deno)](#express-deno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 15983.73 | 1831.82 | 17786.32 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 13949.64 | 15802.69 | 16653.08 | 16845.61 | 17001.83 | 17079.17 | 17240.28 |
| **Latency** | 2ms      | 2ms      | 3ms      | 3ms      | 3ms      | 3ms      | 4ms      |

### [Fast](#fast)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 78860.06 | 4555.78 | 122027.84 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 76373.53 | 77623.47 | 79114.67 | 80426.88 | 81911.53 | 83021.81 | 87208.86 |
| **Latency** | 548µs    | 587µs    | 637µs    | 675µs    | 705µs    | 736µs    | 833µs    |

### [Fastify](#fastify)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 32176.49 | 3201.96 | 35065.84 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 31701.16 | 32223.67 | 32731.33 | 33121.17 | 33381.03 | 33617.78 | 34135.65 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Fastro](#fastro)

| **Stat** | Mean     | Stddev    | Max |
| -------- | -------- | --------- | --- |
| 80177.67 | 10331.28 | 111704.27 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95        | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | --------- | --------- |
| **Req/Sec** | 72675.84 | 74371.57 | 76603.45 | 85042.27 | 94743.68 | 101416.14 | 107761.93 |
| **Latency** | 445µs    | 552µs    | 639µs    | 700µs    | 734µs    | 761µs     | 871µs     |

### [Hono](#hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 77174.38 | 4135.29 | 92518.36 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 75153.34 | 76320.22 | 77424.54 | 78733.23 | 79848.02 | 80901.99 | 83769.04 |
| **Latency** | 563µs    | 598µs    | 650µs    | 687µs    | 716µs    | 751µs    | 845µs    |

### [http](#http)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 50916.45 | 5908.41 | 60331.65 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 44536.99 | 51227.90 | 52601.22 | 53798.52 | 54916.19 | 55505.86 | 56630.57 |
| **Latency** | 666µs    | 920µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Hyper Express](#hyper-express)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 106080.19 | 11936.95 | 142107.69 |     |

| **Stat**    | 10       | 25       | 50        | 75        | 90        | 95        | 99        |
| ----------- | -------- | -------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 92422.89 | 96914.61 | 104468.92 | 113622.68 | 122526.05 | 127836.53 | 135875.33 |
| **Latency** | 276µs    | 351µs    | 459µs     | 565µs     | 651µs     | 755µs     | 1ms       |

### [Little](#little)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 35036.35 | 5259.04 | 41736.62 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 31520.89 | 33378.94 | 36608.16 | 38204.78 | 38872.26 | 39377.11 | 40317.76 |
| **Latency** | 883µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      |

### [Megalo](#megalo)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 71406.18 | 4352.36 | 82921.67 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 70109.75 | 71105.56 | 71949.41 | 72874.94 | 73812.20 | 74371.08 | 75585.27 |
| **Latency** | 615µs    | 646µs    | 702µs    | 739µs    | 764µs    | 789µs    | 917µs    |

### [NHttp](#nhttp)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 79720.75 | 4162.71 | 95728.49 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 77173.28 | 78417.85 | 79985.18 | 81449.70 | 82900.61 | 84090.91 | 87440.90 |
| **Latency** | 540µs    | 580µs    | 629µs    | 668µs    | 700µs    | 736µs    | 829µs    |

### [Node](#node)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 36086.93 | 3065.67 | 43360.01 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 35561.76 | 36086.86 | 36538.15 | 36949.55 | 37309.95 | 37479.31 | 38003.52 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Oak](#oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 40897.65 | 4323.79 | 44213.00 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 39567.87 | 41139.79 | 41903.76 | 42684.38 | 43226.42 | 43425.70 | 43737.68 |
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
| 62129.49 | 3533.67 | 66470.20 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 60851.29 | 61940.56 | 62887.78 | 63405.22 | 64021.75 | 64307.44 | 65095.31 |
| **Latency** | 706µs    | 736µs    | 814µs    | 851µs    | 878µs    | 905µs    | 1ms      |

### [Router](#router)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 48673.96 | 4877.15 | 63604.31 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 43430.38 | 47866.41 | 50019.37 | 51336.17 | 52198.50 | 52608.17 | 53790.11 |
| **Latency** | 695µs    | 972µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Stric](#stric)

| **Stat**  | Mean     | Stddev    | Max |
| --------- | -------- | --------- | --- |
| 123347.85 | 12806.76 | 151563.79 |     |

| **Stat**    | 10        | 25        | 50        | 75        | 90        | 95        | 99        |
| ----------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 105940.45 | 113261.57 | 123470.97 | 133332.11 | 140575.07 | 143959.21 | 147121.96 |
| **Latency** | 243µs     | 306µs     | 383µs     | 470µs     | 602µs     | 682µs     | 886µs     |

### [Servest](#servest)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 8724.01  | 2437.94 | 13578.87 |     |

| **Stat**    | 10      | 25      | 50      | 75       | 90       | 95       | 99       |
| ----------- | ------- | ------- | ------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 5538.18 | 7043.19 | 9321.41 | 10409.97 | 11408.93 | 12112.58 | 12839.56 |
| **Latency** | 4ms     | 4ms     | 5ms     | 6ms      | 8ms      | 9ms      | 15ms     |

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
| 79654.86 | 4182.51 | 104857.77 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 77252.86 | 78560.50 | 79865.94 | 81210.74 | 82905.20 | 84106.06 | 86925.66 |
| **Latency** | 541µs    | 581µs    | 630µs    | 669µs    | 699µs    | 734µs    | 829µs    |

---

<p align="center">Generated 2026-01-26T00:36:09.924Z</p>
