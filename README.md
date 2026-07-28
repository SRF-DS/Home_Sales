# Home Sales with PySpark

## Problem
Housing sales files get big fast — you need SparkSQL patterns (views, cache, parquet, partitions) that stay fast as data grows.

## What we built
A PySpark analysis of home sales that loads CSV (including remote via SparkFiles), runs aggregations, and compares query performance across caching and storage strategies.

## How to run
```bash
pip install pyspark findspark
# open and run the Home Sales notebook in this repo
```

## Stack
Python · PySpark · SparkSQL · Parquet

## Fun closer
Caching feels like cheating until you time the same query twice and smile.
