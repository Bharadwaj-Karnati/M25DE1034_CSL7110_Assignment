# Hadoop MapReduce Assignment – CSL7110

This repository contains the implementation and analysis of Hadoop MapReduce programs developed as part of the CSL7110 Big Data course.

## 🔧 Environment

- OS: Ubuntu 24.04 LTS (WSL2)
- Hadoop Version: 3.3.6
- Java Version: 1.8
- Execution Mode: Single-node pseudo-distributed setup

---

## 📌 Assignment Overview

The assignment covers:

1. Implementation of WordCount using Hadoop MapReduce
2. Debugging and extending MapReduce programs
3. Running MapReduce on large datasets (Project Gutenberg)
4. HDFS block analysis
5. Replication factor experiments
6. Performance counter analysis
7. Filesystem health verification

---

## 📂 Project Structure

- `src/` → Contains all Java MapReduce source files
- `sample-data/` → Small test input files
- `docs/` → Assignment documentation and screenshots

---

## 🚀 How to Compile

```bash
javac -classpath `hadoop classpath` -d . WordCount_QX.java
jar -cvf WordCount_QX.jar *
