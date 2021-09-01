# Conector Python para Presto ou Trino

# Introduction

Este notebook provê a possibilidade de conexão do Python ao Presto ou Trino e a exportação de CSVs gerador a partir de queries SQL nessas engines.

# Installation

```
$ pip install trino
$ pip install pandas

```

# Quick Start

Edite a linha abaixo com os dados de conexão ao presto / trino.

```python
conn = connection('trino', 'your_user', 'your_password', 'ip or hostname from server', 'port_number', 'your_database')
```
