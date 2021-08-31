# Conector Python para Presto ou Trino

# Introduction

Este pacote provê a possibilidade de conexão do Python ao Presto ou Trino e a exportação de CSVs gerador a partir de queries SQL nessas engines.

# Installation

```
$ pip install trino
$ pip install pandas

```

# Quick Start

Use a linha abaixo, e insira os dados de conexão com o presto / trino.

```python
conn = connection('trino', 'your_user', 'your_password', 'ip or hostname from server', 'port_number', 'your_database')
```
