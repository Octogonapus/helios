---
layout: docs
title: Benchmarking
permalink: /docs/benchmarks/
---

## Current Benchmarks

You can see the current Helios benchmarks [here](https://github.com/47deg/helios/tree/master/benchmarks/master_benchmark.json)

<fortyseven-robeen data-url="https://raw.githubusercontent.com/47deg/helios/master/benchmarks/master_benchmark.json"></fortyseven-robeen>

## Comparing Helios

We have [here](https://github.com/47deg/helios/tree/master/benchmarks/libraries_benchmark.json) a benchmark comparison
between Helios and some of the most common Kotlin Json libraries.

<fortyseven-robeen data-url="https://raw.githubusercontent.com/47deg/helios/master/benchmarks/libraries_benchmark.json"></fortyseven-robeen>


## Running Benchmarks

To run the benchmarks for comparing Helios with other Json libraries, execute the following command:

```bash
./gradlew :helios-benchmarks:executeBenchmarks
```

To run the benchmarks with Helios' performance, execute the following command:

```bash
./gradlew :helios-benchmarks:executeHeliosBenchmark
```
