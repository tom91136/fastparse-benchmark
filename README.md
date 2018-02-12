# Benchmark for FastParse

This repo aims to provide a standardised JMH benchmark for comparing the performance
of [FastParse](https://github.com/lihaoyi/fastparse) versus other parsing 
libraries such as [parsec-for-scala](https://bitbucket.org/J_mie6/parsec-for-scala).

Latest results are [here](results/data.pdf)

The benchmark fixtures are [here](src/main/scala/net/kurobako/fastparsebench/Fixtures.scala)

To run benchmarks:

    ./sbt jmh:run