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