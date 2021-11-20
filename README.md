# README

This is a simple cookiecutter template for Apache Spark SQL project in Scala.

## How to use this template

```
~/git$ pip3 install cookiecutter
~/git$ cookiecutter https://github.com/jazzwang/init-spark-sql
repo_name [spark-sql]: new-spark-sql   ### Enter the project name
~/git$ cd new-spark-sql/
~/git/new-spark-sql$ git init
~/git/new-spark-sql$ git add .
~/git/new-spark-sql$ git commit -m 'initial project'
[master (root-commit) ecd1806] initial project
 5 files changed, 72 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 build.sbt
 create mode 100644 src/main/resources/log4j.properties
 create mode 100644 src/main/resources/spark-defaults.conf
 create mode 100644 src/main/scala/Hello.scala
~/git/new-spark-sql$ sbt run
```

## Notes

```
~/git/spark-sql$ spark-shell
Setting default log level to "WARN".
To adjust logging level use sc.setLogLevel(newLevel). For SparkR, use setLogLevel(newLevel).
Spark context Web UI available at http://localhost:4040
Spark context available as 'sc' (master = local[*], app id = local-1637456657918).
Spark session available as 'spark'.
Welcome to
      ____              __
     / __/__  ___ _____/ /__
    _\ \/ _ \/ _ `/ __/  '_/
   /___/ .__/\_,_/_/ /_/\_\   version 3.0.0
      /_/

Using Scala version 2.12.10 (OpenJDK 64-Bit Server VM, Java 1.8.0_312)
Type in expressions to have them evaluated.
Type :help for more information.

scala> :import
 1) import java.lang._             (118 types, 124 terms)
 2) import scala._                 (178 types, 172 terms)
 3) import scala.Predef._          (125 terms, 62 are implicit)
 4) import org.apache.spark.SparkContext._ (71 terms, 1 are implicit)
 5) import spark.implicits._       (1 types, 69 terms, 39 are implicit)
 6) import spark.sql               (1 terms)
 7) import org.apache.spark.sql.functions._ (422 terms)
 ```