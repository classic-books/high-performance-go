---
id: high-performance-go
title: Go 语言高性能编程
description: Go 语言高性能编程，涵盖 benchmark 基准测试、pprof 性能分析、常用数据结构、并发编程、编译优化与语言陷阱。
order: 20
featured: false
outline:
  - part: 序言
    chapters:
      - high-performance-go
  - part: 性能分析
    chapters:
      - hpg-benchmark
      - hpg-pprof
  - part: 常用数据结构
    chapters:
      - hpg-string-concat
      - hpg-slice
      - hpg-range
      - hpg-reflect
      - hpg-empty-struct
      - hpg-struct-alignment
  - part: 并发编程
    chapters:
      - hpg-mutex
      - hpg-timeout-goroutine
      - hpg-exit-goroutine
      - hpg-concurrency-control
      - hpg-sync-pool
      - hpg-sync-once
      - hpg-sync-cond
  - part: 编译优化
    chapters:
      - hpg-reduce-size
      - hpg-escape-analysis
      - hpg-dead-code-elimination
  - part: 语言陷阱
    chapters:
      - hpg-gotchas-array-slice
repo: https://github.com/geektutu/high-performance-go
---
