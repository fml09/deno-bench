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
| Bun                                                                                  | 110705.38 | 6404.61  | 127600.20 | 100%     |
| Stric                                                                                | 110266.65 | 6157.07  | 126458.94 | 100%     |
| Hyper Express                                                                        | 108897.22 | 7507.39  | 128542.78 | 98%      |
| Elysia                                                                               | 99676.61  | 9922.17  | 122079.42 | 90%      |
| Deno                                                                                 | 93897.48  | 7303.20  | 119991.67 | 85%      |
| NHttp                                                                                | 90140.77  | 9923.08  | 118032.44 | 81%      |
| Fastro                                                                               | 86927.45  | 7592.03  | 114531.69 | 79%      |
| Vixeny (Deno)                                                                        | 86809.71  | 8243.96  | 113137.78 | 78%      |
| Fast                                                                                 | 85763.96  | 8957.09  | 118731.72 | 77%      |
| Hono                                                                                 | 84277.86  | 10121.24 | 118365.72 | 76%      |
| Megalo                                                                               | 76841.35  | 6969.15  | 115291.98 | 69%      |
| Deso                                                                                 | 75275.57  | 6393.58  | 112114.62 | 68%      |
| Alosaur                                                                              | 66982.06  | 3803.06  | 72734.56  | 61%      |
| Reno                                                                                 | 63905.50  | 3398.52  | 69314.73  | 58%      |
| Cheetah                                                                              | 60963.47  | 6347.11  | 72781.52  | 55%      |
| http                                                                                 | 53311.22  | 6015.73  | 64549.89  | 48%      |
| Router                                                                               | 51865.27  | 4772.98  | 58991.89  | 47%      |
| Danet V2 (Hono)                                                                      | 50577.07  | 3664.20  | 55360.81  | 46%      |
| Danet (Oak)                                                                          | 45790.61  | 3359.98  | 48679.06  | 41%      |
| Oak                                                                                  | 42336.82  | 3872.03  | 45503.57  | 38%      |
| Node                                                                                 | 38348.33  | 3384.21  | 42768.04  | 35%      |
| Little                                                                               | 37242.99  | 4660.61  | 43582.79  | 34%      |
| Aqua                                                                                 | 36830.73  | 4611.87  | 43816.29  | 33%      |
| Fastify                                                                              | 33975.86  | 3618.19  | 41837.53  | 31%      |
| Dinatra                                                                              | 23574.17  | 3601.74  | 40890.43  | 21%      |
| Abc                                                                                  | 20921.13  | 2977.25  | 25338.23  | 19%      |
| Express (Deno)                                                                       | 15601.28  | 2663.77  | 18651.23  | 14%      |
| Express                                                                              | 9320.26   | 1613.77  | 12295.08  | 8%       |
| Servest                                                                              | 7158.67   | 2132.96  | 16032.13  | 6%       |
| Acorn                                                                                | 0.00      | 0.00     | 0.00      | 0%       |
| Opine                                                                                | 0.00      | 0.00     | 0.00      | 0%       |
| Peko                                                                                 | 0.00      | 0.00     | 0.00      | 0%       |
| Vixeny (Bun)                                                                         | 0.00      | 0.00     | 0.00      | 0%       |
| ![Chart](https://quickchart.io/chart/render/zf-0ce0ffe6-0c24-40c5-84fb-ca376150df03) |           |          |           |          |

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
| 20921.13 | 2977.25 | 25338.23 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 16827.03 | 19415.07 | 21819.27 | 22812.39 | 23979.71 | 24344.93 | 24802.33 |
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
| 66982.06 | 3803.06 | 72734.56 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 66061.61 | 67007.59 | 67578.86 | 68310.54 | 68719.23 | 69145.58 | 70002.88 |
| **Latency** | 657µs    | 686µs    | 751µs    | 788µs    | 812µs    | 831µs    | 971µs    |

### [Aqua](#aqua)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 36830.73 | 4611.87 | 43816.29 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 29855.40 | 35554.54 | 38301.47 | 39642.31 | 40476.20 | 41194.98 | 42244.37 |
| **Latency** | 868µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Bun](#bun)

| **Stat**  | Mean    | Stddev    | Max |
| --------- | ------- | --------- | --- |
| 110705.38 | 6404.61 | 127600.20 |     |

| **Stat**    | 10        | 25        | 50        | 75        | 90        | 95        | 99        |
| ----------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 102237.62 | 106733.78 | 111192.68 | 115165.03 | 118459.66 | 120230.37 | 123618.54 |
| **Latency** | 281µs     | 357µs     | 443µs     | 512µs     | 650µs     | 718µs     | 877µs     |

### [Cheetah](#cheetah)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 60963.47 | 6347.11 | 72781.52 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 56711.96 | 60237.49 | 61727.59 | 63019.30 | 66552.03 | 68526.63 | 70656.03 |
| **Latency** | 691µs    | 741µs    | 819µs    | 871µs    | 919µs    | 983µs    | 1ms      |

### [Danet (Oak)](#danet-oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 45790.61 | 3359.98 | 48679.06 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 45201.79 | 45928.06 | 46464.17 | 46938.19 | 47427.58 | 47670.88 | 48057.65 |
| **Latency** | 947µs    | 980µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Danet V2 (Hono)](#danet-v2-hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 50577.07 | 3664.20 | 55360.81 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 49865.93 | 50765.24 | 51224.29 | 51805.26 | 52146.85 | 52340.84 | 52735.56 |
| **Latency** | 862µs    | 891µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      |

### [Deno](#deno)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 93897.48 | 7303.20 | 119991.67 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90        | 95        | 99        |
| ----------- | -------- | -------- | -------- | -------- | --------- | --------- | --------- |
| **Req/Sec** | 86032.68 | 89030.51 | 93735.62 | 98442.99 | 103126.85 | 105300.88 | 110108.21 |
| **Latency** | 383µs    | 460µs    | 540µs    | 601µs    | 647µs     | 696µs     | 791µs     |

### [Deso](#deso)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 75275.57 | 6393.58 | 112114.62 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 71456.10 | 72749.51 | 74114.33 | 76038.13 | 81831.96 | 86761.06 | 99714.86 |
| **Latency** | 568µs    | 643µs    | 673µs    | 701µs    | 729µs    | 759µs    | 852µs    |

### [Dinatra](#dinatra)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 23574.17 | 3601.74 | 40890.43 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 18514.08 | 21028.12 | 25071.88 | 26014.29 | 26450.48 | 26645.30 | 27105.17 |
| **Latency** | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 3ms      | 4ms      |

### [Elysia](#elysia)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 99676.61 | 9922.17 | 122079.42 |     |

| **Stat**    | 10       | 25       | 50        | 75        | 90        | 95        | 99        |
| ----------- | -------- | -------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 86049.63 | 93392.59 | 100934.50 | 107315.31 | 111206.83 | 113470.93 | 117814.83 |
| **Latency** | 320µs    | 396µs    | 475µs     | 563µs     | 713µs     | 833µs     | 1ms       |

### [Express](#express)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 9320.26  | 1613.77 | 12295.08 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90       | 95       | 99       |
| ----------- | ------- | ------- | ------- | ------- | -------- | -------- | -------- |
| **Req/Sec** | 7351.74 | 9045.59 | 9412.67 | 9886.81 | 11600.10 | 11958.02 | 12145.52 |
| **Latency** | 4ms     | 4ms     | 5ms     | 5ms     | 6ms      | 7ms      | 8ms      |

### [Express (Deno)](#express-deno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 15601.28 | 2663.77 | 18651.23 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 10753.73 | 14915.76 | 16841.50 | 17238.68 | 17601.48 | 17840.23 | 18229.04 |
| **Latency** | 2ms      | 2ms      | 3ms      | 3ms      | 4ms      | 4ms      | 6ms      |

### [Fast](#fast)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 85763.96 | 8957.09 | 118731.72 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95        | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | --------- | --------- |
| **Req/Sec** | 78646.98 | 80272.74 | 83500.03 | 90818.28 | 97641.40 | 101904.44 | 111250.75 |
| **Latency** | 423µs    | 513µs    | 598µs    | 655µs    | 689µs    | 722µs     | 824µs     |

### [Fastify](#fastify)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 33975.86 | 3618.19 | 41837.53 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 32403.16 | 33174.26 | 34734.15 | 35321.01 | 35807.80 | 36035.57 | 39923.89 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Fastro](#fastro)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 86927.45 | 7592.03 | 114531.69 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 80112.12 | 81713.31 | 85729.30 | 91651.16 | 96500.31 | 99708.24 | 105640.85 |
| **Latency** | 424µs    | 507µs    | 589µs    | 645µs    | 680µs    | 712µs    | 809µs     |

### [Hono](#hono)

| **Stat** | Mean     | Stddev    | Max |
| -------- | -------- | --------- | --- |
| 84277.86 | 10121.24 | 118365.72 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95        | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | --------- | --------- |
| **Req/Sec** | 75976.94 | 77828.49 | 81492.53 | 89663.09 | 97736.19 | 103044.99 | 115894.69 |
| **Latency** | 423µs    | 506µs    | 612µs    | 674µs    | 709µs    | 737µs     | 826µs     |

### [http](#http)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 53311.22 | 6015.73 | 64549.89 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 45691.59 | 52417.86 | 54784.40 | 56137.94 | 58120.20 | 59913.10 | 61906.28 |
| **Latency** | 663µs    | 807µs    | 955µs    | 1ms      | 1ms      | 1ms      | 2ms      |

### [Hyper Express](#hyper-express)

| **Stat**  | Mean    | Stddev    | Max |
| --------- | ------- | --------- | --- |
| 108897.22 | 7507.39 | 128542.78 |     |

| **Stat**    | 10       | 25        | 50        | 75        | 90        | 95        | 99        |
| ----------- | -------- | --------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 99480.63 | 104874.11 | 109522.15 | 114124.27 | 117495.76 | 119526.34 | 123329.94 |
| **Latency** | 293µs    | 363µs     | 451µs     | 526µs     | 648µs     | 723µs     | 927µs     |

### [Little](#little)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 37242.99 | 4660.61 | 43582.79 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 32278.32 | 34039.47 | 39183.34 | 40297.07 | 41139.35 | 41738.17 | 42640.61 |
| **Latency** | 839µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      |

### [Megalo](#megalo)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 76841.35 | 6969.15 | 115291.98 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- |
| **Req/Sec** | 73412.16 | 74725.73 | 75901.12 | 77350.26 | 83410.46 | 87885.42 | 101832.96 |
| **Latency** | 542µs    | 605µs    | 659µs    | 702µs    | 729µs    | 754µs    | 865µs     |

### [NHttp](#nhttp)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 90140.77 | 9923.08 | 118032.44 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90        | 95        | 99        |
| ----------- | -------- | -------- | -------- | -------- | --------- | --------- | --------- |
| **Req/Sec** | 79503.62 | 83459.88 | 90013.88 | 95912.44 | 101993.69 | 106237.53 | 115278.51 |
| **Latency** | 388µs    | 462µs    | 566µs    | 641µs    | 687µs     | 726µs     | 820µs     |

### [Node](#node)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 38348.33 | 3384.21 | 42768.04 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 37614.60 | 38256.76 | 38756.18 | 39315.38 | 39871.69 | 40205.12 | 41012.19 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Oak](#oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 42336.82 | 3872.03 | 45503.57 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 41282.43 | 42377.40 | 43275.42 | 43802.52 | 44247.57 | 44378.56 | 44756.91 |
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
| 63905.50 | 3398.52 | 69314.73 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 63213.55 | 63988.70 | 64421.24 | 64989.13 | 65419.14 | 65702.89 | 66523.23 |
| **Latency** | 689µs    | 718µs    | 791µs    | 828µs    | 852µs    | 873µs    | 1ms      |

### [Router](#router)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 51865.27 | 4772.98 | 58991.89 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 46259.15 | 51556.61 | 53276.67 | 54469.14 | 55381.52 | 55884.01 | 56797.79 |
| **Latency** | 670µs    | 871µs    | 988µs    | 1ms      | 1ms      | 1ms      | 2ms      |

### [Stric](#stric)

| **Stat**  | Mean    | Stddev    | Max |
| --------- | ------- | --------- | --- |
| 110266.65 | 6157.07 | 126458.94 |     |

| **Stat**    | 10        | 25        | 50        | 75        | 90        | 95        | 99        |
| ----------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| **Req/Sec** | 101685.66 | 106520.37 | 110884.33 | 114484.73 | 117508.77 | 120005.04 | 123034.74 |
| **Latency** | 282µs     | 360µs     | 447µs     | 513µs     | 652µs     | 718µs     | 882µs     |

### [Servest](#servest)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 7158.67  | 2132.96 | 16032.13 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95       | 99       |
| ----------- | ------- | ------- | ------- | ------- | ------- | -------- | -------- |
| **Req/Sec** | 4818.34 | 5919.36 | 7058.83 | 8336.98 | 9797.59 | 10442.25 | 12556.43 |
| **Latency** | 5ms     | 6ms     | 6ms     | 7ms     | 9ms     | 10ms     | 15ms     |

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
| 86809.71 | 8243.96 | 113137.78 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95        | 99        |
| ----------- | -------- | -------- | -------- | -------- | -------- | --------- | --------- |
| **Req/Sec** | 79146.32 | 81005.30 | 85612.28 | 91909.75 | 97874.30 | 101114.04 | 106131.35 |
| **Latency** | 419µs    | 500µs    | 591µs    | 650µs    | 687µs    | 721µs     | 814µs     |

---

<p align="center">Generated 2026-03-30T00:45:09.277Z</p>
